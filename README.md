<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Space</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Shared Menu -->
    <nav class="navbar">
        <ul>
            <li><a href="index.html" class="active">Personal Space</a></li>
            <li><a href="css-landing.html">CSS Landing Page</a></li>
            <li><a href="bs-landing.html">Bootstrap Landing Page</a></li>
        </ul>
    </nav>

    <main style="padding: 20px;">
        <h1>Welcome to My Personal Space</h1>
        <p>This is the main HTML page showcasing my profile, interests, and project links.</p>
    </main>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Landing Page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Shared Menu -->
    <nav class="navbar">
        <ul>
            <li><a href="index.html">Personal Space</a></li>
            <li><a href="css-landing.html" class="active">CSS Landing Page</a></li>
            <li><a href="bs-landing.html">Bootstrap Landing Page</a></li>
        </ul>
    </nav>

    <header class="hero-section">
        <h1>Custom CSS Product Landing</h1>
        <p>Styled completely with vanilla CSS layout techniques.</p>
    </header>

</body>
</html>
/* Navigation Menu Styling */
.navbar {
    background-color: #333;
    padding: 15px;
}
.navbar ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    display: flex;
    gap: 20px;
}
.navbar a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}
.navbar a.active {
    color: #4CAF50;
}
/* Hero Section Styling */
.hero-section {
    background: #f4f4f4;
    padding: 60px 20px;
    text-align: center;
}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bootstrap Landing Page</title>
    <!-- Bootstrap CSS CDN -->
    <link href="https://jsdelivr.net" rel="stylesheet">
</head>
<body>

    <!-- Bootstrap Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <div class="container-fluid">
            <div class="navbar-nav">
                <a class="nav-link" href="index.html">Personal Space</a>
                <a class="nav-link" href="css-landing.html">CSS Landing Page</a>
                <a class="nav-link active" href="bs-landing.html">Bootstrap Landing Page</a>
            </div>
        </div>
    </nav>

    <!-- Bootstrap Hero -->
    <div class="bg-light p-5 text-center">
        <h1 class="display-4">Bootstrap Framework Landing</h1>
        <p class="lead">Built smoothly using responsive Bootstrap grid and utility classes.</p>
    </div>

    <!-- Bootstrap JS Bundle -->
    <script src="https://jsdelivr.net"></script>
</body>
</html>
