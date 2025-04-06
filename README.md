<!DOCTYPE html><html lang="de">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>NordFenster – Fenster, Türen & Tore</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-50 text-gray-800">
  <!-- Header -->
  <header class="bg-white shadow">
    <div class="container mx-auto px-4 py-6 flex justify-between items-center">
      <div class="flex items-center space-x-4">
        <img src="/mnt/data/file-4bNpvVu8Bw3E1qdf5zgjjo" alt="NordFenster Logo" class="h-16">
        <h1 class="text-2xl font-bold text-blue-800">NordFenster</h1>
      </div>
      <nav class="space-x-4">
        <a href="#about" class="hover:text-blue-600">Über uns</a>
        <a href="#products" class="hover:text-blue-600">Produkte</a>
        <a href="#gallery" class="hover:text-blue-600">Galerie</a>
        <a href="#contact" class="hover:text-blue-600">Kontakt</a>
        <a href="#lang-switch" class="hover:text-blue-600">PL</a>
      </nav>
    </div>
  </header>  <!-- Hero Section -->  <section class="bg-blue-100 py-20 text-center">
    <h2 class="text-4xl font-bold mb-4">Fenster, Türen & Tore – Qualität aus dem Norden</h2>
    <p class="text-lg mb-6">Für alle, die klare Verhältnisse lieben… sogar bei der Heizkostenabrechnung!</p>
    <a href="#contact" class="bg-blue-800 text-white px-6 py-3 rounded hover:bg-blue-700">Jetzt Angebot anfordern</a>
  </section>  <!-- Language Switch Section -->  <section id="lang-switch" class="bg-white py-4 text-center">
    <p>Sprache wählen / Wybierz język: 
      <a href="#" onclick="switchToPL()" class="text-blue-800 underline">Polski</a> | 
      <a href="#" onclick="switchToDE()" class="text-blue-800 underline">Deutsch</a>
    </p>
  </section>  <!-- About Section -->  <section id="about" class="py-16 px-4 container mx-auto">
    <div id="about-de">
      <h3 class="text-3xl font-semibold mb-4">Über NordFenster</h3>
      <p class="mb-6">Wir sind ein junges Unternehmen, das sich auf den Vertrieb von hochwertigen Fenstern, Türen und Toren spezialisiert hat – direkt aus Polen auf den deutschen Markt. Mit einem Auge fürs Detail und einem Gespür für Qualität bringen wir nordische Eleganz in jedes Zuhause.</p>
    </div>
    <div id="about-pl" class="hidden">
      <h3 class="text-3xl font-semibold mb-4">O firmie NordFenster</h3>
      <p class="mb-6">Jesteśmy młodą firmą specjalizującą się w sprzedaży wysokiej jakości okien, drzwi i bram – bezpośrednio z Polski na rynek niemiecki. Z dbałością o szczegóły i wyczuciem jakości wprowadzamy nordycką elegancję do każdego domu.</p>
    </div>
  </section>  <!-- Products Section -->  <section id="products" class="bg-gray-100 py-16 px-4 container mx-auto">
    <div id="products-de">
      <h3 class="text-3xl font-semibold mb-8 text-center">Unsere Produkte</h3>
      <div class="grid md:grid-cols-3 gap-8">
        <div class="bg-white p-6 rounded shadow">
          <h4 class="text-xl font-bold mb-2">Fenster</h4>
          <p>Moderne, energieeffiziente Fenster in verschiedenen Designs und Materialien.</p>
        </div>
        <div class="bg-white p-6 rounded shadow">
          <h4 class="text-xl font-bold mb-2">Türen</h4>
          <p>Sichere und stilvolle Haustüren sowie Innentüren für jeden Geschmack.</p>
        </div>
        <div class="bg-white p-6 rounded shadow">
          <h4 class="text-xl font-bold mb-2">Tore</h4>
          <p>Garagentore, Rolltore und mehr – praktisch, langlebig und zuverlässig.</p>
        </div>
      </div>
    </div>
    <div id="products-pl" class="hidden">
      <h3 class="text-3xl font-semibold mb-8 text-center">Nasze produkty</h3>
      <div class="grid md:grid-cols-3 gap-8">
        <div class="bg-white p-6 rounded shadow">
          <h4 class="text-xl font-bold mb-2">Okna</h4>
          <p>Nowoczesne, energooszczędne okna w różnych wzorach i materiałach.</p>
        </div>
        <div class="bg-white p-6 rounded shadow">
          <h4 class="text-xl font-bold mb-2">Drzwi</h4>
          <p>Bezpieczne i stylowe drzwi wejściowe oraz wewnętrzne dla każdego gustu.</p>
        </div>
        <div class="bg-white p-6 rounded shadow">
          <h4 class="text-xl font-bold mb-2">Bramy</h4>
          <p>Bramy garażowe, rolowane i inne – praktyczne, trwałe i niezawodne.</p>
        </div>
      </div>
    </div>
  </section>  <!-- Gallery Section -->  <section id="gallery" class="py-16 px-4 container mx-auto">
    <h3 class="text-3xl font-semibold mb-8 text-center">Galerie / Galeria</h3>
    <h4 class="text-2xl font-semibold mb-4">Drutex</h4>
    <div class="grid md:grid-cols-3 gap-8 mb-8">
      <img src="https://tse3.mm.bing.net/th?id=OIP.low5ySqyk0DV_54lRygcvwHaHa&pid=Api" alt="IGLO Premier" class="rounded shadow">
      <img src="https://tse3.mm.bing.net/th?id=OIP.9GmOZAREBeUOa32M-clDeQHaHa&pid=Api" alt="IGLO 5 Classic" class="rounded shadow">
      <img src="https://tse1.mm.bing.net/th?id=OIP.RCqZALCO315QENc0toRwrwHaHa&pid=Api" alt="Drzwi MB-70" class="rounded shadow">
    </div>
    <h4 class="text-2xl font-semibold mb-4">Gałat</h4>
    <div class="grid md:grid-cols-3 gap-8">
      <img src="https://www.galat.pl/wp-content/uploads/2023/01/ogrod-zimowy-galat-1.jpg" alt="Ogród zimowy" class="rounded shadow">
      <img src="https://www.galat.pl/wp-content/uploads/2023/01/drzwi-automatyczne-galat.jpg" alt="Drzwi automatyczne" class="rounded shadow">
      <img src="https://www.galat.pl/wp-content/uploads/2023/01/fasady-aluminiowe-galat.jpg" alt="Fasady aluminiowe" class="rounded shadow">
    </div>
  </section>  <!-- Contact Section -->  <section id="contact" class="py-16 px-4 container mx-auto">
    <h3 class="text-3xl font-semibold mb-4 text-center">Kontaktieren Sie uns / Skontaktuj się z nami</h3>
    <form class="max-w-xl mx-auto grid gap-4">
      <input type="text" placeholder="Ihr Name / Twoje imię" class="p-3 border rounded">
      <input type="email" placeholder="Ihre E-Mail / Twój e-mail" class="p-3 border rounded">
      <textarea placeholder="Ihre Nachricht / Twoja wiadomość" class="p-3 border rounded h-32"></textarea>
      <button type="submit" class="bg-blue-800 text-white py-3 rounded hover:bg-blue-700">Absenden / Wyślij</button>
    </form>
  </section>  <!-- Footer -->  <footer class="bg-white text-center py-6 border-t mt-10">
    <p>&copy; 2025 NordFenster – Maciej Benderski | Tel: 0048669205242</p>
  </footer>  <!-- Language Switch Script -->  <script>
    function switchToPL() {
      document.getElementById('about-de').classList.add('hidden');
      document.getElementById('products-de').classList.add('hidden');
      document.getElementById('about-pl').classList.remove('hidden');
      document.getElementById('products-pl').classList.remove('hidden');
    }
    function switchToDE() {
      document.getElementById('about-pl').classList.add('hidden');
      document.getElementById('products-pl').classList.add('hidden');
      document.getElementById('about-de').classList.remove('hidden');
      document.getElementById('products-de').classList.remove('hidden');
    }
  </script></body>
</html>
