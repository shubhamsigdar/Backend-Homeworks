 How to connect index.html with index.js?
 <script src="index.js"></script>


 What moment.js library do?
 It is a library which can help format dates in a human readable way


 How we use moment function in index.js?
 first we have to install file http://momentjs.com/ and then copy and paste on moment.min.js file and then we can use moment function in index.js
 we can add moment.js to our website by downloading the moment.min.js file in the same directory and including it in our index.html file.
<!-- index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Example</title>
  <link rel="stylesheet" href="index.css">
  <script src="moment.min.js"></script>
  <script src="index.js"></script>
</head>
<body>
  <h1>Hello from HTML!</h1>
</body>
</html>
 
// index.js
  console.log("Hello from JavaScript!");
  console.log(moment().startOf('day').fromNow());



Why we write <script src="moment.min.js"></script> before <script src="index.js"></script>?
moment.min.js gets loaded before index.js, which means you can use the moment function in index.js 


What is npm?
It is a package manager made specifically for node.js, a JavaScript runtime designed to run on the server, not the frontend. 


How to check node is installed in your computer?
node -v


What is package.json file and How we can create?
This is a configuration file that npm uses to save all project information. 
we can create this by writing on terminal npm init