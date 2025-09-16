# Getting Started with Create React App

This project was created as part of the Free Code Camp curriculum (https://www.freecodecamp.org/learn/coding-interview-prep/take-home-projects/show-the-local-weather)

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.


### `npm run build`

Builds the app for production to the `build` folder.
It correctly bundles React in production mode and optimizes the build for the best performance.



### Updates
Due to outdated versions or dependencies not being installed, run these if error occurs

->  'npm install react-scripts@5.0.1 --save --legacy-peer-deps' to install 
->  Sometimes the install is corrupted. Clean and reinstall:

    ' rd /s /q node_modules
    del package-lock.json
    npm install --legacy-peer-deps '


   Then check if the folder exists:

   'dir node_modules\react-scripts'   
#### The warnings you see (deprecated, vulnerabilities) are common with older CRA projects — they don’t stop your app from running. You can fix them later with npm audit fix, but it’s optional.
-> Install the correct ajv version 
   'npm install ajv@^6.12.6 ajv-keywords@^3.5.2 --save-dev --legacy-peer-deps'

