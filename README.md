<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Video Links</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }

        .video-container {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
            gap: 20px;
        }

        .video-item {
            position: relative;
            padding-bottom: 56.25%; /* 16:9 aspect ratio */
            overflow: hidden;
            border: 1px solid #ddd;
            border-radius: 8px;
            box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
        }

        .video-item iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
        }
    </style>
</head>
<body>
    <h1>Video Links</h1>

    <div class="video-container">
        <!-- Replace the src attribute with your video links -->
        <div class="video-item">
            <iframe src="https://www.youtube.com/embed/VIDEO_ID1" frameborder="0" allowfullscreen></iframe>
        </div>

        <div class="video-item">
            <iframe src="https://www.youtube.com/embed/VIDEO_ID2" frameborder="0" allowfullscreen></iframe>
        </div>

        <!-- Add more video items as needed -->
    </div>
</body>
</html>
