# Ex02 Commercial Website
### Name:Swetha D
### Reg no:212223040222
## AIM
To create a commercial website using CSS Flexbox.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for Homepage, Products / Services, About Us, Contact Details and User Account.

### STEP 5
Include social media links at the footer with copyright information.

### STEP 6
Define global styles for fonts, colors, and layout.

### STEP 7
Style the header, navigation bar, and sections.

### STEP 8
Use Flexbox for layout design.

### STEP 9
Add hover effects and transitions for interactivity.

### STEP 10
Add Images and Media.

### STEP 11
Use optimized images for a professional look.

### STEP 12
Open the HTML file in a browser to check layout and functionality.

### STEP 13
Fix styling issues and refine content placement.

### STEP 14
Deploy the website.

### STEP 15
Upload to GitHub Pages for free hosting.

## PROGRAM
### main.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Amazon Store</title>
  <link rel="stylesheet" href="main.css">
  <link href="https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css" rel="stylesheet">
</head>
<body>
  <div class="header">
    <div class="container">
      <div class="navbar">
        <div class="logo">
            <li><a href="main.html">Products</a></li>

          <h1><span class="amazon-orange">Amazon</span> <span class="store-black">Store</span></h1>
        </div>
        <nav>
    <ul>
        <li><a href="main.html">Home</a></li>
        <li><a href="prod.html">Products</a></li>
          <li><a href="contact.html">Contacts</a></li>
        <li><a href="account.html">Account</a></li>
    </ul>
</nav>

        <div class="nav-icon">
          <a href="#"><i class='bx bx-search'></i></a>
          <a href="#"><i class='bx bx-user'></i></a>
          <a href="cart.html"><i class='bx bx-cart'></i></a>

          <div class="bx bx-menu" id="menu-icon"></div>
        </div>
      </div>

      <div class="home">
        <div class="text">
          <div class="image">
          <img src="images/home.png" alt="Banner Image">
        </div>
          <a href="#" class="btn">Shop Now</a>
        </div>
      </div>
    </div>
  </div>
  <footer>
    <p>&copy; 2025 Commercial Inc. | Follow us on
      <a href="#">Facebook</a>, <a href="#">Twitter</a>, <a href="#">Instagram</a>
    </p>
  </footer>
</body>
</html>
```
### product.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Amazon Store - Products</title>
  <link rel="stylesheet" href="main.css" />
  <link href="https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css" rel="stylesheet" />
</head>
<body>
  <div class="header">
    <div class="container">
      <div class="navbar">
        <div class="logo">
          <h1><span class="amazon-orange">Amazon</span> <span class="store-black">Store</span></h1>
        </div>
        <nav>
          <ul>
             <li><a href="main.html">Home</a></li>
            <li><a href="prod.html">Product</a></li>
            <li><a href="contact.html">Contact</a></li>
            <li><a href="account.html">Account</a></li>
          </ul>
        </nav>
        <div class="nav-icon">
          <a href="#"><i class='bx bx-search'></i></a>
          <a href="#"><i class='bx bx-user'></i></a>
          <a href="cart.html"><i class='bx bx-cart'></i></a>
          <a href="#"><i class='bx bx-home'></i></a>
          <div class="bx bx-menu" id="menu-icon"></div>
        </div>
      </div>

      <div class="product-header">
        <h2>Our Products</h2>
      </div>

      <div class="product-grid">
        <div class="product-card">
          <img src="images/red.png" alt="Product 1" />
          <h3>Red T-shirt</h3>
          <p>$19.99</p>
          <button>Add to Cart</button>
        </div>
        <div class="product-card">
          <img src="images/blue.png" alt="Product 2" />
          <h3>Blue Hoodie</h3>
          <p>$29.99</p>
          <button>Add to Cart</button>
        </div>
        <div class="product-card">
          <img src="images/yellow.png" alt="Product 3" />
          <h3>Yellow Jacket</h3>
          <p>$49.99</p>
          <button>Add to Cart</button>
        </div>
        <div class="product-card">
          <img src="images/black.png" alt="Product 4" />
          <h3>Black Sneakers</h3>
          <p>$59.99</p>
          <button>Add to Cart</button>
        </div>
      </div>
    </div>
  </div>
  <footer>
    <p>&copy; 2025 Commercial Inc. | Follow us on
      <a href="#">Facebook</a>, <a href="#">Twitter</a>, <a href="#">Instagram</a>
    </p>
  </footer>
</body>
</html>
```
### contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact - Commercial Website</title>
  <link rel="stylesheet" href="main.css">
</head>
<body>
  <header>
    <nav>
      <ul class="navbar">
        <li><a href="main.html">Home</a></li>
        <li><a href="prod.html">Product</a></li>
        <li><a href="contact.html">Contact</a></li>
        <li><a href="account.html">Account</a></li>
        <a href="cart.html"><i class='bx bx-cart'></i></a>
      </ul>
    </nav>
  </header>

  <section id="contact" class="section">
    <h2>Contact Us</h2>
    <p>Have any questions? Reach out to us through the following channels:</p>
    <ul>
      <li>Email: contact@Procart.com</li>
      <li>Phone: (+91)7654347891</li>
    </ul>
  </section>

  <footer>
    <p>&copy; 2025 Commercial Inc. | Follow us on
      <a href="#">Facebook</a>, <a href="#">Twitter</a>, <a href="#">Instagram</a>
    </p>
  </footer>
</body>
</html>
```
### cart.html
```

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Cart - Amazon Store</title>
  <link rel="stylesheet" href="main.css" />
</head>
<body>

  <header>
    <h1>Amazon Store</h1>
    <nav>
      <a href="main.html">Home</a>
      <a href="product.html">Products</a>
      <a href="contact.html">contact</a>
      <a href="account.html">Account</a>
        <a href="cart.html"><i class='bx bx-cart'></i></a>
    </nav>
  </header>

  <main class="cart-container">
    <h2>Your Shopping Cart</h2>

    <table class="cart-table">
      <thead>
        <tr>
          <th>Product</th>
          <th>Title</th>
          <th>Price</th>
          <th>Quantity</th>
          <th>Total</th>
          <th>Remove</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td><img src="images/blue.png" alt="Product 1" class="cart-img"></td>
          <td>Casual T-Shirt</td>
          <td>$25.00</td>
          <td><input type="number" value="1" min="1" class="qty-input"/></td>
          <td>$25.00</td>
          <td><button class="remove-btn">X</button></td>
        </tr>
        <tr>
          <td><img src="images/black.png" alt="Product 2" class="cart-img"></td>
          <td>Wireless Headphones</td>
          <td>$89.00</td>
          <td><input type="number" value="1" min="1" class="qty-input"/></td>
          <td>$89.00</td>
          <td><button class="remove-btn">X</button></td>
        </tr>
      </tbody>
    </table>

    <div class="cart-summary">
      <h3>Subtotal: $114.00</h3>
      <button class="checkout-btn">Proceed to Checkout</button>
    </div>
  </main>

  <footer>
    <p>&copy; 2025 Commercial Inc. | Follow us on
      <a href="#">Facebook</a>, <a href="#">Twitter</a>, <a href="#">Instagram</a>
    </p>
  </footer>
</body>
</html>
```
### account.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Account - ProCart</title>
  <link rel="stylesheet" href="main.css">
</head>
<body>
  <header>
    <nav>
      <ul class="navbar">
        <li><a href="main.html">Home</a></li>
        <li><a href="services.html">Services</a></li>
        <li><a href="contact.html">Contact</a></li>
        <li><a href="account.html">Account</a></li>
        <a href="cart.html"><i class='bx bx-cart'></i></a>
      </ul>
    </nav>
  </header>

  <section id="account" class="section">
    <h2>User Account</h2>
    <p>Create an account to manage your orders and track your purchases.</p>

    <!-- Account Form Box -->
    <div class="account-box">
      <h3>Sign Up</h3>
      <form action="#" method="POST" id="signUpForm">
        <div class="form-field">
          <label for="username">Username</label>
          <input type="text" id="username" name="username" required placeholder="Enter your username">
        </div>
        <div class="form-field">
          <label for="email">Email Address</label>
          <input type="email" id="email" name="email" required placeholder="Enter your email">
        </div>
        <div class="form-field">
          <label for="password">Password</label>
          <input type="password" id="password" name="password" required placeholder="Enter your password">
        </div>
        <div class="form-field">
          <label for="confirm-password">Confirm Password</label>
          <input type="password" id="confirm-password" name="confirm-password" required placeholder="Confirm your password">
        </div>
        <button type="submit" class="sign-up-btn">Sign Up</button>
      </form>

      <p>Already have an account? <a href="login.html">Log in</a></p>
    </div>

  </section>

  <footer>
    <p>&copy; 2025 ProCart. Follow us on 
      <a href="#">Facebook</a>, <a href="#">Twitter</a>, <a href="#">Instagram</a>
    </p>
  </footer>

  <script>
    // Basic validation for password match
    document.getElementById('signUpForm').addEventListener('submit', function(event) {
      const password = document.getElementById('password').value;
      const confirmPassword = document.getElementById('confirm-password').value;

      if (password !== confirmPassword) {
        alert("Passwords do not match!");
        event.preventDefault(); // Prevent form submission
      }
    });
  </script>
</body>
</html>
```
### main.css
```
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body, html {
  font-family: Arial, sans-serif;
  height: 100%;
}

/* Full background gradient */
.header {
  background: linear-gradient(to right, #ffd6d6, #ffffff);
  min-height: 100vh;
}

/* Container Layout */
.container {
  max-width: 1300px;
  margin: auto;
  padding: 25px;
}

.image img {
  width: 100%; /* Or a fixed size like 800px */
  max-width: 800px; /* Optional: max width limit */
  height: auto;
  display: block;
  margin: 0 auto; /* Center the image horizontally */
}

/* Navbar */
.navbar {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding-bottom: 20px;
}

.logo h1 {
  font-size: 24px;
}

.amazon-orange {
  color: orange;
  font-weight: bold;
}

.store-black {
  color: black;
  font-weight: bold;
}

nav {
  flex: 1;
  text-align: center;
}

nav ul {
  list-style: none;
}

nav ul li {
  display: inline-block;
  margin-right: 20px;
}

a {
  text-decoration: none;
  color: #555;
}

.nav-icon a {
  margin-left: 10px;
  font-size: 20px;
  color: #000;
}

/* Home Section */
.home {
  display: flex;
  align-items: center;
  justify-content: center;
  flex-wrap: wrap;
  min-height: calc(100vh - 80px); /* Adjust based on header height */
  text-align: center;
  padding: 50px 20px;
  background: linear-gradient(to right, #ffd6d6, #ffffff); /* fallback if .header not used */
}

.home .text {
  flex: 1 1 400px;
  padding: 20px;
}

.home .text h1 {
  font-size: 40px;
  margin-bottom: 20px;
}

.home .text h1 span {
  color: #003366;
}

.home .text p {
  font-size: 16px;
  color: #555;
  margin-bottom: 20px;
}

.btn {
  display: inline-block;
  background: #ff3e3e;
  color: #fff;
  padding: 10px 20px;
  border-radius: 30px;
  transition: 0.3s;
}

.btn:hover {
  background: #e62e2e;
}

.home .image {
  flex: 1 1 400px;
  padding: 20px;
  display: flex;
  justify-content: center;
  align-items: center;
}
.home .image img {
  width: 100%;
  max-width: 700px; /* Adjust this value as needed */
  height: auto;
  display: block;
  margin: 0 auto;
}

{
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body, html {
      font-family: Arial, sans-serif;
      height: 100%;
    }

    .header {
      background: linear-gradient(to right, #ffd6d6, #ffffff);
      min-height: 100vh;
    }

    .container {
      max-width: 1200px;
      margin: auto;
      padding: 20px;
    }

    .navbar {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding-bottom: 20px;
    }

    .logo h1 {
      font-size: 24px;
    }

    .amazon-orange {
      color: orange;
      font-weight: bold;
    }

    .store-black {
      color: black;
      font-weight: bold;
    }

    nav {
      flex: 1;
      text-align: center;
    }

    nav ul {
      list-style: none;
    }

    nav ul li {
      display: inline-block;
      margin-right: 20px;
    }

    nav ul li a {
      text-decoration: none;
      color: #555;
    }

    .nav-icon a {
      margin-left: 10px;
      font-size: 20px;
      color: #000;
    }

    #menu-icon {
      display: none;
    }

    /* Product Section */
    .product-header {
      text-align: center;
      margin: 40px 0 20px;
    }

    .product-header h2 {
      font-size: 32px;
      font-weight: bold;
    }

    .product-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 30px;
    }

    .product-card {
      background: #fff;
      border-radius: 10px;
      padding: 20px;
      text-align: center;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      transition: transform 0.3s ease;
    }

    .product-card:hover {
      transform: translateY(-5px);
    }

    .product-card img {
      width: 100%;
      max-height: 200px;
      object-fit: contain;
      margin-bottom: 15px;
    }

    .product-card h3 {
      font-size: 20px;
      margin-bottom: 10px;
      color: #333;
    }

    .product-card p {
      font-size: 16px;
      color: #666;
      margin-bottom: 15px;
    }

    .product-card button {
      background: #ff3e3e;
      color: #fff;
      border: none;
      padding: 10px 20px;
      border-radius: 20px;
      cursor: pointer;
      font-size: 14px;
    }

    .product-card button:hover {
      background: #e62e2e;
    }

    @media (max-width: 768px) {
      .navbar {
        flex-direction: column;
        align-items: flex-start;
      }
      nav {
        text-align: left;
      }
    }
    /* Reset & Base Styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  line-height: 1.6;
  background: linear-gradient(to right, #ffd6d6, #ffffff);
  color: #333;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
}

/* Navigation */
header {
  background-color: #fff;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  padding: 10px 0;
}

.navbar {
  list-style: none;
  display: flex;
  justify-content: center;
  gap: 30px;
}

.navbar li a {
  text-decoration: none;
  color: #333;
  font-weight: 500;
  padding: 10px;
  transition: color 0.3s ease;
}

.navbar li a:hover {
  color: #e63946;
}

/* Contact Section */
.section {
  padding: 60px 20px;
  text-align: center;
  flex: 1;
}

.section h2 {
  font-size: 36px;
  margin-bottom: 20px;
  color: #222;
}

.section p {
  font-size: 18px;
  margin-bottom: 30px;
  color: #444;
}

.section ul {
  list-style-type: none;
  font-size: 18px;
  color: #555;
}

.section ul li {
  margin: 10px 0;
}

/* Footer */
footer {
  background-color: #222;
  color: #fff;
  text-align: center;
  padding: 20px;
  font-size: 14px;
}

footer a {
  color: #f4a261;
  text-decoration: none;
  margin: 0 5px;
}

footer a:hover {
  color: #e76f51;
}
/* Reset & Base Styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  line-height: 1.6;
  background: linear-gradient(to right, #ffd6d6, #ffffff);
  color: #333;
  min-height: 100vh;
  display: flex;
  flex-direction: column;
}

/* Navigation */
header {
  background-color: #fff;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
  padding: 10px 0;
}

.navbar {
  list-style: none;
  display: flex;
  justify-content: center;
  gap: 30px;
}

.navbar li a {
  text-decoration: none;
  color: #333;
  font-weight: 500;
  padding: 10px;
  transition: color 0.3s ease;
}

.navbar li a:hover {
  color: #e63946;
}

/* Contact Section */
.section {
  padding: 60px 20px;
  text-align: center;
  flex: 1;
}

.section h2 {
  font-size: 36px;
  margin-bottom: 20px;
  color: #222;
}

.section p {
  font-size: 18px;
  margin-bottom: 30px;
  color: #444;
}

.section ul {
  list-style-type: none;
  font-size: 18px;
  color: #555;
}

.section ul li {
  margin: 10px 0;
}

/* Footer */
footer {
  background-color: #222;
  color: #fff;
  text-align: center;
  padding: 20px;
  font-size: 14px;
}

footer a {
  color: #f4a261;
  text-decoration: none;
  margin: 0 5px;
}

footer a:hover {
  color: #e76f51;
}
/* Reset & Base Styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  background: linear-gradient(to right, #ffeaea, #ffffff);
  color: #333;
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}

/* Header */
header {
  background-color: #fff;
  padding: 20px;
  text-align: center;
  border-bottom: 1px solid #ddd;
}

header h1 {
  font-size: 32px;
  color: #e47911; /* Amazon orange */
  margin-bottom: 10px;
}

nav {
  display: flex;
  justify-content: center;
  gap: 30px;
}

nav a {
  text-decoration: none;
  color: #333;
  font-weight: bold;
  transition: color 0.3s ease;
}

nav a:hover {
  color: #e63946;
}

/* Cart Container */
.cart-container {
  padding: 40px 20px;
  flex: 1;
}

.cart-container h2 {
  text-align: center;
  margin-bottom: 30px;
  font-size: 28px;
}

/* Table */
.cart-table {
  width: 90%;
  max-width: 1000px;
  margin: 0 auto 30px auto;
  border-collapse: collapse;
  background-color: #fff;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
}

.cart-table th, .cart-table td {
  padding: 15px;
  text-align: center;
  border-bottom: 1px solid #ddd;
}

.cart-img {
  width: 80px;
  height: auto;
  border-radius: 4px;
}

.qty-input {
  width: 60px;
  padding: 5px;
  font-size: 16px;
}

.remove-btn {
  background-color: #e74c3c;
  color: white;
  border: none;
  padding: 8px 12px;
  font-size: 14px;
  cursor: pointer;
  border-radius: 5px;
}

.remove-btn:hover {
  background-color: #c0392b;
}

/* Cart Summary */
.cart-summary {
  text-align: center;
  font-size: 20px;
}

.cart-summary h3 {
  margin-bottom: 15px;
}

.checkout-btn {
  background-color: #e47911;
  color: white;
  padding: 12px 24px;
  border: none;
  border-radius: 6px;
  font-size: 16px;
  cursor: pointer;
  transition: background 0.3s ease;
}

.checkout-btn:hover {
  background-color: #d26900;
}

/* Footer */
footer {
  background-color: #222;
  color: #fff;
  text-align: center;
  padding: 20px;
  font-size: 14px;
}

footer a {
  color: #f4a261;
  margin: 0 5px;
  text-decoration: none;
}

footer a:hover {
  color: #e76f51;
}

/* Responsive */
@media screen and (max-width: 768px) {
  .cart-table th, .cart-table td {
    padding: 10px;
    font-size: 14px;
  }

  .qty-input {
    width: 40px;
  }

  .checkout-btn {
    width: 90%;
    max-width: 300px;
  }
}
/* Account Page Specific Styles */
#account .account-box {
    background-color: white;
    padding: 30px;
    border-radius: 8px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    width: 350px;
    margin: 40px auto;
    border: 2px solid #007bff; /* Border for the box */
}

#account .account-box h3 {
    margin-bottom: 20px;
}

#account .account-box .form-field {
    margin-bottom: 20px;
}

#account .account-box .form-field label {
    display: block;
    font-weight: bold;
    margin-bottom: 5px;
}

#account .account-box .form-field input {
    width: 100%;
    padding: 10px;
    margin-top: 5px;
    border: 1px solid #ccc;
    border-radius: 5px;
    background-color: #f9f9f9;
}

#account .account-box .sign-up-btn {
    width: 100%;
    padding: 12px;
    background-color: #007bff;
    color: white;
    border: none;
    cursor: pointer;
    border-radius: 5px;
    font-size: 16px;
}

#account .account-box .sign-up-btn:hover {
    background-color: #0056b3;
}

#account .account-box p {
    margin-top: 20px;
}

#account .account-box p a {
    text-decoration: none;
    color: #007bff;
}

#account .account-box p a:hover {
    text-decoration: underline;
}
```
## OUTPUT
![{7AE28C0D-E08B-4F6D-A03E-B00A8530195B}](https://github.com/user-attachments/assets/08de0baf-b172-44b7-a170-064988921ad6)
![{0837EA9E-ACFB-4643-AB47-46D12D27F502}](https://github.com/user-attachments/assets/22664f93-0d46-4e2c-b171-46ccf50f2924)
![{2EEEC31C-B029-4B58-A920-F51885749CA9}](https://github.com/user-attachments/assets/c8687710-280a-4c48-8eed-9ef24ab76c0c)
![{20DE6441-733B-4C31-A921-3C3D567177B7}](https://github.com/user-attachments/assets/7db11300-b55f-4aea-954b-81a151589885)
![{8CB19EF0-FAD5-4714-A3CF-6E3B8924CC87}](https://github.com/user-attachments/assets/a6cb7939-fd4b-4cad-8586-b782c3734525)

## RESULT
The program for creating commercial website using CSS Flexbox is executed successfully.
