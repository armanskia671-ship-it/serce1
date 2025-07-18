<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Projekt Serce</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Projekt Serce</h1>
    <nav>
      <a href="#galeria">Galeria</a>
      <a href="#kontakt">Kontakt</a>
    </nav>
  </header>

  <section id="galeria">
    <h2>Galeria</h2>
    <img src="serce1.jpg" alt="Serce 1">
    <img src="serce2.jpg" alt="Serce 2">
  </section>

  <section id="kontakt">
    <h2>Kontakt</h2>
    <form>
      <input type="text" placeholder="Twoje imię" required>
      <input type="email" placeholder="Twój email" required>
      <textarea placeholder="Wiadomość" required></textarea>
      <button type="submit">Wyślij</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Projekt Serce</p>
  </footer>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #fdfdfd;
  color: #333;
}

header {
  background-color: #e63946;
  color: white;
  padding: 20px;
  text-align: center;
}

nav a {
  margin: 0 10px;
  color: white;
  text-decoration: none;
}

section {
  padding: 20px;
}

img {
  width: 200px;
  margin: 10px;
  border-radius: 8px;
}

form {
  display: flex;
  flex-direction: column;
  max-width: 400px;
}

input, textarea {
  margin: 10px 0;
  padding: 10px;
  font-size: 1em;
}

button {
  padding: 10px;
  background-color: #457b9d;
  color: white;
  border: none;
  cursor: pointer;
}

footer {
  background-color: #e63946;
  color: white;
  text-align: center;
  padding: 10px;
}
serce1.jpg
serce2.jpg
