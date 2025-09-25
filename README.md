# testni-projekat
<!DOCTYPE html>
<html lang="hr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Moja Zanimljiva Stranica</title>
  <link rel="stylesheet" href="style.css">
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
</head>
<body>

  <header>
    <nav>
      <div class="logo">🌟 Moja Stranica</div>
      <ul class="nav-links">
        <li><a href="#pocetna">Početna</a></li>
        <li><a href="#o-nama">O nama</a></li>
        <li><a href="#galerija">Galerija</a></li>
        <li><a href="#kontakt">Kontakt</a></li>
      </ul>
    </nav>
  </header>

  <section class="hero" id="pocetna">
    <h1>Dobrodošli!</h1>
    <p>Ovo je moja zanimljiva web stranica napravljena u Visual Studio Code.</p>
    <a href="#o-nama" class="btn">Saznaj više</a>
  </section>

  <section class="about" id="o-nama">
    <h2>O Nama</h2>
    <p>Mi smo tim koji voli praviti lijepe i korisne web stranice. Naš cilj je jednostavnost i funkcionalnost. Danas je osamnaesti septembar dvije hiljade dvadeset pete. Najviše se brinemo o sljedećim stvarima koje svaka stranica treba imati:</p>
    <ul>
      <li>Kreativan dizajn</li>
      <li>Moderni alati</li>
      <li>Prilagođeno korisnicima</li>
    </ul>
  </section>

  <section class="gallery" id="galerija">
    <h2>Galerija</h2>
    <div class="gallery-container">
      <img src="https://th.bing.com/th/id/OIP.Zyz_0Gq74ILbkcWwh-vzcAHaE8?w=233&h=180&c=7&r=0&o=7&pid=1.7&rm=3" alt="Slika 1">
      <img src="https://th.bing.com/th/id/OIP.72hWIsuRw3k8wNXPMie_9wHaEx?w=275&h=180&c=7&r=0&o=7&pid=1.7&rm=3" alt="Slika 2">
      <img src="https://th.bing.com/th/id/OIP.Zyz_0Gq74ILbkcWwh-vzcAHaE8?w=233&h=180&c=7&r=0&o=7&pid=1.7&rm=3" alt="Slika 3">
      <img src="https://th.bing.com/th/id/OIP.Zyz_0Gq74ILbkcWwh-vzcAHaE8?w=233&h=180&c=7&r=0&o=7&pid=1.7&rm=3" alt="Slika 4">
    </div>
  </section>

  <section class="contact" id="kontakt">
    <h2>Kontakt</h2>
    <form action="#" method="post" class="contact-form">
      <label for="ime">Ime:</label>
      <input type="text" id="ime" name="ime" required>

<label for="email">Email:</label>
<input type="email" id="email" name="email" required>

<label for="poruka">Poruka:</label>
<textarea id="poruka" name="poruka" rows="5" required></textarea>

<button type="submit">Pošalji poruku</button>
    </form>
  </section>

  <footer>
    <p>© 2025 Moja Stranica. Sva prava pridržana.</p>
  </footer>

</body>
</html>


