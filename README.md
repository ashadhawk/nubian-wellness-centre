# Nubian Wellness Temple
Welcome to the README file for my first milestone project.
This project is to create a website for a fitness centre dedicated to promoting physical activity among black people and other people of colour.

##UX Design

**Strategy** A systematic search of online resources revealed a significant lack of fitness and physical activity resources dedicated to promotion of exercise in black people in western countries. The health brenefits of exercise and physical activities are incontrovertible. This means black people are less likely to obtain these benefits. Apart from the economic factors, there are also numerous social and environmental factors that restrict the engagement of black people in physical activities. The additional factor of weather with reduced sunshine hours especially in winter further impacts on physical activity engagement. The strategy for the project evolved from the folloowing user story. "As a black person, I want a gym/fitness facility that understands my need as a black person so I can become more active and healthy".

**Scope** This project has therefore been initiated to create a website for a fitness that tries to address some of the imbalance with regards to access to opportunity for physical activity. While there is a social responsibility component to the mission statement, the centre needs economic viability for sustainability.
Key objectives of the projects are 1 To provide a supportive environment that will facilitate regular particiopation in exercise and physical activities. 
2. To create brand awareness.
3. To promote healthy lifestyle in people of colour.
4. Act as an advocate for black people to increase access to affordable facilities for exercise and physical activities.

**Structure** :The structure to implement this project will be based on a principle to make desired information and service readily avaialble and to crearte a website that will be both pleasing and engaging for the user.
The website will be easily accessible across various viewing platforms from mobile phones to desktop. In an increasingly mobile world, a mobile first aprroach willbwe undetaken for the design of the website.

**Skeleton** A mock up of the project was initailly stencilled with paper and pen. A couple of different versions were created to enhance my understanding and competence in creating the skeleton/wireframe of the project. This was converted to a low fidelity digital version using Balsamiq wireframe. 

** Surface** With the wireframe now done, I am now progressing to the surface plane to create the website using the knowledge I have acquired from the various lessons and tutorials.
Here is to a Happy coding!

For this project, I have utilised the framework of the example provided during the lesson on the use of boostrap. 
This is to increase my familiarity with the bootsrap framework and also to explore other functionaliries within the system. 
I have also used the bootsrap version 4 as used in the module lessons though I am aware that version 5 now exists.
I created an asset folder which holds my image files. The images were mostly obtained from pexels.com and unsplash.com
My project will have a set up with 4 pages set up as follows:
1 A home/landing page that gives the user information about the service. It will also hav the navigation elements as well as contact information. 
For a unique product tacking a bespoke population, I feel it is important for the landing page to provide vital information relating to that.
The rule of thirds will be implemented in all the pages of the project. The website logo was created through resources obtained at jimdo.com, a logo creator resource.
The set up of the home page with a header and footer section that is common to all the pages of the website. Content variation will be in the middle section of the pages. 
2. An activities page will show case some of the the various activities on offer. On this page, the activities will be presented with an image overlay that turns to text with hover functionality.
3. A gallery page to show various pictures. The middle section of this page hosts the pictures which have been sdet up to display in 4 columns on a desktop screen and 2 columns on mdeium sized screens and single on small devices.
The coding and styling ideas were obtained from w3schools.com with some modifications I added to fix some bugs. This is in relattion to blank spaces appeaaring on the screen in desktop mode.
4. The Join Us/ Contact page utilised na simple form structure with 2 rows of input information for name and email.
This is followed by a textarea section, all similar to the example project in the tutorials. I added an additional check box to 
further ensure that certaion requirements are fulfilled befgor form submission.

The key issue that has impacted on the smooth completion of the project is getting to understand bootsrap grid flexbox system.
Activity page:
The activities page has display issues in tablet size screens which I have tried a couple different solutions. 
I think the issue is related to the bootsrap grid which I might need to override with custom css styling.
Solved the text overlay "appear on hover" effect by creating a new overlay and a :hover class in the div housing the activity-text and changing the opacity to zero. 
I then created new css property for overlay class and hover to appear with an opacity of 1.
I need to play around with the text color considering the white is not easily readable of light aspects of the background image.
I experimented with diferrent background colors and currently leaving it as lavender.
Also need to change the hvr-sweep-to-bottom class as reusing this as current set for the nav elements is 
not fully covering all the text in the activity columns. I will explore hover.css for suitable effects to applyv to the activities section with appropriate sizing.
Still has the issue of text spilling over into the footer section on medium and tablet size screen size to fix and also the activity-name spills into the footer column 
and not sitting at the bottom of the column. I posted this issue of text overspill into the footer section on various coding forums. I also requested tutor support at this stage 
Based on the various responses I received from the different forums, I fixed the activity-name by introducing a row class with position: relative to override the default one from bootstrap, 
and then added a bottom: 0 to the activity-name class. This then works with the existing position: absolute to force the activity-name class to the bottom of the row div. 
I also fixed the spilling activity text when you resize the window by using font-size: max(0.8em, 12px) instead of the 16px. 
This means that the normal size of the text will at least be 12px (i.e. when the window is reduced ) or 0.8em when at full screen.
All the pages are looking nice no issues with HTML or CSS validation check.

Next stage is to add the href for all the links and make the pages work as one document rather just series of pages.
