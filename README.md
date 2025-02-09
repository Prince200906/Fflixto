<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fflix - Free Movies & TV Shows</title>
    <style>
        /* Global Styles */
        body {
            font-family: Arial, sans-serif;
            background-color: #121212;
            color: white;
            margin: 0;
            padding: 0;
            text-align: center;
        }

        /* Header */
        .header {
            background-color: black;
            padding: 15px;
            text-align: center;
        }

        .header h1 {
            font-size: 32px;
            font-weight: bold;
        }

        .header span {
            color: red;
        }

        /* Hero Section */
        .hero {
            padding: 40px 20px;
        }

        .hero h2 {
            font-size: 28px;
            font-weight: bold;
        }

        .hero p {
            max-width: 600px;
            margin: 10px auto;
            font-size: 16px;
            color: #cccccc;
        }

        .btn {
            background-color: red;
            color: white;
            padding: 12px 24px;
            border: none;
            border-radius: 5px;
            font-size: 18px;
            cursor: pointer;
            margin-top: 20px;
        }

        /* Movie Gallery */
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 15px;
            padding: 20px;
            max-width: 900px;
            margin: auto;
        }

        .gallery img {
            width: 100%;
            border-radius: 8px;
            transition: transform 0.3s;
        }

        .gallery img:hover {
            transform: scale(1.05);
        }

        /* Responsive */
        @media (max-width: 600px) {
            .hero h2 {
                font-size: 24px;
            }
            .gallery {
                grid-template-columns: repeat(auto-fit, minmax(100px, 1fr));
            }
        }
    </style>
</head>
<body>

    <!-- Header -->
    <div class="header">
        <h1><span>Fflix</span> - Watch Free Movies</h1>
    </div>

    <!-- Hero Section -->
    <div class="hero">
        <h2>Stream Unlimited Movies & TV Shows for Free</h2>
        <p>Enjoy the latest Hollywood hits and classic favorites with no sign-ups or subscriptions.</p>
        <button class="btn">View Full Site</button>
    </div>

    <!-- Movie Gallery -->
    <div class="gallery">
        <img src="https://via.placeholder.com/150x220?text=Movie+1" alt="Movie 1">
        <img src="https://via.placeholder.com/150x220?text=Movie+2" alt="Movie 2">
        <img src="https://via.placeholder.com/150x220?text=Movie+3" alt="Movie 3">
        <img src="https://via.placeholder.com/150x220?text=Movie+4" alt="Movie 4">
        <img src="https://via.placeholder.com/150x220?text=Movie+5" alt="Movie 5">
        <img src="https://via.placeholder.com/150x220?text=Movie+6" alt="Movie 6">
    </div>

</body>
</html>
