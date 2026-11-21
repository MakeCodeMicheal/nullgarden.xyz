# nullgarden.xyz
My own little website (in dev). Hopefully this will grow into something like the stuff on neocities !! 

BACKUP CSS

.container  {
    max-width: 1000px;
    margin: 50px auto;
    display: grid;
    grid-gap: 20px;
    grid-template-columns: 250px minmax(0, 1fr);
    background-color: #E9EAEC;
}

body {
    background-image: url("Images/nullGardenBackG1.png"); 
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
    background-attachment: fixed;
}

header, nav, main, footer {
    background-color: #F8F8F8;
    border: 2px solid #B8BBC2;
}

header {
    grid-row: 1 / 2;
    grid-column: 1 / 3;
}

nav {
    grid-row: 2 / 3;
    grid-column: 1 / 2;
    height: max-content;
}

main {
    grid-row: 2 / 3;
    grid-column: 2 / 3;
    height: max-content;
}

footer {
    grid-row: 3 / 4;
    grid-column: 1 / 3;
}

/* Hide scrollbar across browsers */
html {
    scrollbar-width: none; /* Firefox */
}

html::-webkit-scrollbar {
    display: none; /* Chrome, Opera, Safari */
}

/* Custom text selection */
::selection {
    background: #8799AF;
    color: #FFFFFF;
}

/* Links */
a {
    text-decoration: none;
    color: #343840;
    transition: color 0.2s ease;
}

/* Link hover */
a:hover {
    color: #8799AF;
}

HTML BACKUP


<!DOCTYPE html>

<html lang="en">

<head>

    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="icon" href="Images/nullGardenTabIcon1.gif">
    <title>𝄃𝄂𝄂𝄀𝄁𝄃𝄂𝄂𝄃 N U L L  G A R D E N 𝄃𝄂𝄂𝄀𝄁𝄃𝄂𝄂𝄃</title>
    <link href="style.css" rel="stylesheet" type="text/css">
    <!-- Hatsune Miku - https://www.cursors-4u.com/cursor/hatsune-miku -->
    <link rel="stylesheet" href="https://cdn.cursors-4u.net/cursors/animated/hatsune-miku-81a2620d-32.css">
    <!-- End www.Cursors-4U.com Code -->

</head>

<body>

    <div class="container">

        <header>

            <h1>N U L L  G A R D E N</h1>

        </header>

        <nav>

            <p>Welcome :D</p>

        </nav>

        <main>

            <p>This website is the beginning of my website development project.</p>

        </main>

        <footer>

            <p>I claim this corner of the internet.</p>

        </footer>

    </div>

</body>

</html>