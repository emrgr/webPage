<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Demo Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
            text-align: center;
        }
        header {
            background-color: #6200ea;
            color: white;
            padding: 20px 0;
        }
        main {
            padding: 20px;
        }
        video {
            max-width: 100%;
            height: auto;
            margin: 20px 0;
        }
        img {
            max-width: 100%;
            height: auto;
            margin: 20px 0;
            border: 2px solid #ddd;
            border-radius: 8px;
        }
        footer {
            background-color: #333;
            color: white;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to the Demo Page</h1>
    </header>
    <main>
        <h2>Video Demonstration</h2>
        <video controls>
            <source src="video-demo.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>

        <h2>Photo Gallery</h2>
        <img src="photo1.jpg" alt="Demo Photo 1">
        <img src="photo2.jpg" alt="Demo Photo 2">
    </main>
    <footer>
        <p>&copy; 2025 Demo Webpage. All rights reserved.</p>
    </footer>
</body>
</html>
