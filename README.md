# Project Responsive Web Design using Bootstrap
## Date:26-10-25

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
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Bootstrap Page</title>
  <!-- Bootstrap CSS -->
  <link
    href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css"
    rel="stylesheet"
  />
  <style>
 
    section {
      padding-top: 60px;
      padding-bottom: 60px;
    }
    footer {
      background-color: #000000;
    }
  </style>
</head>
<body>

  <!-- Navigation Bar -->
  <nav class="navbar navbar-expand-lg navbar-dark bg-warning sticky-top shadow-sm">
    <div class="container">
      <a class="navbar-brand fw-bold" href="#">MySite</a>
      <button
        class="navbar-toggler"
        type="button"
        data-bs-toggle="collapse"
        data-bs-target="#navMenu"
        aria-controls="navMenu"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse" id="navMenu">
        <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#intro"
              >Intro</a
            >
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#services">Services</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#about">About</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <!-- Intro Section -->
  <section id="intro" class="bg-primary text-center">
    <div class="container">
      <h1 class="display-4 mb-3">Welcome to MySite</h1>
      <p class="lead mb-4">
        Discover the best solutions tailored for your needs.
      </p>
      <a href="#services" class="btn btn-info btn-lg shadow-sm"
        >Explore Services</a
      >
    </div>
  </section>

  <!-- Services Section -->
  <section id="services" class="container">
    <h2 class="text-center mb-5">Our Services</h2>
    <div class="row g-4">
      <div class="col-md-4">
        <div class="card h-100 border-info shadow-sm">
          <div class="card-body text-center">
            <i class="bi bi-laptop fs-1 text-info mb-3"></i>
            <h5 class="card-title">Web Development</h5>
            <p class="card-text">
              Modern, responsive websites built to impress and perform.
            </p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card h-100 border-info shadow-sm">
          <div class="card-body text-center">
            <i class="bi bi-phone fs-1 text-info mb-3"></i>
            <h5 class="card-title">Mobile Apps</h5>
            <p class="card-text">
              Native and cross-platform mobile apps with great UX.
            </p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card h-100 border-info shadow-sm">
          <div class="card-body text-center">
            <i class="bi bi-bar-chart fs-1 text-info mb-3"></i>
            <h5 class="card-title">Analytics</h5>
            <p class="card-text">
              Data-driven insights to help your business grow.
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="bg-secondary text-white text-center">
    <div class="container">
      <h2 class="mb-4">About Us</h2>
      <p class="fs-5 mx-auto" style="max-width: 700px;">
       MySite is committed to delivering top-notch digital solutions
        tailored for your success. Our expert team combines creativity and
        technology to build experiences that matter.
      </p>
    </div>
  </section>

  <!-- Footer -->
  <footer class="text-center text-white py-3">
    <div class="container">
      <small>&copy;Devesh C (25011036) 2025&reg;.All Rights Reserved.</small>
    </div>
  </footer>

  <!-- Bootstrap JS Bundle (Popper included) -->
  <script
    src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"
  ></script>

  <!-- Bootstrap Icons CDN (optional for icons) -->
  <link
    rel="stylesheet"
    href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css"
  />
</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot (40).png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
