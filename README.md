# Project Responsive Web Design using Bootstrap
## Date: 21-11-2024

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
index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Design Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Top Navigation Bar -->
    <div class="top-bar">
        <input type="text" class="search-bar" placeholder="Search...">
        <a href="#" class="nav-item">Shots</a>
        <a href="#" class="nav-item">Designer</a>
        <a href="#" class="nav-item">Teams</a>
        <a href="#" class="nav-item">Community</a>
        <a href="#" class="nav-item blue-text">Jobs</a>
        <a href="#" class="nav-item blue-text">Log in</a>
    </div>

    <!-- Header Section -->
    <header>
        <div class="header-content">
            <h1>Explore Your Thoughts</h1>
            <p>Explore work from the most talented and accomplished designers ready to take on your next project</p>
            <input type="text" class="search-input" placeholder="What are you looking for?">
        </div>
    </header>

    <!-- Trending Searches Section -->
    <section class="trending">
        <h2>Trending Searches</h2>
        <div class="trending-tags">
            <span>Wild Animals</span>
            <span>Birds</span>
            <span>Fragrant flowers</span>
            <span>Poisnous Snake</span>
            <span>Whale Sharks</span>
            <span>Wild Trees</span>
        </div>
    </section>

    <!-- Gallery Section -->
    <section class="gallery">

        <div class="card">
            <img src="https://i.pinimg.com/736x/71/3c/ee/713cee828c6948955922be6023959397.jpg" alt="Design Sample">
            <h3>Elephant</h3>
            <p>7.2k Views</p>
        </div>

        <div class="card">
            <img src="https://i.pinimg.com/736x/9f/ed/7f/9fed7f4716dc5bf5c32be5936b5b0538.jpg" alt="Design Sample">
            <h3>Fishes</h3>
            <p>7.2k Views</p>
        </div>

        <div class="card">
            <img src="https://i.pinimg.com/736x/06/60/d3/0660d36678555330fb06cc268a685908.jpg" alt="Design Sample">
            <h3>Humming Birds</h3>
            <p>7.2k Views</p>
        </div>

        <div class="card">
            <img src="https://i.pinimg.com/736x/72/93/ed/7293ed6b031059e3dc42034120e41081.jpg" alt="Design Sample">
            <h3>Red Panda</h3>
            <p>7.2k Views</p>
        </div>

        <div class="card">
            <img src="https://i.pinimg.com/736x/1d/c7/ac/1dc7ac3c3e5e90b5e88ec910bc8d8a9f.jpg" alt="Design Sample">
            <h3>Spider</h3>
            <p>7.2k Views</p>
        </div>

        <div class="card">
            <img src="https://i.pinimg.com/736x/ff/ff/83/ffff834cf27a88abcbca158fd3dfca27.jpg" alt="Design Sample">
            <h3>Squirrel</h3>
            <p>7.2k Views</p>
        </div>

        <div class="card">
            <img src="https://i.pinimg.com/736x/f7/a7/7f/f7a77fcda5eb9db53173b9f177b39437.jpg" alt="Design Sample">
            <h3>Deer</h3>
            <p>7.2k Views</p>
        </div>

        <div class="card">
            <img src="https://i.pinimg.com/736x/cc/7a/c7/cc7ac7461e61b16ca4ba0662cf41c584.jpg" alt="Design Sample">
            <h3>Eagle</h3>
            <p>7.2k Views</p>
        </div>

        <div class="card">
            <img src="https://i.pinimg.com/736x/dd/1a/5f/dd1a5f87662b3a58221f42e7e6cfc95d.jpg" alt="Design Sample">
            <h3>Cheetah</h3>
            <p>7.2k Views</p>
        </div>

        <div class="card">
            <img src="https://i.pinimg.com/736x/79/a9/96/79a996bcb04fe3fe0b249c3fd7df3016.jpg" alt="Design Sample">
            <h3>Butterflies</h3>
            <p>7.2k Views</p>
        </div>

        <div class="card">
            <img src="https://i.pinimg.com/736x/4e/07/31/4e0731cc876ab2e978ad2e821bbc14f5.jpg" alt="Design Sample">
            <h3>Snake</h3>
            <p> 7.2k Views</p>
        </div>

        <div class="card">
            <img src="https://i.pinimg.com/736x/eb/6e/09/eb6e097ff22c9f55471509f97a6ad6c0.jpg" alt="Design Sample">
            <h3>Polar Bear</h3>
            <p>7.2k Views</p>
        </div>
        <!-- Add more cards as needed -->
    </section>
    <center>
        <h3>
    <p>MONISH N</p>
    <br>
    <p>212223240097</p>
    </h3>
    </center>
    <!-- Footer Section -->
    <footer>
        <p>&copy; 2024 Design Portfolio. All rights reserved.</p>
    </footer>

    <script src="scripts.js"></script>
</body>
</html>
```
style.css
```
/* Reset and basic styles */
body, h1, h2, p, a, input, button {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    background-color: #f5f5f5;
    color: #333;
}

/* Top Bar Styling */
.top-bar {
    display: flex;
    align-items: center;
    background-color: #ffffff;
    padding: 10px 20px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
}

.search-bar {
    margin-right: 15px;
    padding: 8px;
    border: 1px solid #ddd;
    border-radius: 4px;
    outline: none;
}

.nav-item {
    margin: 0 10px;
    color: #333;
    text-decoration: none;
}

.blue-text {
    color: #007bff;
    font-weight: bold;
}

.blue-text:hover {
    text-decoration: underline;
}

/* Header Section */
header {
    background-image: url('https://i.pinimg.com/736x/39/36/8f/39368ff17f09c0a77de5971f4b1caef7.jpg'); /* Add your header image */
    background-size: cover;
    padding: 80px 20px;
    text-align: center;
    color: #fff;
}

.header-content h1 {
    font-size: 36px;
    margin-bottom: 10px;
}

.header-content p {
    font-size: 18px;
    margin-bottom: 20px;
}

.search-input {
    padding: 10px;
    width: 60%;
    max-width: 500px;
    border: none;
    border-radius: 4px;
    outline: none;
}

/* Trending Searches Section */
.trending {
    padding: 20px;
    text-align: center;
}

.trending h2 {
    font-size: 24px;
    margin-bottom: 10px;
}

.trending-tags {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
}

.trending-tags span {
    background-color: #007bff;
    color: #fff;
    padding: 5px 10px;
    margin: 5px;
    border-radius: 4px;
    font-size: 14px;
}

/* Gallery Section */
.gallery {
    padding: 20px;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
}

.card {
    background-color: #fff;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
    overflow: hidden;
    width: 200px;
    text-align: center;
}

.card img {
    width: 100%;
    height: auto;
}

.card h3 {
    font-size: 16px;
    margin: 10px 0;
}

.card p {
    font-size: 12px;
    color: #555;
    margin-bottom: 10px;
}

/* Gallery Section */
.gallery {
    padding: 20px;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
}

.card {
    background-color: #fff;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
    overflow: hidden;
    width: 200px;
    text-align: center;
    position: relative;
}

.card img {
    width: 100%;
    height: auto;
    transition: transform 0.3s ease;
}

.card:hover img {
    transform: scale(1.2); /* Scale image to 120% on hover */
}

.card h3 {
    font-size: 16px;
    margin: 10px 0;
}

.card p {
    font-size: 12px;
    color: #555;
    margin-bottom: 10px;
}

/* Footer Section */
footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px 20px;
    margin-top: 20px;
}
```
scripts.js
```
// Search functionality
const searchBar = document.querySelector('.search-bar');

searchBar.addEventListener('keydown', function(event) {
    if (event.key === 'Enter') {
        event.preventDefault(); // Prevent default form submission
        alert(`Searching for: ${searchBar.value}`);
    }
});
```
## OUTPUT:
![alt text](<Screenshot (241).png>)
![alt text](<Screenshot (242).png>)
## RESULT:
The Project for responsive web design using Bootstrap is completed successfully.
