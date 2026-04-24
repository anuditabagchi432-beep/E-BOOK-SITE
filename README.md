# E-BOOK-SITE

E-BOOK SITE IN WEB DEVLOPMENT

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>E-Book Discovery Hub</title>
    <style>
        body { font-family: 'Segoe UI', sans-serif; margin: 0; background: #f4f4f9; }
        header { background: #232f3e; color: white; padding: 1rem 2rem; display: flex; justify-content: space-between; align-items: center; }
        .nav-links a { color: white; text-decoration: none; margin-left: 20px; font-weight: bold; }
        .hero { text-align: center; padding: 50px 20px; background: #fff; border-bottom: 1px solid #ddd; }
        .platform-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 20px; padding: 40px; max-width: 1200px; margin: auto; }
        .card { background: white; padding: 20px; border-radius: 10px; box-shadow: 0 4px 6px rgba(0,0,0,0.1); text-align: center; transition: transform 0.3s; }
        .card:hover { transform: translateY(-10px); }
        .card h3 { color: #232f3e; }
        footer { text-align: center; padding: 20px; background: #232f3e; color: white; }
    </style>
</head>
<body>

<header>
    <h1>E-Book Hub</h1>
    <nav class="nav-links">
        <a href="#">Home</a>
        <a href="#">Library</a>
        <a href="#">My Profile</a>
    </nav>
</header>

<section class="hero">
    <h2>Explore Top Reading Platforms</h2>
    <p>Your portal to millions of stories and books.</p>
</section>

<main class="platform-grid">
    <div class="card"><h3>Wattpad</h3><p>Community stories & amateur fiction.</p></div>
    <div class="card"><h3>Kindle</h3><p>Professional e-books & bestsellers.</p></div>
    <div class="card"><h3>Goodreads</h3><p>Book tracking & social reviews.</p></div>
    <div class="card"><h3>Scribd</h3><p>Digital library & audiobooks.</p></div>
    <div class="card"><h3>Kobo</h3><p>Global e-reading ecosystem.</p></div>
    <div class="card"><h3>Project Gutenberg</h3><p>Classic literature & public domain.</p></div>
</main>

<footer>
    <p>&copy; 2026 E-Book Discovery Hub - Educational Prototype</p>
</footer>

</body>
</html>
