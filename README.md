
<h1>Inventory Management System API</h1>

<h2>ERD</h2>
https://imgur.com/a/8KeO6xA

<h2>Repositories for application</h2>
https://github.com/Team-Zero-Errors/ims-project-api
<p></p>
https://github.com/Team-Zero-Errors/ims-project-client
<p></p>

<h2>How it Works</h2>
<p>After user logins in, all items are automatically displayed for that specific
user, showing item name, price and quantity for items in that users inventory.
User can create new items that will automatically be added to display.
For each item in the inventory you can update and delete. For update a new
view will appear and the input fields are automatically populated with the
current info, the user can change it and save it, which will then be automatically
populated into the inventory list. If the user deletes and item it will be
removed from the inventory list.</p>

<h2>Deployed sites</h2>
https://ims-project-api.herokuapp.com
<br>
https://team-zero-errors.github.io/ims-project-client/

<h2>What technologies were used:</h2>

<ul>
<li>Express</li>
<li>Mongoose</li>
<li>MongoDB</li>
<li>Command Terminal</li>
<li>Curl scripts</li>
<li>Heroku</li>
<li>mLab</li>
</ul>

<h2>Development Process:</h2>
<ul>
<li>Team worked together on getting the repositories for both client and api up and running</li>
<li>Team of three: Scott Holm, Katherine Ward, Jason Vo</li>
<li>We started out with each person working on a feature. One person worked on the user authentication in the front end, one person set up the handlebars in the front end, and the last person worked on setting up the backend.</li>
<li>Made a new file and set up our item model schema and its parameters (name, price, quantity) in the models folder.</li>
<li>Made a new file and set up our item routes</li>
<li>Require route files in server.js and register route files.</li>
<li>Created an item folder under scripts that contain curl scripts for each crud action. (create, destroy, index, show, update)</li>
<li>Test curlscripts and once successful, move to client side and start making the connection between client and api.</li>
</ul>

<h2>Future Iteration/ fixed problems</h2>
<ul>
<li>Fix: Update Price and Quantity to be numbers vs string</li>
<li>Future: create user profile and associated company they work for</li>
<li>Future: create ability for user to create orders which will automatically
update the inventory</li>
</ul>

<h2>API Routes</h2>
<ul>
<li>user/sign-in    **GET</li>
<li>user/sign-up    **POST</li>
<li>user/sign-out    **DELETE</li>
<li>user/change-password    **PATCH</li>
<li>items/    **GET</li>
<li>items/:id    **GET</li>
<li>items/:id    **PATCH</li>
<li>items/:id    **DELETE</li>
<li>items/    **POST</li>
</ul>
