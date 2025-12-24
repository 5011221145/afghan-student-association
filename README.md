<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Afghanistan Student Association | Karabük University</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <style>
    /* Smooth scrolling */
    html {
      scroll-behavior: smooth;
    }
    
    /* Custom animations */
    @keyframes fadeInUp {
      from {
        opacity: 0;
        transform: translateY(30px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
    
    .fade-in-up {
      animation: fadeInUp 0.8s ease-out;
    }
    
    /* Custom gradient for active nav */
    .active-nav {
      background: linear-gradient(90deg, #166534 0%, #000 50%, #991b1b 100%);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      font-weight: bold;
    }
    
    /* Hover effect for cards */
    .hover-card {
      transition: all 0.3s ease;
    }
    
    .hover-card:hover {
      transform: translateY(-10px);
      box-shadow: 0 15px 30px rgba(0, 0, 0, 0.1);
    }
  </style>
</head>

<body class="bg-gray-100 font-sans text-black">

<!-- Header with improved mobile responsiveness -->
<header class="bg-gradient-to-r from-green-800 via-black to-red-700 text-white sticky top-0 z-50 shadow-lg">
  <div class="max-w-7xl mx-auto flex flex-col md:flex-row justify-between items-center px-6 py-4">
    <div class="flex justify-between w-full md:w-auto items-center">
      <div>
        <h1 class="text-2xl font-bold flex items-center">
          <i class="fas fa-flag mr-3"></i>
          Afghanistan Student Association
        </h1>
        <p class="text-sm opacity-80">Karabük University</p>
      </div>
      <button id="mobile-menu-btn" class="md:hidden text-2xl">
        <i class="fas fa-bars"></i>
      </button>
    </div>
    
    <nav id="main-nav" class="hidden md:flex flex-col md:flex-row md:space-x-6 font-medium mt-4 md:mt-0 text-center">
      <a href="#home" class="py-2 md:py-0 hover:text-red-300 nav-link active-nav">Home</a>
      <a href="#about" class="py-2 md:py-0 hover:text-red-300 nav-link">About</a>
      <a href="#events" class="py-2 md:py-0 hover:text-red-300 nav-link">Events</a>
      <a href="#gallery" class="py-2 md:py-0 hover:text-red-300 nav-link">Gallery</a>
      <a href="#contact" class="py-2 md:py-0 hover:text-red-300 nav-link">Contact</a>
    </nav>
  </div>
</header>

<!-- Hero Section with improved design -->
<section id="home" class="bg-gradient-to-br from-white to-gray-100 relative overflow-hidden">
  <div class="max-w-7xl mx-auto grid md:grid-cols-2 gap-10 px-6 py-20 items-center fade-in-up">
    <div>
      <h2 class="text-4xl md:text-5xl font-extrabold text-green-800 leading-tight">
        Unity, Culture & Academic Excellence
      </h2>
      <p class="mt-6 text-gray-700 text-lg leading-relaxed">
        Supporting Afghan students at Karabük University through cultural, academic,
        and social activities. We foster a supportive community that celebrates Afghan heritage while promoting academic success.
      </p>
      <div class="flex flex-col sm:flex-row gap-4 mt-8">
        <a href="#about"
           class="px-8 py-3 bg-green-700 text-white rounded-lg hover:bg-green-800 transition-all shadow-md hover:shadow-lg flex items-center justify-center">
          <i class="fas fa-info-circle mr-2"></i> Learn More
        </a>
        <a href="#contact"
           class="px-8 py-3 bg-red-700 text-white rounded-lg hover:bg-red-800 transition-all shadow-md hover:shadow-lg flex items-center justify-center">
          <i class="fas fa-envelope mr-2"></i> Contact Us
        </a>
      </div>
    </div>
    <div class="hidden md:block relative">
      <img src="https://images.unsplash.com/photo-1523050854058-8df90110c9f1"
           class="rounded-xl shadow-2xl transform hover:scale-105 transition duration-500"
           alt="University students collaborating">
      <div class="absolute -bottom-4 -left-4 bg-gradient-to-r from-green-800 to-red-700 text-white p-4 rounded-lg shadow-lg">
        <p class="font-bold">Since 2015</p>
        <p class="text-sm">Serving Afghan Students</p>
      </div>
    </div>
  </div>
</section>

<!-- About Section with enhanced content -->
<section id="about" class="bg-gray-50 py-20">
  <div class="max-w-6xl mx-auto px-6">
    <div class="text-center mb-12">
      <h3 class="text-3xl font-bold text-green-800 inline-block border-b-4 border-red-700 pb-2">About Us</h3>
    </div>
    
    <div class="grid md:grid-cols-2 gap-12 items-center">
      <div class="fade-in-up">
        <p class="text-gray-700 text-lg leading-relaxed mb-6">
          The Afghanistan Student Association represents Afghan students at Karabük University.
          We aim to support academic success, preserve cultural identity, and build strong student unity.
        </p>
        <p class="text-gray-700 leading-relaxed">
          Our organization provides a home away from home for Afghan students, offering guidance,
          resources, and a supportive community to help navigate academic life in Turkey while
          celebrating our rich Afghan heritage.
        </p>
        
        <div class="mt-10 grid grid-cols-2 gap-6">
          <div class="bg-white p-4 rounded-lg shadow border-l-4 border-green-700">
            <h4 class="font-bold text-green-800 flex items-center">
              <i class="fas fa-users mr-2"></i> Community
            </h4>
            <p class="text-sm mt-1">150+ Active Members</p>
          </div>
          <div class="bg-white p-4 rounded-lg shadow border-l-4 border-red-700">
            <h4 class="font-bold text-green-800 flex items-center">
              <i class="fas fa-calendar-alt mr-2"></i> Events
            </h4>
            <p class="text-sm mt-1">10+ Yearly Events</p>
          </div>
        </div>
      </div>
      
      <div class="bg-gradient-to-br from-green-50 to-red-50 p-8 rounded-xl shadow-lg">
        <h4 class="text-xl font-bold text-green-800 mb-6 flex items-center">
          <i class="fas fa-bullseye mr-3"></i> Our Mission
        </h4>
        <ul class="space-y-4">
          <li class="flex items-start">
            <i class="fas fa-check-circle text-green-700 mt-1 mr-3"></i>
            <span>Provide academic support and resources for Afghan students</span>
          </li>
          <li class="flex items-start">
            <i class="fas fa-check-circle text-green-700 mt-1 mr-3"></i>
            <span>Promote Afghan culture and heritage at Karabük University</span>
          </li>
          <li class="flex items-start">
            <i class="fas fa-check-circle text-green-700 mt-1 mr-3"></i>
            <span>Facilitate integration and networking opportunities</span>
          </li>
          <li class="flex items-start">
            <i class="fas fa-check-circle text-green-700 mt-1 mr-3"></i>
            <span>Organize social, cultural, and educational events</span>
          </li>
        </ul>
      </div>
    </div>
  </div>
</section>

<!-- Events Section with interactive cards -->
<section id="events" class="bg-white py-20">
  <div class="max-w-6xl mx-auto px-6">
    <div class="text-center mb-12">
      <h3 class="text-3xl font-bold text-green-800 inline-block border-b-4 border-red-700 pb-2">Our Activities</h3>
      <p class="mt-4 text-gray-600 max-w-2xl mx-auto">
        We organize various events throughout the academic year to support our members
      </p>
    </div>
    
    <div class="grid md:grid-cols-3 gap-8">
      <div class="bg-gray-100 p-6 rounded-xl shadow border-t-4 border-green-700 hover-card">
        <div class="text-green-700 text-3xl mb-4">
          <i class="fas fa-user-friends"></i>
        </div>
        <h4 class="font-bold text-lg text-green-800">Welcome Programs</h4>
        <p class="mt-2 text-gray-600">
          Orientation and support for new Afghan students to help them adapt to university life in Turkey.
        </p>
        <div class="mt-4 pt-4 border-t border-gray-300">
          <span class="text-sm font-medium text-green-700">Upcoming: September 15, 2025</span>
        </div>
      </div>
      
      <div class="bg-gray-100 p-6 rounded-xl shadow border-t-4 border-black hover-card">
        <div class="text-black text-3xl mb-4">
          <i class="fas fa-music"></i>
        </div>
        <h4 class="font-bold text-lg text-green-800">Cultural Events</h4>
        <p class="mt-2 text-gray-600">
          Celebrating Afghan culture, traditions, language, and national holidays with the university community.
        </p>
        <div class="mt-4 pt-4 border-t border-gray-300">
          <span class="text-sm font-medium text-green-700">Nowruz Celebration: March 21</span>
        </div>
      </div>
      
      <div class="bg-gray-100 p-6 rounded-xl shadow border-t-4 border-red-700 hover-card">
        <div class="text-red-700 text-3xl mb-4">
          <i class="fas fa-graduation-cap"></i>
        </div>
        <h4 class="font-bold text-lg text-green-800">Academic Seminars</h4>
        <p class="mt-2 text-gray-600">
          Educational workshops, tutoring sessions, and academic guidance for all departments.
        </p>
        <div class="mt-4 pt-4 border-t border-gray-300">
          <span class="text-sm font-medium text-green-700">Weekly Study Groups</span>
        </div>
      </div>
    </div>
    
    <div class="mt-12 text-center">
      <a href="#contact" class="inline-flex items-center px-6 py-3 bg-gradient-to-r from-green-700 to-red-700 text-white rounded-lg hover:opacity-90 transition-all shadow-md">
        <i class="fas fa-calendar-plus mr-2"></i> Propose an Event
      </a>
    </div>
  </div>
</section>

<!-- Gallery Section (New) -->
<section id="gallery" class="bg-gray-50 py-20">
  <div class="max-w-6xl mx-auto px-6">
    <div class="text-center mb-12">
      <h3 class="text-3xl font-bold text-green-800 inline-block border-b-4 border-red-700 pb-2">Gallery</h3>
      <p class="mt-4 text-gray-600 max-w-2xl mx-auto">
        Moments from our events and activities
      </p>
    </div>
    
    <div class="grid grid-cols-2 md:grid-cols-4 gap-4">
      <div class="col-span-2 row-span-2">
        <div class="bg-gradient-to-br from-green-800 to-red-700 h-full rounded-xl shadow-lg flex items-center justify-center p-6">
          <div class="text-white text-center">
            <i class="fas fa-images text-5xl mb-4"></i>
            <h4 class="text-2xl font-bold">Our Memories</h4>
            <p class="mt-2">Celebrating Afghan Culture</p>
          </div>
        </div>
      </div>
      <div class="bg-gray-200 h-40 rounded-xl shadow flex items-center justify-center">
        <i class="fas fa-landmark text-4xl text-gray-500"></i>
      </div>
      <div class="bg-gray-200 h-40 rounded-xl shadow flex items-center justify-center">
        <i class="fas fa-utensils text-4xl text-gray-500"></i>
      </div>
      <div class="bg-gray-200 h-40 rounded-xl shadow flex items-center justify-center">
        <i class="fas fa-book-open text-4xl text-gray-500"></i>
      </div>
      <div class="bg-gray-200 h-40 rounded-xl shadow flex items-center justify-center">
        <i class="fas fa-graduation-cap text-4xl text-gray-500"></i>
      </div>
    </div>
  </div>
</section>

<!-- Contact Section with improved layout -->
<section id="contact" class="bg-white py-20">
  <div class="max-w-6xl mx-auto px-6">
    <div class="text-center mb-12">
      <h3 class="text-3xl font-bold text-green-800 inline-block border-b-4 border-red-700 pb-2">Contact Us</h3>
      <p class="mt-4 text-gray-600 max-w-2xl mx-auto">
        Get in touch with the Afghanistan Student Association
      </p>
    </div>
    
    <div class="grid md:grid-cols-2 gap-12">
      <div>
        <div class="bg-gradient-to-r from-green-50 to-red-50 p-8 rounded-xl shadow-lg">
          <h4 class="text-xl font-bold text-green-800 mb-6 flex items-center">
            <i class="fas fa-paper-plane mr-3"></i> Contact Information
          </h4>
          
          <div class="space-y-6">
            <div class="flex items-start">
              <div class="bg-green-100 p-3 rounded-lg mr-4">
                <i class="fas fa-envelope text-green-700"></i>
              </div>
              <div>
                <h5 class="font-bold text-green-800">Email</h5>
                <p class="text-gray-700">afghan.students@karabuk.edu.tr</p>
              </div>
            </div>
            
            <div class="flex items-start">
              <div class="bg-red-100 p-3 rounded-lg mr-4">
                <i class="fas fa-map-marker-alt text-red-700"></i>
              </div>
              <div>
                <h5 class="font-bold text-green-800">Location</h5>
                <p class="text-gray-700">Karabük University Campus</p>
                <p class="text-gray-600 text-sm">Student Clubs Building, Floor 3</p>
              </div>
            </div>
            
            <div class="flex items-start">
              <div class="bg-black p-3 rounded-lg mr-4">
                <i class="fas fa-clock text-white"></i>
              </div>
              <div>
                <h5 class="font-bold text-green-800">Office Hours</h5>
                <p class="text-gray-700">Tuesday & Thursday: 2:00 PM - 5:00 PM</p>
              </div>
            </div>
          </div>
          
          <div class="mt-10 pt-6 border-t border-gray-300">
            <h5 class="font-bold text-green-800 mb-4">Follow Us</h5>
            <div class="flex space-x-4">
              <a href="#" class="bg-green-700 text-white p-3 rounded-full hover:bg-green-800 transition">
                <i class="fab fa-facebook-f"></i>
              </a>
              <a href="#" class="bg-blue-400 text-white p-3 rounded-full hover:bg-blue-500 transition">
                <i class="fab fa-twitter"></i>
              </a>
              <a href="#" class="bg-red-600 text-white p-3 rounded-full hover:bg-red-700 transition">
                <i class="fab fa-instagram"></i>
              </a>
              <a href="#" class="bg-blue-700 text-white p-3 rounded-full hover:bg-blue-800 transition">
                <i class="fab fa-telegram"></i>
              </a>
            </div>
          </div>
        </div>
      </div>
      
      <div>
        <div class="bg-gray-50 p-8 rounded-xl shadow-lg">
          <h4 class="text-xl font-bold text-green-800 mb-6">Send Us a Message</h4>
          <form id="contact-form" class="space-y-6">
            <div>
              <label class="block text-gray-700 mb-2 font-medium" for="name">Full Name</label>
              <input type="text" id="name" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-green-500" required>
            </div>
            
            <div>
              <label class="block text-gray-700 mb-2 font-medium" for="email">Email Address</label>
              <input type="email" id="email" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-green-500" required>
            </div>
            
            <div>
              <label class="block text-gray-700 mb-2 font-medium" for="message">Message</label>
              <textarea id="message" rows="5" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-green-500" required></textarea>
            </div>
            
            <button type="submit" class="w-full bg-gradient-to-r from-green-700 to-red-700 text-white py-3 rounded-lg font-medium hover:opacity-90 transition-all shadow-md">
              <i class="fas fa-paper-plane mr-2"></i> Send Message
            </button>
          </form>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- Footer with enhanced design -->
<footer class="bg-gradient-to-r from-green-800 via-black to-red-700 text-white py-10">
  <div class="max-w-6xl mx-auto px-6">
    <div class="grid md:grid-cols-3 gap-8 mb-8">
      <div>
        <h4 class="text-xl font-bold mb-4 flex items-center">
          <i class="fas fa-flag mr-3"></i>
          ASA Karabük
        </h4>
        <p class="text-gray-300 text-sm">
          The Afghanistan Student Association at Karabük University, fostering unity and academic excellence among Afghan students.
        </p>
      </div>
      
      <div>
        <h4 class="text-xl font-bold mb-4">Quick Links</h4>
        <ul class="space-y-2">
          <li><a href="#home" class="text-gray-300 hover:text-white transition">Home</a></li>
          <li><a href="#about" class="text-gray-300 hover:text-white transition">About Us</a></li>
          <li><a href="#events" class="text-gray-300 hover:text-white transition">Events</a></li>
          <li><a href="#contact" class="text-gray-300 hover:text-white transition">Contact</a></li>
        </ul>
      </div>
      
      <div>
        <h4 class="text-xl font-bold mb-4">University Links</h4>
        <ul class="space-y-2">
          <li><a href="#" class="text-gray-300 hover:text-white transition">Karabük University</a></li>
          <li><a href="#" class="text-gray-300 hover:text-white transition">International Office</a></li>
          <li><a href="#" class="text-gray-300 hover:text-white transition">Student Clubs</a></li>
        </ul>
      </div>
    </div>
    
    <div class="pt-8 border-t border-gray-700 text-center text-sm text-gray-400">
      <p>© 2025 Afghanistan Student Association – Karabük University. All rights reserved.</p>
      <p class="mt-2">Designed with <i class="fas fa-heart text-red-400"></i> for the Afghan student community</p>
    </div>
  </div>
</footer>

<script>
  // Mobile menu toggle
  document.getElementById('mobile-menu-btn').addEventListener('click', function() {
    const nav = document.getElementById('main-nav');
    nav.classList.toggle('hidden');
    
    // Change icon
    const icon = this.querySelector('i');
    if (icon.classList.contains('fa-bars')) {
      icon.classList.remove('fa-bars');
      icon.classList.add('fa-times');
    } else {
      icon.classList.remove('fa-times');
      icon.classList.add('fa-bars');
    }
  });
  
  // Nav link active state
  const navLinks = document.querySelectorAll('.nav-link');
  const sections = document.querySelectorAll('section');
  
  // Update active nav on scroll
  window.addEventListener('scroll', function() {
    let current = '';
    
    sections.forEach(section => {
      const sectionTop = section.offsetTop;
      const sectionHeight = section.clientHeight;
      if (scrollY >= (sectionTop - 200)) {
        current = section.getAttribute('id');
      }
    });
    
    navLinks.forEach(link => {
      link.classList.remove('active-nav');
      if (link.getAttribute('href') === `#${current}`) {
        link.classList.add('active-nav');
      }
    });
  });
  
  // Form submission
  document.getElementById('contact-form').addEventListener('submit', function(e) {
    e.preventDefault();
    
    // Get form values
    const name = document.getElementById('name').value;
    const email = document.getElementById('email').value;
    const message = document.getElementById('message').value;
    
    // In a real application, this would be sent to a server
    // For now, we'll just show an alert
    alert(`Thank you, ${name}! Your message has been received. We'll contact you at ${email} soon.`);
    
    // Reset form
    this.reset();
  });
  
  // Animate elements on scroll
  const observerOptions = {
    threshold: 0.1,
    rootMargin: '0px 0px -50px 0px'
  };
  
  const observer = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
      if (entry.isIntersecting) {
        entry.target.classList.add('fade-in-up');
      }
    });
  }, observerOptions);
  
  // Observe elements for animation
  document.querySelectorAll('.hover-card').forEach((el) => {
    observer.observe(el);
  });
</script>
</body>
</html>
