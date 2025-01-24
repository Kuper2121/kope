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
