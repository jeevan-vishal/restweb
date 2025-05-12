# Ex.07 Restaurant Website
## Date:12/05/2025

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
home.html
<html>
  <head>
    <title>Restaurant website</title>
    <style>
    .imgbg{
      background-image: url("premium.jpg");
      background-size: cover;
      background-position: center;
      height: 60vh;
    }
   nav {
      background-color: black;
      color: white;
      padding: 10px;
      display: flex;
      justify-content: center;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
    }


      .text1{
        font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
         text-align: center;
         color: black;
         background-color:rgba(0, 0, 0, 0.178);
      }
  </style>
  </head>
  <body>
     <div class="imgbg">
         <h1>Restaraunt</h1>
         <nav>
          <a href="fourth.html">Home</a>
          <a href="first.html">Menu</a>
          <a href="second.html">About</a>
          <a href="third.html">Contact</a>
          </nav>
        <div style="width: 2px; height: 100px; background-color: black;"></div>
    </div>
    <div class="text1">
      <br><br><br><br><h1>The Gilded Spoon</h1>
      <h1>Savor the Flavor. Experience the Difference(created by R.Rubasri)</h1>
       <h3>The premium and authentic cuisines</h3>
      <p>Good food. Great company. That’s what we’re all about. 
        Whether you're here for a quick bite or a celebration, 
        we’ve got something for everyone to enjoy.</p>
    </div>
     
  </body>
</html>

menu.html
<!DOCTYPE html>
<html>
<head>
  <style>
    body {
  background-color: #f5f5f569; 
  margin: 0;
  font-family: Arial, sans-serif;
}

    .card-container {
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
      margin-top: 30px; 
    }

    .card {
      width: 300px;
      border: 1px solid #ddd;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      overflow: hidden;
      background-color: #fff;
      transition: transform 0.3s;
      border-color:black;
      border-width: 5px;
    }

    .card:hover {
      transform: scale(1.03);
    }

    .card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }

    .card-content {
      padding: 15px;
      text-align: center;
    }

    .card-content h3 {
      margin: 10px 0;
    }

    .card-content p {
      color: #555;
      font-size: 14px;
    }

    .text {
      background-color: #555555de;
      color: white;
      text-align: center;
      padding: 10px 0;
    }
   nav {
      background-color: black;
      color: white;
      padding: 10px;
      display: flex;
      justify-content: center;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
    }
  </style>
</head>
<body class="body">
  <nav class="nav">
    <br><a href="fourth.html" color: white>Home</a>
    <a href="first.html">Menu</a>
    <a href="second.html">About</a>
    <a href="third.html">Contact</a>
    </nav>
  <div class="text">
    <h1>MENU (FROM OUR HEART TO YOUR TABLE)</h1>
  </div>
  <div class="card-container">
    <div class="card">
      <img src="dish1.webp" alt="Dish Image">
      <div class="card-content">
        <h3>Moroccan Fennel Salad</h3>
        <p>The revved-up flavours of modern Jerusalem and beyond including a truly memorable Moroccan fennel salad with a yoghurty harissa dressing.</p>
        <p>Price: $120</p>
      </div>
    </div>

    <div class="card">
      <img src="dish2.jpg" alt="Dish Image">
      <div class="card-content">
        <h3>Spaghetti</h3>
        <p>This is a real Italian spaghetti carbonara recipe, in all its creamy glory but made the traditional way with no cream!</p>
        <p>Price: $12–$18</p>
      </div>
    </div>

    <div class="card">
      <img src="dish3.jpg" alt="Dish Image">
      <div class="card-content">
        <h3>Paella – Spain</h3>
        <p>This famous saffron-infused rice dish is a traditional Spanish recipe that comes fully loaded with seafood or anything your heart desires!</p>
        <p>Price: $20</p>
      </div>
    </div>

    <div class="card">
      <img src="dish4.jpg" alt="Dish Image">
      <div class="card-content">
        <h3>Greek Moussaka</h3>
        <p> A very traditional Greek Moussaka recipe made with thick layers of eggplant, beef in tomato sauce, topped with béchamel sauce.</p>
        <p>Price: $25</p>
      </div>
    </div>
    <div class="card">
      <img src="dish5.jpg" alt="Dish Image">
      <div class="card-content">
        <h3>Sushi Rolls (Japan)</h3>
        <p>The filling of Spicy Tuna Rolls is raw fish. But the spiciness from the sriracha makes the diced raw tuna easier to eat raw fish.</p>
        <p>Price: $15</p>
      </div>
    </div>
    <div class="card">
      <img src="dish7.jpg" alt="Dish Image">
      <div class="card-content">
        <h3>Dim Sum (China) – Steamed dumplings and buns</h3>
        <p>a traditional Chinese meal consisting of small, bite-sized dishes, often served in steamer baskets or small plates, and typically enjoyed for brunch.</p>
        <p>Price: $15</p>
      </div>
    </div>
    <div class="card">
      <img src="dish6.jpg" alt="Dish Image">
      <div class="card-content">
        <h3>Chicken Tikka Masala(India)</h3>
        <p>Chicken tikka masala is a popular curried dish made with boneless chicken, ground spices, onions, tomatoes, cream and herbs.</p>
        <p>Price: $15</p>
      </div>
    </div>
    <div class="card">
      <img src="dish8.jpg" alt="Dish Image">
      <div class="card-content">
        <h3>beef soft rib fry</h3>
        <p>Mix brown sugar, chile sauce, ketchup, soy sauce, Worcestershire sauce, rum, garlic, mustard, and pepper together in a bowl. Coat ribs with sauce and marinate.</p>
        <p>Price: $25</p>
      </div>
    </div>
  </div>
</body>
</html>

About.html
<!DOCTYPE html>
<html>
<head>
  <title>About Us | [Restaurant Name]</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #0a02027e;
      color: #921414d8;
    }

    nav {
      background-color: black;
      color: white;
      padding: 10px;
      display: flex;
      justify-content: center;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
    }

    .about-container {
      max-width: 1000px;
      margin: 40px auto;
      padding: 0 20px;
      
    }

    .about-container h1 {
      text-align: center;
      color: #444;
    }

    .about-text {
      font-size: 20px;
      line-height: 1.6;
      margin-top: 20px;
      font-family:Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
      font-style: italic;
    }

    .about-image {
      text-align: center;
      margin: 30px 0;
    }

    .about-image img {
      max-width: 90%;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }
    .text2{
        background-color: #444;
        color:aliceblue;
    }
  </style>
</head>
<body>
  <nav>
    <a href="fourth.html">Home</a>
    <a href="first.html">Menu</a>
    <a href="second.html">About</a>
    <a href="third.html">Contact</a>
  </nav>

  <div class="about-container">
    <h1 class="text2">About Us</h1>

    <div class="about-image">
      <img src="restaraunt image.jpg" alt="Our Restaurant">
    </div>

    <div class="about-text">
      <p>
        Welcome to <strong>The Gilded spoon Restaraunt</strong> — where every dish is a celebration of flavor, culture, and community. Founded in 1994, our mission has always been to bring authentic, handcrafted meals to your table, blending traditional recipes with modern techniques.
      </p>
      <p>
        Our chefs source the finest ingredients, locally when possible, and craft dishes that not only satisfy hunger but tell a story. From our signature  to our warm and welcoming atmosphere, we invite you to experience food that feels like home.
      </p>
      <p>
        Whether you're here for a casual lunch, a romantic dinner, or a special family gathering, we strive to make every visit memorable.
      </p>
    </div>
  </div>
</body>
</html>

contact page
<html>
    <head>
        <title>Contact Us|The Gilded Spoon</title>
        <style>
     nav {
      background-color: black;
      color: white;
      padding: 10px;
      display: flex;
      justify-content: center;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
    }
    .heading{
        background-color: rgba(0, 0, 0, 0.384);
        color: rgba(219, 235, 8, 0.719);
        font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
        font-style:italic;
        text-align:center;
    }
    .text1{
        height:500px;
        width:500px;
        background-color: rgba(8, 117, 81, 0.815);
        color:black;
        text-align: left;
        border-radius:5px;
        border-width: 10px solid black;
   
    }
    .align{
        text-align: center;
        display: flex;
        justify-content: center;
    }
    .text2{
        background-color: green;
        color: white;
        height:30px;
        width:500px;
    }
    .text3{
        text-align: center;
    }
    .btn{
        background-color: green;
        color:white;
        border-radius: 5px;
        border-width: 5px;
        border-color: black;
        height:50px;
        width:90px;
    }
    .btn-align{
        text-align: center;
    }
     body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background: #03471893;
}
        </style>
    </head>
    <body>
     <nav>
    <a href="fourth.html">Home</a>
    <a href="first.html">Menu</a>
    <a href="second.html">About</a>
    <a href="third.html">Contact</a>
  </nav>
  <div class="heading">
    <h1>The Gilded Spoon Restaraunt</h1>
  </div>
  <div class="align">
    <div class="text1">
    <div class="text2">
       <h3 class="text3"> Contact Us </h3></div>
    <form>
        <br>
        Name:
        <input type="text" ><br><br>
        Email Id:
        <input type="text" ><br><br>
        Phone no:
        <input type="text"><br><br>
        Message:
        <input type="textarea"><hr color="black"><br><br>
       <div class="btn-align"><button class="btn">
        Submit</button></div> 
    </form>
    <center><h3><i>For any further details or queries contact us at 
        www.gildedspoon.com or through an email gildedspoon@gmail.com
        For booking Purposes you can place your order by calling
        the below number 8100 8800 7569
        To Know about more details about our restaraunt click the link!!!
        <a href="fifth.html" color: white>www.adminpage.ac.in</a>
    </i></h3></center>

    </div>
  </div>
 
    </body>
</html>
Admin page
<html>
    <head>
        <title>Staffs details</title>
         <meta charset="UTF-8" />
         <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
         <title>Admin - Staff Management</title>
        <style>
         nav {
      background-color: black;
      color: white;
      padding: 10px;
      display: flex;
      justify-content: center;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
    }
    body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background: #1414148c;
}

header {
  background-color: #343a40;
  color: white;
  padding: 20px;
  text-align: center;
}

.staff-container {
  padding: 30px;
}

.staff-container h2 {
  text-align: center;
  margin-bottom: 20px;
}

.staff-card {
  display: flex;
  background-color: white;
  margin: 20px auto;
  max-width: 800px;
  box-shadow: 0 0 10px rgba(0,0,0,0.1);
  border-radius: 10px;
  overflow: hidden;
}

.staff-card img {
  width: 200px;
  object-fit: cover;
  height: auto;
}

.staff-info {
  padding: 20px;
}

.staff-info h3 {
  margin-top: 0;
}

</style>
    </head>
    <body>
  <nav>
    <a href="fourth.html">Home</a>
    <a href="first.html">Menu</a>
    <a href="second.html">About</a>
    <a href="third.html">Contact</a>
  </nav>
  <body>
  <header>
    <h1>Restaurant Admin Panel</h1>
  </header>

  <section class="staff-container">
    <h2>Chefs and Staff</h2>
    <div class="staff-card">
      <img src="staff1.jpg" alt="Chef Mario" />
      <div class="staff-info">
        <h3>Chef Mario Rossi</h3>
        <p><strong>Speciality:</strong> Italian Cuisine</p>
        <p>Experience: 10 years</p>
      </div>
    </div>

    <div class="staff-card">
      <img src="staff2.jpg" alt="Chef Aisha" />
      <div class="staff-info">
        <h3>Chef Sanjana Kapoor</h3>
        <p><strong>Speciality:</strong> Indian Cuisine</p>
        <p>Experience: 8 years</p>
      </div>
    </div>
     <div class="staff-card">
      <img src="staff3.jpg" alt="Chef Aisha" />
      <div class="staff-info">
        <h3>Chef Luna Wei</h3>
        <p><strong>Speciality:</strong> chinese Cuisine</p>
        <p>Experience: 8 years</p>
      </div>
    </div>
    <div class="staff-card">
      <img src="manager.jpg" alt="Chef Aisha" />
      <div class="staff-info">
        <h3>Manager Sara  </h3>
        <p>Experience: 8 years</p>
      </div>
    </div>
    <!-- Add more staff-card blocks as needed -->
  </section>
    </body>
</html>
```

## OUTPUT:

![alt text](<Screenshot 2025-05-11 163352.png>)

![alt text](<Screenshot 2025-05-11 163430.png>)

![alt text](<Screenshot 2025-05-11 163608.png>)

![alt text](<Screenshot 2025-05-11 163817.png>)

![alt text](<Screenshot 2025-05-11 163904.png>)

![alt text](<Screenshot 2025-05-11 163933.png>)

![alt text](<Screenshot 2025-05-11 164017.png>)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
