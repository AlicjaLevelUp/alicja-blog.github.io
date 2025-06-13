# alicja-blog.github.io
<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Alicja w Krainie Słów</title>
  <link rel="icon" href="favicon.ico" type="image/x-icon" />
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #f9f6f2;
      color: #333;
    }
    header {
      background: linear-gradient(to right, #e0c3fc, #8ec5fc);
      color: white;
      padding: 2rem;
      text-align: center;
    }
    header h1 {
      font-size: 2.5rem;
      margin: 0;
      font-family: 'Georgia', serif;
    }
    .container {
      max-width: 960px;
      margin: auto;
      padding: 2rem;
    }
    section {
      margin-bottom: 3rem;
    }
    h2 {
      color: #5e4b8b;
      border-bottom: 2px solid #e0c3fc;
      padding-bottom: 0.3rem;
    }
    .card {
      background-color: #ffffff;
      padding: 1.5rem;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.05);
      margin-bottom: 1.5rem;
    }
    .card h3 {
      margin-top: 0;
    }
    .card a.button {
      display: inline-block;
      margin-top: 1rem;
      padding: 0.5rem 1rem;
      background-color: #8a77d1;
      color: white;
      text-decoration: none;
      border-radius: 5px;
    }
    .card a.button:hover {
      background-color: #6c5bbf;
    }
    footer {
      background-color: #5e4b8b;
      color: white;
      padding: 1rem;
      text-align: center;
    }
    a {
      color: #5e4b8b;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    @media (max-width: 600px) {
      header h1 {
        font-size: 2rem;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Alicja w Krainie Słów</h1>
    <p>Blog dla nauczycieli i rodziców uczniów</p>
  </header>

  <div class="container">

    <section class="about">
      <h2>O mnie</h2>
      <p>Nazywam się <strong>Alicja Ciempa</strong>. Jestem nauczycielką języka polskiego, bibliotekarką i oligofrenopedagogiem. Mam bogate doświadczenie w pracy z dziećmi i młodzieżą, w tym z uczniami ze specjalnymi potrzebami edukacyjnymi.</p>
    </section>

    <section class="ebooks">
      <h2>E-booki do pobrania</h2>
      
      <div class="card">
        <h3>Jak wspierać ucznia z niepełnosprawnością?</h3>
        <p>Praktyczny przewodnik dla nauczycieli i wychowawców. Gotowe scenariusze, przykłady i narzędzia.</p>
        <a class="button" href="#">Pobierz PDF</a>
      </div>
      
      <div class="card">
        <h3>Pomysły na godziny wychowawcze</h3>
        <p>Inspiracje, które budują relacje i rozwijają kompetencje emocjonalno-społeczne.</p>
        <a class="button" href="#">Pobierz PDF</a>
      </div>
    </section>

    <section class="blog">
      <h2>Wpisy blogowe</h2>

      <div class="card">
        <h3>5 sposobów na ciekawą lekcję języka polskiego</h3>
        <p>Nie musisz sięgać po ekran — wystarczy kilka prostych metod, które zaangażują uczniów i pobudzą ich wyobraźnię.</p>
        <a class="button" href="#">Czytaj więcej</a>
      </div>

      <div class="card">
        <h3>Zastępstwo bez stresu: gotowe pomysły</h3>
        <p>Nieplanowana lekcja? Skorzystaj z gotowych rozwiązań, które sprawdzą się na każdej godzinie.</p>
        <a class="button" href="#">Czytaj więcej</a>
      </div>
    </section>

    <section class="contact">
      <h2>Kontakt</h2>
      <form action="https://formspree.io/f/moqpdjzn" method="POST">
        <label for="email">Twój e-mail:</label><br>
        <input type="email" name="email" id="email" required style="width: 100%; padding: 0.5rem; margin-top: 0.3rem;"><br><br>
        
        <label for="message">Wiadomość:</label><br>
        <textarea name="message" id="message" rows="5" required style="width: 100%; padding: 0.5rem; margin-top: 0.3rem;"></textarea><br><br>
        
        <button type="submit" style="background-color: #8a77d1; color: white; border: none; padding: 0.6rem 1.2rem; border-radius: 5px;">Wyślij</button>
      </form>
    </section>

  </div>

  <footer>
    &copy; 2025 Alicja Ciempa. Wszelkie prawa zastrzeżone.
  </footer>
</body>
</html>
