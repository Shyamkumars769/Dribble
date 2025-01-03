# Project Responsive Web Design using Bootstrap
## Date:28-12-24

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
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribbble</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <nav class="navbar navbar-expand-lg bg-light shadow-sm">
        <div class="container">
            <a class="navbar-brand fw-bold text-primary" href="#">Dribbble</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav me-auto">
                    <li class="nav-item"><a class="nav-link text-dark" href="#">Discover</a></li>
                    <li class="nav-item"><a class="nav-link text-dark" href="#">Designers</a></li>
                    <li class="nav-item"><a class="nav-link text-dark" href="#">Projects</a></li>
                </ul>
                <input type="search" class="form-control w-auto me-3" placeholder="Search">
                <a class="btn btn-outline-primary me-2" href="#">Sign in</a>
                <a class="btn btn-primary" href="#">Sign Up</a>
            </div>
        </div>
    </nav>
    <header class="bg-primary text-white py-5">
        <div class="container text-center">
            <h1 class="display-4 fw-bold">Showcase Your Creativity</h1>
            <p class="lead">Find inspiration, connect with creatives, and share your designs with the world.</p>
            <a href="#popular" class="btn btn-light btn-lg">Explore Now</a>
        </div>
    </header>
    <section class="py-5">
        <div class="container">
            <div class="row text-center">
                <div class="col-md-4">
                    <div class="card border-0 shadow-sm">
                        <div class="card-body">
                            <h5 class="fw-bold">Inspiration</h5>
                            <p class="text-muted">Discover thousands of design ideas from top creatives worldwide.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card border-0 shadow-sm">
                        <div class="card-body">
                            <h5 class="fw-bold">Collaboration</h5>
                            <p class="text-muted">Connect with other designers to bring your projects to life.</p>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="card border-0 shadow-sm">
                        <div class="card-body">
                            <h5 class="fw-bold">Exposure</h5>
                            <p class="text-muted">Showcase your best work and build your design portfolio.</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <section id="popular" class="py-5 bg-light">
        <div class="container">
            <h2 class="fw-bold text-center mb-4">Popular Shots</h2>
            <div class="row row-cols-1 row-cols-md-3 g-4">
                <div class="col">
                    <div class="card border-0 shadow-sm">
                        <img src="Landscapes.jpg" class="card-img-top" alt="Shot 1">
                        <div class="card-body">
                            <h5 class="card-title text-center">Creative Design</h5>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card border-0 shadow-sm">
                        <img src="unique.jpg" class="card-img-top" alt="Shot 2">
                        <div class="card-body">
                            <h5 class="card-title text-center">Unique Concepts</h5>
                        </div>
                    </div>
                </div>
                <div class="col">
                    <div class="card border-0 shadow-sm">
                        <img src="abstract.png" class="card-img-top" alt="Shot 3">
                        <div class="card-body">
                            <h5 class="card-title text-center">Innovative Ideas</h5>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <footer class="bg-dark text-white py-4">
        <div class="container">
            <div class="row">
                <div class="col-md-6 text-center text-md-start">
                    <p class="mb-0">designed by shyamkumar.S(24001160)</p>
                </div>
                <div class="col-md-6 text-center text-md-end">
                    <a href="#" class="text-white me-3">Privacy Policy</a>
                    <a href="#" class="text-white">Terms of Service</a>
                </div>
            </div>
        </div>
    </footer>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```

## OUTPUT:

![alt text](1.png) 

![alt text](2.png)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
