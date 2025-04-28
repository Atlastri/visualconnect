<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>VisualConnect - Conecta tu proyecto con el talento adecuado</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
  <style>
    body { background-color: #f9f8ff; font-family: 'Poppins', sans-serif; }
    .fade-in { opacity: 0; transform: translateY(20px); transition: opacity 0.8s ease-out, transform 0.8s ease-out; }
    .fade-in.visible { opacity: 1; transform: translateY(0); }
  </style>
</head>
<body class="text-gray-800">
  <header class="flex justify-between items-center py-6 px-4 bg-white shadow-md">
    <div class="flex items-center space-x-2">
      <!-- Logo SVG incrustado -->
      <svg width="40" height="40" viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
        <circle cx="50" cy="50" r="45" fill="#7C3AED"/>
        <!-- Ojo (visión) -->
        <ellipse cx="50" cy="40" rx="18" ry="10" fill="#34D399"/>
        <circle cx="50" cy="40" r="4" fill="#7C3AED"/>
        <!-- Cámara (conexión audiovisual) -->
        <rect x="30" y="65" width="40" height="20" rx="3" ry="3" fill="#34D399"/>
        <circle cx="50" cy="75" r="5" fill="#7C3AED"/>
      </svg>
      <span class="text-2xl font-bold text-purple-800">VisualConnect</span>
    </div>
    <nav class="flex space-x-6 text-sm">
      <a href="#inicio" class="hover:text-purple-700">Inicio</a>
      <a href="#como" class="hover:text-purple-700">Cómo funciona</a>
      <a href="#publicar" class="hover:text-purple-700">Publicar Proyecto</a>
      <a href="#contacto" class="hover:text-purple-700">Contacto</a>
    </nav>
  </header>

  <!-- ... resto del código queda igual ... -->
