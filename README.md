<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Clan Webpage</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #e0f7fa;
            color: #01579b;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #0277bd;
            color: white;
            text-align: center;
            padding: 1em 0;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #0288d1;
            padding: 1em 0;
        }
        nav a {
            margin: 0 1em;
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        section {
            padding: 2em;
            max-width: 900px;
            margin: auto;
        }
        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .container div {
            margin: 1em;
            padding: 1em;
            background-color: #e1f5fe;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            flex: 1 1 300px;
            max-width: 45%;
        }
        footer {
            background-color: #0277bd;
            color: white;
            text-align: center;
            padding: 1em 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to Our Efootball Clan</h1>
    <img src="clan_logo.png" alt="Clan Logo" width="150">
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#about">About Clan</a>
    <a href="#history">History</a>
    <a href="#teams">Teams</a>
    <a href="#captains">Captains</a>
    <a href="#players">Players</a>
    <a href="#achievements">Achievements</a>
    <a href="#founders">Founders</a>
    <a href="#contact">Contact</a>
</nav>

<section id="home">
    <h2>Home</h2>
    <p>Welcome to the official webpage of our Efootball Clan. Here, you will find information about our history, teams, captains, players, achievements, and founders.</p>
</section>

<section id="about">
    <h2>About Clan</h2>
    <p>Learn more about our clan's mission, values, and what makes us a unique and powerful team in the world of Efootball.</p>
</section>

<section id="history">
    <h2>History of Clan</h2>
    <p>Discover the origins of our clan, our journey through various tournaments, and how we have evolved over the years.</p>
</section>

<section id="teams">
    <h2>Teams in Clan</h2>
    <div class="container">
        <div>
            <h3>Team A</h3>
            <p>Details about Team A.</p>
        </div>
        <div>
            <h3>Team B</h3>
            <p>Details about Team B.</p>
        </div>
        <!-- Add more teams as needed -->
    </div>
</section>

<section id="captains">
    <h2>Captains of Clan</h2>
    <div class="container">
        <div>
            <h3>Captain 1</h3>
            <p>Bio and achievements of Captain 1.</p>
        </div>
        <div>
            <h3>Captain 2</h3>
            <p>Bio and achievements of Captain 2.</p>
        </div>
        <!-- Add more captains as needed -->
    </div>
</section>

<section id="players">
    <h2>Players of Clan</h2>
    <div class="container">
        <div>
            <h3>Player 1</h3>
            <p>Bio and achievements of Player 1.</p>
        </div>
        <div>
            <h3>Player 2</h3>
            <p>Bio and achievements of Player 2.</p>
        </div>
        <!-- Add more players as needed -->
    </div>
</section>

<section id="achievements">
    <h2>Achievements</h2>
    <p>Our clan's major achievements, awards, and milestones.</p>
</section>

<section id="founders">
    <h2>Founders</h2>
    <p>Information about the founding members of the clan and their vision.</p>
</section>

<section id="contact">
    <h2>Contact Information</h2>
    <p>Follow us on Instagram: <a href="https://www.instagram.com/Believe_in_tomboy" target="_blank">@Believe_in_tomboy</a></p>
</section>

<footer>
    <p>&copy; 2024 Efootball Clan. All rights reserved.</p>
</footer>

</body>
</html>
