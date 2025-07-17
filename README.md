<!DOCTYPE html>
<html lang="en" data-theme="dark">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Animated Portfolio</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet" /><link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    [data-theme='light'] {
      --tw-bg-opacity: 1;
      background-color: #ffffff;
      color: #000000;
    }
    [data-theme='dark'] {
      background-color: #111827;
      color: #ffffff;
    }
  </style>
</head>
<body class="transition duration-300">

  <!-- ✅ Navbar with Toggle -->
  <nav class="bg-gray-900 px-6 py-4 flex items-center justify-between sticky top-0 z-50 shadow">
  <div class="text-2xl font-bold text-red-400">MyPortfolio</div>
  
  <!-- Desktop Menu -->
<ul class="hidden md:flex space-x-6 text-gray-300 font-medium">
  <li><a href="#home" class="hover:text-red-300">Home</a></li>
  <li><a href="#about" class="hover:text-red-300">About</a></li>
  <li><a href="#skills" class="hover:text-red-300">Skills</a></li>
  <li><a href="#portfolio" class="hover:text-red-300">Portfolio</a></li>
  <li><a href="#services" class="hover:text-red-300">Services</a></li>
  <li><a href="#testimonials" class="hover:text-red-300">Review</a></li>
  <li><a href="#contact" class="hover:text-red-300">Contact</a></li>
</ul>


  <!-- Mobile Hamburger -->
  <div class="md:hidden text-3xl text-red-400 cursor-pointer" onclick="toggleMenu()" id="menuIcon">☰</div>
</nav>

<!-- Mobile Menu -->
<div id="mobileMenu" class="hidden flex flex-col bg-gray-900 text-center text-gray-300 space-y-4 py-6 md:hidden">
  <a href="#home" class="hover:text-red-400">Home</a>
  <a href="#about" class="hover:text-red-400">About</a>
  <a href="#skills" class="hover:text-red-400">Skills</a>
  <a href="#portfolio" class="hover:text-red-400">Portfolio</a>
  <a href="#services" class="hover:text-red-400">Services</a>
  <a href="#testimonials" class="hover:text-red-400">Review</a>
  <a href="#contact" class="hover:text-red-400">Contact</a>
</div>

</script>
  <!-- ✅ Hero -->
  <section id="home" class="flex flex-col lg:flex-row items-center justify-between px-8 py-20 bg-gradient-to-r from-black to-red-600 ">

    <div class="lg:w-1/2 text-center lg:text-left mb-12 lg:mb-0" data-aos="fade-right">
      <h1 class="text-4xl md:text-5xl font-bold   text-white">Build Your <span class="text-red-400">Professional Website</span></h1>
      <p class="text-lg text-gray-300 mb-4">Clean, responsive, and creative websites for your brand.</p>
      <a href="#contact" class="px-6 py-3 bg-red-500 hover:bg-red-600 rounded-lg shadow font-semibold transition">💼 Hire Me</a>
    </div>
    <div class="lg:w-1/2 flex justify-center" data-aos="fade-left">
      <img src="img/19.jpg" class="w-72 h-auto rounded-2xl border-4 border-red-400 shadow-xl mt-5"/>
}
    </div>
  </section>

  <!-- ✅ About Section -->
  <section id="about" class="bg-gray-900 py-20 px-6">
    <div class="max-w-6xl mx-auto flex flex-col-reverse lg:flex-row items-center gap-10" data-aos="fade-up">
      <div class="lg:w-1/2 text-center lg:text-left">
        <h2 class="text-3xl md:text-4xl font-bold text-red-400 mb-4">About Me</h2>
        <p class="text-gray-300 mb-4">
          I’m a passionate web designer with a love for creating stunning and user-friendly websites using modern tools like <span class="text-white font-semibold">Tailwind CSS</span>, <span class="text-white font-semibold">JavaScript</span>, and responsive design techniques.
        </p>
        <p class="text-gray-400">
          My goal is to help brands stand out by building websites that are fast, functional, and visually engaging. I'm always learning and exploring new design trends to stay ahead of the curve.
        </p>
      </div>
      <div class="lg:w-1/2 relative w-full">
        <img src="img/16.jpg" alt="About Image" class="w-full rounded-2xl shadow-lg border-4 border-red-500">
        <div class="absolute inset-0 bg-black opacity-20 rounded-2xl pointer-events-none"></div>
      </div>
    </div>
  </section>

<section id="skills" class="bg-gray-900 py-20 px-6 relative ">
     <h2 class="text-4xl md:text-5xl font-bold text-red-400 text-center mb-12 absolute left-1/2 transform -translate-x-1/2 -translate-y-1/2 top-0">
    My Skills
      </h2>
  
  <div class="max-w-6xl mx-auto flex flex-col lg:flex-row items-center justify-center gap-12 mt-16" data-aos="fade-up"> 

    
    <!-- Skills List -->
    <div class="lg:w-1/2 w-full space-y-6">
      <div class="flex items-center gap-4">
        <img src="img/23.jpg" alt="HTML" class="w-10 h-10">
        <div class="w-full">
          <div class="flex justify-between mb-1 text-sm">
            <span class="text-gray-300">HTML</span>
            <span class="text-gray-300">95%</span>
          </div>
          <div class="w-full bg-gray-700 rounded-full h-4">
            <div class="bg-red-500 h-4 rounded-full" style="width: 95%;"></div>
          </div>
        </div>
      </div>
      <div class="flex items-center gap-4">
        <img src="img/css.png" alt="CSS" class="w-10 h-10">
        <div class="w-full">
          <div class="flex justify-between mb-1 text-sm">
            <span class="text-gray-300">CSS</span>
            <span class="text-gray-300">90%</span>
          </div>
          <div class="w-full bg-gray-700 rounded-full h-4">
            <div class="bg-red-500 h-4 rounded-full" style="width: 90%;"></div>
          </div>
        </div>
      </div>
      <div class="flex items-center gap-4">
        <img src="img/word.jpg" alt="Tailwind CSS" class="w-10 h-10">
        <div class="w-full">
          <div class="flex justify-between mb-1 text-sm">
            <span class="text-gray-300">wordpress</span>
            <span class="text-gray-300">85%</span>
          </div>
          <div class="w-full bg-gray-700 rounded-full h-4">
            <div class="bg-red-500 h-4 rounded-full" style="width: 85%;"></div>
          </div>
        </div>
      </div>
      <div class="flex items-center gap-4">
        <img src="img/js.png" alt="JavaScript" class="w-10 h-10">
        <div class="w-full">
          <div class="flex justify-between mb-1 text-sm">
            <span class="text-gray-300">JavaScript</span>
            <span class="text-gray-300">70%</span>
          </div>
          <div class="w-full bg-gray-700 rounded-full h-4">
            <div class="bg-red-500 h-4 rounded-full" style="width: 70%;"></div>
          </div>
        </div>
      </div>
      <div class="flex items-center gap-4">
        <img src="img/jq.png" alt="jQuery" class="w-10 h-10">
        <div class="w-full">
          <div class="flex justify-between mb-1 text-sm">
            <span class="text-gray-300">jQuery</span>
            <span class="text-gray-300">65%</span>
          </div>
          <div class="w-full bg-gray-700 rounded-full h-4">
            <div class="bg-red-500 h-4 rounded-full" style="width: 65%;"></div>
          </div>
        </div>
      </div>
    </div>

    <!-- Image -->
    <div class="lg:w-1/2 w-full flex justify-center" data-aos="fade-left">
      <img src="img/26.jpg" alt="Skills Image" class="rounded-2xl shadow-lg border-4 border-red-500 w-full max-w-xs lg:max-w-sm">
    </div>
  </div>
</section>


<!-- ✅ Portfolio Section -->
<section id="portfolio" class="bg-gray-900 py-20 px-6">
  <div class="max-w-6xl mx-auto" data-aos="zoom-in">
    <h2 class="text-4xl md:text-5xl font-bold text-red-400 text-center mb-12">My Portfolio</h2>
    <div class="grid gap-6 md:grid-cols-2 lg:grid-cols-4">
      <!-- Project 1 -->
      <div class="bg-gray-800 rounded-xl overflow-hidden shadow-lg hover:shadow-xl transition-all">
        <img src="img/28.png" alt="Project 1" class="w-full h-48 object-cover cursor-pointer w-full transform transition duration-300 hover:scale-105" onclick="openProject('https://www.facebook.com/twoinsoft.training')">
        <div class="p-4">
          <h3 class="text-white text-lg font-semibold mb-2">E-commerce Website</h3>
          <p class="text-gray-400 text-sm">Responsive shopping site with product filtering & cart features.</p>
        </div>
      </div>

      <!-- Project 2 -->
      <div class="bg-gray-800 rounded-xl overflow-hidden shadow-lg hover:shadow-xl transition-all">
        <img src="img/27.jpg" alt="Project 2" class="w-full h-48 object-cover cursor-pointer w-full transform transition duration-300 hover:scale-105" onclick="openProject('https://example.com/project2')">
        <div class="p-4">
          <h3 class="text-white text-lg font-semibold mb-2">Restaurant Website</h3>
          <p class="text-gray-400 text-sm">Interactive food menu, booking table system, and photo gallery.</p>
        </div>
      </div>

      <!-- Project 3 -->
      <div class="bg-gray-800 rounded-xl overflow-hidden shadow-lg hover:shadow-xl transition-all">
        <img src="img/30.jpg" alt="Project 3" class="w-full h-48 object-cover cursor-pointer w-full transform transition duration-300 hover:scale-105" onclick="openProject('https://example.com/project3')">
        <div class="p-4">
          <h3 class="text-white text-lg font-semibold mb-2">Portfolio Website</h3>
          <p class="text-gray-400 text-sm">Personal branding, dark/light mode switch, smooth animations.</p>
        </div>
      </div>

      <!-- Project 4 -->
      <div class="bg-gray-800 rounded-xl overflow-hidden shadow-lg hover:shadow-xl transition-all">
        <img src="img/29.jpg" alt="Project 4" class="w-full h-48 object-cover cursor-pointer w-full transform transition duration-300 hover:scale-105" onclick="openProject('https://example.com/project4')">
        <div class="p-4">
          <h3 class="text-white text-lg font-semibold mb-2">Landing Page</h3>
          <p class="text-gray-400 text-sm">Modern and clean landing page with high conversion design.</p>
        </div>
      </div>
    </div>
  </div>
</section>

<section id="services" class="bg-gradient-to-r from-gray-900 via-black to-gray-900 py-20 px-6 overflow-hidden">
  <div class="max-w-6xl mx-auto text-center" data-aos="fade-up">
    <h2 class="text-4xl md:text-5xl font-bold text-red-400 mb-10">service</h2>
    <p class="text-gray-300 max-w-3xl mx-auto mb-16 text-lg">As a passionate web designer, I provide sleek, modern, and fully responsive websites tailored to your needs. With clean UI, smooth UX, and performance in mind — I make your ideas come alive on the web.</p>

    <div class="relative flex flex-col lg:flex-row flex-wrap justify-center items-center gap-12">
      <div class="bg-gray-800/30 backdrop-blur-lg border border-gray-600 p-8 rounded-3xl shadow-lg hover:shadow-2xl hover:scale-105 transition-all duration-300 w-full lg:w-1/3" data-aos="zoom-in-up">
        <h3 class="text-white text-xl font-semibold mb-3">💻 Website Design</h3>
        <p class="text-gray-400">Modern, user-focused designs using HTML, Tailwind CSS & responsive layout techniques.</p>
      </div>

      <div class="bg-gray-800/30 backdrop-blur-lg border border-gray-600 p-8 rounded-3xl shadow-lg hover:shadow-2xl hover:scale-105 transition-all duration-300 w-full lg:w-1/3" data-aos="zoom-in-up" data-aos-delay="100">
        <h3 class="text-white text-xl font-semibold mb-3">⚙️ Custom Features</h3>
        <p class="text-gray-400">Interactive elements, animations, sliders, forms — all tailored to your project goals.</p>
      </div>

      <div class="bg-gray-800/30 backdrop-blur-lg border border-gray-600 p-8 rounded-3xl shadow-lg hover:shadow-2xl hover:scale-105 transition-all duration-300 w-full lg:w-1/3" data-aos="zoom-in-up" data-aos-delay="200">
        <h3 class="text-white text-xl font-semibold mb-3">📱 Responsive Design</h3>
        <p class="text-gray-400">Pixel-perfect rendering across mobile, tablet, and desktop with performance optimization.</p>
      </div>

      <div class="bg-gray-800/30 backdrop-blur-lg border border-gray-600 p-8 rounded-3xl shadow-lg hover:shadow-2xl hover:scale-105 transition-all duration-300 w-full lg:w-1/3" data-aos="zoom-in-up" data-aos-delay="300">
        <h3 class="text-white text-xl font-semibold mb-3">🔍 SEO Optimization</h3>
        <p class="text-gray-400">Basic on-page SEO so your site is friendly for Google & loads lightning fast.</p>
      </div>

      <div class="bg-gray-800/30 backdrop-blur-lg border border-gray-600 p-8 rounded-3xl shadow-lg hover:shadow-2xl hover:scale-105 transition-all duration-300 w-full lg:w-1/3" data-aos="zoom-in-up" data-aos-delay="400">
        <h3 class="text-white text-xl font-semibold mb-3">🛠 Maintenance & Support</h3>
        <p class="text-gray-400">Need small tweaks or bug fixes later? I provide hassle-free ongoing support.</p>
      </div>

      <div class="bg-gray-800/30 backdrop-blur-lg border border-gray-600 p-8 rounded-3xl shadow-lg hover:shadow-2xl hover:scale-105 transition-all duration-300 w-full lg:w-1/3" data-aos="zoom-in-up" data-aos-delay="500">
        <h3 class="text-white text-xl font-semibold mb-3">🚀 Speed Optimization</h3>
        <p class="text-gray-400">Optimized assets and lazy loading to make sure your site is blazing fast.</p>

      </div>
    </div>
  </div><button onclick="window.scrollTo({top:0,behavior:'smooth'})" 
  class="fixed bottom-6 right-6 p-4 rounded-full bg-red-500 hover:bg-red-600 text-white shadow-lg">
  ↑
</button>
</section>

<section id="testimonials" class="bg-gray-900 py-20 px-6">
  <div class="max-w-6xl mx-auto text-center" data-aos="fade-up">
    <h2 class="text-4xl md:text-5xl font-bold text-red-400 mb-10">Review</h2>
    <div class="flex flex-col lg:flex-row gap-8 items-center justify-center">

      <div class="bg-gray-800/30 backdrop-blur-lg border-l-4 border-red-500 p-8 rounded-3xl shadow-lg hover:scale-105 transition-all duration-300 w-full lg:w-1/3" data-aos="fade-right">
        <img src="img/32.jpg" alt="Client 1" class="w-16 h-16 mx-auto rounded-full border-2 border-red-500 mb-4 object-cover">
        <div class="flex justify-center mb-4">
          <span class="text-yellow-400">★★★★★</span>
        </div>
        <p class="text-gray-300 italic mb-4">“Absolutely thrilled with my new website. It’s fast, stylish, and exactly what my brand needed.”</p>
        <h4 class="text-white font-semibold">Sarah Ali</h4>
        <p class="text-gray-400 text-sm">Founder, ShopX</p>
      </div>

      <div class="bg-gray-800/30 backdrop-blur-lg border-l-4 border-red-500 p-8 rounded-3xl shadow-lg hover:scale-105 transition-all duration-300 w-full lg:w-1/3" data-aos="fade-up" data-aos-delay="100">
        <img src="img/31.jpg" alt="Client 2" class="w-16 h-16 mx-auto rounded-full border-2 border-red-500 mb-4 object-cover">
        <div class="flex justify-center mb-4">
          <span class="text-yellow-400">★★★★☆</span>
        </div>
        <p class="text-gray-300 italic mb-4">“Delivered above expectations! Great sense of design and very professional.”</p>
        <h4 class="text-white font-semibold">Michael Tanvir</h4>
        <p class="text-gray-400 text-sm">CEO, DevLabs</p>
      </div>

      <div class="bg-gray-800/30 backdrop-blur-lg border-l-4 border-red-500 p-8 rounded-3xl shadow-lg hover:scale-105 transition-all duration-300 w-full lg:w-1/3" data-aos="fade-left" data-aos-delay="200">
        <img src="img/33.jpg" alt="Client 3" class="w-16 h-16 mx-auto rounded-full border-2 border-red-500 mb-4 object-cover">
        <div class="flex justify-center mb-4">
          <span class="text-yellow-400">★★★★★</span>
        </div>
        <p class="text-gray-300 italic mb-4">“Quick, efficient, and exactly what I envisioned. Highly recommend.”</p>
        <h4 class="text-white font-semibold">Jasmine Rahman</h4>
        <p class="text-gray-400 text-sm">Freelance Writer</p>
      </div>

    </div>
  </div>
</section>

  
  <!-- ✅ Contact Section -->
  <section id="contact" class="bg-gray-900 py-20 px-6">
    <div class="max-w-6xl mx-auto grid grid-cols-1 md:grid-cols-2 gap-10 items-center" data-aos="fade-up">
      <div class="w-full h-full">
        <h3 class="text-2xl font-semibold text-red-400 mb-4">My Location</h3>
        <div class="rounded-lg overflow-hidden shadow-lg border-4 border-red-500">
          <iframe src="https://www.google.com/maps/embed?...your-map..." width="100%" height="300" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
        </div>
      </div>
      <div>
        <h3 class="text-2xl font-semibold text-red-400 mb-4">Contact Me</h3>
        <form class="space-y-4">
          <input type="text" placeholder="Your Name" class="w-full px-4 py-3 bg-gray-900 border border-gray-700 rounded" />
          <input type="email" placeholder="Your Email" class="w-full px-4 py-3 bg-gray-900 border border-gray-700 rounded" />
          <textarea rows="4" placeholder="Your Message" class="w-full px-4 py-3 bg-gray-900 border border-gray-700 rounded"></textarea>
          <button type="submit" class="px-6 py-3 bg-red-500 hover:bg-red-600 rounded-lg font-semibold text-white">📩 Send Message</button>
        </form>
      </div>
    </div>
  </section>

<footer class="relative bg-gray-900 py-8 px-4 overflow-hidden">
  <!-- floating circles -->
  <div class="absolute -top-10 left-1/4 w-32 h-32 bg-red-500/10 rounded-full blur-2xl animate-ping"></div>
  <div class="absolute -bottom-10 right-1/3 w-24 h-24 bg-red-500/10 rounded-full blur-2xl animate-ping animation-delay-2000"></div>

  <!-- content -->
  <div class="relative max-w-6xl mx-auto text-center space-y-4 z-10">
    <h2 class="text-2xl font-semibold text-white">ready to start your journey?</h2>
    <p class="text-gray-400 max-w-2xl mx-auto text-sm">i design experiences that make life simple. let’s work together and make your ideas stand out.</p>

    <div class="flex justify-center space-x-6 mt-6">
      <a href="#" class="text-gray-400 hover:text-red-400 transition duration-300 hover:scale-105 text-sm">facebook</a>
      <a href="#" class="text-gray-400 hover:text-red-400 transition duration-300 hover:scale-105 text-sm">instagram</a>
      <a href="#" class="text-gray-400 hover:text-red-400 transition duration-300 hover:scale-105 text-sm">github</a>
    </div>

    <p class="text-gray-500 text-xs mt-6">© 2025 mywebdesign. crafted with ❤️</p>
  </div>
</footer>




  <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
  <script>
  function openProject(url) {
    window.open(url, '_blank');
  }
</script>
<script>
    AOS.init();
    function toggleMenu() {
      const menu = document.getElementById('mobileMenu');
      menu.classList.toggle('hidden');
    }
    function toggleTheme() {
      const html = document.documentElement;
      const current = html.getAttribute('data-theme');
      html.setAttribute('data-theme', current === 'dark' ? 'light' : 'dark');
    }
  </script>

  <script>
  function openProject(url) {
    window.open(url, '_blank');
  }
</script>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>
