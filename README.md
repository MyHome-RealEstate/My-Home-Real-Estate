# My-Home-Real-Estate
/* General styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
}

.container {
    width: 80%;
    margin: 0 auto;
}

header {
    background-color: #4CAF50;
    color: white;
    padding: 20px 0;
    text-align: center;
}

nav {
    background-color: #333;
}

nav ul {
    list-style-type: none;
    text-align: center;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 18px;
}

nav ul li a:hover {
    text-decoration: underline;
}

h2 {
    font-size: 2em;
    margin-bottom: 20px;
}

.property-list {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
}

.property-item {
    background-color: white;
    border: 1px solid #ddd;
    border-radius: 8px;
    width: 30%;
    padding: 15px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.property-item h3 {
    font-size: 1.5em;
    color: #4CAF50;
}

footer {
    background-color: #333;
    color: white;
    padding: 10px 0;
    text-align: center;
}

footer a {
    color: #4CAF50;
    text-decoration: none;
}
