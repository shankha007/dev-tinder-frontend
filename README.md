# DevTinder

- Create a Vite + React application
- Removed unnecessary code and create a Hello World app
- Install Tailwind CSS
- Install Daisy UI
- Add Navbar component to App.jsx
- Create a separate Navbar.jsx component file
- Installed react-router-dom
- Create Browser Router > Routes > Route=/ Body > RouteChildren
- Create an Outlet in the Body component
- Create a Footer
- Create a Login page
- Install axios
- CORS - Install cors in backend => add middleware with configurations: origin, credentials: true
- Whenever you are making a API call, pass axios => { withCredentials: true }
- Install react-redux + Redux Toolkit - https://redux-toolkit.js.org/tutorials/quick-start
- configureStore => Provider => createSlice => add reducer to store
- Add Redux DevTools in Chrome
- Login and see if your data is coming properly in the store
- Navbar should update as soon as user logs in
- Refactor our code to add constants file + create a components folder
- You should not be able to access other routes without login
- If token is not present, redirect user to login page
- Logout Feature
- Get the feed and add the feed in the store
- Build the User Card on Feed

## Component Design

Body
----Navbar
----Route=/ => Feed
----Route=/login => Login
----Route=/connections => Connections
----Route=/profile => Profile
