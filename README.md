<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>All About Cats | Test Website</title>
    <style>
        /* Basic Reset & Styling */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f9f9f9;
        }
        header {
            background-color: #ff9f43;
            color: white;
            padding: 2rem;
            text-align: center;
        }
        header h1 {
            margin-bottom: 0.5rem;
        }
        nav {
            background-color: #333;
            text-align: center;
            padding: 0.5rem;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 0.5rem 1rem;
            margin: 0 0.5rem;
        }
        nav a:hover {
            color: #ff9f43;
        }
        .container {
            max-width: 1000px;
            margin: 2rem auto;
            padding: 0 1rem;
        }
        .main-content {
            display: grid;
            grid-template-columns: 2fr 1fr;
            gap: 2rem;
        }
        @media (max-width: 768px) {
            .main-content {
                grid-template-columns: 1fr;
            }
        }
        .card {
            background: white;
            padding: 1.5rem;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
            margin-bottom: 1.5rem;
        }
        .card h2 {
            color: #ff9f43;
            margin-bottom: 1rem;
        }
        img.cat-img {
            width: 100%;
            height: auto;
            border-radius: 6px;
            margin-bottom: 1rem;
        }
        ul {
            list-style-position: inside;
            margin-left: 1rem;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1.5rem;
            margin-top: 3rem;
        }
    </style>
</head>
<body>

    <header>
        <h1>The Purr-fect Corner</h1>
        <p>A simple test website dedicated to our feline friends</p>
    </header>

    <nav>
        <a href="#about">About</a>
        <a href="#breeds">Popular Breeds</a>
        <a href="#facts">Fun Facts</a>
    </nav>

    <div class="container main-content">
        <main>
            <section id="about" class="card">
                <h2>Why We Love Cats</h2>
                <img src="https://images.unsplash.com/photo-1514888286974-6c03e2ca1dba?w=800" alt="Cute sleeping cat" class="cat-img">
                <p>Cats have been companions to humans for thousands of years. Known for their independence, playful antics, and soothing purrs, they make incredible pets. Whether they are chasing a laser pointer or curling up on your lap, cats bring endless joy and a bit of mystery to our lives.</p>
            </section>

            <section id="breeds" class="card">
                <h2>Popular Cat Breeds</h2>
                <p>While every cat is unique, here are a few breeds known for distinct traits:</p>
                <br>
                <ul>
                    <li><strong>Siamese:</strong> Highly vocal, social, and strikingly beautiful.</li>
                    <li><strong>Maine Coon:</strong> One of the largest domesticated breeds, known as "gentle giants."</li>
                    <li><strong>Ragdoll:</strong> Famous for their calm temperament and tendency to go limp when held.</li>
                    <li><strong>Bengal:</strong> Active and wild-looking, with beautiful spotted or marbled coats.</li>
                </ul>
            </section>
        </main>

        <aside>
            <div class="card" id="facts">
                <h2>Quick Cat Facts</h2>
                <hr style="border: 0; height: 1px; background: #eee; margin: 1rem 0;">
                <p>🐱 Cats sleep for roughly <strong>70% of their lives</strong>.</p>
                <br>
                <p>🔊 A cat has the ability to make over <strong>100 distinct vocal sounds</strong> (dogs can only make about 10).</p>
                <br>
                <p>🏃‍♂️ House cats can reach top speeds of up to <strong>30 mph (48 km/h)</strong> in short bursts.</p>
            </div>
        </aside>
    </div>

    <footer>
        <p>&copy; 2026 The Purr-fect Corner | Built with HTML & CSS</p>
    </footer>

</body>
</html>
