```html
<!DOCTYPE html>
<html>
<head>
    <title>Image Gallery</title>
    <style>
        body {
            font-family: Arial;
            background: #f1f5f9;
            padding: 20px;
        }

        h1 {
            text-align: center;
        }

        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 15px;
        }

        .gallery img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-radius: 10px;
        }
    </style>
</head>
<body>
    <h1>My Photo Gallery</h1>

    <div class="gallery">
        <img src="https://picsum.photos/id/10/400/300" alt="Nature">
        <img src="https://picsum.photos/id/20/400/300" alt="Laptop">
        <img src="https://picsum.photos/id/30/400/300" alt="Mountains">
        <img src="https://picsum.photos/id/40/400/300" alt="Sea">
        <img src="https://picsum.photos/id/50/400/300" alt="Forest">
        <img src="https://picsum.photos/id/60/400/300" alt="Flowers">
        <img src="https://picsum.photos/id/70/400/300" alt="Travel">
        <img src="https://picsum.photos/id/80/400/300" alt="City">
    </div>
</body>
</html>
```