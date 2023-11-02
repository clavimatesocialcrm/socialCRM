# socialCRM
                                          ManageMe

It's a low-code platform for building web applications for enterprise, to manage internal processes of business like CRM.

Features

Drag-and-drop Form Builder to configure user interface
Built-in data sources and connections to existing databases like MongoDB, etc.
Scripting - customize application anywhere with JavaScript
Functions - cloud functions to evaluating business logic
Permission - user access limitation for any data or element of interface
Live data - each device gets synchronized data in real-time.


Roadmap
Social CRM project.
MERN stack components: MongoDB, Express.js, React.js, Node.js.
Importance of Social CRM in enhancing customer relationships and engagement.
Overview of the design process using Figma.

Design Phase

Figma Design:

Provide a link to the Figma project where the application's design is created.
Include screenshots or mockups of the application's user interface.
Describe key design elements, colour schemes, and interactive components.

How to use figma

1. Creating an Account:
Go to the Figma website and sign up for a free account.
You can use your Google account or create a new Figma account.

2. Creating a New Project:
Once logged in, click on the "New" button to create a new project.
Choose the type of project you want to create: "Design," "Prototype," or "File."
Give your project a name and click "Create."


3. Interface Overview:
Canvas: The main area where you design your interface.
Layers Panel: Displays all the layers in your design.
Toolbar: Contains tools for creating shapes, text, images, and more.
Properties Panel: Shows properties and styles of the selected object.
Assets: Access to colors, styles, and components for consistent design.

4. Creating and Editing Designs:
Adding Shapes: Click on the shape tool in the toolbar, drag to create a shape on the canvas. You can modify its size and color in the properties panel.
Adding Text: Click the text tool, click on the canvas, and start typing. You can change font, size, and color in the properties panel.
Importing Images: Drag and drop images from your computer directly onto the canvas.
Layers: Use the layers panel to organize your design elements. You can group, rename, and rearrange layers.

5. Components and Styles:
Components: Create reusable UI elements like buttons or headers. Select an element, click "Create Component" in the properties panel, and use it across your design.
Styles: Define color, text, and effect styles. Create a style, and it will automatically update all instances when you edit the style.

6. Prototyping:
Create Links: Select an object, click the "Prototype" tab, and drag a connection to another frame to create a link.
Transitions: Define how the transition between frames should behave (slide, dissolve, etc.).
Preview: Click "Present" in the top-right corner to see your prototype in action.

7. Collaboration:
Sharing: Click on the "Share" button to generate a shareable link. You can set permissions to view, comment, or edit.
Real-time Collaboration: Multiple users can edit the same file simultaneously. Changes are synced in real-time.

8. Plugins and Integrations:
Figma supports various plugins that enhance functionality.
It also integrates with other tools like Slack, Jira, and GitHub for seamless collaboration.



9. Version History:
Figma keeps track of version history, allowing you to revert to previous versions if needed.
10. Learning Resources:
Figma offers tutorials, documentation, and a community forum to help users learn and troubleshoot.

Remember that Figma's interface is intuitive, and the best way to learn is by exploring and experimenting. As you work on your projects, you'll discover more advanced features and techniques to enhance your design workflow.

 Design v0.1
https://www.figma.com/file/DBCXUza3n9p35rg3HcUooj/DESIGN-V0.1?type=design&node-id=1%3A300&mode=design&t=m1vQ2P0s4z1xahRP-1

  
 Design v0.2
https://www.figma.com/file/T6ohP4BGMiEmiMOaJUcstT/design-v0.2?type=design&node-id=0%3A1&mode=design&t=QsafXqN0yp1bZUek-1


 Project Setup
Prerequisites:
MongoDB installed and running.
Node.js and npm installed.
Text editor or IDE (e.g., Visual Studio Code).
Postman
Mongodb compass


Setting Up the Frontend (React.js):

Generate a new React app: npx create-react-app client(or socialcrm)
Navigate to the client directory: cd client (or socialcrm)
Install Axios for API calls: npm install axios
Start the React development server: npm start
Here ( socialcrm) is a file name

├── node_modules      
├── package-lock.json     
├── package.json          
├── public                
│   ├── favicon.ico       
│   └── index.html        
├── src                   
│   ├── Assets           
│   ├── App.css                         
│   ├── components ├──DoMore      
│   ├── App.js           ├──Feature      
│   ├── index.js        ├──Footer       
│                                 ├──Home
                                   ├──Main
                                   ├──Navbar
                                   ├──Platforms


                                Project Root Directory

node_modules: This folder contains all the project's dependencies. When you run npm install, packages are downloaded and stored here.

package-lock.json: This file is automatically generated by npm and provides version information for project dependencies.

package.json: This file contains metadata about the project, as well as the list of dependencies, scripts, and other configurations.

public: This directory contains static files that are served directly without any processing. Files like favicon.ico and index.html are commonly placed here.

favicon.ico: This is the icon that appears in the browser tab when the application is open.

index.html: The main HTML file that acts as the entry point of the React application. It usually contains a <div> with an id where the React application is rendered.

src: This directory contains the source code of your React application.

Assets: This folder can store static assets such as images, fonts, or other media files used in your application.

App.css: A CSS file that contains styles for the components used in the App.js file.

components: This directory holds various components of your application. Based on the provided structure, it seems you have different components organized within subdirectories:

DoMore: A component (or a set of components) related to doing more actions in your application.
DoMore.js: Component file for handling additional actions within the application.
DoMore.css: CSS file specific to the DoMore component, providing styles for this component only.


Feature: A component (or a set of components) related to a specific feature in your application.

Footer: A component responsible for displaying the footer section of your application.

Home: A component representing the home page of your application.

Main: A component that serves as the main content section of your application.

Navbar: A component responsible for the navigation bar/menu of your application.

Platforms: A component related to different platforms, possibly indicating integration with multiple platforms.

Your React application seems to be structured into different components, each organized under specific directories. You can further develop these components, import them into other components or pages, and create a fully functional user interface for your application. Remember that React components can be nested within each other, allowing you to create complex UI structures by composing smaller, reusable components.
             



