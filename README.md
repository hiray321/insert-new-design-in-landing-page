<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Your Landing Page</title>
</head>
<style>
    /* Normalize CSS */
    * {
        box-sizing: border-box;
        margin: 0;
        padding: 0;
    }

    body {
        font-family: 'Arial', sans-serif;
        line-height: 1.6;
        background-color: #f8f8f8;
        color: #333;
    }

    .container {
        max-width: 1200px;
        margin: 0 auto;
        padding: 0 20px;
    }

    header, main, footer {
        padding: 20px;
        background-color: #ffffff33;
        border-radius: 8px;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        margin-bottom: 20px;
    }

    header h1 {
        color: #f4ad42;
    }

    section {
        margin-bottom: 20px;
    }

    .features-list {
        list-style-type: none;
        padding: 0;
        margin: 0;
        display: flex;
        justify-content: space-around;
        align-items: center;
    }

    .feature-item {
        text-align: center;
    }

    .feature-icon {
        font-size: 24px;
        margin-bottom: 10px;
    }

    footer {
        text-align: center;
        color: #777;
    }

    /* Responsive Design */
    @media (max-width: 600px) {
        header, main, footer {
            padding: 10px;
        }
    }
</style>
<body>
    <header>
        <div class="container">
            <h1>Ram Ram</h1>
            <p>Jai Shree Ram !</p>
        </div>
    </header>

    <main>
        <section class="features">
            <div class="container">
                <h2>Available Features</h2>
                <ul class="features-list">
                    <li class="feature-item">
                        <i class="fas fa-globe feature-icon"></i>
                        <p>Global Reach</p>
                    </li>
                    <li class="feature-item">
                        <i class="fas fa-heart feature-icon"></i>
                        <p>Passionate Community</p>
                    </li>
                    <li class="feature-item">
                        <i class="fas fa-star feature-icon"></i>
                        <p>Top-rated Experience</p>
                    </li>
                </ul>
            </div>
        </section>

        <section class="get-started">
            <div class="container">
                <h2>Get Started</h2>
                <p>Sign up now to experience the awesomeness.</p>
            </div>
        </section>

        <section class="additional-features">
            <div class="container">
                <h2>More Features Coming Soon</h2>
                <p>Stay tuned for exciting updates and new features.</p>
            </div>
        </section>
    </main>

    <footer>
        <div class="container">
            <p>&copy; 2024 Your Website. All rights reserved.</p>
            <p>Contact: pankajhiray52@gmail.com</p>
        </div>
    </footer>
</body>
</html>
