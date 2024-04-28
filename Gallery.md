<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Photo Gallery</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-image: url(''); /* Replace 'background.jpg' with your image file */
            background-size: cover;
            background-position: center;
            color: white; /* Change text color if necessary */
        }
        .container {
            width: 90%;
            margin: 50px auto;
            padding: 20px;
            background-color: rgba(0, 0, 0, 0.5); /* Adjust transparency as needed */
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(255, 255, 255, 0.3); /* Add shadow effect */
            position: relative;
            overflow: hidden;
        }
        h1, h2, h3, h4, h5, h6 {
            text-align: center;
            margin-top: 20px;
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            margin-top: 20px;
        }
        .gallery img {
            width: 200px; /* Adjust image size as needed */
            margin: 10px; /* Adjust margin between images */
            border-radius: 5px; /* Add rounded corners to images */
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Photo Gallery</h1>
        <div class="gallery">
            <!-- Replace 'image1.jpg', 'image2.jpg', 'image3.jpg', and 'image4.jpg' with your image file names -->
            <img src="image1.jpg" alt="Image 1">
            <img src="image2.jpg" alt="Image 2">
            <img src="image3.jpg" alt="Image 3">
            <img src="image4.jpg" alt="Image 4">
            <!-- Add more image tags for additional images -->
        </div>
    </div>
</body>
</html>
