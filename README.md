<!doctype html>
<html lang="en"> 
 <head> 
  <meta charset="UTF-8"> 
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
  <title>BlueDark and White Themed Website</title> 
  <style>
        /* Basic Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background-color: #001f3f; /* BlueDark Background */
            color: #f1f1f1; /* White Text */
            font-family: Arial, sans-serif;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }

        /* Header Section */
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px;
            background-color: #003366; /* Darker Blue for Header */
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.5);
        }

        /* Logo Style */
        .logo {
            font-size: 30px;
            font-weight: bold;
            color: #f1f1f1; /* White logo */
            text-transform: uppercase;
            letter-spacing: 2px;
        }

        /* Navigation Links */
        nav {
            display: flex;
            justify-content: space-between;
            width: 250px; /* Distance between links */
        }

        nav a {
            color: #f1f1f1;
            text-decoration: none;
            font-size: 18px;
            font-weight: bold;
            transition: color 0.3s ease;
        }

        nav a:hover {
            color: #00aced; /* Hover Color for Facebook & YouTube */
        }

        /* Main Section */
        .main-content {
            text-align: center;
            padding: 100px 20px;
            flex-grow: 1;
        }

        .main-content h1 {
            font-size: 48px;
            margin-bottom: 20px;
        }

        .main-content p {
            font-size: 20px;
            line-height: 1.6;
        }

        /* Footer Section */
        footer {
            background-color: #003366; /* Darker Blue for Footer */
            padding: 10px 0;
            text-align: center;
        }

        footer p {
            margin: 0;
            color: #fff;
            font-size: 16px;
        }
    </style> 
 </head> 
 <body> <!-- Header Section --> 
  <header> 
   <div class="logo">
    Using free
   </div> <!-- Custom Designed Logo --> 
   <nav> <!-- Facebook and YouTube Links --> <a href="https://www.facebook.com" target="_blank">Facebook</a> <a href="https://www.youtube.com" target="_blank">YouTube</a> 
   </nav> 
  </header> <!-- Main Content --> 
  <div class="main-content"> 
   <h1>Welcome to the BlueDark and White Themed Website</h1> 
   <p>This is a simple website where you can find links to Facebook and YouTube. Enjoy exploring our platform!</p> 
  </div> <!-- Footer Section --> 
  <footer> 
   <p>© 2024 My Website. All rights reserved.</p> 
  </footer> 
 </body>
</html>