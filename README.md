<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gaming Forum</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #121212;
            color: #e0e0e0;
        }

        header {
            background-color: #1f1f1f;
            padding: 20px;
            text-align: center;
            border-bottom: 2px solid #333;
        }

        header h1 {
            color: #ffffff;
            margin: 0;
        }

        nav {
            display: flex;
            justify-content: center;
            gap: 20px;
            padding: 10px 0;
            background-color: #1a1a1a;
            border-bottom: 1px solid #333;
        }

        nav a {
            text-decoration: none;
            color: #e0e0e0;
            font-weight: bold;
            transition: color 0.3s ease;
        }

        nav a:hover {
            color: #00bcd4;
        }

        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
            background-color: #1f1f1f;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
        }

        .category {
            margin-bottom: 20px;
        }

        .category h2 {
            margin-bottom: 10px;
            color: #00bcd4;
        }

        .thread {
            padding: 15px;
            border: 1px solid #333;
            border-radius: 5px;
            margin-bottom: 10px;
            background-color: #292929;
        }

        .thread a {
            text-decoration: none;
            color: #e0e0e0;
            font-size: 1.1em;
            font-weight: bold;
        }

        .thread a:hover {
            color: #00bcd4;
        }

        .discussion {
            margin-bottom: 20px;
        }

        .discussion h2 {
            color: #00bcd4;
            margin-bottom: 15px;
        }

        .discussion .comment {
            padding: 10px;
            border: 1px solid #333;
            border-radius: 5px;
            margin-bottom: 10px;
            background-color: #292929;
        }

        .discussion .comment p {
            margin: 0;
        }

        footer {
            text-align: center;
            padding: 10px;
            background-color: #1a1a1a;
            border-top: 1px solid #333;
            color: #757575;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Gaming Forum</h1>
    </header>

    <nav>
        <a href="#">Home</a>
        <a href="#">Categories</a>
        <a href="#">Login</a>
        <a href="#">Register</a>
        <a href="discussion.html">Discussion</a>
    </nav>

    <div class="container">
        <div class="category">
            <h2>General Discussion</h2>
            <div class="thread">
                <a href="#">Welcome to the Forum!</a>
                <p>by Admin - 5 replies</p>
            </div>
            <div class="thread">
                <a href="#">What's your favorite game?</a>
                <p>by Gamer123 - 20 replies</p>
            </div>
        </div>

        <div class="category">
            <h2>Game Reviews</h2>
            <div class="thread">
                <a href="#">Cyberpunk 2077: Thoughts?</a>
                <p>by ReviewerX - 10 replies</p>
            </div>
            <div class="thread">
                <a href="#">Best indie games of 2023</a>
                <p>by IndieFan - 15 replies</p>
            </div>
        </div>
    </div>

    <footer>
        <p>&copy; 2025 Gaming Forum. All rights reserved.</p>
    </footer>
</body>
</html>

<!-- discussion.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Discussion</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #121212;
            color: #e0e0e0;
        }

        header {
            background-color: #1f1f1f;
            padding: 20px;
            text-align: center;
            border-bottom: 2px solid #333;
        }

        header h1 {
            color: #ffffff;
            margin: 0;
        }

        nav {
            display: flex;
            justify-content: center;
            gap: 20px;
            padding: 10px 0;
            background-color: #1a1a1a;
            border-bottom: 1px solid #333;
        }

        nav a {
            text-decoration: none;
            color: #e0e0e0;
            font-weight: bold;
            transition: color 0.3s ease;
        }

        nav a:hover {
            color: #00bcd4;
        }

        .container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background-color: #1f1f1f;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
        }

        .discussion {
            margin-bottom: 20px;
        }

        .discussion h2 {
            color: #00bcd4;
            margin-bottom: 15px;
        }

        .discussion .comment {
            padding: 10px;
            border: 1px solid #333;
            border-radius: 5px;
            margin-bottom: 10px;
            background-color: #292929;
        }

        .discussion .comment p {
            margin: 0;
        }

        .discussion textarea {
            width: 100%;
            padding: 10px;
            margin-top: 10px;
            border: 1px solid #333;
            border-radius: 5px;
            background-color: #292929;
            color: #e0e0e0;
            resize: none;
            height: 100px;
        }

        .discussion button {
            margin-top: 10px;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            background-color: #00bcd4;
            color: #ffffff;
            font-weight: bold;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        .discussion button:hover {
            background-color: #008c9e;
        }

        footer {
            text-align: center;
            padding: 10px;
            background-color: #1a1a1a;
            border-top: 1px solid #333;
            color: #757575;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Gaming Forum - Discussion</h1>
    </header>

    <nav>
        <a href="index.html">Home</a>
        <a href="#">Categories</a>
        <a href="#">Login</a>
        <a href="#">Register</a>
    </nav>

    <div class="container">
        <div class="discussion">
            <h2>Discussion Topic: Favorite Games</h2>
            <div class="comment">
                <p><strong>Gamer123:</strong> I absolutely love RPGs like The Witcher 3!</p>
            </div>
            <div class="comment">
                <p><strong>IndieFan:</strong> Indie games have been my go-to recently. Hollow Knight is a masterpiece.</p>
            </div>

            <textarea placeholder="Write your comment..."></textarea>
            <button>Post Comment</button>
        </div>
    </div>

    <footer>
        <p>&copy; 2025 Gaming Forum. All rights reserved.</p>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gaming Forum</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #121212;
            color: #e0e0e0;
        }

        header {
            background-color: #1f1f1f;
            padding: 20px;
            text-align: center;
            border-bottom: 2px solid #333;
        }

        nav {
            margin: 10px 0;
            text-align: center;
        }

        nav a {
            color: #e0e0e0;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
        }

        nav a:hover {
            text-decoration: underline;
        }

        main {
            padding: 20px;
            text-align: center;
        }

        .form-container {
            background-color: #1f1f1f;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
            display: inline-block;
        }

        input[type="text"], input[type="email"], input[type="password"] {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #333;
            border-radius: 5px;
            background-color: #121212;
            color: #e0e0e0;
        }

        button {
            background-color: #6200ea;
            color: white;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
        }

        button:hover {
            background-color: #3700b3;
        }

        .gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 10px;
            margin-top: 20px;
        }

        .gallery img {
            width: 200px;
            height: 150px;
            border-radius: 10px;
            object-fit: cover;
            border: 2px solid #333;
        }

        .discussion {
            text-align: left;
            margin: 20px auto;
            max-width: 800px;
            background-color: #1f1f1f;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
        }

        .discussion h3 {
            margin-top: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Gaming Forum</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="discussion.html">Discussion</a>
        </nav>
    </header>

    <main>
        <h2>Register</h2>
        <div class="form-container">
            <form action="/register" method="POST">
                <input type="text" name="username" placeholder="Username" required>
                <input type="email" name="email" placeholder="Email" required>
                <input type="password" name="password" placeholder="Password" required>
                <button type="submit">Register</button>
            </form>
        </div>

        <h2>Gaming Gallery</h2>
        <div class="gallery">
            <img src="https://via.placeholder.com/200x150" alt="Gaming Tournament 1">
            <img src="https://via.placeholder.com/200x150" alt="Gaming Tournament 2">
            <img src="https://via.placeholder.com/200x150" alt="Gaming Tournament 3">
        </div>

        <h2>Latest Discussions</h2>
        <div class="discussion">
            <h3>Topic 1: Best Strategies in FPS Games</h3>
            <p>Join the discussion about the best strategies to dominate FPS games. Share your tips and tricks!</p>
        </div>
        <div class="discussion">
            <h3>Topic 2: Upcoming Tournaments</h3>
            <p>Discuss the most exciting upcoming gaming tournaments and events. Who are you rooting for?</p>
        </div>
    </main>
</body>
</html>
