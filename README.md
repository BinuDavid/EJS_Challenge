# EJS Challenge

## Challenge 1
Add Home route to server code, and load content

## Challenge 2
Utilizing EJS, push server content to webpage

## Challenge 3
Utilizing EJS, add existing partials for header and footer to home route

## Challenge 4
Modify file structure to include a "partials" folder within views. Correct any errors seen in browser

## Challenge 5
Build out the about and contact pages similar to the home route

## Challenge 6
Make navigation links function

## Challenge 7
Add Compose route to server code, and add content

## Challenge 8
Using the text input in compose, send that data from server into console.log

## Challenge 9
Modify form elements to match design provided. Should include 2 labels, text, and textarea with publish styled utilizing bootstrap

## Challenge 10
Save both the post title and content as an object on server

## Challenge 11
Create a global variable posts which should be an array. Each post generated from compose route should get moved into this variable. Once posts is updated, you should be automatically navigated to the home route.

## Challenge 12
Remove any log statements from app.js except for the log statement within app.listen. Within home.ejs, insert a log statement which will show the posts array

## Challenge 13
Modifying the existing code within home.ejs, create a for loop to target just the title's of the post array, and log them to the console. To test, make sure to create 2 - 3 posts from the compose route

## Challenge 14
Modify existing for loop from Challenge 13 with the forEach method

## Challenge 15
Replace the console.log statement last used in Challenge 14, to render each post on home.ejs

## Challenge 16
Using route parameters, log any path following the posts route (localhost:3000/posts/{any path})

## Challenge 17
Create a post titled "Test", and create a route in app.js that will log "Match found!" if the route specified in the browser matches the post title

## Challenge 18
Utilize Lo Dash by reading the documentation, installing, and using lowercase method to allow the browser url to match post title in cases where the url is in an alternate case or has hyphen(s) between post titles, such as: "Another-post"

## Challenge 19
Utilizing post.ejs and app.js, replace the log statement for "Match found!" produced in Challenge 18 with code to dynamically generate the title and content of the matched post

## Challenge 20
As blog posts are generated in the home route, the webpage can get easily cluttered. Research how to truncate the blog posts on the home route, and implement

