# nullgarden.xyz
My own little website (in dev). Hopefully this will grow into something like the stuff on neocities !! 


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