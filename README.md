# Ex.07 Restaurant Website
## Date:

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

## index.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SAVEETHA UNAVAGAM</title>
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Labrada:ital,wght@0,100..900;1,100..900&family=Lobster&family=Paytone+One&family=Spicy+Rice&display=swap" rel="stylesheet">
</head>
<body>
    <DIv class="title">
        SAVEETHA UNAVAGAM
    </DIv>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
                <li><a href="Resiter.html">Register</a></li>
            </ul>
        </nav>
    </header>
    <DIv>
        <div class="banner">
            <img class="fil" src="Landing Page.png" alt="">
            <div>
                <h1 class="te1">WELCOME TO SAVEETHA UNAVAGAM</h1>
                <p class="te2">Menus can vary from simple to elaborate, with options ranging from à la carte (ordering individual items) to prix fixe (set menus at a fixed price).
                   Dining experiences often vary by restaurant style, with casual settings offering quick, informal service, while fine dining places offer a slower-paced, more formal experience.
                   Chefs: Responsible for preparing the food. In fine dining, there may be multiple chefs specializing in different areas (e.g., pastry chefs, sous chefs).
                   
                  
                </p>
            </div>
        </div>
    </DIv>
    <footer>
        <p>&copy; 2024 Your Name</p>
    </footer>
</body>
</html>
```
## administration.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration - My Food Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <DIv class="title">
        SAVEETHA UNAVAGAM
    </DIv>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
                <li><a href="Resiter.html">Register</a></li>
            </ul>
        </nav>
    </header>

    <section class="administration">
        <h2>Meet Our Team</h2>
        <div class="team-member">
            <img src="https://images.squarespace-cdn.com/content/v1/57a6a44d2994ca6cbb9460b6/0326d596-2813-4e05-b225-1221a845e2b8/IMG_2256.jpeg" alt="Person 1">
            <h3>Dr. N.M. Veeraiyan - founder</h3>
        </div>
        <div class="team-member">
            <img src="https://pbs.twimg.com/profile_images/1835616750349750272/rMh3Kno__400x400.jpg" alt="Person 2">
            <h3>Madhampatty Rangaraj - Manager</h3>
        </div>
        <div class="team-member">
            <img src="https://kgo.googleusercontent.com/profile_vrt_raw_bytes_1587515369_10614.jpg" alt="Person 3">
            <h3>Sanjeev Kapoor  - Chef</h3>
        </div>
        <div class="team-member">
            <img src="https://yt3.googleusercontent.com/4G1SgaqEl81izq095JJwYmOawkBLEnMVBUP81Pef8uGTq80zn25FI2fzz2uwLRm7E0wN2QKj=s900-c-k-c0x00ffffff-no-rj" alt="Person 4">
            <h3>Venkatesh Bhat - Sous Chef</h3>
        </div>
        <div class="team-member">
            <img src="https://www.shutterstock.com/image-photo/young-african-waitress-wearing-apron-260nw-1059547040.jpg" alt="Person 5">
            <h3>Sarah Williams - Waitstaff</h3>
        </div>
        <div class="team-member">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRsC-lw3T2Fzg9GxJ15q3UbCOixaWI17Z4fEw&s" alt="Person 6">
            <h3>David Lee - Waitstaff</h3>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Your Name</p>
    </footer>
</body>
</html>
contact html:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - My Food Website</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <DIv class="title">
        SAVEETHA UNAVAGAM
    </DIv>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
                <li><a href="Resiter.html">Register</a></li>
            </ul>
        </nav>
    </header>

    <section class="contact">
        <h2>Contact Us</h2>
        <p>Address: 123 Food Street, Food City, FC 12345</p>
        <p>Phone: (123) 456-7890</p>
        <p>Email: info@foodwebsite.com</p>
    </section>

    <footer>
        <p>&copy; 2024 Your Name</p>
    </footer>
</body>
</html>
```
## menu.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - My Food Website</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="style2.css">
</head>
<body>
    <DIv class="title">
        SAVEETHA UNAVAGAM
    </DIv>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
                <li><a href="Resiter.html">Register</a></li>
            </ul>
        </nav>
    </header>
    <div class="menu-section">
        <h2>Our Menu</h2>
        <div class="menu-items">
            <div class="menu-item">
                <img src="download.jpg" alt="ICE CREAMS">
                <h3>ICE CREAMS</h3>
                <p><strong>140</strong></p>
            </div>
            <div class="menu-item">
                <img src="https://www.kannammacooks.com/wp-content/uploads/street-style-chicken-rice-recipe-1-3.jpg" alt="CHICKEN RICE">
                <h3>CHICKEN RICE</h3>
                <p><strong>990</strong></p>
            </div>
            <div class="menu-item">
                <img src="https://pipingpotcurry.com/wp-content/uploads/2024/04/Chicken-Biryani-Piping-Pot-Curry.jpg" alt="BIRIYANI">
                <h3>BIRIYANI</h3>
                <p><strong>1100</strong></p>
            </div>
            <div class="menu-item">
                <img src="https://thefriendlyepicurean.com/wp-content/uploads/2020/06/img_5490.jpg" alt="CHAPATI">
                <h3>CHAPATI</h3>
                <p><strong>200</Strong></p>
            </div>
            <div class="menu-item">
                <img src="https://www.indianhealthyrecipes.com/wp-content/uploads/2022/03/chicken-65-restaurant-style-500x375.jpg" alt="CHICKEN LOLLIPOP">
                <h3>CHICKEN 65</h3>
                <p><strong>800</Strong></p>
            </div>
            <div class="menu-item">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSP-kCOFzi3mmfoN0Gx-Z34Z4iJmurmg02YWw&s" alt="MAGGI">
                <h3>MIO AMORE</h3>
                <p><strong>400</Strong></p>
            </div>
            <div class="menu-item">
                <img src="https://butfirstchai.com/wp-content/uploads/2023/03/yemeni-chicken-mandi-recipe.jpg" alt="MANDHI RICE">
                <h3>MANDHI RICE</h3>
                <p><strong>2500</Strong></p>
            </div>
            <div class="menu-item">
                <img src="https://thewhiskaddict.com/wp-content/uploads/2024/01/IMG_9911-scaled.jpg" alt="PAROTTA">
                <h3>PAROTTA</h3>
                <p><strong>250</Strong></p>
                    </DIV>
            <div class="menu-item">
                <img src="https://www.ohmyveg.co.uk/wp-content/uploads/2023/07/Idli-1-scaled-e1722868852202-720x720.jpg" alt="IDLY">
                <h3>IDLY</h3>
                <p><strong>500</Strong></p>
            </div>
            <div class="menu-item">
                <img src="https://www.cookwithmanali.com/wp-content/uploads/2020/05/Masala-Dosa.jpg" alt="DOSAI">
                <h3>DOSAI</h3>
                <p><strong>120</Strong></p>
            </div>
            <div class="menu-item">
                <img src="https://www.indianhealthyrecipes.com/wp-content/uploads/2020/12/poori-puri-recipe.jpg" alt="PURI">
                <h3>PURI</h3>
                <p><strong>150</Strong></p>
            </div>
            <div class="menu-item">
                <img src="https://d2jx2rerrg6sh3.cloudfront.net/image-handler/picture/2018/4/shutterstock_1By_stockcreations.jpg" alt="JUICE">
                <h3>JUICE</h3>
                <p><strong>70</Strong></p>
                </diV>
            
</body>
</html>
```
## register.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - My Food Website</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="style2.css">
</head>
<body>
    <DIv class="title">
        SAVEETHA UNAVAGAM
    </DIv>
    <header>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
                <li><a href="Resiter.html">Register</a></li>
            </ul>
        </nav>
    </header>
    <div class="menu-section">
        <h2>Our Menu</h2>
        <div class="menu-items">
            <div class="menu-item">
                <img src="download.jpg" alt="ICE CREAMS">
                <h3>ICE CREAMS</h3>
                <p><strong>140</strong></p>
            </div>
            <div class="menu-item">
                <img src="https://www.kannammacooks.com/wp-content/uploads/street-style-chicken-rice-recipe-1-3.jpg" alt="CHICKEN RICE">
                <h3>CHICKEN RICE</h3>
                <p><strong>990</strong></p>
            </div>
            <div class="menu-item">
                <img src="https://pipingpotcurry.com/wp-content/uploads/2024/04/Chicken-Biryani-Piping-Pot-Curry.jpg" alt="BIRIYANI">
                <h3>BIRIYANI</h3>
                <p><strong>1100</strong></p>
            </div>
            <div class="menu-item">
                <img src="https://thefriendlyepicurean.com/wp-content/uploads/2020/06/img_5490.jpg" alt="CHAPATI">
                <h3>CHAPATI</h3>
                <p><strong>200</Strong></p>
            </div>
            <div class="menu-item">
                <img src="https://www.indianhealthyrecipes.com/wp-content/uploads/2022/03/chicken-65-restaurant-style-500x375.jpg" alt="CHICKEN LOLLIPOP">
                <h3>CHICKEN 65</h3>
                <p><strong>800</Strong></p>
            </div>
            <div class="menu-item">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSP-kCOFzi3mmfoN0Gx-Z34Z4iJmurmg02YWw&s" alt="MAGGI">
                <h3>MIO AMORE</h3>
                <p><strong>400</Strong></p>
            </div>
            <div class="menu-item">
                <img src="https://butfirstchai.com/wp-content/uploads/2023/03/yemeni-chicken-mandi-recipe.jpg" alt="MANDHI RICE">
                <h3>MANDHI RICE</h3>
                <p><strong>2500</Strong></p>
            </div>
            <div class="menu-item">
                <img src="https://thewhiskaddict.com/wp-content/uploads/2024/01/IMG_9911-scaled.jpg" alt="PAROTTA">
                <h3>PAROTTA</h3>
                <p><strong>250</Strong></p>
                    </DIV>
            <div class="menu-item">
                <img src="https://www.ohmyveg.co.uk/wp-content/uploads/2023/07/Idli-1-scaled-e1722868852202-720x720.jpg" alt="IDLY">
                <h3>IDLY</h3>
                <p><strong>500</Strong></p>
            </div>
            <div class="menu-item">
                <img src="https://www.cookwithmanali.com/wp-content/uploads/2020/05/Masala-Dosa.jpg" alt="DOSAI">
                <h3>DOSAI</h3>
                <p><strong>120</Strong></p>
            </div>
            <div class="menu-item">
                <img src="https://www.indianhealthyrecipes.com/wp-content/uploads/2020/12/poori-puri-recipe.jpg" alt="PURI">
                <h3>PURI</h3>
                <p><strong>150</Strong></p>
            </div>
            <div class="menu-item">
                <img src="https://d2jx2rerrg6sh3.cloudfront.net/image-handler/picture/2018/4/shutterstock_1By_stockcreations.jpg" alt="JUICE">
                <h3>JUICE</h3>
                <p><strong>70</Strong></p>
                </diV>
            
</body>
</html>
```
## style.css:
```
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}
.title{
    font-family: Arial, Helvetica, sans-serif;
    font-size: xx-large;
    font-weight: bolder;
    text-align: center;
    background-color:#e8ce0b;
    margin: auto;
    padding: 1%;
    display: block;

}
header {
    background-color: #333;
    color: white;
    padding: 10px;
    text-align: center;
}

nav ul {
    list-style-type: none;
    padding: 0;
}
.img1{
    image-resolution: 100%;
    i
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
    position: fixed;
    width: 100%;
    bottom: 0;
}

.banner {
    background-size: auto;
    color: rgb(238, 8, 8); 
    text-align: center;
    padding: 80px 0;
    background-color:#e8ce0b;
.fil{
  -webkit-filter: blur(5px); 
  filter: blur(3px);
  border-radius: 50px;
}    
    
}
.te1{
    font-family: "Labrada", serif;
    color:antiquewhite;
    position: absolute;
    top: 40%;
    left: 50%;
    transform: translate(-50%, -50%);
    text-shadow: #333;
    font-size: 60px;
    
} 
.te2{
    position: absolute;
    top: 80%;
    left: 50%;
    transform: translate(-50%, -50%);
    font-family: "Labrada", serif;
    color:antiquewhite;
    font-size: 30px;
}


.menu {
    padding: 20px;
    background-color: #fff;
    text-align: center;
}

.menu h2 {
    font-size: 2em;
    color: #333;
}

.menu ul {
    list-style-type: none;
    padding: 0;
}

.menu ul li {
    font-size: 1.2em;
    margin: 10px 0;
}

.administration {
    padding: 20px;
    background-color: #fff;
    text-align: center;
}

.team-member {
    display: inline-block;
    width: 300px;
    margin: 100px;
    text-align: center;
}

.team-member img {
    width: 100%;
    border-radius: 40%;
}

.team-member h3 {
    font-size: 1.1em;
    color: #333;
}
.contact {
    padding: 20px;
    background-color: #fff;
    text-align: center;
}

.contact p {
    font-size: 1.2em;
    color: #333;
}
.lobster-regular {
    font-family: "Lobster", sans-serif;
    font-weight: 400;
    font-style: normal;
  }
  
* {box-sizing: border-box;}
 .input-container {
    display: flex;
    width: 100%;
    margin-bottom: 15px;
  }
  
.icon {
    padding: 10px;
    background: dodgerblue;
    color: white;
    min-width: 50px;
    text-align: center;
  }
.input-field {
    width: 100%;
    padding: 10px;
    outline: none;
  }
  
.input-field:focus {
    border: 2px solid dodgerblue;
  }
.btn {
    background-color: dodgerblue;
    color: white;
    padding: 15px 20px;
    border: none;
    cursor: pointer;
    width: 100%;
    opacity: 0.9;
  }
  
.btn:hover {
    opacity: 1;
  }
  body{
    background-color:#e8ce0b;
    
}
.menu-items {
    display: flex;
    justify-content: center;
    gap: 50px;
    flex-wrap: wrap;
    margin-bottom: 10px;
}
.menu-item {
    background-color: #e6e5d8;
    padding: 20px;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    width: 250px;
    text-align: center;
}
.menu-item img {
    width: 100%;
    height: 150px;
    object-fit: cover;
    border-radius: 5px;
}
.menu-item h3 {
    color: #2c3e50;
}
.menu-section {
    text-align: center;
    margin-top: 30px;
    background-color: #e8ce0b;
}
.menu-section h2 {
    color: #2c3e50;
}
```
## OUTPUT:
![395438701-87195c65-28d7-4677-934d-c358656ee230](https://github.com/user-attachments/assets/5ef1bb67-9c25-46d3-934f-255a4e13d918)
![395438724-3ccdfee9-0454-4d30-a85b-580ea0e6ef1d](https://github.com/user-attachments/assets/59db14f0-b15a-4363-ab34-09ad4b5efc68)
![395438746-1baa529b-6460-4d97-861b-8286bc6cf351](https://github.com/user-attachments/assets/34d1daeb-cf3a-4940-9701-d39b4e243aae)
![395438788-769bb191-35e6-4b85-9531-40f6974da988](https://github.com/user-attachments/assets/ffd34d8a-e86d-4c3d-8753-3e3e3e8d0ccc)
![395438831-3463b00d-368f-4df2-b70c-5c5df1359bda](https://github.com/user-attachments/assets/5ca4a272-8e69-47e4-846c-08ae19d49c92)
![395438844-53faafa9-18ae-4986-a970-06e8f6b8bcda](https://github.com/user-attachments/assets/7f8279a6-e5de-49c7-94e0-2fb68f51e76f)
![395438871-4b5d1a68-2250-4171-b94a-20dc0b434dd6](https://github.com/user-attachments/assets/d5fe90db-c818-4cee-87ec-f70e0c15c241)
![395438885-9942b41c-7a4c-485a-90fc-15d112359052](https://github.com/user-attachments/assets/2faf8757-89f6-49de-a039-517d945ec72c)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
