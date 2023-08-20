
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>My Simple Website</title>
</head>
<body>
    <header>
        <h1>Welcome to My Website</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Services</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>
    <main>
        <section>
            <h2>About Us</h2>
            <p>This is a simple website created using HTML and CSS.</p>
        </section>
    </main>
    <footer>
        <p>&copy; 2023 My Simple Website</p>
    </footer>
</body>
</html>
CSS (styles.css):

css
Copy code
/* Reset some default styles for consistency */
body, h1, h2, p {
    margin: 0;
    padding: 0;
}

/* Basic styling */
body {
    font-family: Arial, sans-serif;
    background-color: #f7f7f7;
    color: #333;
}

header {
    background-color: #007bff;
    color: #fff;
    padding: 20px;
    text-align: center;
}

nav {
    background-color: #333;
    color: #fff;
    padding: 10px;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
}

nav a {
    text-decoration: none;
    color: #fff;
    margin: 0 15px;
}

main {
    padding: 20px;
}

section {
    margin-bottom: 20px;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 10px;
}
