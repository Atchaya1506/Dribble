# Project Responsive Web Design using Bootstrap
## Date:24/12/2024

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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribbble Clone</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body class="bg-light text-light">
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container">
            <a class="navbar-brand" href="#">Dribbble Clone</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <a class="nav-link" href="#home">home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#profile">profile</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#shots">shots</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#now">now</a>
                    </li>
                    <li class="nav-item">
                        <a href="#signup" class="btn btn-success ms-2">Sign Up</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>

    
    <section class="text-center py-5 bg-primary">
        <div class="container ">
            <h1 class="display-4 text-light">Discover Your Creative Mind</h1>
            <p class="lead text-light">ThE Man Who Started Dribble With 50 T-Shirts</p>
            <img src="dibble.png">
            <p>Zack oniska</p>
        </div>
    </section>
    <section class="py-5 bg-secondary">
        <div class="container">
            <h2 class="text-light text-center mb-4">Our Works</h2>
            <div class="row g-4">
                <div class="col-6 col-md-4 col-lg-3">
                    <img src="img 1.png"class="img-fluid rounded" alt="Work 1" >
                </div>
                <div class="col-6 col-md-4 col-lg-3">
                    <img src="img 2.png" class="img-fluid rounded" alt="Work 2">
                </div>
                <div class="col-6 col-md-4 col-lg-3">
                    <img src="img 3.png" class="img-fluid rounded" alt="Work 3">
                </div>
                <div class="col-6 col-md-4 col-lg-3">
                    <img src="img 4.png" class="img-fluid rounded" alt="Work 4">
                </div>
                <div class="col-6 col-md-4 col-lg-3">
                    <img src="img 5.png" class="img-fluid rounded" alt="Work 5">
                </div>
                <div class="col-6 col-md-4 col-lg-3">
                    <img src="img 6.png" class="img-fluid rounded" alt="Work 6">
                </div>
                <div class="col-6 col-md-4 col-lg-3">
                    <img src="img 7.png" class="img-fluid rounded" alt="Work 7">
                </div>
                <div class="col-6 col-md-4 col-lg-3">
                    <img src="img 8.png" class="img-fluid rounded" alt="Work 8">
                </div>
                <div class="col-6 col-md-4 col-lg-3">
                    <img src="img 9.png"class="img-fluid rounded" alt="Work 1" >
                </div>
                <div class="col-6 col-md-4 col-lg-3">
                    <img src="img 10.png" class="img-fluid rounded" alt="Work 2">
                </div>
                <div class="col-6 col-md-4 col-lg-3">
                    <img src="img 11.png" class="img-fluid rounded" alt="Work 3">
                </div>
                <div class="col-6 col-md-4 col-lg-3">
                    <img src="img 12.png" class="img-fluid rounded" alt="Work 4">
                </div>
                <div class="col-6 col-md-4 col-lg-3">
                    <img src="img 13.png" class="img-fluid rounded" alt="Work 5">
                </div>
                <div class="col-6 col-md-4 col-lg-3">
                    <img src="img 14.png" class="img-fluid rounded" alt="Work 6">
                </div>
                <div class="col-6 col-md-4 col-lg-3">
                    <img src="img 15.png" class="img-fluid rounded" alt="Work 7">
                </div>
                <div class="col-6 col-md-4 col-lg-3">
                    <img src="img 16.png" class="img-fluid rounded" alt="Work 8">
                </div>
            </div>
        </div>
    </section>
    
    <footer class="bg-dark text-light py-3">
        <div class="container text-center">
            <p>&copy; DESIGNED BY ATCHAYA B</p>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```

## OUTPUT:
![alt text](<Screenshot 2024-12-24 054834.png>)
![alt text](<Screenshot 2024-12-24 054846.png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
