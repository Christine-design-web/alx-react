Using the previous project (0x05. React inline styling), we have modularized our React application without worrying about interactions and state, which is usually a recommended process of development. Now, our application is in a good place to start adding logic and state.

Modify the App component in task_0/dashboard/src/App.App.js:

Create a local state to store a displayDrawer element:

Define the default state for the state in the constructor of the Class
Create a function named handleDisplayDrawer that will change the value of displayDrawer to true
Create a function named handleHideDrawer that will change the value of displayDrawer to false