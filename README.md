<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-100 text-gray-900 font-sans">
  <!-- Header -->
  <header class="bg-white shadow-md p-6">
    <h1 class="text-3xl font-bold">Harshit's Portfolio</h1>
    <p class="text-gray-600">Motion Graphic Designer | 2D and 3D Animator</p>
  </header>

  <!-- Projects Section -->
  <main class="max-w-5xl mx-auto p-6">
    <h2 class="text-2xl font-semibold mb-4">My Work</h2>
    <div class="grid grid-cols-1 md:grid-cols-2 gap-6">

      <!-- Project Card Example -->
      <div class="bg-white rounded-2xl shadow-md p-4">
        <h3 class="text-xl font-bold">Project 1: Showreel</h3>
        <video controls class="rounded-lg w-full mt-2">
          <source src="videos/showreel.mp4" type="video/mp4">
        </video>
        <p class="mt-2 text-gray-700">Short showreel of my animation works.</p>
      </div>

      <div class="bg-white rounded-2xl shadow-md p-4">
        <h3 class="text-xl font-bold">Project 2: Motion Graphic</h3>
        <img src="images/motion-thumb.gif" alt="Motion Graphic" class="rounded-lg w-full mt-2">
        <p class="mt-2 text-gray-700">Explainer video style motion graphics.</p>
      </div>

      <!-- Add more project cards here -->

    </div>
  </main>

  <!-- Footer -->
  <footer class="bg-gray-900 text-white text-center p-4 mt-8">
    <p>© 2025 My Portfolio | Connect on 
      <a href="https://mail.google.com/mail/?view=cm&fs=1&to=soniharshit934@gmail.com" class="underline">Gmail</a>
    </p>
  </footer>
</body>
</html>
