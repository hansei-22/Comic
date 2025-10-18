my-comic/
├── index.html        ← Homepage
├── style.css         ← Styles (colors, fonts, layout)
├── chapter1/
│   ├── page1.jpg
│   ├── page2.jpg
│   └── ...
├── chapter2/
│   ├── page1.jpg
│   └── ...
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Comic</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>My Comic</h1>
    <nav>
      <a href="chapter1/page1.html">Chapter 1</a>
      <a href="chapter2/page1.html">Chapter 2</a>
    </nav>
  </header>

  <main>
    <p>Welcome to my comic! Click a chapter to start reading.</p>
  </main>

  <footer>
    <p>© 2025 Your Name</p>
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Chapter 1 - Page 1</title>
  <link rel="stylesheet" href="../style.css">
</head>
<body>
  <header>
    <h1>Chapter 1</h1>
    <nav>
      <a href="page1.html">1</a>
      <a href="page2.html">2</a>
      <!-- Add more pages -->
      <a href="../index.html">Home</a>
    </nav>
  </header>

  <main>
    <img src="page1.jpg" alt="Chapter 1 Page 1">
    <a href="page2.html">Next Page →</a>
  </main>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  background-color: #fdfdfd;
  text-align: center;
  margin: 0;
  padding: 0;
}

header, footer {
  background-color: #222;
  color: white;
  padding: 10px;
}

nav a {
  color: #fff;
  margin: 0 10px;
  text-decoration: none;
}

img {
  max-width: 100%;
  height: auto;
  margin: 20px 0;
}

main a {
  display: inline-block;
  margin: 20px;
  text-decoration: none;
  color: #222;
  font-weight: bold;
}
