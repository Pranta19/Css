css
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: sans-serif;
}

body {
  background: linear-gradient(135deg, #f8d146, #fca311);
  color: #1a1a1a;
  padding: 2rem;
}

header .logo {
  font-weight: bold;
  font-size: 1.5rem;
  margin-bottom: 2rem;
}

.hero h2 {
  color: #d87d00;
  font-size: 1rem;
  margin-bottom: 0.5rem;
}

.hero h1 {
  font-size: 2rem;
  line-height: 1.4;
  margin-bottom: 1rem;
}

.tags {
  margin-bottom: 1.5rem;
}

.tags button {
  background-color: #fff;
  border: none;
  margin: 0.3rem;
  padding: 0.6rem 1rem;
  border-radius: 20px;
  font-size: 0.9rem;
  cursor: pointer;
}

.cta-button {
  display: inline-block;
  margin-top: 1rem;
  padding: 0.8rem 1.5rem;
  background-color: #1a1a1a;
  color: white;
  text-decoration: none;
  border-radius: 25px;
  font-weight: bold;
}

.info {
  margin-top: 2rem;
  font-size: 1rem;
}
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Paint Landing</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <div class="logo">PAINT</div>
  </header>
  <main>
    <section class="hero">
      <h2>RISUS PRAESENT VULPUTATE.</h2>
      <h1>Cursus Integer<br>Consequat Tristique.</h1>
      <div class="tags">
        <button>Cursus Integer</button>
        <button>Integer Consequat</button>
        <button>Tellus Euismod Pellentesque</button>
        <button>Aliquet Tristique</button>
        <button>Pellentesque Tempus</button>
        <button>Mattis Fermentum Praesent</button>
      </div>
      <a href="#" class="cta-button">Lorem Ipsum →</a>
    </section>

    <section class="info">
      <p>Phasellus a vitae magna eleifend odio.</p>
    </section>
  </main>
</body>
</html>
