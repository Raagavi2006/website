# Ex.07 Restaurant Website
# Date:05.12.2024
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
```
<html>
    <head>
    <title>Cafeteria</title>
    </head>
    <body>
        <style>
            ::after,
*           ::before {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}

.html {
  font-size: 62.5%;
  font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
}
.body {
  font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
}
.container {
  max-width: 1200px;
  width: 90%;
  margin: auto;
}
.btn-primary {
  color: #fff;
  background: #16a083;
  display: inline-block;
  cursor: pointer;
  outline: none;
  padding: 0.5em 1.5em;
  border-radius: 50px;
}
.navbar {
  box-shadow: 0px 5px 10px 0px #aaa;
  position: fixed;
  width: 100%;
  background: #fff;
  color: #000;
  opacity: 0.85;
  height: 50px;
  z-index: 12;
}
.navbar-container {
  display: flex;
  justify-content: space-between;
  height: 64px;
  align-items: center;
}
.showcase-area {
  height: 50vh;
  background: linear-gradient(
      rgba(240, 240, 240, 0.144),
      rgba(255, 255, 255, 0.336)
    ),
    url("cafe.jpg");
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}
.main-title {
  text-transform: uppercase;
  margin-top: 1.5em;
}
#about {
  padding: 50px 0;
  background: #f5f5f7;
  font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
}
.menu-items {
  order: 2;
  display: flex;
  font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
}
.menu-items li {
  list-style: none;
  margin-left: 1.5rem;
  margin-bottom: 0.5rem;
  font-size: 1.2rem;
}
.logo {
    position: absolute;
    left: 15px;
    font-size: xx-large;
    font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
  }
        </style>
        <nav class="navbar">
            <div class="navbar-container container">
                <div class="hamburger-lines">
                    <span class="line line1"></span>
                    <span class="line line2"></span>
                    <span class="line line3"></span>
                </div>
                <ul class="menu-items">
                    <li><a href="#home">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="cafe food.html">Menu</a></li>
                    <li><a href="cafe contact.html">Contact</a></li>
                    <li><a href="cafe admin.html">Admin</a></li>
                </ul>
                <h1 class="logo">The Cozy Cup</h1>
            </div>
        </nav>
        <section class="showcase-area" id="showcase">
            <div class="showcase-container">
            </div>
          </section>
          <section id="about">
            <div class="about-wrapper container">
              <div class="about-text">
                <h2>Just Brewed happiness in a cup!!!</h2>
                <h2>About Us</h2>
                <h3>
                  Escape the hustle, find your heaven.
                  Cozy atmosphere, specialty coffees and delicious treats.
                </h3>
                <hr>
                <h4>Opening Time : 8 AM</h4>
                <h4>Closing Time : 8 PM</h4>
                <h4>Lunch Time : 1 PM - 3 PM</h4>
                <hr>
              </div>
              <h1>Restaurant &copy; All Rights Reserved</h1>
    </body>
</html>

<html>
    <head>
        <title>Cafe Food Menu</title>
    </head>
    <body style="background-color:bisque">
        <style>
            .html {
  font-size: 62.5%;
  font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
}
.body {
  font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
}
.container {
  max-width: 1200px;
  width: 90%;
  margin: auto;
}
            .btn-primary {
  color: #fff;
  background: #16a083;
  display: inline-block;
  cursor: pointer;
  outline: none;
  padding: 0.5em 1.5em;
  border-radius: 50px;
}
.menu-items {
  order: 2;
  display: flex;
  font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
}
.menu-items li {
  list-style: none;
  margin-left: 1.5rem;
  margin-bottom: 0.5rem;
  font-size: 1.2rem;
}
.food-menu-heading {
  text-align: center;
  font-size: xx-large;
  font-weight: 400;
  color: solid black;
  font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
}
            
.main-title {
  text-transform: uppercase;
  margin-top: 1.5em;
}
            .logo {
    position: absolute;
    left: 15px;
    font-size: xx-large;
    font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
  }
  .navbar {
  box-shadow: 0px 5px 10px 0px #aaa;
  position: fixed;
  width: 100%;
  background: #fff;
  color: #000;
  opacity: 0.85;
  height: 50px;
  z-index: 12;
}
.navbar-container {
  display: flex;
  justify-content: space-between;
  height: 64px;
  align-items: center;
}
        </style>
        <nav class="navbar">
            <div class="navbar-container container">
                <h1 class="logo">The Cozy Cup - Menu</h1>
            </div>
        </nav>
        <section class="showcase-area" id="showcase">
            <div class="showcase-container">
            </div>
          </section>
        <section class="showcase-area" id="showcase">
            <div class="showcase-container">
            </div>
            
            <section id="food-menu">
                <div class="food-menu-container container">
                  <div class="food-menu-item">
                    <div class="food-img">
                      <img src="cappuccino.jpg" />
                    </div>
                    <div class="food-description">
                        
                      <h2 class="food-titile">Cappuccino</h2>
                      <p>
                        A freshly pulled shot of espresso layered with steamed whole milk and thick rich foam to offer a luxurious velvety texture and complex aroma.
                      </p>
                      <p>Price: ₹120</p>
                    </div>
                  </div>
                  <div class="food-menu-item">
                    <div class="food-img">
                      <img src="americano.jpg"/>
                    </div>
                    <div class="food-description">
                      <h2 class="food-titile">Americano</h2>
                      <p>
                        A coffee drink made by diluting espresso with hot water, and is typically described as a balance of robustness and smoothness. 
                      </p>
                      <p>Price: ₹129</p>
                    </div>
                  </div>
                  <div class="food-menu-item">
                    <div class="food-img">
                      <img src="iced latte.jpg" height="250px" width="300px"/>
                    </div>
                    <div class="food-description">
                      <h2 class="food-titile">Iced latte</h2>
                      <p>
                        A cold coffee drink made with espresso, milk, and ice. It's a variation of the traditional latte, but with cold milk instead of hot.
                      </p>
                      <p>Price: ₹129</p>
                    </div>
                  </div>
                  <div class="food-menu-item">
                    <div class="food-img">
                      <img src="black coffee.jpg" height="250px" width="300px" />
                    </div>
                    <div class="food-description">
                      <h2 class="food-titile">Black coffee</h2>
                      <p>
                        A hot drink made from ground coffee and water, and it's usually served without any additives like milk, cream, or sugar.
                      </p>
                      <p>Price: ₹110</p>
                    </div>
                  </div>
                  <div class="food-menu-item">
                    <div class="food-img">
                      <img src="Frappuccino.jpg" height="250px" width="300px"/>
                    </div>
                    <div class="food-description">
                      <h2 class="food-titile">Frappuccino</h2>
                      <p>
                        A blended iced coffee drink that's typically made with coffee or espresso, milk, ice, sweeteners, and flavorings
                      </p>
                      <p>Price: ₹470</p>
                    </div>
                  </div>
                  <div class="food-menu-item">
                    <div class="food-img">
                      <img src="filter-coffee.jpg" height="250px" width="300px"/>
                    </div>
                    <div class="food-description">
                      <h2 class="food-titile">Filter Coffee</h2>
                      <p>
                        A coffee drink that's made by brewing coffee grounds with hot water and then pouring the coffee through a filter.
                      </p>
                      <p>Price: ₹50</p>
                    </div>
                  </div>
                  <div class="food-menu-item">
                    <div class="food-img">
                      <img src="esp.jpg" height="250px" width="300px"/>
                    </div>
                    <div class="food-description">
                      <h2 class="food-titile">Espresso</h2>
                      <p>
                        Espresso is a delicious concentrated form of coffee, served in shots.
                      </p>
                      <p>Price: ₹120</p>
                    </div>
                  </div>
                  <div class="food-menu-item">
                    <div class="food-img">
                      <img src="chocolate coff.jpg" height="250px" width="300px"/>
                    </div>
                    <div class="food-description">
                      <h2 class="food-titile">Chocolate Coffee</h2>
                      <p>
                        Drinking chocolate, or sipping chocolate, is exactly what it sounds like – luxurious, melted chocolate you can drink!
                      </p>
                      <p>Price: ₹100</p>
                    </div>
                  </div>
                  <div class="food-menu-item">
                    <div class="food-img">
                      <img src="aff.jpeg" height="250px" width="300px"/>
                    </div>
                    <div class="food-description">
                      <h2 class="food-titile">Affogato</h2>
                      <p>
                        A big scoop of vanilla ice cream with a hot espresso shot poured over it. When the affogato is ready to serve, the ice cream looks as if it has drowned in the coffee.
                      </p>
                      <p>Price: ₹200</p>
                    </div>
                  </div>
                  <div class="food-menu-item">
                    <div class="food-img">
                      <img src="cafe mac.jpg" height="250px" width="300px"/>
                    </div>
                    <div class="food-description">
                      <h2 class="food-titile">Caffe Macchito</h2>
                      <p>
                        A shot of espresso or strong coffee and a small amount of steamed milk or foam on top. 
                      </p>
                      <p>Price: ₹200</p>
                    </div>
                  </div>                                                           
                </div>
        </section>
    </body>
</html>

<html>
    <head>
        <style>
        html {
          box-sizing: border-box;
        }
        
        *, *:before, *:after {
          box-sizing: inherit;
        }
        
        .column {
          float: left;
          width: 30%;
          margin-bottom: 16px;
          padding: 0 8px;
        }
        
        @media screen and (max-width: 650px) {
          .column {
            width: 70%;
            display: block;
          }
        }
        
        .card {
          box-shadow: 0 4px 8px 0 rgba(0, 0, 0, 0.2);
        }
        
        .container {
          padding: 0 16px;
        }
        
        .container::after, .row::after {
          content: "";
          clear: both;
          display: table;
        }
        
        .title {
          color: grey;
        }
        
        .button {
          border: none;
          outline: 0;
          display: inline-block;
          padding: 8px;
          color: white;
          background-color: #000;
          text-align: center;
          cursor: pointer;
          width: 75%;
        }
        
        .button:hover {
          background-color: #555;
        }
        </style>
    </head>
    <body style="background-color: antiquewhite;">
        <center style="background-color: #000;">
        <h1 style="color: aqua; font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif; font-size: xx-large;">Admin Page</h1>
        <h2 style="color: aqua; font-family: 'Times New Roman', Times, serif; font-size: xx-large;">Provides administrative support to ensure efficient operation of the office.</h2>
        <br>
        </center>
        <div class="row">
          <div class="column">
            <div class="card">
              <img src="owner.jpg" style="width:75%" height="300px">
              <div class="container">
                <h1>Zara</h1>
                <h2 class="title">Owner</h2>
                <h3>Curates a welcoming space that blends quality coffee, tasty treats, and a sense of community.</h3>
                <h3>zara887@gmail.com</h3>
                <p><button class="button">Contact</button></p>
              </div>
            </div>
          </div>
        
          <div class="column">
            <div class="card">
              <img src="manager.jpg" style="width:75%" height="300px">
              <div class="container">
                <h1>Noah</h1>
                <h2 class="title">Manager</h2>
                <h3>I oversee daily operations, ensuring smooth service, team coordination, and a welcoming atmosphere for customers.</h3>
                <h3>noah@gmail.com</h3>
                <p><button class="button">Contact</button></p>
              </div>
            </div>
          </div>

          <div class="column">
            <div class="card">
              <img src="accountant.jpg" style="width:75%" height="300px">
              <div class="container">
                <h1>Olivia</h1>
                <h2 class="title">Accountant</h2>
                <h3>Manages finances, tracks expenses, and ensures profitability while maintaining accurate records for smooth operations.</h3>
                <h3>oli4456@gmail.com</h3>
                <p><button class="button">Contact</button></p>
              </div>
            </div>
          </div>

          <div class="column">
            <div class="card">
              <img src="host.jpg" style="width:75%" height="300px">
              <div class="container">
                <h1>Theodore</h1>
                <h2 class="title">Host</h2>
                <h3>I warmly greet and guide guests, ensuring they have a pleasant and personalized experience from arrival to departure.</h3>
                <h3>theo@gmail.com</h3>
                <p><button class="button">Contact</button></p>
              </div>
            </div>
          </div>

          <div class="column">
            <div class="card">
              <img src="barista.jpg" style="width:75%" height="300px">
              <div class="container">
                <h1>Sophia</h1>
                <h2 class="title">Barista</h2>
                <h3>Crafts expertly brewed coffee and espresso drinks while providing friendly, attentive service to create a welcoming atmosphere for every customer.</h3>
                <h3>sophi@gmail.com</h3>
                <p><button class="button">Contact</button></p>
              </div>
            </div>
          </div>
          
          <div class="column">
            <div class="card">
              <img src="store assistant.webp" style="width:75%" height="300px">
              <div class="container">
                <h1>Lucas</h1>
                <h2 class="title">Store Assistant</h2>
                <h3>Provides friendly customer service, prepares beverages and food, and helps maintain a clean and organized café environment.</h3>
                <h3>luca334@gmail.com</h3>
                <p><button class="button">Contact</button></p>
              </div>
            </div>
          </div>
        </div>
        
        </body>
</html>

<html>
    <head>
        <title>Cafe Contact</title>
    </head>
    <body>
        <style>
             

.html {
  font-size: 62.5%;
  font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
}
.container {
  max-width: 1200px;
  width: 50%;
  margin: auto;
}
.btn-primary {
  color: #fff;
  background: #16a083;
  display: inline-block;
  cursor: pointer;
  outline: none;
  padding: 0.5em 1.5em;
  border-radius: 50px;
}
            .showcase-area {
  height: 50vh;
  background: linear-gradient(
      rgba(240, 240, 240, 0.144),
      rgba(255, 255, 255, 0.336)
    ),
    url("cafe.jpg");
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
}
.logo {
    position: absolute;
    left: 15px;
    font-size: xx-large;
    font-family:'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
  }
  .navbar {
  box-shadow: 0px 5px 10px 0px #aaa;
  position: fixed;
  width: 100%;
  background: #fff;
  color: #000;
  opacity: 0.85;
  height: 60px;
  z-index: 12;
}
.navbar-container {
  display: flex;
  justify-content: space-between;
  height: 64px;
  align-items: center;
}
body {font-family: Arial, Helvetica, sans-serif;}
* {box-sizing: border-box;}

input[type=text], select, textarea{
  width: 25%;
  padding: 12px;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
  margin-top: 6px;
  margin-bottom: 16px;
  resize: vertical;
}

input[type=email]{
  width: 25%;
  padding: 12px;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
  margin-top: 6px;
  margin-bottom: 16px;
  resize: vertical;
}

input[type=submit] {
  background-color: #04AA6D;
  color: white;
  padding: 12px 20px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

input[type=submit]:hover {
  background-color: #45a049;
}

.container {
  border-radius: 5px;
  background-color: #f2f2f2;
  padding: 20px;
}
        </style>
        <nav class="navbar">
            <div class="navbar-container container">
                <div class="hamburger-lines">
                    <span class="line line1"></span>
                    <span class="line line2"></span>
                    <span class="line line3"></span>
                </div>
                <h1 class="logo">The Cozy Cup</h1>
            </div>
        </nav>
        <section class="showcase-area" id="showcase">
            <div class="showcase-container">
            </div>
        </section>
        <center>
        <section id="contact">
            <div class="form-container">
              <form action="/action_page.php"></form>
                <h1>Contact Us</h1>
                <label for="fname">First Name</label>
                <input type="text" id="fname" name="firstname" placeholder="Your name.."><br>

                <label for="lname">Last Name</label>
                <input type="text" id="lname" name="lastname" placeholder="Your last name.."><br>

                <label for="email">E-Mail</label>
                <input type="email" placeholder="Your E-Mail.." /><br>

                <label for="subject">Message</label>
                <textarea id="subject" name="subject" placeholder="Write something.." style="height:70px"></textarea><br>

                <input type="submit" value="Submit">
            </form>
            </div>
          </section>
          <h2>Restraunt &copy; all rights reserved</h2>
          </center>
    </body>
</html>
```
# OUTPUT:

Home
![alt text](<WEB 7-Home.png>)

Menu
![alt text](<WEB 7-Menu 1.png>)
![alt text](<WEB 7-Menu 2.png>)
![alt text](<WEB 7-Menu 3.png>)
![alt text](<WEB 7-Menu 4.png>)
![alt text](<WEB 7-Menu 5.png>)

Admin
![alt text](<WEB 7-Admin 1.png>)
![alt text](<WEB 7-Admin 2.png>)

Contact
![alt text](<WEB 7-Contact.png>)

# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
