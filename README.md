AlmaBetter Frontend Capstone Project

Resume-Builder

Introducing Resume Builder, the ultimate React application that empowers you to craft eye-catching resumes like never before. You can easily customise your resume with Resume Builder's user-friendly interface to highlight your unique skills and professional experience.

Stand out from the crowd and make a lasting impression with Resume Builder, the perfect tool to land your dream job. Start building your future today!

Just select template - Fill in the details and voila! Your resume is ready to preview and download.

Installation
Clone this repository in your local machine and install the needed dependencies

Type npm start in terminal to start the application after installing the dependencies using npm install <package_name>

Technologies and Libraries used
React
React-router-dom
React-hook-form
Redux
jspdf
Material UI and Icons
Tailwing-css
Application Folder Structure
├── public/
│	├── index.html
│    	├──images/
│		├── template1.png
│		├── template2.png
│		├── template3.png
│		├── template4.png	
├──src/
│	├──App.js
│	├──App.css
│	├──App.test.js
│	├──index.css
│	├──index.js
│	├──setupTests.js
│	├──Components/
│		├──images/
│			├──LOGO.png
│			├──Right.png
│			├──aboutus.png
│			├──download.png
│			├──nodata.png
│   	├── Education.jsx
│		├──GettingStarted.jsx
│		├──Keyskills.jsx
│		├──Myresume.jsx
│		├──PersonalInformation.jsx
│		├──Workexperience.jsx
│	├──Data/
│		├──data.js
│	├──Pages/
│		├──About US/
│			├──Aboutus.jsx
│		├──Details Filing/
│			├──Detailfilling.jsx
│			├──sidebar.css 
│		├──Home/
│			├──TempleteCard.jsx
│			├──Templetes.jsx
│		├──Preview/
│			├──Preview,jsx
│	├──Redux/
│		├──actions/
│			├──actions.js
│			├──saveresume.js
│			├──setcontact.js
│			├──seteducation.js
│			├──setexperience.js
│			├──setkeyskills.js
│			├──settemplate.js
│		├──constants/
│			├──typeCodes.js
│		├──reducers/
│			├──initialState.js
│			├──rootReducer.js
│			├──saveresume.js
│			├──setcontact.js
│			├──seteducation.js
│			├──setexperience.js
│			├──setkeyskills.js
│			├──settemplate.js
│		├──store
│			├──store.js
│	├──Templetes/
│		├──Resume1.css
│		├──Resume1.jsx
│		├──Resume2.jsx
│		├──Resume3.css
│		├──Resume3.jsx
│		├──Resume4.css
│		├──Resume4.jsx
├──index.js   
├──package-lock.json
├──package.json
└──tailwind.config.js
Components and Pages of Application:
Template Selection - From this component user can choose their favourite template.
![Screenshot 2023-10-31 110616](https://github.com/Shiv199206/shiv-capstone-project/assets/126183364/f3104a73-b2a4-4ec4-8b3b-63eca8523b16)


template selection

Details Filling Page - From this component user can add their details of personal info, education, experience and skills.
![Screenshot 2023-10-31 110829](https://github.com/Shiv199206/shiv-capstone-project/assets/126183364/60b98724-8270-4ce7-a549-4d04ffaffee4)


perosnal




