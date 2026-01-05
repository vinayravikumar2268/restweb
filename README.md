# Ex.07 Restaurant Website
## Date:23.12.2025

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
admin.html
~~~
<!DOCTYPE html>
<html>
<head>
    <title>Madurai - Administration</title>
    <link rel="stylesheet" href="index.css">
</head>
<body>
<header>
    <h1>Madurai Biriyani Restaurant</h1>
</header>

<nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<section>
    <h2>Meet Our Team</h2>
    <div class="team-grid">
        <div class="card"><img src="chef.png" ><p>Head Chef </p></div>
        <div class="card"><img src="manager.png"><p> Manager</p></div>
    </div>
</section>

<footer>
    © Designed by kamalesh.
</footer>
</body>
</html>
~~~
menu.html
~~~

<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Madurai Biriyani - Menu</title>
    <link rel="stylesheet" href="index.css">
</head>
<body>
<header>
    <h1>Madurai Biriyani Restaurant</h1>
</header>

<nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<section>
    <h2>Our Menu</h2>
    <div class="menu-grid">
        <div class="card"><img src="lunch.jpeg"><p>lunch-₹660</p></div>
        <div class="card"><img src="Kari-Dosa-1024x538.jpg"><p> Kari Dosa- ₹60</p></div>
        <div class="card"><img src="nonveg.jpeg"><p>Nonveg items - ₹320</p></div>
        <div class="card"><img src="CHICKENBIRYANI.jpeg"><p>CHICKENBIRYANI - ₹250</p></div>
    </div>
</section>

<footer>
    © Designed by kamalesh.
</footer>
</body>
</html>
~~~
contact.html
~~~
<!DOCTYPE html>
<html>
<head>
    <title>Madurai Biriyani Restaurant</title>
    <link rel="Welcome" href="index.css">
</head>
<body>
<header>
    <h1>Madurai Biriyani Restaurant</h1>
</header>

<nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<section>
    <img src="poster.jpeg" alt="Banner" style="width:80%; max-width:900px; border-radius:10px;">
    <h2>Welcome to Madurai Biriyani </h2>
    <p>Authentic flavors, fresh meat, and a cozy dining experience.</p>
</section>

<footer>
    © Designed by kamalesh.
</footer>
</body>
</html>
~~~
index.css
~~~
body {
    font-family: Arial, sans-serif;
    margin: 0;
    background-color: white;
    color: #333;
}
header {
    background-color: black; /* Primary color */
    color: white;
    padding: 20px;
    text-align: center;
}
nav {
    background-color: #333;
    text-align: center;
}
nav a {
    color: white;
    text-decoration: none;
    margin: 0 15px;
    padding: 8px;
    display: inline-block;
}
nav a:hover {
    background-color: cyan; /* Accent color */
    color: #333;
}
section {
    padding: 40px;
    text-align: center;
}
h2 {
    color: #b33a3a;
    font-style:oblique;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}
.menu-grid, .team-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
    max-width: 1000px;
    margin: 20px auto;
    text-align: center;
}
.card {
    background-color: white;
    padding: 15px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    font-style: italic;
    color:#b33a3a;
    text-shadow: fuchsia;
}
.card img {
    width: 80px;
    height: 100px;
    object-fit: cover;
    border-radius: 25px;
    align-items: center;
    border: orange;}
footer {
    background-color:#333;
    color: white;
    
    text-align: center;
    padding: 15px;
}
contact-container {
            max-width: 800px;
            margin: 0 auto;
            text-align: left;
            padding: 20px;
            background-color: white;
            border-radius: 12px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        .contact-container h2 {
            text-align: center;
            color: blue;
        }
        .contact-container p {
            font-size: 18px;
            margin: 10px 0;
        }
        .contact-container b {
            color: silver;
        }
~~~
homt.html
~~~
<!DOCTYPE html>
<html>
<head>
    <title>Madurai Biriyani Restaurant</title>
    <link rel="Welcome" href="index.css">
</head>
<body>
<header>
    <h1>Madurai Biriyani Restaurant</h1>
</header>

<nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
</nav>

<section>
    <img src="poster.jpeg" alt="Banner" style="width:80%; max-width:900px; border-radius:10px;">
    <h2>Welcome to Madurai Biriyani </h2>
    <p>Authentic flavors, fresh meat, and a cozy dining experience.</p>
</section>

<footer>
    © Designed by kamalesh.
</footer>
</body>
~~~
## OUTPUT:
<img width="1477" height="779" alt="Screenshot 2026-01-05 172355" src="https://github.com/user-attachments/assets/33009f6d-594d-4bfe-b364-b416228b968d" />
<img width="1536" height="784" alt="Screenshot 2026-01-05 172036" src="https://github.com/user-attachments/assets/1039c86e-20a2-4002-8434-121bba565b14" />
<img width="1471" height="574" alt="Screenshot 2026-01-05 172134" src="https://github.com/user-attachments/assets/65cd7340-ab89-4e18-9973-4a44a58cb6b5" />
<img width="1479" height="494" alt="Screenshot 2026-01-05 172248" src="https://github.com/user-attachments/assets/7939fd01-e0c6-40c3-8eb3-df540749626d" />


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
