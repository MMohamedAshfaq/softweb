# Ex.07 Restuarant Website
<<<<<<< HEAD
## Date:
=======
## Date:14-11-25
>>>>>>> 38a9883 (success)

## AIM:
To develop a static Resturant website to display the menu and services provided by the resturant.

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
<<<<<<< HEAD


## OUTPUT:
=======
```
Home.html:

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>La Tavola Italiana - Home</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
  <header>
    <h1>La Tavola Italiana</h1>
    <p>Authentic Italian Cuisine with Love</p>
  </header>

  <nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">About</a>
    <a href="contact.html">Contact</a>
  </nav>

  <div class="hero" id="home">
    <h2>Benvenuti alla Tavola!</h2>
  </div>

  <section id="menu">
    <h2>Our Italian Classics</h2>
    <div class="image-row">
      <img src="https://www.allrecipes.com/thmb/Vg2cRidr2zcYhWGvPD8M18xM_WY=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc()/11973-spaghetti-carbonara-ii-DDMFS-4x3-6edea51e421e4457ac0c3269f3be5157.jpg" alt="Spaghetti Carbonara">
      <img src="https://www.orchidsandsweettea.com/wp-content/uploads/2019/05/Veggie-Pizza-2-of-5-e1691215701129.jpg" alt="Veggie Pizza">
      <img src="https://www.tasteofhome.com/wp-content/uploads/2025/07/Best-Lasagna_EXPS_ATBBZ25_36333_DR_07_01_2b.jpg" alt="Lasagna">
      <img src="https://assets.epicurious.com/photos/60abd3d94128fb7fa6411297/1:1/w_3493,h_3493,c_limit/ScallopsPineAppleRisotto_HERO_RECIPE_052021_16402.jpg" alt="Risotto">
      <img src="https://www.sandravalvassori.com/wp-content/uploads/2022/04/Tiramisu-11484.jpg" alt="Tiramisu">
      <img src="https://cdn.loveandlemons.com/wp-content/uploads/2025/05/bruschetta.jpg" alt="Bruschetta">
    </div>
  </section>

  <footer>
    <p>&copy; 2025 La Tavola Italiana. All Rights Reserved.</p>
  </footer>
</body>
</html>


Menu.html:


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>La Tavola Italiana - Menu</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
  <header>
    <h1>La Tavola Italiana - Menu</h1>
  </header>

  <nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">About</a>
    <a href="contact.html">Contact</a>
  </nav>

  <main>
    <h2>Food Items</h2>
    <div class="image-row">
      <img src="https://www.allrecipes.com/thmb/Vg2cRidr2zcYhWGvPD8M18xM_WY=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc()/11973-spaghetti-carbonara-ii-DDMFS-4x3-6edea51e421e4457ac0c3269f3be5157.jpg" alt="Spaghetti Carbonara">
      <img src="https://www.orchidsandsweettea.com/wp-content/uploads/2019/05/Veggie-Pizza-2-of-5-e1691215701129.jpg" alt="Veggie Pizza">
      <img src="https://www.tasteofhome.com/wp-content/uploads/2025/07/Best-Lasagna_EXPS_ATBBZ25_36333_DR_07_01_2b.jpg" alt="Lasagna">
      <img src="https://assets.epicurious.com/photos/60abd3d94128fb7fa6411297/1:1/w_3493,h_3493,c_limit/ScallopsPineAppleRisotto_HERO_RECIPE_052021_16402.jpg" alt="Risotto">
      <img src="https://www.sandravalvassori.com/wp-content/uploads/2022/04/Tiramisu-11484.jpg" alt="Tiramisu">
      <img src="https://cdn.loveandlemons.com/wp-content/uploads/2025/05/bruschetta.jpg" alt="Bruschetta">
    </div>
  </main>

  <footer>
    <p>&copy; 2025 La Tavola Italiana. All Rights Reserved.</p>
  </footer>
</body>
</html>


Admin.html:


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>La Tavola Italiana - About Us</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
  <header>
    <h1>La Tavola Italiana - Our Team</h1>
  </header>

  <nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">About</a>
    <a href="contact.html">Contact</a>
  </nav>

  <section id="about">
    <h2>About Us</h2>
    <p style="text-align:center; max-width:800px; margin:auto;">
      La Tavola Italiana brings the warmth and authenticity of Italy to your table.
      From traditional pastas to freshly baked pizzas, every dish is crafted with passion and premium ingredients.
      Meet our talented team who make it all possible:
    </p>

    <div class="image-row">
      <img src="https://images.unsplash.com/photo-1607746882042-944635dfe10e?auto=format&fit=crop&w=800&q=80" alt="Chef Marco Rossi">
      <img src="https://images.unsplash.com/photo-1529626455594-4ff0802cfb7e?auto=format&fit=crop&w=800&q=80" alt="Lucia Bianchi">
      <img src="https://images.unsplash.com/photo-1506794778202-cad84cf45f1d?auto=format&fit=crop&w=800&q=80" alt="Giovanni Romano">
      <img src="https://images.unsplash.com/photo-1544005313-94ddf0286df2?auto=format&fit=crop&w=800&q=80" alt="Sofia Conti">
    </div>
  </section>

  <footer>
    <p>&copy; 2025 La Tavola Italiana. All Rights Reserved.</p>
  </footer>
</body>
</html>


Contact.html:

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>La Tavola Italiana - Contact</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
  <header>
    <h1>Contact Us</h1>
  </header>

  <nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">About</a>
    <a href="contact.html">Contact</a>
  </nav>

  <section id="contact">
    <h2>Contact</h2>
    <p style="text-align:center;">📍 123 Roma Street, Florence, Italy</p>
    <p style="text-align:center;">📞 +39 555 123 4567</p>
    <p style="text-align:center;">📧 info@latavolaitaliana.com</p>
  </section>

  <footer>
    <p>&copy; 2025 La Tavola Italiana. All Rights Reserved.</p>
  </footer>
</body>
</html>

```


## OUTPUT:
Home.html:
![alt text](7.5.png)

Menu.html:
![alt text](7.6.png)

Admin.html:
![alt text](7.7.png)

Contact.html:
![alt text](7.8.png)



>>>>>>> 38a9883 (success)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.


# Ex.07 Restuarant Website
## Date:

## AIM:
To develop a static Resturant website to display the menu and services provided by the resturant.

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


## OUTPUT:


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
