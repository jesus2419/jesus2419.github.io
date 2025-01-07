# jesus2419.github.io

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #121212;
            color: #ffffff;
        }

        header {
            padding: 20px;
            text-align: center;
            background-color: #1e1e1e;
        }

        header h1 {
            font-size: 2rem;
            margin: 0;
        }

        header p {
            font-size: 1rem;
            margin: 10px 0;
        }

        header button {
            padding: 10px 20px;
            font-size: 1rem;
            border: none;
            border-radius: 5px;
            background-color: #6a5acd;
            color: white;
            cursor: pointer;
        }

        .section {
            padding: 40px 20px;
            max-width: 1200px;
            margin: 0 auto;
        }

        .recent-posts, .featured-works {
            margin-top: 20px;
        }

        .recent-posts h2, .featured-works h2 {
            font-size: 1.5rem;
            margin-bottom: 20px;
        }

        .post-card, .work-card {
            background-color: #292929;
            padding: 20px;
            border-radius: 8px;
            margin-bottom: 20px;
        }

        .post-card h3, .work-card h3 {
            font-size: 1.2rem;
            margin-bottom: 10px;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #1e1e1e;
            margin-top: 40px;
        }

        footer a {
            margin: 0 10px;
            color: white;
            text-decoration: none;
        }

        footer p {
            font-size: 0.9rem;
            margin-top: 10px;
        }

        .card-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Hi, I am Jesus Osorio Galvez, Full Stack Developer</h1>
        <p>In this web page you will see my work experience</p>
        <button>Download Resume</button>
    </header>

    <div class="section recent-posts">
        <h2>Recent Posts</h2>
        <div class="card-grid">
            <div class="post-card">
                <h3>Making a design system from scratch</h3>
                <p>12 Feb 2020 | Design, Pattern</p>
                <p>Short description about the post goes here...</p>
            </div>
            <div class="post-card">
                <h3>Creating pixel perfect icons in Figma</h3>
                <p>12 Feb 2020 | Figma, Icon Design</p>
                <p>Short description about the post goes here...</p>
            </div>
        </div>
    </div>

    <div class="section featured-works">
        <h2>Featured Works</h2>
        <div class="card-grid">
            <div class="work-card">
                <h3>Designing Dashboards</h3>
                <p>2020 | Dashboard</p>
                <p>Brief description of the work goes here...</p>
            </div>
            <div class="work-card">
                <h3>Vibrant Portraits of 2020</h3>
                <p>2020 | Illustration</p>
                <p>Brief description of the work goes here...</p>
            </div>
            <div class="work-card">
                <h3>36 Days of Malayalam type</h3>
                <p>2020 | Typography</p>
                <p>Brief description of the work goes here...</p>
            </div>
        </div>
    </div>

    <footer>
        <a href="#">Facebook</a>
        <a href="#">Twitter</a>
        <a href="#">Instagram</a>
        <p>&copy; 2025 All rights reserved</p>
    </footer>
</body>
</html>
