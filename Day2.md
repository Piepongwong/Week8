# Authentication with React with Localstorage

We used to maintain most of the session data in a session on the server (req.session.user). Because with react you are rendering on the server side, you would like to have some user data always at hand. With that data we can render things like the navbar correctly. One way to do this, is to keep the user date in a central state, like App.js. However, if you keep the session data in localstorage, the data is persisted on page reloads.

After today you:

* Understand the login and signup flow within react
* Know what localstorage is
* Know why you need localstorage
* Know what CORS is and how you can prevent it
* Understand the benefit of having a central auth.js file where you store authentication functions
* Todays Lab is adding a login and signup page in the beers api assignment. If you're done, you can move on to the React-Profile assignment on moodle.

Off you go!