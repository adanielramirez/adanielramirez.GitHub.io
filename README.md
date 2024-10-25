# adanielramirez.GitHub.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Spin-off of "Project: Travel webpage"</title>
    <style>
        /* Basic Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #f0f8ff;
            color: #333;
        }

        /* Header Styling */
        header {
            background-color: #007bff;
            color: #fff;
            text-align: center;
            padding: 1.5rem 0;
        }

        header h1 {
            font-size: 2.5rem;
        }

        /* Main Content */
        .content {
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 2rem;
        }

        /* Attractions Section */
        .attractions {
            margin-top: 2rem;
        }

        .attractions h2 {
            font-size: 2rem;
            margin-bottom: 1rem;
        }

        .attractions ul {
            list-style-type: none;
            font-size: 1.1rem;
        }

        .attractions ul li {
            padding: 0.5rem 0;
        }

        /* Image Styling */
        .attractions img {
            width: 100%;
            max-width: 500px;
            border-radius: 10px;
            transition: transform 0.3s;
        }

        /* Hover Effect */
        .attractions img:hover {
            transform: scale(1.05);
        }

        /* Paragraph Styling */
        .description {
            max-width: 600px;
            text-align: center;
            margin-top: 1rem;
            line-height: 1.6;
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to Mazatlán!</h1>
    <p>Your Ultimate Travel Guide</p>
</header>

<div class="content">
    <div class="attractions">
        <h2>Top Attractions</h2>
        <ul>
            <li>El Faro Lighthouse - Breathtaking views await at one of the highest lighthouses in the Americas.</li>
            <li>Historic Old Town - Explore charming architecture, cultural spots, and art galleries.</li>
            <li>Playa Olas Altas - A beautiful beach perfect for surfers and sun-seekers.</li>
            <li>Malecon Boardwalk - Scenic ocean views and the perfect place to watch the sunset.</li>
        </ul>
    </div>

    <div class="description">
        <p>Discover the magic of Mazatlán, a coastal city rich in culture, scenic beauty, and exciting attractions. Whether you're looking to explore the vibrant Old Town, take a scenic walk along the Malecon, or relax on golden beaches, Mazatlán has something for every traveler!</p>
    </div>

    <!-- Sample Image (Replace the URL with actual image links) -->
    <div class="attractions">
        <img src="https://cdn.kastatic.org/third_party/javascript-khansrc/live-editor/build/images/creatures/Hopper-Cool.png" alt="Mazatlán Malecon">
        <p>Mazatlán Malecon</p>
    </div>
</div>

</body>
</html>
