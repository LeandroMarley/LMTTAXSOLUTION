/* Reset básico */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Estilos gerais */
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
}

/* Cabeçalho */
header {
    background-color: #2c3e50;
    color: #fff;
    padding: 20px 0;
}

header .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header h1 {
    font-size: 2em;
}

header nav ul {
    list-style: none;
}

header nav ul li {
    display: inline;
    margin: 0 15px;
}

header nav ul li a {
    color: #fff;
    text-decoration: none;
    font-size: 1.1em;
}

/* Seções */
section {
    padding: 40px 0;
    background-color: #fff;
}

section h2 {
    font-size: 2em;
    margin-bottom: 20px;
}

.container {
    width: 80%;
    margin: 0 auto;
}

.intro p {
    font-size: 1.2em;
}

.services .service-item {
    margin-bottom: 20px;
}

.service-item h3 {
    font-size: 1.5em;
    margin-bottom: 10px;
}

.about p {
    font-size: 1.1em;
    line-height: 1.6;
}

.contact form {
    display: flex;
    flex-direction: column;
}

.contact label {
    margin-top: 10px;
}

.contact input, .contact textarea {
    padding: 10px;
    margin-top: 5px;
    border: 1px solid #ccc;
    font-size: 1em;
}

.contact button {
    padding: 10px;
    margin-top: 20px;
    background-color: #2c3e50;
    color: #fff;
    border: none;
    cursor: pointer;
}

.contact button:hover {
    background-color: #34495e;
}

/* Rodapé */
footer {
    background-color: #2c3e50;
    color: #fff;
    text-align: center;
    padding: 20px 0;
}
