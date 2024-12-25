# Project Responsive Web Design using Bootstrap
## Date:25/12/2024

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
    <title>Biocon Pharmacy Company</title>
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
</head>
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>

<body>

    <!-- Header -->
    <header class="bg-dark text-white text-center py-3">
        <h1>Biocon Pharmacy Company</h1>
        <nav class="navbar navbar-expand-lg navbar-light bg-light">
            <a class="navbar-brand" href="#">Pharmacy</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                    <li class="nav-item active">
                        <a class="nav-link" href="home.html">Home</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="Products.html">Products</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="Contact.html">Contact Us</a>
                    </li>
                </ul>
            </div>
        </nav>
    </header>

    <!-- Main Content -->
    <div class="container mt-4">
        <div class="row">
            <div class="col-md-8">
                <h2>Our Services</h2>
                <p>We offer a wide range of pharmaceutical services including prescription medications, over-the-counter drugs, and health consultations.</p>
            </div>
            <div class="col-md-4">
                <h2>Latest News</h2>
                <ul class="list-group">
                    <li class="list-group-item">50% off on all medicines</li>
                    <li class="list-group-item">Flu season is here, get your vaccine today!</li>
                    <li class="list-group-item">Check out our new line of health supplements.</li>
                </ul>
            </div>
        </div>
    </div>
    <br><br><br><br>

    <!-- Footer -->
    <footer class="bg-dark text-white text-center py-3">
        <p>Designed and Developed by K.Mohamed Althaf</p>
    </footer>
    </body>
</html>

<html>
    <head>
    <title>Biocon Pharmacy Company</title>
    <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    </head>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>

    <body>
        <header class="bg-dark text-white text-center py-3">
            <h1>Biocon Pharmacy Company</h1>
        </header>
        <br>

        <center>
            <h2>
        <ul class="text-capitalise">
            <li>We offer a wide range of English medecines at the very lowest price.</li>
            <br><li>We also have traditional medecines in our pharmacy.
</li> <br>
<li>we do have a small clinic in our pharmacy in which we diagonise minor allergies,fever and even blood pressure/diabetes level
</li>
</ul>
</h2>
      </center><br><br>
      <button>
        <a  class="text-secondary" href="Homepage.html">Back to home</a>
    </button><br><br>
    <footer class="bg-dark text-white text-center py-3">
        <p>Designed and Developed by K.Mohamed Althaf</p>
    </footer>

    </body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Biocon Pharmacy Company</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
        }
        .contact-section {
            padding: 20px;
        }
        .contact-section p {
            font-size: 18px;
        }
        .contact-section textarea {
            width: 100%;
            height: 100px;
            margin-top: 10px;
        }
        .contact-section button {
            margin-top: 10px;
            padding: 10px 20px;
            cursor: pointer;
            background-color: #333;
            color: white;
            border: none;
        }
        .footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <div class="header">
        <h1>Biocon Pharmacy Company</h1>
    </div>

    <div class="contact-section">
        <p>Contact us at:</p>
        <p>xyz@gmail.com</p>
        <p>+917860024110</p>

        <p>Write to us!</p>
        <textarea></textarea>
        <br>
        <button onclick="window.location.href='home.html';">Back to home</button>
    </div>

    <div class="footer">
        <p>Designed and Developed by K.Mohamed Althaf</p>
    </div>
</body>
</html>

<html>
    <head>
        <title>Biocon Pharmacy Company</title>
        <link href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" rel="stylesheet">
    </head>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
    <body>
        <header class="bg-dark text-center text-white py-3">
            <h1>Biocon Pharmacy Company</h1>
        </header>
        <section class="products-section">
  <div class="container">
    <h2>Featured Products</h2>
    <div class="row">
      <div class="col-md-4">
        <div class="card">
          <img src="https://tweakindia.com/wp-content/uploads/2023/04/cleanseme.jpg" class="card-img-top" alt="Product 1">
          <div class="card-body">
            <h5 class="card-title">CleanseMe Lotion</h5>
            <p class="card-text">CleanseMe gentle skin cleansing lotion is a fragnance-free,ph-balanced daily cleanser designed for sensitive and irritated skin.</p>
            <a href="#" class="btn btn-primary">Buy Now</a>
          </div>
        </div>
      </div>
      </div>
  </div>
</section>
        <button>
            <a  class="text-secondary " href="Homepage.html">Back to home</a>
        </button>
        <footer class="bg-dark text-white text-center py-3">
            <p>Designed and Developed by K.Mohamed Althaf</p>
        </footer>
    
    </body>
</html>

```

## OUTPUT:

![alt text](<Screenshot 2024-12-25 131911.png>)
![alt text](<Screenshot 2024-12-25 131853.png>)
![alt text](<Screenshot 2024-12-25 132005.png>)
![alt text](<Screenshot 2024-12-25 132604.png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
