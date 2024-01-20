<h1>Application Succesfully Deployed: https://tunes-akiledar.netlify.app/</h1>

# TUNES_THE_E-COMMERCE_WEBSITE

DESCRIPTION:-

Tunes-The Shopping website is an e-commerce application that has various guitars as the product to be sold and purchased by customers. This project is a full-stack project developed using MERN Stack. The server side code is written using ExpressJS Framework. 

<ol>
<li>MongoDB is used to store the required data, retreive it and modify it as per user operations. The following Models are created on MongoDB:-</li>

<ul>
<li>User model to store User data like firstname, lastname, email, password, user cart containing items, purchase history and user role(general user or admin) that has rules for each field </li>
<li>Product model to store product details like Model, Brand name, Price, details of images of products etc that has rules for each field </li>
<li>Brand model that stores various brand names that has rules for each field. </li>
<li>Site Vars model that stores details like address, office timings, contact no. etc. for the organistion and has rules for each field.</li>
</ul>

<li>Various RESTful APIs are developed here that has end-points to perform various operations, being it registering new user, signing in previous user, adding, updating and deleting of previous products, and updating user details.
</li>

<li>Nodemailer and Mailgen are used in order to generate a mail for authenticating user email address, whenever the user registers, or updates the email address. The link sent via mail is used to authenticate the mail and update the change on database.</li>

<li>The password is encrypted using bcrypt library, so that encrypted password that has salt is stored on database, and the same is retreived and verified when signing in.
</li>
<li>josnwebtoken is used to generate a token and store it as a cookie when the user sign in.
</li>
<li>Site vars like address, office timings, contact no. etc. can also be added and updated using the routes created for the same.
</li>
</ol>

<ol>
<li>The front end for this project is created using ReactJS. Various libraries like Material UI, Toastify, React Bootstrap are used to create a UI that the user will love to use and stay on the site.
</li>
<li>Formik and Yup are used to create the forms for various purposes like registering new users, signing in and much more. Axios is used to send requests to the backend, which further reverts back to the front end.
</li>

<li>
  React Redux is used to create a store that stores the data like details of current user, currently selected product, notifications(if any). The required actions are dispatched and reducers update the current state of the data stored in the store.
</li>

<li>
   Modals are used at various places and stepper is created for email change, that has 3 steps:- check previous mail, check if new mail is not same as previous one and confirm.
</li>
<li>
  All the roues created on back-end can be used from this front-end through forms created using formik.

</li>
<li>
  Various Roles have been defined, which states that Product Details, and Site Vars can be updated only by admin, while other detials like, user details, can be updated by respective users.

</li>
<li>
  Item selected by user adds into the cart, and order is confirmed by making a payment via a paypal gateway used at the front-end.

</li>
<li>
  New Purchase history is added to the database and and displayed in the form of a a table.

</li>
<li>
  Various toasts are displayed, like a success toast whenever an operation is succesfully made and error toast is displayed whenever an error occurs.

</li>
  
</ol>
