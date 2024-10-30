<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Talha Ahmer - Full Stack Web Developer</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/tailwindcss/2.2.19/tailwind.min.css">
  <style>
    /* Add custom styles here */
    .main-header {
      background-image: url('https://source.unsplash.com/random/1600x900?technology');
      background-size: cover;
      background-position: center;
      padding: 80px 0;
    }
    .social-icons a {
      margin: 0 10px;
      transition: transform 0.3s;
    }
    .social-icons a:hover {
      transform: scale(1.1);
    }
  </style>
</head>
<body class="bg-gray-900 text-gray-300">

  <!-- Header Section -->
  <header class="main-header text-center text-white">
    <h1 class="text-4xl font-bold mb-2">Talha Ahmer</h1>
    <h2 class="text-2xl font-semibold">Full Stack Web Developer from Pakistan</h2>
    <p class="mt-4">Passionate about coding and building responsive, dynamic web applications.</p>
    <div class="social-icons mt-6">
      <a href="https://www.linkedin.com/in/talha-ahmer-488063306/" target="_blank"><i class="fab fa-linkedin fa-2x"></i></a>
      <a href="https://x.com/talha_ahmer" target="_blank"><i class="fab fa-twitter fa-2x"></i></a>
      <a href="https://mail.google.com/mail/u/0/#inbox" target="_blank"><i class="fas fa-envelope fa-2x"></i></a>
      <a href="https://www.instagram.com/talha_8303/" target="_blank"><i class="fab fa-instagram fa-2x"></i></a>
      <a href="https://www.facebook.com/talhaahmer.17" target="_blank"><i class="fab fa-facebook fa-2x"></i></a>
      <a href="https://stackoverflow.com/users/25674080/talha-ahmer" target="_blank"><i class="fab fa-stack-overflow fa-2x"></i></a>
    </div>
  </header>

  <!-- About Section -->
  <section class="py-12 px-6">
    <div class="max-w-4xl mx-auto text-center">
      <h3 class="text-3xl font-semibold mb-4">About Me</h3>
      <p class="text-lg leading-relaxed">I'm a Full Stack Web Developer with a strong focus on creating user-friendly and responsive websites. My expertise includes HTML, CSS, JavaScript, Bootstrap, PHP, MySQL, and more. I am currently working on my project, <strong>Bubble & Bauble</strong>, while continually expanding my knowledge in PHP, Tailwind, and MySQL.</p>
    </div>
  </section>

  <!-- Skills Section -->
  <section class="bg-gray-800 py-12 px-6">
    <div class="max-w-4xl mx-auto text-center">
      <h3 class="text-3xl font-semibold mb-8 text-white">Skills & Technologies</h3>
      <div class="flex flex-wrap justify-center space-x-4 space-y-4">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" height="50" alt="HTML5 logo">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" height="50" alt="CSS3 logo">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="50" alt="JavaScript logo">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jquery/jquery-original.svg" height="50" alt="jQuery logo">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg" height="50" alt="Bootstrap logo">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg" height="50" alt="PHP logo">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" height="50" alt="MySQL logo">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-plain.svg" height="50" alt="Tailwind CSS logo">
        <img src="https://skillicons.dev/icons?i=postman" height="50" alt="Postman logo">
      </div>
    </div>
  </section>

  <!-- Projects Section -->
  <section class="py-12 px-6">
    <div class="max-w-4xl mx-auto">
      <h3 class="text-3xl font-semibold mb-8 text-center">Projects</h3>
      <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
        <!-- Example Project Card -->
        <div class="bg-gray-800 p-6 rounded-lg shadow-lg">
          <h4 class="text-xl font-semibold mb-2">Bubble & Bauble</h4>
          <p class="text-gray-400">A project aimed at ... (brief project description)</p>
          <a href="https://github.com/talhaahmer" class="text-blue-400 hover:underline mt-4 inline-block">View Project on GitHub</a>
        </div>
      </div>
    </div>
  </section>

  <!-- GitHub Stats Section -->
  <section class="bg-gray-800 py-12 px-6">
    <div class="max-w-4xl mx-auto text-center">
      <h3 class="text-3xl font-semibold mb-8 text-white">GitHub Stats</h3>
      <div class="flex justify-center space-x-6">
        <img src="https://github-readme-stats.vercel.app/api?username=talhaahmer&show_icons=true&theme=dracula" class="w-1/2" alt="GitHub stats">
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=talhaahmer&layout=compact&theme=dracula" class="w-1/2" alt="Top Languages">
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section class="py-12 px-6">
    <div class="max-w-4xl mx-auto text-center">
      <h3 class="text-3xl font-semibold mb-8">Get in Touch</h3>
      <p>If you'd like to discuss a project or just say hi, feel free to reach out!</p>
      <a href="mailto:talhaahmer125@gmail.com" class="mt-4 inline-block bg-blue-600 text-white px-6 py-3 rounded-lg shadow-lg hover:bg-blue-700">Contact Me</a>
    </div>
  </section>

  <!-- Footer Section -->
  <footer class="py-4 bg-gray-900 text-center text-gray-500">
    <p>&copy; 2024 Talha Ahmer. All rights reserved.</p>
  </footer>

</body>
</html>
