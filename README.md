# Minx
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Local Artisanal Market</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        header {
            background-color: #ff6f61;
            color: white;
            padding: 20px;
            text-align: center;
        }

        .container {
            padding: 20px;
        }

        .featured-artisans {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }

        .artisan-card {
            background-color: #f4f4f4;
            border: 1px solid #ddd;
            border-radius: 8px;
            overflow: hidden;
            width: 300px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }

        .artisan-card img {
            width: 100%;
            height: auto;
        }

        .artisan-card .content {
            padding: 15px;
        }

        .artisan-card h3 {
            margin-top: 0;
        }

        footer {
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
    <header>
        <h1>Local Artisanal Market</h1>
        <p>Connecting you with unique, handmade products from Filipino artisans</p>
    </header>
    
    <div class="container">
        <h2>Featured Artisans</h2>
        <div class="featured-artisans">
            <div class="artisan-card">
                <img src="artisan1.jpg" alt="Artisan 1">
                <div class="content">
                    <h3>Artisan Name 1</h3>
                    <p>Brief description about Artisan 1 and their craft.</p>
                </div>
            </div>
            <div class="artisan-card">
                <img src="artisan2.jpg" alt="Artisan 2">
                <div class="content">
                    <h3>Artisan Name 2</h3>
                    <p>Brief description about Artisan 2 and their craft.</p>
                </div>
            </div>
            <!-- Add more artisan cards as needed -->
        </div>
    </div>

    <footer>
        <p>&copy; 2024 Local Artisanal Market. All rights reserved.</p>
    </footer>
</body>
</html>
