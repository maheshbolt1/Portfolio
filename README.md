* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    color: #333;
}

header {
    background: #333;
    color: #fff;
    padding: 20px 0;
    position: fixed;
    top: 0;
    width: 100%;
    z-index: 1000;
}

nav {
    max-width: 1200px;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

nav ul {
    list-style: none;
    display: flex;
}

nav ul li {
    margin-left: 20px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
}

.hero {
    height: 100vh;
    background-color: #f5f5f5;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
}

.hero h1 {
    font-size: 3em;
    margin-bottom: 10px;
}

.hero h2 {
    font-size: 2em;
    color: #777;
}

section {
    padding: 60px 20px;
    text-align: center;
}

.about, .contact {
    background-color: #f5f5f5;
}

.projects {
    background-color: #fff;
}

.project-cards {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
    margin-top: 20px;
}

.card {
    width: 30%;
    margin: 20px;
    background-color: #eee;
    padding: 20px;
    border-radius: 8px;
}

.card img {
    width: 100%;
    height: auto;
    border-radius: 8px;
}

.card h3 {
    margin-top: 10px;
    font-size: 1.5em;
}

.card p {
    color: #777;
}

.contact a {
    display: inline-block;
    margin-top: 20px;
    padding: 10px 20px;
    background-color: #333;
    color: #fff;
    text-decoration: none;
    border-radius: 5px;
}

footer {
    text-align: center;
    background-color: #333;
    color: #fff;
    padding: 20px 0;
}
