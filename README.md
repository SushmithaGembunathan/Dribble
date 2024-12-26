# Project Responsive Web Design using Bootstrap
## Date:26-12-2024

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
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    
    <header class="bg-light border-bottom py-3">
        <div class="container d-flex justify-content-between align-items-center">
            <h1 class="h4 mb-0">Dribbble</h1>
            <nav>
                <ul class="list-unstyled d-flex mb-0">
                    <li class="mx-3"><a href="#" class="text-decoration-none">Explore</a></li>
                    <li class="mx-3"><a href="#" class="text-decoration-none">Hire a Designer</a></li>
                    <li class="mx-3"><a href="#" class="text-decoration-none">Find Jobs</a></li>
                    <li class="mx-3"><a href="#" class="text-decoration-none">Blog</a></li>
                </ul>
            </nav>
            <div>
                <button class="btn btn-outline-dark me-2">Sign up</button>
                <button class="btn btn-dark">Log in</button>
            </div>
        </div>
    </header>

    
    <section class="text-center py-5">
        <div class="container">
            <h2 class="fw-bold">Discover the world's top designers</h2>
            <p class="text-muted">Explore work from the most talented and accomplished designers ready to take on your next project</p>
            <form class="row g-2 justify-content-center mt-4">
                <div class="col-auto">
                    <input type="text" class="form-control" placeholder="What are you looking for?">
                </div>
                <div class="col-auto">
                    <select class="form-select">
                        <option value="shots">Shots</option>
                    </select>
                </div>
                <div class="col-auto">
                    <button type="submit" class="btn btn-primary">Search</button>
                </div>
            </form>
            <p class="mt-3">Trending searches: <a href="#" class="text-decoration-none">landing page</a>, <a href="#" class="text-decoration-none">e-commerce</a>, <a href="#" class="text-decoration-none">mobile app</a>, <a href="#" class="text-decoration-none">logo design</a>, <a href="#" class="text-decoration-none">dashboard</a>, <a href="#" class="text-decoration-none">icons</a></p>
        </div>
    </section>

    
    <nav class="bg-light py-3">
        <div class="container">
            <ul class="nav nav-pills justify-content-center">
                <li class="nav-item"><a class="nav-link active" href="#">Discover</a></li>
                <li class="nav-item"><a class="nav-link" href="#">Animation</a></li>
                <li class="nav-item"><a class="nav-link" href="#">Branding</a></li>
                <li class="nav-item"><a class="nav-link" href="#">Illustration</a></li>
                <li class="nav-item"><a class="nav-link" href="#">Mobile</a></li>
                <li class="nav-item"><a class="nav-link" href="#">Print</a></li>
                <li class="nav-item"><a class="nav-link" href="#">Product Design</a></li>
                <li class="nav-item"><a class="nav-link" href="#">Typography</a></li>
                <li class="nav-item"><a class="nav-link" href="#">Web Design</a></li>
            </ul>
        </div>
    </nav>

    
    <section class="py-5 bg-dark">
        <div class="container">
            <h2 class="text-light text-center mb-4">Our Featured Works</h2>
            <div class="row g-4">
                <div class="col-6 col-md-4 col-lg-3">
                    <img src="d1.png"class="img-fluid rounded" alt="Work 1" >
                </div>
                <div class="col-6 col-md-4 col-lg-3">
                    <img src="d2.png" class="img-fluid rounded" alt="Work 2">
                </div>
                <div class="col-6 col-md-4 col-lg-3">
                    <img src="d3.png" class="img-fluid rounded" alt="Work 3">
                </div>
                <div class="col-6 col-md-4 col-lg-3">
                    <img src="d4.png" class="img-fluid rounded" alt="Work 4">
                </div>
                <div class="col-6 col-md-4 col-lg-3">
                    <img src="d5.png" class="img-fluid rounded" alt="Work 5">
                </div>
                <div class="col-6 col-md-4 col-lg-3">
                    <img src="d6.png" class="img-fluid rounded" alt="Work 6">
                </div>
                <div class="col-6 col-md-4 col-lg-3">
                    <img src="d7.png" class="img-fluid rounded" alt="Work 7">
                </div>
                <div class="col-6 col-md-4 col-lg-3">
                    <img src="d8.png" class="img-fluid rounded" alt="Work 8">
                </div>
            </div>
        </div>
    </section>


    <footer class="bg-light py-4">
        <div class="container text-center">
            <p class="mb-0 text-muted">&copy; 2024 SUSHMITHA GEMBUNATHAN. All Rights Reserved.</p>
        </div>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>

```



## OUTPUT:
![alt text](<Screenshot 2024-12-26 205728.png>)
![alt text](<Screenshot 2024-12-26 205738.png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
