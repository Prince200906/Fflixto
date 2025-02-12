Fflix - Enjoy free HD movies
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fflix - Watch Free Movies & TV Shows now </title>
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
            font-size: 30px;
            font-weight: bold;
        }
         .header span {
            color: red;
        }
         /* Section Styling */
        .section {
            padding: 30px 20px;
            max-width: 950px;
            margin: auto;
            text-align: left;
        }
            .section h2 {
            font-size: 24px;
            font-weight: bold;
        }
          .section p {
            font-size: 14px;
            line-height: 1.6;
            color: #cccccc;
        }
           .italic {
            font-style: italic;
            font-weight: bold;
            color: lightgray;
        }

        /* Movie Image */
        .hero-image {
            width: 100%;
            max-width: 900px;
            border-radius: 8px;
            margin-top: 15px;
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
            .section h2 {
                font-size: 22px;
            }
            .gallery {
                grid-template-columns: repeat(auto-fit, minmax(100px, 1fr));
            }
        }
        </style>
        </head>
        <body>
        <!-- Header -->
        <div class="header"> <h1><span>Fflix</span> - Watch Free Movies & TV Shows now </h1>
    </div> 
    <!-- About Section -->
    <div class="section">
        <h2>What Is Fflix?</h2>
 Fflix is a free online streaming platform offering an extensive selection of movies and TV shows across various genres. Designed for viewers who value convenience and quality, without the need for sign-ups or subscriptions.
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Movie Posters</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #222;
            color: white;
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 10px;
            margin-top: 15px;
        }
        .movie {
            width: 135px;
        }
        .movie img {
            width: 50%;
            border-radius: 8px;
        }
        .movie-title {
            margin-top: 10px;
            font-size: 14px;
        }
    </style>
</head>
<body>
    <h1>Movie Gallery</h1>
    <div class="gallery" id="movieGallery"></div>
        <script>
        const movies = [
            { title: "The Matrix", img: "https://image.tmdb.org/t/p/w500/f89U3ADr1oiB1s9GkdPOEpXUk5H.jpg" }, // Replacing Inception
             { title: "Interstellar", img: "https://image.tmdb.org/t/p/w500/gEU2QniE6E77NI6lCU6MxlNBvIx.jpg" }, // Fixed Interstellar
            { title: "The Dark Knight", img: "https://image.tmdb.org/t/p/w500/qJ2tW6WMUDux911r6m7haRef0WH.jpg" },
        ];

        const gallery = document.getElementById("movieGallery");

        movies.forEach(movie => {
            const movieDiv = document.createElement("div");
            movieDiv.classList.add("movie");

            const img = document.createElement("img");
            img.src = movie.img;
            img.alt = movie.title;

            const title = document.createElement("div");
            title.classList.add("movie-title");
            title.textContent = movie.title;

            movieDiv.appendChild(img);
            movieDiv.appendChild(title);
            gallery.appendChild(movieDiv);
        });
    </script>
</body>
</html>
