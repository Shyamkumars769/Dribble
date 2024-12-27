# Project Responsive Web Design using Bootstrap
## Date:27-12-24

## AIM:
To create a simplified clone of Dribbble (https://dribbble.com/) landing page.


## DESIGN STEPS:

### Step 1:
Clone the repository from GitHub.

### Step 2:
Create Django Admin project.

### Step 3:
Create a New App under the Django Admin project.

### Step 4:
Insert the necessary CSS and JavaScript files as external in order to use Bootstrap.

### Step 5:
Create a HTML file and include the needed Bootstrap components.

### Step 6:
Publish the website in the LocalHost.

## PROGRAM :

```
Home.html

<html>
<head>
  <title>Dribbble - Home</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
  <style>
    body { font-family: Arial, sans-serif; }
    .custom-header { background: linear-gradient(to right, #6a11cb, #2575fc); color: white; padding: 40px 20px; text-align: center; }
    .navbar { background-color: #343a40; padding: 15px; }
    .navbar-brand { font-size: 1.8rem; color: white; }
    .navbar .nav-link { color: white !important; margin-right: 15px; font-size: 1rem; }
    footer { background-color: #343a40; color: white; text-align: center; padding: 20px 0; }
  </style>
</head>
<body>

  <header class="custom-header">
    <h1>Welcome to Dribbble</h1>
    <p>Your destination for creative inspiration</p>
  </header>

  <nav class="navbar navbar-expand-lg">
    <div class="container">
      <a class="navbar-brand" href="Home.html">Dribbble</a>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="Explore.html">Explore</a></li>
          <li class="nav-item"><a class="nav-link" href="Contact.html">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <section class="section">
    <h2 class="text-center">Home Page</h2>
    <p class="text-center">Welcome to Dribbble! Discover incredible art and designs from creators worldwide.</p>
  </section>

  <footer>
    <p>Designed by Shyamkumar.S</p>
  </footer>

</body>
</html>

Explore.html

<html>
<head>
  <title>Dribbble - Explore</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
  <style>
    body { font-family: Arial, sans-serif; }
    .custom-header { background: linear-gradient(to right, #6a11cb, #2575fc); color: white; padding: 40px 20px; text-align: center; }
    .navbar { background-color: #343a40; padding: 15px; }
    .navbar-brand { font-size: 1.8rem; color: white; }
    .navbar .nav-link { color: white !important; margin-right: 15px; font-size: 1rem; }
    .portfolio-section { background-color: #ffffff; padding: 60px 20px; }
    .portfolio-item { text-align: center; margin-bottom: 30px; }
    .portfolio-item img { width: 100%; max-height: 200px; object-fit: cover; border-radius: 10px; }
    footer { background-color: #343a40; color: white; text-align: center; padding: 20px 0; }
  </style>
</head>
<body>

  <header class="custom-header">
    <h1>Explore Dribbble</h1>
    <p>Explore the stunning designs and artworks created by talented artists</p>
  </header>

  <nav class="navbar navbar-expand-lg">
    <div class="container">
      <a class="navbar-brand" href="Home.html">Dribbble</a>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="Explore.html">Explore</a></li>
          <li class="nav-item"><a class="nav-link" href="Contact.html">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <section class="portfolio-section">
    <h2 class="text-center">Our Portfolio</h2>
    <div class="container">
      <div class="row">
        <div class="col-md-4 portfolio-item">
          <img src="Morden.avif" alt="Design 1">
          <h5>Modern Art</h5>
        </div>
        <div class="col-md-4 portfolio-item">
          <img src="abstract.png" alt="Design 2">
          <h5>Abstract Fusion</h5>
        </div>
        <div class="col-md-4 portfolio-item">
          <img src="Landscapes.jpg" alt="Design 3">
          <h5>Creative Landscapes</h5>
        </div>
      </div>
    </div>
  </section>

  <footer>
    <p>Designed by Shyamkumar.S</p>
  </footer>

</body>
</html>

<html>
<head>
  <title>Dribbble - Contact</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
  <style>
    body { font-family: Arial, sans-serif; }
    .custom-header { background: linear-gradient(to right, #6a11cb, #2575fc); color: white; padding: 40px 20px; text-align: center; }
    .navbar { background-color: #343a40; padding: 15px; }
    .navbar-brand { font-size: 1.8rem; color: white; }
    .navbar .nav-link { color: white !important; margin-right: 15px; font-size: 1rem; }
    .contact-section { background-color: #f9f9f9; text-align: center; padding: 60px 20px; }
    footer { background-color: #343a40; color: white; text-align: center; padding: 20px 0; }
  </style>
</head>
<body>

  <header class="custom-header">
    <h1>Contact Dribbble</h1>
    <p>We would love to hear from you!</p>
  </header>

  <nav class="navbar navbar-expand-lg">
    <div class="container">
      <a class="navbar-brand" href="Home.html">Dribbble</a>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="Explore.html">Explore</a></li>
          <li class="nav-item"><a class="nav-link" href="Contact.html">Contact</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <section class="contact-section">
    <h2>Contact Us</h2>
    <form>
      <div class="mb-3">
        <label for="name" class="form-label">Name</label>
        <input type="text" class="form-control" id="name" placeholder="Your Name">
      </div>
      <div class="mb-3">
        <label for="email" class="form-label">Email</label>
        <input type="email" class="form-control" id="email" placeholder="Your Email">
      </div>
      <div class="mb-3">
        <label for="message" class="form-label">Message</label>
        <textarea class="form-control" id="message" rows="3" placeholder="Your Message"></textarea>
      </div>
      <button type="submit" class="btn btn-primary">Submit</button>
    </form>
  </section>

  <footer>
    <p>Designed by Shyamkumar.S</p>
  </footer>

</body>
</html>

```

## OUTPUT:

![alt text](<Home img.png>) 

![alt text](<explore img.png>) 

![alt text](<Contact img.png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
