# Portfolioindex.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Ramzi Tabit - Portfolio</title>
    <link rel="stylesheet" href="css/styles.css" />
    <!-- Google Fonts for a clean look -->
    <link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet" />
</head>
<body>
    <!-- Header / Navigation -->
    <header>
        <h1>Ramzi Tabit</h1>
        <nav>
            <ul>
                <li><a href="#about">About Me</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#soccer">Soccer & Tech</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Main Content -->
    <main>
        <!-- About Section -->
        <section id="about" class="section">
            <h2>About Me</h2>
            <p>Hello! I'm Ramzi, passionate about soccer and technology. I love creating web projects and staying active on the field. Welcome to my portfolio!</p>
        </section>

        <!-- Projects Section -->
        <section id="projects" class="section">
            <h2>My Projects</h2>
            <div class="project-grid">
                <!-- Example Project Card -->
                <div class="card">
                    <h3>Weather App</h3>
                    <p>A responsive weather app using Web APIs to show current weather data.</p>
                    <a href="#" target="_blank">View Project</a>
                </div>
                <!-- Add more project cards as needed -->
                <div class="card">
                    <h3>Soccer Stats Dashboard</h3>
                    <p>Live stats and scores from soccer matches using external APIs.</p>
                    <a href="#" target="_blank">View Project</a>
                </div>
            </div>
        </section>

        <!-- Soccer & Tech Interests -->
        <section id="soccer" class="section">
            <h2>Soccer & Tech</h2>
            <p>I enjoy playing soccer and following professional leagues. I also love exploring new technologies and building web applications to combine my passions.</p>
            <button id="more-info-btn">Click for Fun Fact!</button>
            <p id="fun-fact" style="display:none;">Did you know? The first soccer World Cup was held in 1930 in Uruguay!</p>
        </section>

        <!-- Contact -->
        <section id="contact" class="section">
            <h2>Contact Me</h2>
            <p>You can reach me via email at <a href="mailto:ramzi@example.com">ramzi@example.com</a></p>
        </section>
    </main>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Ramzi Tabit</p>
    </footer>

    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <script src="js/scripts.js"></script>

    <!-- Existing code above -->

<!-- Weather Section -->
<section id="weather" class="section">
  <h2>Current Weather</h2>
  <button id="get-weather">Get Weather</button>
  <div id="weather-info"></div>
</section>

<!-- Soccer Scores Section -->
<section id="live-scores" class="section">
  <h2>Live Soccer Scores</h2>
  <div id="soccer-scores">Click "Get Scores" to load live scores.</div>
</section>

<!-- GitHub Repos Section -->
<section id="github" class="section">
  <h2>My GitHub Repositories</h2>
  <div id="github-repos">Loading repositories...</div>
</section>

<!-- Existing code below -->

</body>
</html>
