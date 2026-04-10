# doc
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Damro Furniture</title>

<style>
    body {
        margin: 0;
        font-family: Arial, sans-serif;
        background-color: #f5f9ff;
    }

    header {
        background: #0a3d91;
        color: white;
        padding: 15px 40px;
        display: flex;
        justify-content: space-between;
        align-items: center;
    }

    header h1 {
        margin: 0;
    }

    nav a {
        color: white;
        margin-left: 20px;
        text-decoration: none;
        font-weight: bold;
    }

    .hero {
        background: url('https://images.unsplash.com/photo-1586023492125-27b2c045efd7') no-repeat center/cover;
        height: 400px;
        display: flex;
        align-items: center;
        justify-content: center;
        color: white;
        text-align: center;
    }

    .hero h2 {
        font-size: 50px;
        background: rgba(0,0,0,0.6);
        padding: 20px;
        border-radius: 10px;
    }

    .section {
        padding: 40px;
    }

    .section h2 {
        text-align: center;
        color: #0a3d91;
    }

    .products {
        display: grid;
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
        gap: 20px;
        margin-top: 30px;
    }

    .card {
        background: white;
        border-radius: 10px;
        overflow: hidden;
        box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        transition: 0.3s;
    }

    .card:hover {
        transform: scale(1.05);
    }

    .card img {
        width: 100%;
        height: 200px;
        object-fit: cover;
    }

    .card h3 {
        margin: 10px;
        color: #0a3d91;
    }

    .card p {
        margin: 10px;
    }

    footer {
        background: #0a3d91;
        color: white;
        text-align: center;
        padding: 20px;
        margin-top: 40px;
    }
</style>
</head>

<body>

<header>
    <h1>Damro Furniture</h1>
    <nav>
        <a href="#">Home</a>
        <a href="#">Sofas</a>
        <a href="#">Beds</a>
        <a href="#">Dining</a>
    </nav>
</header>

<div class="hero">
    <h2>🔥 FLAT 30% OFF ON ALL FURNITURE 🔥</h2>
</div>

<div class="section">
    <h2>Sofas</h2>
    <div class="products">
        <div class="card">
            <img src="https://images.unsplash.com/photo-1555041469-a586c61ea9bc">
            <h3>Modern Sofa</h3>
            <p>Comfortable 3-seater sofa</p>
        </div>
        <div class="card">
            <img src="https://images.unsplash.com/photo-1582582429416-88f1a1a8f7b0">
            <h3>Luxury Sofa</h3>
            <p>Premium fabric sofa</p>
        </div>
    </div>
</div>

<div class="section">
    <h2>Beds</h2>
    <div class="products">
        <div class="card">
            <img src="https://images.unsplash.com/photo-1505693416388-ac5ce068fe85">
            <h3>King Size Bed</h3>
            <p>Spacious and stylish</p>
        </div>
        <div class="card">
            <img src="https://images.unsplash.com/photo-1616594039964-ae9021a400a0">
            <h3>Wooden Bed</h3>
            <p>Classic wooden finish</p>
        </div>
    </div>
</div>

<div class="section">
    <h2>Dining Tables</h2>
    <div class="products">
        <div class="card">
            <img src="https://images.unsplash.com/photo-1600585154340-be6161a56a0c">
            <h3>Dining Set</h3>
            <p>6-seater dining table</p>
        </div>
        <div class="card">
            <img src="https://images.unsplash.com/photo-1595526114035-0d45ed16cfbf">
            <h3>Modern Dining</h3>
            <p>Minimalist design</p>
        </div>
    </div>
</div>

<footer>
    <p>© 2026 Damro Furniture | All Rights Reserved</p>
</footer>

</body>
</html>
