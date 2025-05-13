name : sanjeevpriya k
reg no: 212224040289
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

## PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Colorful Food Image</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: #fff0e6;
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    header {
      background-color: #ff6f61;
      color: white;
      width: 100%;
      padding: 20px 0;
      text-align: center;
      font-size: 1.8em;
    }

    main {
      padding: 40px 20px;
      text-align: center;
    }

    img {
      max-width: 500px;
      width: 90%;
      height: auto;
      border-radius: 12px;
      box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
    }

    footer {
      background-color: #ff6f61;
      color: white;
      text-align: center;
      padding: 15px;
      width: 100%;
      position: fixed;
      bottom: 0;
    }
  </style>
</head>
<body>
  <header>
    Colorful Food Gallery
  </header>

  <main>
    <h2>Delicious & Vibrant Dish</h2>
    <img src="https://images.unsplash.com/photo-1600891964599-f61ba0e24092" alt="Colorful Food">
    <p>A perfect blend of taste and colors to make your meal joyful!</p>
  </main>

  <footer>
    &copy; 2025 FoodArt Gallery
  </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Colorful Food Menu</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, sans-serif;
      background-color: #fff8f0;
      color: #333;
    }

    header {
      background-color: #ff6f61;
      color: white;
      padding: 20px;
      text-align: center;
      font-size: 2em;
    }

    .container {
      max-width: 900px;
      margin: 40px auto;
      padding: 20px;
      background-color: white;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
      border-radius: 12px;
    }

    .image-container {
      text-align: center;
      margin-bottom: 30px;
    }

    .image-container img {
      width: 100%;
      max-width: 500px;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
    }

    h2 {
      color: #d35400;
      margin-bottom: 10px;
    }

    .menu-item {
      display: flex;
      justify-content: space-between;
      border-bottom: 1px dashed #ccc;
      padding: 10px 0;
      font-size: 1.1em;
    }

    .menu-item:last-child {
      border-bottom: none;
    }

    .contact-form {
      margin-top: 40px;
    }

    .contact-form label {
      display: block;
      margin-top: 15px;
      margin-bottom: 5px;
      font-weight: bold;
    }

    .contact-form input,
    .contact-form textarea {
      width: 100%;
      padding: 10px;
      border-radius: 5px;
      border: 1px solid #ccc;
      font-size: 1em;
    }

    .contact-form button {
      margin-top: 20px;
      padding: 10px 20px;
      background-color: #ff6f61;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      font-size: 1em;
    }

    footer {
      background-color: #ff6f61;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <header>
    Colorful Food Menu
  </header>

  <div class="container">
    <div class="image-container">
      <img src="https://images.unsplash.com/photo-1600891964599-f61ba0e24092" alt="Colorful Food">
    </div>

    <h2>Today's Specials</h2>
    <div class="menu-item">
      <span>Rainbow Veggie Bowl</span>
      <span>$9.99</span>
    </div>
    <div class="menu-item">
      <span>Fruit Explosion Salad</span>
      <span>$7.49</span>
    </div>
    <div class="menu-item">
      <span>Sunset Smoothie</span>
      <span>$4.99</span>
    </div>
    <div class="menu-item">
      <span>Spicy Tofu Wrap</span>
      <span>$8.25</span>
    </div>

    <div class="contact-form">
      <h2>Contact Us</h2>
      <form action="#" method="post">
        <label for="name">Your Name:</label>
        <input type="text" id="name" name="name" required>

        <label for="email">Your Email:</label>
        <input type="email" id="email" name="email" required>

        <label for="message">Message:</label>
        <textarea id="message" name="message" rows="5" required></textarea>

        <button type="submit">Send Message</button>
      </form>
    </div>
  </div>

  <footer>
    &copy; 2025 Colorful Bites | Contact us for orders and events!
  </footer>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Colorful Food Menu</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, sans-serif;
      background-color: #fff8f0;
      color: #333;
    }

    header {
      background-color: #ff6f61;
      color: white;
      padding: 20px;
      text-align: center;
      font-size: 2em;
    }

    .container {
      max-width: 900px;
      margin: 40px auto;
      padding: 20px;
      background-color: white;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
      border-radius: 12px;
    }

    .image-container {
      text-align: center;
      margin-bottom: 30px;
    }

    .image-container img {
      width: 100%;
      max-width: 500px;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
    }

    h2 {
      color: #d35400;
      margin-bottom: 10px;
    }

    .menu-item {
      display: flex;
      justify-content: space-between;
      border-bottom: 1px dashed #ccc;
      padding: 10px 0;
      font-size: 1.1em;
    }

    .menu-item:last-child {
      border-bottom: none;
    }

    footer {
      background-color: #ff6f61;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <header>
    Colorful Food Menu
  </header>

  <div class="container">
    <div class="image-container">
      <img src="https://images.unsplash.com/photo-1600891964599-f61ba0e24092" alt="Colorful Food">
    </div>

    <h2>Today's Specials</h2>
    <div class="menu-item">
      <span>Rainbow Veggie Bowl</span>
      <span>$9.99</span>
    </div>
    <div class="menu-item">
      <span>Fruit Explosion Salad</span>
      <span>$7.49</span>
    </div>
    <div class="menu-item">
      <span>Sunset Smoothie</span>
      <span>$4.99</span>
    </div>
    <div class="menu-item">
      <span>Spicy Tofu Wrap</span>
      <span>$8.25</span>
    </div>
  </div>

  <footer>
    &copy; 2025 Colorful Bites | Made with ❤️ and flavor
  </footer>

</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Colorful Food Image</title>
  <style>
    body {
      background-color: #fefae0;
      text-align: center;
      font-family: Arial, sans-serif;
    }
    img {
      max-width: 80%;
      height: auto;
      border-radius: 16px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
      margin-top: 40px;
    }
    h1 {
      color: #bc6c25;
    }
  </style>
</head>
<body>
  <h1>Delicious Colorful Food</h1>
  <img src="https://images.unsplash.com/photo-1600891964599-f61ba0e24092" alt="Colorful Food">
</body>
</html>
```

## OUTPUT:
![Screenshot 2025-05-12 184345](https://github.com/user-attachments/assets/90f8dfcf-bb49-4063-bddd-958720da40e3)
![Screenshot 2025-05-12 184633](https://github.com/user-attachments/assets/f4a626fb-53fa-448c-b3ae-ccd55b364276)
![Screenshot 2025-05-13 122631](https://github.com/user-attachments/assets/cad8c751-6a7f-45eb-8894-fea9b5e24de1)
![Screenshot 2025-05-13 122807](https://github.com/user-attachments/assets/2bace0dd-d220-4915-aca5-4ba02a0dbce4)



## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
