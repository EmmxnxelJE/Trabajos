<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Mi CV-Emmanuel Juárez Esquivel</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
  <style>
    body { font-family: 'Poppins', sans-serif; }
    .gradient-bg {
      background: linear-gradient(135deg, #2563eb, #9333ea);
    }
  </style>
</head>
<body class="bg-gray-100 text-gray-900">

  <!-- HEADER -->
  <header class="gradient-bg text-white py-12">
    <div class="max-w-5xl mx-auto px-6 text-center">
      <img src="yo.jpg" alt="Foto recreativa jeje" class="mx-auto rounded-full w-32 h-32 border-4 border-white shadow-lg object-cover object-center">
      <h1 class="text-4xl font-bold mt-4">Emmanuel Juárez Esquivel</h1>
      <p class="text-lg opacity-90">Desarrollador de Software | Creativo | Apasionado por la tecnología</p>
      <div class="mt-4 space-x-4">
        <a href="https://www.linkedin.com/in/emmanuel-juárez-esquivel-3374b013a" class="underline">LinkedIn</a>
        <a href="https://github.com/EmmxnxelJE" class="underline">GitHub</a>
        <a href="Cv-EmmanuelJuárezEsquivel.pdf" class="underline">Cv</a>
      </div>
    </div>
  </header>

  <!-- CONTENIDO PRINCIPAL -->
  <main class="max-w-5xl mx-auto px-6 py-12 grid md:grid-cols-3 gap-10">

    <!-- SECCIÓN LATERAL -->
    <aside class="md:col-span-1 space-y-6">
      <section class="bg-white p-6 rounded-2xl shadow">
        <h2 class="text-xl font-bold mb-3">Contacto</h2>
        <ul class="text-sm space-y-2">
          <li>📍 Ecatepec, México</li>
          <li>📧 emmanueljuareze@gmail.com</li>
          <li>📞 +52 55 8767 8636</li>
        </ul>
      </section>

      <section class="bg-white p-6 rounded-2xl shadow">
        <h2 class="text-xl font-bold mb-3">Habilidades</h2>
        <div class="space-y-2 text-sm">
          <p>💻 C / C++ / Python</p>
          <p>🌐 HTML / CSS / JavaScript</p>
          <p>⚙️ Sistemas Operativos</p>
          <p>🤖 Inteligencia Artificial</p>
        </div>
      </section>

      <section class="bg-white p-6 rounded-2xl shadow">
        <h2 class="text-xl font-bold mb-3">Idiomas</h2>
        <p>🇪🇸 Español (Nativo)</p>
        <p>🇺🇸 Inglés (A1)</p>
      </section>
    </aside>

    <!-- SECCIÓN PRINCIPAL -->
    <section class="md:col-span-2 space-y-8">
      <div class="bg-white p-8 rounded-2xl shadow">
        <h2 class="text-2xl font-bold mb-4 border-b-2 border-indigo-500 inline-block">Perfil</h2>
        <p class="text-gray-700">
          Soy un estudiante de Sistemas Computacionales con pasión por el desarrollo de software, 
          la optimización de sistemas y la creación de soluciones innovadoras. 
          Busco aplicar mis conocimientos en proyectos que impulsen la eficiencia y la creatividad tecnológica.
        </p>
      </div>

      <div class="bg-white p-8 rounded-2xl shadow">
        <h2 class="text-2xl font-bold mb-4 border-b-2 border-indigo-500 inline-block">Experiencia</h2>
        <div class="space-y-4">
          <div>
            <h3 class="font-semibold">Cajero – Tiendas 3B S.A de C.V</h3>
            <p class="text-sm text-gray-500">Abril/2025 - Actualidad</p>
            <ul class="list-disc list-inside text-gray-700 mt-2 text-sm">
              <li>Atencion a clientes</li>
              <li>Manejo de inventario</li>
            </ul>
          </div>
        </div>
        <br>
        <div class="space-y-4">
          <div>
            <h3 class="font-semibold">Mesero – El Totopo Corporeichon</h3>
            <p class="text-sm text-gray-500">Marzo/2024 - Febrero/2025</p>
            <ul class="list-disc list-inside text-gray-700 mt-2 text-sm">
              <li>Atencion a clientes</li>
              <li>Manejo de inventario</li>
            </ul>
          </div>
        </div>
      </div>

      <div class="bg-white p-8 rounded-2xl shadow">
        <h2 class="text-2xl font-bold mb-4 border-b-2 border-indigo-500 inline-block">Educación</h2>
        <div class="space-y-4">
          <div>
            <h3 class="font-semibold">Ingeniería en Sistemas Computacionales</h3>
            <p class="text-sm text-gray-500">Instituto Politecnico Nacional (ESCOM) / 2022 - Actualidad</p>
          </div>
        </div>
      </div>
    </section>
  </main>

  <!-- FOOTER -->
  <footer class="text-center text-gray-500 py-8 text-sm">
    © 2025 Emmanuel Juárez Esquivel. Todos los derechos reservados.
  </footer>

</body>
</html>

