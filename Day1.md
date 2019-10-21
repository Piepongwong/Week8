# Posting data with React

Today we're going to learn how to post data with React. The data we're going to send is first going to be a new beer for the beer API and after it's going to be sign up and login data of a user. Forms in React work a bit different than with traditional apps. The default behaviour of forms is that the user is send to a different page after submitting. We dont want that in a SPA. Also, forms hold data naturally in their input field. React doesn't like that. It likes to control the data itself. 

After today you'll

* understand why Forms work differently with React
* know how to control the data of forms with the onChange event and the handleChange event handler
* know about an alternative way to send to handle form data with a `ref` and the FormData constructor
* can send formdata to a backend route using axios
* Lab exercises of today: make page for creating a new beer and one for signup up a user. (Check the api docs: https://ih-beers-api.herokuapp.com)

Tomorrow we're going to learn how to manage user data for all components with localstorage and authentication functions.