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
        background: url('https://images.unsplash.com/photo-1580428181984-ebec7557f90c?ixlib=rb-4.0.3&auto=format&fit=crop&w=1950&q=80') no-repeat center center fixed;
        background-size: cover;
      }
      .glass {
        background: rgba(255, 255, 255, 0.05);
        backdrop-filter: blur(10px);
      }
      .orbitron {
        font-family: 'Orbitron', sans-serif;
      }
    </style>
  </head>
  <body class="text-white">
    <header class="text-center py-10 bg-black bg-opacity-70">
      <h1 class="text-5xl orbitron text-cyan-400">GörevMars</h1>
      <p class="mt-2 text-lg">Uzay Ajanslarının Bilgi Merkezi</p>
    </header>

    <main class="max-w-6xl mx-auto p-4">
      <!-- SpaceX -->
      <section class="glass p-6 rounded-2xl my-6">
        <h2 class="text-3xl orbitron text-yellow-400">🚀 SpaceX</h2>
        <img class="w-full rounded-xl my-4" src="https://upload.wikimedia.org/wikipedia/commons/e/ed/SpaceX_BFR.jpg" alt="SpaceX" />
        <p>SpaceX, Elon Musk tarafından kurulan ve Mars'a insan göndermeyi hedefleyen özel bir uzay şirketidir.</p>
        <div class="grid md:grid-cols-2 gap-4 mt-4">
          <div class="p-4 bg-black bg-opacity-30 rounded-xl border-l-4 border-cyan-400">
            <h3 class="text-xl font-bold">Starship</h3>
            <p>Mars için geliştirilen tam yeniden kullanılabilir roket.</p>
          </div>
          <div class="p-4 bg-black bg-opacity-30 rounded-xl border-l-4 border-cyan-400">
            <h3 class="text-xl font-bold">Falcon 9</h3>
            <p>Yörüngede görev yapan çok kullanımlı roket.</p>
          </div>
        </div>
      </section>

      <!-- NASA -->
      <section class="glass p-6 rounded-2xl my-6">
        <h2 class="text-3xl orbitron text-yellow-400">🛰️ NASA</h2>
        <img class="w-full rounded-xl my-4" src="https://www.nasa.gov/sites/default/files/thumbnails/image/artemis1_slslaunch.jpg" alt="NASA" />
        <p>NASA, ABD'nin uzay ajansıdır. Ay ve Mars görevleri, teleskop projeleri ve uluslararası iş birlikleri yürütür.</p>
        <div class="grid md:grid-cols-2 gap-4 mt-4">
          <div class="p-4 bg-black bg-opacity-30 rounded-xl border-l-4 border-cyan-400">
            <h3 class="text-xl font-bold">Artemis</h3>
            <p>Ay'a geri dönüş görevi.</p>
          </div>
          <div class="p-4 bg-black bg-opacity-30 rounded-xl border-l-4 border-cyan-400">
            <h3 class="text-xl font-bold">James Webb</h3>
            <p>Evrenin en uzak noktalarını gözlemliyor.</p>
          </div>
        </div>
      </section>

      <!-- ESA -->
      <section class="glass p-6 rounded-2xl my-6">
        <h2 class="text-3xl orbitron text-yellow-400">🇪🇺 ESA</h2>
        <img class="w-full rounded-xl my-4" src="https://www.esa.int/var/esa/storage/images/esa_multimedia/images/2023/03/ariane_6_in_final_stages_of_preparations/24735509-1-eng-GB/Ariane_6_in_final_stages_of_preparations_pillars.jpg" alt="ESA" />
        <p>ESA, Avrupa Uzay Ajansı’dır. Çok uluslu uzay projeleri ve bilimsel araştırmalar yürütür.</p>
        <div class="p-4 bg-black bg-opacity-30 rounded-xl border-l-4 border-cyan-400 mt-4">
          <h3 class="text-xl font-bold">ExoMars</h3>
          <p>Mars’ta yaşam izlerini araştırıyor.</p>
        </div>
      </section>

      <!-- TUA -->
      <section class="glass p-6 rounded-2xl my-6">
        <h2 class="text-3xl orbitron text-yellow-400">🇹🇷 TUA</h2>
        <img class="w-full rounded-xl my-4" src="https://www.tua.gov.tr/uploads/2021/02/ay-mission.jpg" alt="TUA" />
        <p>Türkiye Uzay Ajansı, milli uzay programını yöneten devlete bağlı kuruluştur. Ay görevleri ve uydu projeleri yürütmektedir.</p>
        <div class="p-4 bg-black bg-opacity-30 rounded-xl border-l-4 border-cyan-400 mt-4">
          <h3 class="text-xl font-bold">Milli Uzay Programı</h3>
          <p>2028'e kadar Ay’a iniş hedefi.</p>
        </div>
      </section>
    </main>

    <footer class="text-center py-6 text-sm text-gray-400 bg-black bg-opacity-70">
      GörevMars © 2025 | Uzay Ajanslarının Geleceği Burada Yazılıyor
    </footer>
  </body>
</html>
