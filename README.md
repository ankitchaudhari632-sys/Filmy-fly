# Filmy-fly
Movie platform for new movies download 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>[Movie Title] - Official Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>[Movie Title]</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#cast">Cast</a></li>
                <li><a href="#trailer">Trailer</a></li>
                <li><a href="#reviews">Reviews</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="hero">
        <img src="poster.jpg" alt="[Movie Title] Poster" class="poster">
        <div class="hero-text">
            <h2>Release Date: [Date]</h2>
            <p>[Short tagline or synopsis]</p>
            <button id="watch-trailer">Watch Trailer</button>
        </div>
    </section>
    
    <section id="about">
        <h2>About the Movie</h2>
        <p>[Full synopsis here. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.]</p>
    </section>
    
    <section id="cast">
        <h2>Cast</h2>
        <div class="cast-list">
            <div class="actor">
                <img src="actor1.jpg" alt="Actor 1">
                <p>[Actor 1 Name] as [Character]</p>
            </div>
            <!-- Add more actors -->
        </div>
    </section>
    
    <section id="trailer">
        <h2>Trailer</h2>
        <div id="trailer-container">
            <iframe id="trailer-video" width="560" height="315" src="https://www.youtube.com/embed/[YouTube Video ID]" frameborder="0" allowfullscreen style="display:none;"></iframe>
        </div>
    </section>
    
    <section id="reviews">
        <h2>Reviews</h2>
        <div class="review">
            <p>"[Quote from review]."</p>
            <cite>- [Reviewer Name]</cite>
        </div>
        <!-- Add more reviews -->
    </section>
    
    <footer>
        <p>&copy; 2023 [Movie Title]. All rights reserved.</p>
    </footer>
    
    <script src="script.js"></script>
</body>
</html>
