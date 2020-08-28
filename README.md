# Sign_Up
This repository uses GSON,Rx Java2, Retrofit2 to make an app which enables users to sign up.


<h2> <u>Working of the App</u></h3>
<li> This is a simple app which allows user to signup and after signing in the user user will be able to see all the users that have already signed in.<br>
<li>This list of users is Stored on a remote server(www.apnarajya.in/)<br>
<li> This server act as and API which accepts a POST request to create the new User. </br>
<li> Two users with same name and Email will not be created. <br>
<li> Url used for GET request is http://www.apnarajya.in/GetUsers.php <br>
<li> Url used for POST request is http://www.apnarajya.in/SignUp.php <br><br>

<h2> Libraries used</h2>
<li><h4> Retrofit: </h4> This library has been used to SEND the GET and POST request the API.<br>
<li><h4> rx java 2: </h4> This library has been used to validate the SignUp form. <br>

