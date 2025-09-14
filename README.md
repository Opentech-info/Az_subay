<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Lipataka | Coming Soon</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
  <script src="https://cdn.tailwindcss.com"></script>
  <script src="https://unpkg.com/@lottiefiles/lottie-player@latest/dist/lottie-player.js"></script>
</head>
<body class="bg-gradient-to-br from-indigo-500 via-purple-500 to-pink-500 min-h-screen flex flex-col items-center justify-center text-white font-[Poppins] p-6">

  <!-- Logo / Title -->
  <div class="text-center space-y-6">
    <h1 class="text-4xl md:text-6xl font-extrabold drop-shadow-lg animate-bounce">
      🚀 Lipataka
    </h1>
    <h2 class="text-xl md:text-2xl font-semibold tracking-wide">
      A Cool Project is Coming Soon...
    </h2>
  </div>

  <!-- Cartoon / Animation -->
  <div class="my-10">
    <lottie-player 
      src="https://assets1.lottiefiles.com/packages/lf20_t24tpvcu.json"  
      background="transparent"  
      speed="1"  
      style="width: 300px; height: 300px;"  
      loop  
      autoplay>
    </lottie-player>
  </div>

  <!-- Description -->
  <p class="text-lg md:text-xl text-center max-w-2xl leading-relaxed">
    We’re cooking up something amazing at <span class="font-bold">Lipataka.com</span>.  
    Stay tuned for a fresh digital experience packed with powerful features, 
    clean design, and awesome vibes 🌟
  </p>

  <!-- Progress / Status -->
  <div class="w-full max-w-lg bg-white/10 rounded-2xl mt-10 p-6 backdrop-blur-lg shadow-lg">
    <div class="flex justify-between mb-2">
      <span class="text-sm font-semibold">Development Progress</span>
      <span class="text-sm">70%</span>
    </div>
    <div class="w-full bg-white/20 rounded-full h-3">
      <div class="bg-green-400 h-3 rounded-full animate-pulse" style="width: 70%"></div>
    </div>
  </div>

  <!-- Social / Contact -->
  <div class="flex space-x-6 mt-10">
    <a href="https://github.com/yourusername" target="_blank" class="hover:scale-110 transition transform">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" class="w-8 h-8" />
    </a>
    <a href="mailto:contact@lipataka.com" class="hover:scale-110 transition transform">
      <svg xmlns="http://www.w3.org/2000/svg" class="w-8 h-8" fill="white" viewBox="0 0 24 24"><path d="M12 13.065 1.5 6h21L12 13.065zm0 2.11L1.5 8.106V18h21V8.106L12 15.175z"/></svg>
    </a>
  </div>

  <!-- Footer -->
  <footer class="mt-16 text-sm text-white/70">
    © <span id="year"></span> Lipataka. All Rights Reserved.
  </footer>

  <script>
    document.getElementById("year").innerText = new Date().getFullYear();
  </script>
</body>
</html>
