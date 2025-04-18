<!DOCTYPE html>
<html lang="tr">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>GörevMars | Uzay Ajansları Merkezi</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@600&family=Roboto&display=swap" rel="stylesheet" />
    <style>
      body {
        font-family: 'Roboto', sans-serif;
        background: url('https://cdn.spacetelescope.org/archives/images/screen/heic1509a.jpg') no-repeat center center fixed;
        background-size: cover;
      }
      .glass {
        background: rgba(0, 0, 0, 0.6);
        backdrop-filter: blur(12px);
      }
      .orbitron {
        font-family: 'Orbitron', sans-serif;
      }
    </style>
  </head>
  <body class="text-white">
    <header class="text-center py-10 bg-black bg-opacity-80">
      <h1 class="text-5xl orbitron text-cyan-400">GörevMars</h1>
      <p class="mt-2 text-lg">Uzay Ajanslarını ve Görevlerini Tek Çatı Altında Toplayan Merkez</p>
    </header>

    <nav class="bg-black bg-opacity-70 py-4 text-center sticky top-0 z-50">
      <a href="#spacex" class="mx-4 text-cyan-300 hover:underline">SpaceX</a>
      <a href="#nasa" class="mx-4 text-cyan-300 hover:underline">NASA</a>
      <a href="#esa" class="mx-4 text-cyan-300 hover:underline">ESA</a>
      <a href="#tua" class="mx-4 text-cyan-300 hover:underline">TUA</a>
    </nav>

    <main class="max-w-6xl mx-auto p-6 space-y-8">
      <!-- Ajans Bölümü Şablonu Başlangıç -->
      <section id="spacex" class="glass p-6 rounded-2xl">
        <h2 class="text-3xl orbitron text-yellow-400">🚀 SpaceX</h2>
        <p>SpaceX, Elon Musk tarafından kurulan ve Mars'a insan göndermeyi hedefleyen özel bir uzay şirketidir.</p>
      </section>

      <section id="nasa" class="glass p-6 rounded-2xl">
        <h2 class="text-3xl orbitron text-yellow-400">🛰️ NASA</h2>
        <p>NASA, ABD'nin uzay ajansıdır. Ay ve Mars görevleri, teleskop projeleri ve uluslararası iş birlikleri yürütür.</p>
      </section>

      <section id="esa" class="glass p-6 rounded-2xl">
        <h2 class="text-3xl orbitron text-yellow-400">🇪🇺 ESA</h2>
        <p>ESA, Avrupa Uzay Ajansı’dır. Çok uluslu uzay projeleri ve bilimsel araştırmalar yürütür.</p>
      </section>

      <section id="tua" class="glass p-6 rounded-2xl">
        <h2 class="text-3xl orbitron text-yellow-400">🇹🇷 TUA</h2>
        <p>Türkiye Uzay Ajansı, milli uzay programını yöneten devlet kurumudur. Ay görevleri ve uydu projeleri yürütmektedir.</p>
      </section>
    </main>

    <footer class="text-center py-6 text-sm text-gray-400 bg-black bg-opacity-80">
      GörevMars © 2025 | Tüm Hakları Saklıdır | Uzayın Geleceği Burada
    </footer>
  </body>
</html>
