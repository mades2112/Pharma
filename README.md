# Project Responsive Web Design using Bootstrap
## Date:09-04-2024

## AIM:
To design a responsive website for a Pharmaceutical Company using Bootstrap.


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
APP.HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pharma</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css"  crossorigin="anonymous">
<body>

  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">MAD Pharma</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="#">Home'S</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle active" href="#" id="aboutUsDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              About Us
            </a>
            <ul class="dropdown-menu" aria-labelledby="aboutUsDropdown">
              <li><a class="dropdown-item" href="#">AIM</a></li>
              <li><a class="dropdown-item" href="#">LEADERS</a></li>
              <li><a class="dropdown-item" href="#">FOUNDATION</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="products.html">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="developments.html">developments</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="contact_us.html">Contact_us</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <section class="hero d-flex align-items-center justify-content-center text-center py-5 mb-5">
    <div class="container">
      <h1>ONE STEP WAY HEALTH CARE</h1>
      <p class="lead">Analyzing healthcare policies, including recent reforms, insurance coverage expansion, and the impact of government regulations on healthcare delivery.</p>
      <a href="#" class="btn btn-primary btn-lg">MORE INFORMATION</a>
    </div>
  </section>

  <section class="container">
    <div class="row">
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="/static/hosp.jpeg" class="card-img-top" alt="Image">
          <div class="card-body">
            <h5 class="card-title">QUALITY</h5>
            <p class="card-text">Discussing initiatives and protocols aimed at preventing medical errors, reducing infections, and improving overall patient safety within hospitals.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="hosp2.jpeg" class="card-img-top" alt="Image">
          <div class="card-body">
            <h5 class="card-title">UPDATION</h5>
            <p class="card-text">Explore recent advancements and best practices in patient safety within hospitals, including the implementation of technologies like electronic health records (EHRs), barcode medication administration systems, and artificial intelligence (AI) for early detection of adverse events..</p>
          </div>
        </div>
      </div>
      <div class="col-md-4 mb-4">
        <div class="card">
          <img src="hosp3.jpeg" class="card-img-top" alt="Image">
          <div class="card-body">
            <h5 class="card-title">Patient Care</h5>
            <p class="card-text"> Discuss the importance of placing patients at the center of care delivery and tailoring services to meet their individual needs, preferences, and values. Explore strategies for promoting patient autonomy, dignity, and involvement in decision-making processes..</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <footer class="text-center py-3 bg-light">
    <p>&copy; 2024 MAD Pharma MADESWARAN M(212223040106)</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
</body>
</html>
```
PRODUCTS.HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Our Products</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css"  crossorigin="anonymous">
</head>
<body>


  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">HURAMA Pharma</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="app.html">Home</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle active" href="#" id="aboutUsDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              About Us
            </a>
            <ul class="dropdown-menu" aria-labelledby="aboutUsDropdown">
              <li><a class="dropdown-item" href="#">FOUNDATION</a></li>
              <li><a class="dropdown-item" href="#">AIM</a></li>
              <li><a class="dropdown-item" href="#">LEADERS</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="products.html">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="developments.html">developments</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="contact_us.html">Contact_us</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>

  <section class="container py-5">
    <h1 class="text-center mb-4">Our Products</h1>
    <div class="row row-cols-1 row-cols-md-2 row-cols-lg-3 g-4">
      <div class="col">
        <div class="card">
          <img src="/static/aspirin.jpeg" class="card-img-top" alt="Product Image">
          <div class="card-body">
            <h5 class="card-title">Aspirin</h5>
            <p class="card-text">Aspirin is a nonsteroidal anti-inflammatory drug (NSAID) commonly used to relieve pain, reduce inflammation, and lower fever. It is also often used as a blood thinner to reduce the risk of heart attacks and strokes.</p>
            <a href="#" class="btn btn-primary">Know More</a>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card">
          <img src="/static/Amoxicillin.jpeg" class="card-img-top" alt="Product Image">
          <div class="card-body">
            <h5 class="card-title"> Amoxicillin</h5>
            <p class="card-text"> Amoxicillin is an antibiotic medication belonging to the penicillin group. It is used to treat a wide range of bacterial infections, including respiratory tract infections, ear infections, skin infections, and urinary tract infections.</p>
            <a href="#" class="btn btn-primary">Know More</a>
          </div>
        </div>
      </div>
      <div class="col">
        <div class="card">
          <img src="/static/Lisinopril.jpeg" class="card-img-top" alt="Product Image">
          <div class="card-body">
            <h5 class="card-title">Lisinopril</h5>
            <p class="card-text">  Lisinopril is an angiotensin-converting enzyme (ACE) inhibitor used to treat high blood pressure (hypertension), heart failure, and improve survival following a heart attack</p>
            <a href="#" class="btn btn-primary">Know More</a>
          </div>
        </div>
      </div>
      </div>
  
  
  </section>

  <footer class="text-center py-3 bg-light">
    <p>&copy; 2024 MAD Pharma MADESWARAN M(212223040106)</p>
  </footer>

</body>
</html>
```
DEVELOPMENTS.HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>DEVELOPMENTS</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" crossorigin="anonymous">
</head>
<body>

  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">HURAMA Pharma</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="app.html">Home</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle active" href="#" id="aboutUsDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              About Us
            </a>
            <ul class="dropdown-menu" aria-labelledby="aboutUsDropdown">
              <li><a class="dropdown-item" href="#">FOUNDATION</a></li>
              <li><a class="dropdown-item" href="#">AIM</a></li>
              <li><a class="dropdown-item" href="#">LEADERS</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="products.html">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="developments.html">developments</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="contact_us.html">Contact_us</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>


  <section class="container py-5">
    <h1 class="text-center mb-4">News & Events</h1>
    <div class="row">
      <div class="col-md-3 mb-2">
        <div class="card">
          <img src="/static/microbil.jpeg " class="card-img-top" alt="News Image">
          <div class="card-body">
            <h5 class="card-title">Microbial Warfare in the Gut: Probiotics vs. Dysbiosis</h5>
            <p class="card-text">Probiotics are beneficial bacteria that promote gut health, combating dysbiosis—an imbalance in the gut microbiota linked to various digestive disorders and immune dysfunctions. This microbial warfare within the gut ecosystem highlights the importance of maintaining a healthy balance of gut flora for overall well-being.</p>
            <a href="#" class="btn btn-primary btn-sm">Continue Reading</a>
          </div>
        </div>
      </div>
      <div class="col-md-3 mb-2">
        <div class="card">
          <img src="/static/gener.jpeg" class="card-img-top" alt="News Image">
          <div class="card-body">
            <h5 class="card-title">Gene Editing Battles Genetic Disorders: CRISPR vs. Inherited Diseases</h5>
            <p class="card-text">Gene editing technologies like CRISPR offer the potential to correct genetic mutations responsible for inherited diseases. This interior medical war involves precise manipulation of DNA sequences to combat conditions ranging from cystic fibrosis to sickle cell anemia, ushering in a new era of personalized medicine.</p>
            <a href="#" class="btn btn-primary btn-sm">Continue Reading</a>
          </div>
        </div>
      </div>
    </div>
   
    
    </section>
  <footer class="text-center py-3 bg-light">
    <p>&copy; </p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
</body>
</html>
```
CONTACT_US.HTML
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>contact us</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css"  crossorigin="anonymous">
</head>
<body>

  <nav class="navbar navbar-expand-lg navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">MAD Pharma</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item">
            <a class="nav-link" href="app.html">Home</a>
          </li>
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle active" href="#" id="aboutUsDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              About Us
            </a>
            <ul class="dropdown-menu" aria-labelledby="aboutUsDropdown">
              <li><a class="dropdown-item" href="#">FOUNDATION</a></li>
              <li><a class="dropdown-item" href="#">AIM</a></li>
              <li><a class="dropdown-item" href="#">LEADERS</a></li>
            </ul>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="products.html">Products</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="developments.html">DEVELOPMENTS</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="contact_us.html">Contact_us</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <section class="container py-5">
    <h1 class="text-center mb-4">Contact Us</h1>
    <div class="row">
      <div class="col-md-6">
        <h3>INFO</h3>
        <p>MAD Pharma</p>
        <p>MAD Pharma
           KUMARAN ST,
           KELAMBALAUR,
           KANCHEEPURAM-600129.
        </p>
        <p>Phone Number: <a href="tel:+987654321">224-228-334-887</a></p>
        <p>Email: <a href="mailto:info@mycompany.com">info@MAD.com</a></p>
      </div>
      <div class="col-md-6">
        <h3>To stay in touch </h3>
        <form>
          <div class="mb-3">
            <label for="name" class="form-label">Your Name</label>
            <input type="text" class="form-control" id="name" required>
          </div>
          <div class="mb-3">
            <label for="email" class="form-label">Email Address</label>
            <input type="email" class="form-control" id="email" required>
          </div>
          <div class="mb-3">
            <label for="message" class="form-label">Message</label>
            <textarea class="form-control" id="message" rows="3" required></textarea>
          </div>
          <button type="submit" class="btn btn-primary">Send Message</button>
        </form>
      </div>
    </div>
  </section>

  <footer class="text-center py-3 bg-light">
    <p>&copy; 2024 MAD Pharma MADESWARAN M(212223040106)</p>
  </footer>
  

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot 2024-05-10 172145.png>)
![alt text](<Screenshot 2024-05-10 172155.png>)
![alt text](<Screenshot 2024-05-10 172202.png>)
![alt text](<Screenshot 2024-05-10 172211.png>)

## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
