<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Delicious Pizza</title>
    <style>
        /* General Styling */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-color: #f8f8f8;
        }
        .header {
            background-color: #ff5733;
            color: white;
            padding: 20px;
            font-size: 24px;
            font-weight: bold;
        }
        /* Hero Section */
        .hero {
            background-image: url('https://images.pexels.com/photos/825661/pexels-photo-825661.jpeg');
            background-size: cover;
            background-position: center;
            height: 300px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-size: 36px;
            font-weight: bold;
            text-shadow: 2px 2px 5px black;
            animation: fadeIn 2s ease-in-out;
        }
        /* Menu Section */
        .menu {
            margin: 20px;
            padding: 20px;
            background-color: #fff3e0;
            border-radius: 10px;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.2);
            display: inline-block;
            animation: slideUp 1s ease-in-out;
        }
        .menu h2 {
            color: #d35400;
        }
        /* Menu Item Boxes */
        .menu-item {
            background-color: white;
            padding: 15px;
            border-radius: 10px;
            margin: 15px;
            display: inline-block;
            width: 250px;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            cursor: pointer;
        }
        .menu-item img {
            width: 100%;
            height: 200px;
            border-radius: 10px;
            transition: transform 0.3s ease;
        }
        /* Hover Effects */
        .menu-item:hover {
            transform: scale(1.1);
            box-shadow: 0px 8px 15px rgba(0, 0, 0, 0.3);
        }
        .menu-item:hover img {
            transform: scale(1.05);
        }
        /* Contact Section */
        .contact {
            background-color: #333;
            color: white;
            padding: 20px;
            margin-top: 20px;
        }
        /* Button Styling */
        .btn {
            background-color: #ff5733;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            font-size: 18px;
            cursor: pointer;
            transition: background-color 0.3s ease, transform 0.2s ease;
        }
        .btn:hover {
            background-color: #d84315;
            transform: scale(1.1);
        }
        /* Animations */
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        @keyframes slideUp {
            from { transform: translateY(50px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }
    </style>
</head>
<body>

    <div class="header">🍕 Welcome to Delicious Pizza 🍕</div>

    <div class="hero">Best Pizza in Town!</div>

    <div class="menu">
        <h2>Our Menu</h2>
        <div class="menu-item">
            <img src="https://images.pexels.com/photos/825661/pexels-photo-825661.jpeg" alt="Cheese Pizza">
            <p>Cheese Pizza - $10</p>
            <button class="btn">Order Now</button>
        </div>
        <div class="menu-item">
            <img src="https://images.pexels.com/photos/1566837/pexels-photo-1566837.jpeg" alt="Pepperoni Pizza">
            <p>Pepperoni Pizza - $12</p>
            <button class="btn">Order Now</button>
        </div>
        <div class="menu-item">
            <img src="https://images.pexels.com/photos/708587/pexels-photo-708587.jpeg" alt="Veggie Pizza">
            <p>Veggie Pizza - $11</p>
            <button class="btn">Order Now</button>
        </div>
    </div>

    <div class="contact">
        <h2>Contact Us</h2>
        <p>📍 123 Pizza Street, San Jose, CA</p>
        <p>📞 (123) 456-7890</p>
        <p>📧 info@deliciouspizza.com</p>
    </div>

</body>
</html>
