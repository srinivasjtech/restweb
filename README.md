# Ex.07 Restaurant Website
## Date:05.10.25

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

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Aasife Restaurant</title>
    <link rel="stylesheet" href="style1.css">
</head>
<body>
    <nav class="navbar">
        <div class="logo">Aasife Restaurant</div>
        <ul class="nav-links">
            <li><a href="home.html">Home</a></li>
            <li><a href="menu.html">Menu</a></li>
            <li><a href="admn.html">Administrators</a></li>
            <li><a href="contact.html">Contact Us</a></li>
        </ul>
    </nav>
    <header class="hero">
        <h1>Welcome to Aasife Restaurant</h1>
        <p>Your Wish, Our Dish!</p>
    </header>
    <section class="about">
        <h2>About Us</h2>
        <p>Located in Sirkali, Mayiladuthurai. We serve delicious food with love and care.</p>
    </section>
    <section class="images">
        <img src="ph2.png" alt="Dish 1">
        <img src="ph1.png" alt="Dish 2">
        <img src="ph4.png" alt="Dish 3">
    </section>
    <footer>
        Designed by Srinivas J (25015562)
    </footer>
</body>
</html>

menu.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Menu | Aasife Restaurant</title>
    <link rel="stylesheet" href="style2.css">
</head>
<body>
    <nav class="navbar">
        <div class="logo">Aasife Restaurant</div>
        <ul class="nav-links">
            <li><a href="home.html">Home</a></li>
            <li><a href="menu.html" class="active">Menu</a></li>
            <li><a href="admn.html">Administrators</a></li>
            <li><a href="contact.html">Contact Us</a></li>
        </ul>
    </nav>
    <section class="menu">
        <h2>Our Menu</h2>
        <div class="menu-items">
            <div class="menu-item">
                <img src="buckbiriyani.png" alt="Buck Biriyani">
                <h3>Buck Biriyani</h3>
                <p>Special buck biriyani with aromatic spices.</p>
                <span class="price">₹200</span>
            </div>
            <div class="menu-item">
                <img src="breadgravy.png" alt="Bread Gravy">
                <h3>Bread Gravy</h3>
                <p>Soft bread served with rich, creamy gravy.</p>
                <span class="price">₹120</span>
            </div>
            <div class="menu-item">
                <img src="biriyani.png" alt="Biriyani">
                <h3>Biriyani</h3>
                <p>Classic biriyani with flavorful rice and spices.</p>
                <span class="price">₹180</span>
            </div>
            <div class="menu-item">
                <img src="maincourse.png" alt="Main Course">
                <h3>Main Course</h3>
                <p>Assorted main course dishes for every taste.</p>
                <span class="price">₹250</span>
            </div>
            <div class="menu-item">
                <img src="noodlesrice.png" alt="Noodles & Rice">
                <h3>Noodles & Rice</h3>
                <p>Delicious noodles and rice varieties.</p>
                <span class="price">₹160</span>
            </div>
        </div>
    </section>
    <footer>
        Designed by Srinivas J (25015562)
    </footer>
</body>
</html>

admn.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Administrators | Aasife Restaurant</title>
    <link rel="stylesheet" href="style3.css">
</head>
<body>
    <nav class="navbar">
        <div class="logo">Aasife Restaurant</div>
        <ul class="nav-links">
            <li><a href="home.html">Home</a></li>
            <li><a href="menu.html">Menu</a></li>
            <li><a href="admn.html" class="active">Administrators</a></li>
            <li><a href="contact.html">Contact Us</a></li>
        </ul>
    </nav>
    <div class="admin">
        <h2>Administrators of Aasife</h2>
        <div class="admin-list">
            <div class="admin-card">
                <img src="person1.jpeg" alt="Founder">
                <div class="role founder">Founder</div>
            </div>
            <div class="admin-card">
                <img src="person2.jpg" alt="Leader">
                <div class="role">Leader</div>
            </div>
            <div class="admin-card">
                <img src="person3.webp" alt="CoLeader">
                <div class="role">Co-Leader</div>
            </div>
            <div class="admin-card">
                <img src="person4.png" alt="Administrator">
                <div class="role">Administrator</div>
            </div>
            <div class="admin-card">
                <img src="person5.png" alt="Manager">
                <div class="role">Manager</div>
            </div>
            <div class="admin-card">
                <img src="person6.jpg" alt="Co-Manager">
                <div class="role">Co-Manager</div>
            </div>
            <div class="admin-card">
                <img src="person7.jpg" alt="Employee">
                <div class="role">Employee</div>
            </div>
        </div>
    </div>
    <footer>
        Designed By SRINIVAS J (25015562)
    </footer>
</body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Contact Us | Aasife Restaurant</title>
    <link rel="stylesheet" href="style4.css">
</head>
<body>
    <nav class="navbar">
        <div class="logo">Aasife Restaurant</div>
        <ul class="nav-links">
            <li><a href="home.html">Home</a></li>
            <li><a href="menu.html">Menu</a></li>
            <li><a href="admn.html">Administrators</a></li>
            <li><a href="contact.html" class="active">Contact Us</a></li>
        </ul>
    </nav>
    <div class="contact-container">
        <h2>Contact Us</h2>
        <div class="contact-info">
            <p><b>Instagram:</b> <a href="https://www.instagram.com/sri_ni_vas____03" target="_blank">@sri_ni_vas____03</a></p>
            <p><b>Facebook:</b> Aasife_restaurant</p>
            <p><b>Phone:</b> 9876543210</p>
        </div>
    </div>
    <footer>
        <i>Srinivas J (25015562)</i>
    </footer>
</body>
</html>

style1.css

body {
    font-family: Arial, sans-serif;
    margin: 0;
    background: #f8f8f8;
    color: #222;
}

.navbar {
    background: #8d5524;
    color: #fff;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 40px;
}

.logo {
    font-size: 1.8em;
    font-weight: bold;
}

.nav-links {
    list-style: none;
    display: flex;
    gap: 30px;
    margin: 0;
    padding: 0;
}

.nav-links li a {
    color: #fff;
    text-decoration: none;
    font-size: 1.1em;
    transition: color 0.2s;
}

.nav-links li a:hover {
    color: #ffd700;
}

.hero {
    background: #fff3e0;
    text-align: center;
    padding: 60px 20px 30px 20px;
}

.hero h1 {
    margin: 0 0 10px 0;
    font-size: 2.5em;
}

.about {
    text-align: center;
    margin: 40px 0 20px 0;
}

.images {
    display: flex;
    justify-content: center;
    gap: 30px;
    margin: 30px 0;
}

.images img {
    width: 300px;
    height: 200px;
    object-fit: cover;
    border-radius: 10px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.1);
}

footer {
    background: #8d5524;
    color: #fff;
    text-align: center;
    padding: 15px 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}

style2.css

body {
    font-family: Arial, sans-serif;
    margin: 0;
    background: #f8f8f8;
    color: #222;
}

.navbar {
    background: #8d5524;
    color: #fff;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 40px;
}

.logo {
    font-size: 1.8em;
    font-weight: bold;
}

.nav-links {
    list-style: none;
    display: flex;
    gap: 30px;
    margin: 0;
    padding: 0;
}

.nav-links li a {
    color: #fff;
    text-decoration: none;
    font-size: 1.1em;
    transition: color 0.2s;
}

.nav-links li a.active,
.nav-links li a:hover {
    color: #ffd700;
}

.menu {
    background: #fff;
    padding: 40px 20px;
    text-align: center;
}

.menu h2 {
    margin-bottom: 30px;
    font-size: 2em;
    color: #8d5524;
}
.menu-item img {
    width: 100%;
    height: 140px;
    object-fit: cover;
    border-radius: 8px;
    margin-bottom: 10px;
}

.menu-items {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 30px;
}

.menu-item {
    background: #fff3e0;
    border-radius: 10px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.07);
    padding: 20px 30px;
    width: 250px;
    text-align: left;
}

.menu-item h3 {
    margin: 0 0 10px 0;
    color: #8d5524;
}

.menu-item p {
    margin: 0 0 10px 0;
    font-size: 1em;
}

.price {
    font-weight: bold;
    color: #d2691e;
    font-size: 1.1em;
}

footer {
    background: #8d5524;
    color: #fff;
    text-align: center;
    padding: 15px 0;
    margin-top: 40px;
}

style3.css

body {
    font-family: Arial, sans-serif;
    margin: 0;
    background: #f8f8f8;
    color: #222;
}

.navbar {
    background: #8d5524;
    color: #fff;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 40px;
}

.logo {
    font-size: 1.8em;
    font-weight: bold;
}

.nav-links {
    list-style: none;
    display: flex;
    gap: 30px;
    margin: 0;
    padding: 0;
}

.nav-links li a {
    color: #fff;
    text-decoration: none;
    font-size: 1.1em;
    transition: color 0.2s;
}

.nav-links li a.active,
.nav-links li a:hover {
    color: #ffd700;
}

.admin {
    max-width: 1100px;
    margin: 40px auto 0 auto;
    padding: 20px;
    background: #fff;
    border-radius: 12px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.07);
    text-align: center;
}

.admin h2 {
    color: #8d5524;
    margin-bottom: 30px;
}

.admin-list {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 30px;
}

.admin-card {
    background: #fff3e0;
    border-radius: 10px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.07);
    padding: 20px 15px;
    width: 180px;
    text-align: center;
    transition: transform 0.2s;
}

.admin-card:hover {
    transform: translateY(-5px) scale(1.03);
}

.admin-card img {
    width: 120px;
    height: 120px;
    object-fit: cover;
    border-radius: 50%;
    margin-bottom: 12px;
    border: 3px solid #8d5524;
}

.role {
    font-size: 1.1em;
    color: #8d5524;
    font-weight: bold;
}

.founder {
    color: brown;
}

footer {
    background: #8d5524;
    color: #fff;
    text-align: center;
    padding: 15px 0;
    margin-top: 40px;
}

style4.css

body {
    font-family: Arial, sans-serif;
    margin: 0;
    background: #f8f8f8;
    color: #222;
}

.navbar {
    background: #8d5524;
    color: #fff;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 15px 40px;
}

.logo {
    font-size: 1.8em;
    font-weight: bold;
}

.nav-links {
    list-style: none;
    display: flex;
    gap: 30px;
    margin: 0;
    padding: 0;
}

.nav-links li a {
    color: #fff;
    text-decoration: none;
    font-size: 1.1em;
    transition: color 0.2s;
}

.nav-links li a.active,
.nav-links li a:hover {
    color: #ffd700;
}

.contact-container {
    max-width: 500px;
    margin: 60px auto 0 auto;
    background: #fff;
    border-radius: 12px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.07);
    padding: 40px 30px;
    text-align: center;
}

.contact-container h2 {
    color: #8d5524;
    margin-bottom: 25px;
}

.contact-info p {
    font-size: 1.1em;
    margin: 15px 0;
}

.contact-info a {
    color: #8d5524;
    text-decoration: none;
    font-weight: bold;
}

.contact-info a:hover {
    text-decoration: underline;
}

footer {
    background: #8d5524;
    color: #fff;
    text-align: center;
    padding: 15px 0;
    margin-top: 40px;
}

```

## OUTPUT:
![alt text](<Screenshot (2).png>)

![alt text](<Screenshot (3).png>)

![alt text](<Screenshot (4).png>)

![alt text](<Screenshot (5).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
