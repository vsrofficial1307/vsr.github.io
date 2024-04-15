

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Education Platform</title>
<style>
  body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
  }
  .header {
    background-color: #007bff;
    color: #ffffff;
    padding: 10px 20px;
    text-align: center;
  }
  .nav-bar {
    background-color: #333;
    color: white;
    overflow: hidden;
  }
  .nav-bar a {
    float: left;
    display: block;
    color: white;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
  }
  .nav-bar a:hover {
    background-color: #ddd;
    color: black;
  }
  .main-content {
    padding: 20px;
  }
  .footer {
    background-color: #007bff;
    color: #ffffff;
    text-align: center;
    padding: 10px;
    position: fixed;
    bottom: 0;
    width: 100%;
  }



    /* Style for the courses menu */
    .courses-menu {
      display: none; /* Hidden by default */
      position:absolute; top: 150px; left: 100px; width: 200px; height: 200px;; /* Positioning relative to its container */
      background-color: black;
      min-width: 200px;
      box-shadow: 0 8px 16px 0 rgba(0,0,0,0.2);
      padding: 12px 16px;
      z-index: 1;
    }
    /* ... other existing styles ... */
</style>
</head>
<body>

<div class="header">
  <h1>Welcome to Education Platform VSR </h1>
</div>

<div class="nav-bar">
  <a href="#home">Home</a>
 
  <a href="javascript:void(0);" onclick="toggleCoursesMenu()">Courses</a>
   <!-- Courses Menu -->
   <div id="coursesMenu" class="courses-menu">
     <h4>Course Details</h4>
     <p>Course 1: CHEMISTRY CLASS 12th</p>
     <p>Course 2: Advanced Mathematics</p>
     <p>Course 3: Organic Chemistry</p>
     <!-- Add more courses as needed -->
   </div>
  <a href="#about">About</a>
  <!-- ... existing header, nav-bar, and main-content ... -->

  <!-- Contact Section -->
  <div class="nav-bar">
    <!-- ... existing nav-bar links ... -->
    <a href="javascript:void(0);" onclick="toggleContactMenu()">Contact</a>
  </div>

  <!-- Contact Menu -->
  <div id="contactMenu" class="contact-menu">
    <h4>Contact Details</h4>
    <p>Email: vishalsinghji1307@gmail.com</p>
    <p>Phone: +918448853682</p>
    <p>Address: 123 Education Lane, Knowledge City, 4567</p>
  </div>
  
  

  <!-- ... existing footer ... -->

  <script>
    // Function to toggle the contact menu
    function toggleContactMenu() {
      var contactMenu = document.getElementById("contactMenu");
      if (contactMenu.style.display === "none") {
        contactMenu.style.display = "block";
      } else {
        contactMenu.style.display = "none";
      }
    }
  </script>


<script>
    // Function to toggle the courses menu
    function toggleCoursesMenu() {
      var coursesMenu = document.getElementById("coursesMenu");
      if (coursesMenu.style.display === "none") {
        coursesMenu.style.display = "block";
      } else {
        coursesMenu.style.display = "none";
      }
    }
  </script>



</div>

<div class="main-content">
  <h2>Courses Offered</h2>
  <p>Here you can find courses for various competitive exams like JEE, NEET, and more.</p>
  <!-- Add more content here -->
</div>

<div class="footer">
  <p>Footer content here</p>
</div>




</body>
</html>
