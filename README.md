# first_big_homework_project

<h1></h1>
<p>Below are the requirements I followed to complete this assignment. It involved manipulating an array of objects using functions.</p>
<ol>
    <li>Use the command line to make a new folder called first_big_homework_project.</li>
    <li>Use the command line to create index.html, index.css, and index.js.</li>
    <li>Create a git repository in this folder and connect it to a new Github repo (make commits as you go).</li>
    <li>Use the “code” keyword to open the js file in VS code.</li>
    <li>Go to https://jsonplaceholder.typicode.com/users Links to an external site.and copy the array of 10 user objects.</li>
    <li>Create a new variable called “users” and set it equal to the copied array.</li>
    <li>We no longer want to be responsible for the users’ phone numbers. Please create a function that will loop through the array and set the phone numbers = null. Call the function.</li>
    <li>Make a function called getUserInfo that returns the user object found using the email passed as a parameter.</li>
    <li>Kurtis Weissnat (Telly.Hoeger@billy.biz) just submitted a request to change his username to “Eren Yeager”. We want to be able to change people’s usernames easily.</li>
    <ol>
        <li>Make a function that takes 2 parameters “email” and “newUsername”.</li>
        <li>The function should change the username of the user with that email.</li>
        <li>Pass your arguments changeUsername("Telly.Hoeger@billy.biz", “Eren Yeager”).</li>
    </ol>
    <li>We just started a points program and have a list of how many points each user gets each month based on their subscription. [50, 20, 40, 33, 60, 20, 90, 110, 15, 30].</li>
    <ol>
        <li>The array is ordered so that arr[0] ‘50’ is for the first user, etc.</li>
        <li>Make a function that will Iterate through this array, grab the data, and create new properties on the objects called monthlyPoints and set it equal to the data.</li>
        <li>For example to first user should have a property monthlyPoints: 50.</li>
    </ol>
    <li>Make a variable months and set it equal to a number.</li>
    <li>Make a function that For every month, add points to the users’ account.</li>
    <li>This month is special! We are going to add an additional 10% to everyone’s point totals! Create a function to do this (example: if someone has 200 points, we will bump it up to 220).</li>
    <li>The user with email Chaim_McDermott@dana.io has submitted a request to delete her account. Make a function that will remove her from the array (taking the email as a parameter).</li>
</ol>
