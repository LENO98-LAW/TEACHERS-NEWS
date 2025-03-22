# TEACHERS-NEWS
/education-blog  
 ├── index.html  
 ├── styles.css  
 ├── script.js  
 ├── contact.html  
 ├── images/  
 ├── README.md
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Education Blog</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Education Blog</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="contact.html">Contact</a>
        </nav>
    </header>

    <main>
        <section class="intro">
            <h2>Welcome to Our Blog</h2>
            <p>Sharing knowledge and learning together.</p>
        </section>

        <section class="articles">
            <article>
                <h3>Understanding Learning Styles</h3>
                <p>Discover how different people absorb information best...</p>
                <a href="#">Read More</a>
            </article>

            <article>
                <h3>Top 5 Study Techniques</h3>
                <p>Improve your study habits with these proven methods...</p>
                <a href="#">Read More</a>
            </article>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Education Blog. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f9f9f9;
    text-align: center;
}

header {
    background: #0044cc;
    color: white;
    padding: 20px;
    font-size: 24px;
}

nav a {
    color: white;
    text-decoration: none;
    margin: 0 15px;
}

.intro {
    padding: 50px;
    animation: fadeIn 2s ease-in;
}

.articles {
    display: flex;
    justify-content: center;
    gap: 20px;
    padding: 20px;
}

article {
    background: white;
    padding: 20px;
    box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s;
}

article:hover {
    transform: scale(1.05);
}

@keyframes fadeIn {
    from { opacity: 0; }
    to { opacity: 1; }
}

footer {
    background: #333;
    color: white;
    padding: 10px;
}
document.addEventListener("DOMContentLoaded", () => {
    console.log("Website Loaded!");
});
document.addEventListener("DOMContentLoaded", () => {
    console.log("Website Loaded!");
});
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Contact Us</h1>
        <nav>
            <a href="index.html">Home</a>
            <a href="contact.html">Contact</a>
        </nav>
    </header>

    <main>
        <form action="https://formspree.io/f/{your_form_id}" method="POST">
            <label>Name:</label>
            <input type="text" name="name" required>

            <label>Email:</label>
            <input type="email" name="email" required>

            <label>Message:</label>
            <textarea name="message" required></textarea>

            <button type="submit">Send</button>
        </form>
    </main>

    <footer>
        <p>&copy; 2025 Education Blog</p>
    </footer>
</body>
</html>
