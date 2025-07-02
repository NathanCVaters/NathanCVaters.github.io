<!doctype html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Complete Restoration | Home & Commercial Remodeling</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      darkMode: 'class',
      theme: {
        extend: {
          colors: {
            primary: '#3b82f6',
            secondary: '#10b981',
            accent: '#f59e0b',
            dark: '#1e293b',
          }
        }
      }
    }
  </script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body class="bg-gray-100 dark:bg-dark dark:text-gray-100 transition-colors duration-300">
  <!-- Navigation -->
  <nav class="bg-white dark:bg-gray-800 shadow-lg sticky top-0 z-50">
    <div class="container mx-auto px-4 py-3 flex justify-between items-center">
      <div class="flex items-center space-x-2">
        <i class="fas fa-tools text-primary"></i>
        <span class="text-xl font-bold text-gray-800 dark:text-white">Complete Restoration</span>
      </div>
      <div class="hidden md:flex space-x-8">
        <a href="#services" class="hover:text-primary">Services</a>
        <a href="#portfolio" class="hover:text-primary">Portfolio</a>
        <a href="#testimonials" class="hover:text-primary">Testimonials</a>
        <a href="#contact" class="hover:text-primary">Contact</a>
      </div>
      <button id="theme-toggle" class="p-2 rounded-full hover:bg-gray-200 dark:hover:bg-gray-700">
        <i class="fas fa-moon dark:hidden"></i>
        <i class="fas fa-sun hidden dark:block"></i>
      </button>
      <button class="md:hidden p-2">
        <i class="fas fa-bars text-xl"></i>
      </button>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="relative h-96 flex items-center justify-center bg-[url('https://images.unsplash.com/photo-1600585154340-be6161a56a0c')] bg-cover bg-center">
    <div class="absolute inset-0 bg-black/50"></div>
    <div class="container mx-auto px-4 z-10 text-center">
      <h1 class="text-4xl md:text-5xl font-bold text-white mb-4">Quality Renovations Done Right</h1>
      <p class="text-xl text-white mb-8">Residential & commercial remodeling with 25 years experience</p>
      <a href="#contact" class="bg-primary hover:bg-blue-700 text-white font-bold py-3 px-6 rounded-lg transition">Get a Free Estimate</a>
    </div>
  </section>

  <!-- Services Section -->
  <section id="services" class="py-16 bg-white dark:bg-gray-800">
    <div class="container mx-auto px-4">
      <h2 class="text-3xl font-bold text-center mb-12">Our Services</h2>
      <div class="grid md:grid-cols-3 gap-8">
        <div class="bg-gray-50 dark:bg-gray-700 p-6 rounded-lg shadow-md hover:shadow-lg transition">
          <div class="text-primary text-4xl mb-4">
            <i class="fas fa-home"></i>
          </div>
          <h3 class="text-xl font-semibold mb-2">Home Renovations</h3>
          <p class="text-gray-600 dark:text-gray-300">Complete home makeovers, kitchen & bathroom remodels, basement finishing, and more.</p>
        </div>
        <div class="bg-gray-50 dark:bg-gray-700 p-6 rounded-lg shadow-md hover:shadow-lg transition">
          <div class="text-primary text-4xl mb-4">
            <i class="fas fa-building"></i>
          </div>
          <h3 class="text-xl font-semibold mb-2">Commercial Spaces</h3>
          <p class="text-gray-600 dark:text-gray-300">Office build-outs, retail spaces, restaurants, and commercial property upgrades.</p>
        </div>
        <div class="bg-gray-50 dark:bg-gray-700 p-6 rounded-lg shadow-md hover:shadow-lg transition">
          <div class="text-primary text-4xl mb-4">
            <i class="fas fa-hammer"></i>
          </div>
          <h3 class="text-xl font-semibold mb-2">Custom Carpentry</h3>
          <p class="text-gray-600 dark:text-gray-300">Custom cabinets, built-ins, trim work, and specialty woodworking projects.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Portfolio Section -->
  <section id="portfolio" class="py-16 bg-gray-100 dark:bg-gray-900">
    <div class="container mx-auto px-4">
      <h2 class="text-3xl font-bold text-center mb-12">Recent Projects</h2>
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
        <!-- Project 1 -->
        <div class="rounded-lg overflow-hidden shadow-lg hover:shadow-xl transition">
          <img src="https://images.unsplash.com/photo-1600210492493-0946911123ea" alt="Kitchen remodel" class="w-full h-64 object-cover">
          <div class="p-4 bg-white dark:bg-gray-800">
            <h3 class="font-bold text-xl mb-2">Modern Kitchen Remodel</h3>
            <p class="text-gray-700 dark:text-gray-300">Complete kitchen overhaul with custom cabinetry and quartz countertops.</p>
          </div>
        </div>
        <!-- Project 2 -->
        <div class="rounded-lg overflow-hidden shadow-lg hover:shadow-xl transition">
          <img src="https://images.unsplash.com/photo-1600566752355-35792bedcfea" alt="Bathroom remodel" class="w-full h-64 object-cover">
          <div class="p-4 bg-white dark:bg-gray-800">
            <h3 class="font-bold text-xl mb-2">Luxury Bathroom</h3>
            <p class="text-gray-700 dark:text-gray-300">Spa-like bathroom renovation with walk-in shower and heated floors.</p>
          </div>
        </div>
        <!-- Project 3 -->
        <div class="rounded-lg overflow-hidden shadow-lg hover:shadow-xl transition">
          <img src="https://images.unsplash.com/photo-1493809842364-78817add7ffb" alt="Office buildout" class="w-full h-64 object-cover">
          <div class="p-4 bg-white dark:bg-gray-800">
            <h3 class="font-bold text-xl mb-2">Office Build-out</h3>
            <p class="text-gray-700 dark:text-gray-300">Commercial office space with modern finishes and efficient layout.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Testimonials -->
  <section id="testimonials" class="py-16 bg-white dark:bg-gray-800">
    <div class="container mx-auto px-4">
      <h2 class="text-3xl font-bold text-center mb-12">Client Testimonials</h2>
      <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
        <!-- Testimonial 1 -->
        <div class="bg-gray-50 dark:bg-gray-700 p-6 rounded-lg shadow">
          <div class="flex items-center mb-4">
            <div class="text-accent text-2xl mr-2">
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
            </div>
          </div>
          <p class="text-gray-600 dark:text-gray-300 italic mb-4">"John transformed our outdated kitchen into a modern masterpiece. His attention to detail and craftsmanship exceeded our expectations."</p>
          <div class="flex items-center">
            <div class="w-12 h-12 rounded-full bg-gray-300 mr-4 overflow-hidden">
              <img src="https://randomuser.me/api/portraits/women/43.jpg" alt="Sarah J." class="w-full h-full object-cover">
            </div>
            <div>
              <h4 class="font-semibold">Sarah J.</h4>
              <p class="text-sm text-gray-500">Homeowner</p>
            </div>
          </div>
        </div>
        <!-- Testimonial 2 -->
        <div class="bg-gray-50 dark:bg-gray-700 p-6 rounded-lg shadow">
          <div class="flex items-center mb-4">
            <div class="text-accent text-2xl mr-2">
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
            </div>
          </div>
          <p class="text-gray-600 dark:text-gray-300 italic mb-4">"We've used Complete Restoration for three commercial projects now. Reliable, professional, and exceptional quality every time."</p>
          <div class="flex items-center">
            <div class="w-12 h-12 rounded-full bg-gray-300 mr-4 overflow-hidden">
              <img src="https://randomuser.me/api/portraits/men/32.jpg" alt="Michael T." class="w-full h-full object-cover">
            </div>
            <div>
              <h4 class="font-semibold">Michael T.</h4>
              <p class="text-sm text-gray-500">Business Owner</p>
            </div>
          </div>
        </div>
        <!-- Testimonial 3 -->
        <div class="bg-gray-50 dark:bg-gray-700 p-6 rounded-lg shadow">
          <div class="flex items-center mb-4">
            <div class="text-accent text-2xl mr-2">
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
              <i class="fas fa-star"></i>
              <i class="fas fa-star-half-alt"></i>
            </div>
          </div>
          <p class="text-gray-600 dark:text-gray-300 italic mb-4">"The custom built-ins John created for our living room are stunning. He listened to our needs and delivered perfect results."</p>
          <div class="flex items-center">
            <div class="w-12 h-12 rounded-full bg-gray-300 mr-4 overflow-hidden">
              <img src="https://randomuser.me/api/portraits/women/65.jpg" alt="Lisa M." class="w-full h-full object-cover">
            </div>
            <div>
              <h4 class="font-semibold">Lisa M.</h4>
              <p class="text-sm text-gray-500">Homeowner</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

    <!-- Contact Section -->
    <section id="contact" class="py-16 bg-primary text-white">
    <div class="container mx-auto px-4">
        <h2 class="text-3xl font-bold text-center mb-12">Get In Touch</h2>
        <div class="grid md:grid-cols-2 gap-12">
        <div>
            <h3 class="text-xl font-semibold mb-4">Contact Information</h3>
            <div class="space-y-4">
            <div class="flex items-start">
                <i class="fas fa-map-marker-alt mt-1 mr-3"></i>
                <p>123 Contractor Lane<br>Renocity, RC 12345</p>
            </div>
            <div class="flex items-center">
                <i class="fas fa-phone-alt mr-3"></i>
                <p>(555) 123-4567</p>
            </div>
            <div class="flex items-center">
                <i class="fas fa-envelope mr-3"></i>
                <p>contact@completerestoration.com</p>
            </div>
            <div class="flex items-center">
                <i class="fas fa-clock mr-3"></i>
                <p>Mon-Fri: 8am - 6pm<br>Sat: 9am - 2pm</p>
            </div>
            </div>
            <div class="mt-8">
            <h3 class="text-xl font-semibold mb-4">Follow Us</h3>
            <div class="flex space-x-4">
                <a href="#" class="text-2xl hover:text-accent transition"><i class="fab fa-facebook"></i></a>
                <a href="#" class="text-2xl hover:text-accent transition"><i class="fab fa-instagram"></i></a>
                <a href="#" class="text-2xl hover:text-accent transition"><i class="fab fa-linkedin"></i></a>
                <a href="#" class="text-2xl hover:text-accent transition"><i class="fab fa-houzz"></i></a>
            </div>
            </div>
        </div>
        <div>
            <form action="https://formspree.io/f/xwpbowob" method="POST" class="space-y-4">
            <!-- Honeypot Field (hidden from humans) -->
            <input type="text" name="_gotcha" style="display:none">
            
            <!-- Regular Form Fields -->
            <div>
                <label for="name" class="block mb-1">Name</label>
                <input type="text" id="name" name="name" required class="w-full px-4 py-2 rounded text-gray-800">
            </div>
            <div>
                <label for="email" class="block mb-1">Email</label>
                <input type="email" id="email" name="email" required class="w-full px-4 py-2 rounded text-gray-800">
            </div>
            <div>
                <label for="phone" class="block mb-1">Phone</label>
                <input type="tel" id="phone" name="phone" class="w-full px-4 py-2 rounded text-gray-800">
            </div>
            <div>
                <label for="project" class="block mb-1">Project Type</label>
                <select id="project" name="project" class="w-full px-4 py-2 rounded text-gray-800">
                <option value="">Select project type</option>
                <option value="residential">Residential</option>
                <option value="commercial">Commercial</option>
                <option value="carpentry">Custom Carpentry</option>
                <option value="other">Other</option>
                </select>
            </div>
            <div>
                <label for="message" class="block mb-1">Message</label>
                <textarea id="message" name="message" rows="4" required class="w-full px-4 py-2 rounded text-gray-800"></textarea>
            </div>
            <button type="submit" class="bg-accent hover:bg-amber-600 text-white font-bold py-3 px-6 rounded-lg transition">Send Message</button>
            </form>
        </div>
        </div>
    </div>
    </section>

  <!-- Footer -->
  <footer class="bg-gray-800 text-white py-8">
    <div class="container mx-auto px-4">
      <div class="flex flex-col md:flex-row justify-between items-center">
        <div class="mb-4 md:mb-0">
          <div class="flex items-center space-x-2">
            <i class="fas fa-tools text-accent text-2xl"></i>
            <span class="text-xl font-bold">Complete Restoration</span>
          </div>
          <p class="mt-2 text-gray-400">Quality craftsmanship for 25 years</p>
        </div>
        <div class="text-gray-400 text-sm">
          <p>&copy; 2023 Complete Restoration. All rights reserved.</p>
        </div>
      </div>
    </div>
  </footer>

  <!-- Dark mode toggle script -->
  <script>
    const themeToggle = document.getElementById('theme-toggle');
    const html = document.documentElement;
    
    // Check for saved user preference or system preference
    if (localStorage.getItem('theme') === 'dark' || (!localStorage.getItem('theme') && window.matchMedia('(prefers-color-scheme: dark)').matches)) {
      html.classList.add('dark');
    }
    
    themeToggle.addEventListener('click', () => {
      html.classList.toggle('dark');
      localStorage.setItem('theme', html.classList.contains('dark') ? 'dark' : 'light');
    });
  </script>
</body>
</html>
