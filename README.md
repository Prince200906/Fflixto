Fflix - Free HD movies
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fflix - Watch Free Movies & TV Shows</title>
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

        /* Section Styling */
        .section {
            padding: 30px 20px;
            max-width: 900px;
            margin: auto;
            text-align: left;
        }

        .section h2 {
            font-size: 26px;
            font-weight: bold;
        }

        .section p {
            font-size: 16px;
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
    <div class="header">
        <h1><span>Fflix</span> - Watch Free Movies & TV Shows</h1>
    </div>

    <!-- About Section -->
    <div class="section">
        <h2>What Is Fflix?</h2>
        <p>
            Fflix is a free online streaming platform offering an extensive selection of movies and TV shows across various genres. 
            Designed for viewers who value 
            convenience and quality, Fflix allows users to enjoy the latest Hollywood hits and beloved classics
            without the need for sign-ups or subscriptions.
        </p>
        <p>
            With a user-friendly interface, high-quality streaming, and a constantly updated content library, 
            Fflix is your go-to destination for non-stop entertainment. Whether you're in the mood for a blockbuster, a hidden gem,
            or a binge-worthy series, Fflix delivers an immersive viewing experience tailored to your preferences.

    <!-- Movie Collection Section -->
    <div class="section">
        <h2>Watch Fflix Movies Free Online HD</h2>
        <p class="italic">Extensive HD Movie Library</p>
        <p>
            Fflix provides a vast collection of high-definition movies across all genres, from thrilling blockbusters to heartwarming dramas. 
            Whether you’re in the mood for a recent release or a timeless classic, Fflix offers a diverse range of options, all available in stunning HD quality.
        </p>
    </div>

          <h2>Latest Movies</h2>
    <div class="gallery">
        <img
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Latest Movies</title>
    <style>
        /* Basic styles for the page */
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
        }

        #movies-container {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            padding: 20px;
            justify-content: center;
        }

        .movie-card {
            background-color: white;
            border-radius: 8px;
            width: 250px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            transition: transform 0.3s ease;
        }

        .movie-card:hover {
            transform: scale(1.05);
        }

        .movie-card img {
            width: 100%;
            height: 350px;
            object-fit: cover;
        }

        .movie-card .movie-info {
            padding: 15px;
        }

        .movie-card .movie-info h3 {
            font-size: 18px;
            margin: 0;
            color: #333;
        }

        .movie-card .movie-info p {
            font-size: 14px;
            color: #555;
            margin-top: 8px;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: absolute;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>

<body>

    <header>
        <h1>Latest Movies</h1>
    </header>

    <div id="movies-container">
        <!-- Movies will be displayed here dynamically -->
    </div>

    <footer>
        <p>&copy; 2025 Movie Project | <a href="https://www.themoviedb.org/" target="_blank" style="color: white;">Powered by TMDb</a></p>
    </footer>

    <script>
        // Replace with your own TMDb API key
        const apiKey = 'YOUR_TMDB_API_KEY';  
        const apiUrl = `https://api.themoviedb.org/3/movie/popular?api_key=${apiKey}&language=en-US&page=1`;

        async function fetchLatestMovies() {
            try {
                const response = await fetch(apiUrl);
                const data = await response.json();

                if (data.results) {
                    displayMovies(data.results);
                } else {
                    alert('No movies found.');
                }
            } catch (error) {
                console.error('Error fetching movies:', error);
                alert('An error occurred while fetching movies.');
            }
        }

        function displayMovies(movies) {
            const container = document.getElementById('movies-container');
            container.innerHTML = '';  // Clear any existing content

            movies.forEach(movie => {
                const movieCard = document.createElement('div');
                movieCard.classList.add('movie-card');

                const movieImage = movie.poster_path 
                    ? `https://image.tmdb.org/t/p/w500${movie.poster_path}`
                    : 'https://via.placeholder.com/500x750.png?text=No+Image+Available';  // Fallback if no image

                movieCard.innerHTML = `
                    <img src="${movieImage}" alt="${movie.title}">
                    <div class="movie-info">
                        <h3>${movie.title}</h3>
                        <p>${movie.release_date}</p>
                    </div>
                `;

                container.appendChild(movieCard);
            });
        }

        // Initialize the fetch when the page loads
        window.onload = fetchLatestMovies;
    </script>

PRINCE CELMAR 10-SR
