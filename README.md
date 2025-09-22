<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ClickNexis | Digital Marketing Partner</title>
    <link rel="icon" type="image/x-icon" href="/static/favicon.ico">
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/feather-icons/dist/feather.min.js"></script>
    <script src="https://unpkg.com/feather-icons"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap');
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #0a0a0a;
            color: #f8f8f8;
            scroll-behavior: smooth;
        }
        .glow-card {
            box-shadow: 0 0 15px rgba(59, 130, 246, 0.3);
            transition: all 0.3s ease;
        }
        .glow-card:hover {
            box-shadow: 0 0 25px rgba(59, 130, 246, 0.5);
            transform: translateY(-5px);
        }
        .neon-border {
            position: relative;
        }
        .neon-border::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            border-radius: inherit;
            padding: 2px;
            background: linear-gradient(45deg, #3b82f6, #1e40af);
            -webkit-mask: linear-gradient(#fff 0 0) content-box, linear-gradient(#fff 0 0);
            -webkit-mask-composite: xor;
            mask-composite: exclude;
            pointer-events: none;
        }
        .gradient-text {
            background: linear-gradient(90deg, #3b82f6, #1e40af);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
        }
        /* New styles for enhanced features */
        .progress-bar {
            height: 6px;
            background: #1e293b;
            border-radius: 3px;
            overflow: hidden;
        }
        .progress-fill {
            height: 100%;
            background: linear-gradient(90deg, #3b82f6, #1e40af);
            border-radius: 3px;
        }
        .testimonial-card {
            background: linear-gradient(145deg, #0f172a, #1e293b);
            border: 1px solid #334155;
        }
        .typewriter {
            overflow: hidden;
            border-right: .15em solid #3b82f6;
            white-space: nowrap;
            margin: 0 auto;
            letter-spacing: .15em;
            animation: typing 3.5s steps(40, end), blink-caret .75s step-end infinite;
        }
        @keyframes typing {
            from { width: 0 }
            to { width: 100% }
        }
        @keyframes blink-caret {
            from, to { border-color: transparent }
            50% { border-color: #3b82f6; }
        }
        .floating { 
            animation: float 6s ease-in-out infinite;
        }
        @keyframes float {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-20px); }
            100% { transform: translateY(0px); }
        }
    </style>
</head>
<body class="bg-gray-900 text-gray-100">
    <!-- Navigation -->
    <nav class="fixed w-full bg-gray-900/90 backdrop-blur-md z-50 border-b border-gray-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-16">
                <div class="flex items-center">
                    <a href="#" class="text-2xl font-bold gradient-text">ClickNexis</a>
                </div>
                <div class="hidden md:block">
                    <div class="ml-10 flex items-baseline space-x-8">
                        <a href="#home" class="text-gray-300 hover:text-white px-3 py-2 rounded-md text-sm font-medium">Home</a>
                        <a href="#about" class="text-gray-300 hover:text-white px-3 py-2 rounded-md text-sm font-medium">About</a>
                        <a href="#services" class="text-gray-300 hover:text-white px-3 py-2 rounded-md text-sm font-medium">Services</a>
                        <a href="#skills" class="text-gray-300 hover:text-white px-3 py-2 rounded-md text-sm font-medium">Skills</a>
                        <a href="#projects" class="text-gray-300 hover:text-white px-3 py-2 rounded-md text-sm font-medium">Projects</a>
                        <a href="#testimonials" class="text-gray-300 hover:text-white px-3 py-2 rounded-md text-sm font-medium">Testimonials</a>
                        <a href="#pricing" class="text-gray-300 hover:text-white px-3 py-2 rounded-md text-sm font-medium">Pricing</a>
                        <a href="#contact" class="text-gray-300 hover:text-white px-3 py-2 rounded-md text-sm font-medium">Contact</a>
                    </div>
                </div>
                <div class="-mr-2 flex md:hidden">
                    <button type="button" class="inline-flex items-center justify-center p-2 rounded-md text-gray-400 hover:text-white hover:bg-gray-700 focus:outline-none" aria-controls="mobile-menu" aria-expanded="false" id="mobile-menu-button">
                        <i data-feather="menu"></i>
                    </button>
                </div>
            </div>
        </div>

        <!-- Mobile menu -->
        <div class="hidden md:hidden" id="mobile-menu">
            <div class="px-2 pt-2 pb-3 space-y-1 sm:px-3">
                <a href="#home" class="text-gray-300 hover:text-white block px-3 py-2 rounded-md text-base font-medium">Home</a>
                <a href="#about" class="text-gray-300 hover:text-white block px-3 py-2 rounded-md text-base font-medium">About</a>
                <a href="#services" class="text-gray-300 hover:text-white block px-3 py-2 rounded-md text-base font-medium">Services</a>
                <a href="#skills" class="text-gray-300 hover:text-white block px-3 py-2 rounded-md text-base font-medium">Skills</a>
                <a href="#projects" class="text-gray-300 hover:text-white block px-3 py-2 rounded-md text-base font-medium">Projects</a>
                <a href="#testimonials" class="text-gray-300 hover:text-white block px-3 py-2 rounded-md text-base font-medium">Testimonials</a>
                <a href="#pricing" class="text-gray-300 hover:text-white block px-3 py-2 rounded-md text-base font-medium">Pricing</a>
                <a href="#contact" class="text-gray-300 hover:text-white block px-3 py-2 rounded-md text-base font-medium">Contact</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="pt-32 pb-20 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
        <div class="text-center">
            <h1 class="text-4xl md:text-6xl font-bold mb-6" data-aos="fade-up">
                <span class="typewriter">Your Digital Marketing Partner</span>
            </h1>
            <p class="text-xl md:text-2xl text-gray-300 mb-10 max-w-3xl mx-auto" data-aos="fade-up" data-aos-delay="100">Helping brands grow with SEO, Ads, and Social Media.</p>
            <div class="flex flex-col sm:flex-row justify-center gap-4" data-aos="fade-up" data-aos-delay="200">
                <a href="#contact" class="bg-blue-600 hover:bg-blue-700 text-white font-bold py-3 px-8 rounded-full inline-flex items-center justify-center transition duration-300">
                    Work With Me
                    <i data-feather="arrow-right" class="ml-2"></i>
                </a>
                <a href="#projects" class="border border-blue-600 text-blue-500 hover:bg-blue-600 hover:text-white font-bold py-3 px-8 rounded-full inline-flex items-center justify-center transition duration-300">
                    View Projects
                    <i data-feather="briefcase" class="ml-2"></i>
                </a>
            </div>
        </div>
        <div class="mt-20 flex justify-center" data-aos="fade-up" data-aos-delay="300">
            <div class="floating">
                <img src="https://placehold.co/600x400/1e293b/3b82f6" alt="Digital Marketing Illustration" class="rounded-lg shadow-xl glow-card max-w-full h-auto">
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
        <div class="text-center mb-16">
            <h2 class="text-3xl md:text-4xl font-bold mb-4" data-aos="fade-up">About Me</h2>
            <div class="w-20 h-1 bg-blue-600 mx-auto mb-8" data-aos="fade-up"></div>
        </div>
        <div class="flex flex-col md:flex-row items-center gap-12">
            <div class="md:w-1/2" data-aos="fade-right">
                <img src="https://placehold.co/500x600/1e293b/3b82f6" alt="Biswanath Sahoo" class="rounded-lg shadow-xl glow-card w-full">
            </div>
            <div class="md:w-1/2" data-aos="fade-left">
                <p class="text-lg text-gray-300 mb-6">I'm Biswanath Sahoo, a digital marketing freelancer with over 1 year of experience. I specialize in SEO, Social Media Marketing, and Paid Ads. I've worked with multiple businesses to improve their online presence, increase engagement, and generate leads. I enjoy creating simple and effective campaigns that work.</p>
                
                <div class="grid grid-cols-2 gap-6 mb-8">
                    <div class="text-center p-4 bg-gray-800 rounded-lg glow-card">
                        <div class="text-3xl font-bold text-blue-500 mb-2">10+</div>
                        <div class="text-gray-300">Projects Completed</div>
                    </div>
                    <div class="text-center p-4 bg-gray-800 rounded-lg glow-card">
                        <div class="text-3xl font-bold text-blue-500 mb-2">1+</div>
                        <div class="text-gray-300">Years Experience</div>
                    </div>
                    <div class="text-center p-4 bg-gray-800 rounded-lg glow-card">
                        <div class="text-3xl font-bold text-blue-500 mb-2">8+</div>
                        <div class="text-gray-300">Happy Clients</div>
                    </div>
                    <div class="text-center p-4 bg-gray-800 rounded-lg glow-card">
                        <div class="text-3xl font-bold text-blue-500 mb-2">5+</div>
                        <div class="text-gray-300">Services Offered</div>
                    </div>
                </div>
                
                <div class="flex space-x-4">
                    <a href="https://www.instagram.com/clicknexis/" target="_blank" class="text-gray-400 hover:text-blue-500 transition duration-300 p-3 bg-gray-800 rounded-full">
                        <i data-feather="instagram" class="w-5 h-5"></i>
                    </a>
                    <a href="https://www.facebook.com/profile.php?id=61577877973358" target="_blank" class="text-gray-400 hover:text-blue-500 transition duration-300 p-3 bg-gray-800 rounded-full">
                        <i data-feather="facebook" class="w-5 h-5"></i>
                    </a>
                    <a href="https://www.linkedin.com/company/clicknexis/" target="_blank" class="text-gray-400 hover:text-blue-500 transition duration-300 p-3 bg-gray-800 rounded-full">
                        <i data-feather="linkedin" class="w-5 h-5"></i>
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-20 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto bg-gray-800/50 rounded-xl">
        <div class="text-center mb-16">
            <h2 class="text-3xl md:text-4xl font-bold mb-4" data-aos="fade-up">Services</h2>
            <div class="w-20 h-1 bg-blue-600 mx-auto mb-8" data-aos="fade-up"></div>
            <p class="text-xl text-gray-300 max-w-3xl mx-auto" data-aos="fade-up">Comprehensive digital marketing solutions to grow your business online</p>
        </div>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
            <!-- Service 1 -->
            <div class="bg-gray-800 p-8 rounded-xl glow-card group" data-aos="fade-up">
                <div class="text-blue-500 mb-4 group-hover:scale-110 transition-transform duration-300">
                    <i data-feather="instagram" class="w-10 h-10"></i>
                </div>
                <h3 class="text-xl font-bold mb-3">Social Media Management</h3>
                <p class="text-gray-300 mb-4">Build your brand on Facebook, Instagram & more with strategic content and engagement.</p>
                <p class="text-blue-500 font-bold">₹7,000/month</p>
            </div>
            
            <!-- Service 2 -->
            <div class="bg-gray-800 p-8 rounded-xl glow-card group" data-aos="fade-up" data-aos-delay="100">
                <div class="text-blue-500 mb-4 group-hover:scale-110 transition-transform duration-300">
                    <i data-feather="search" class="w-10 h-10"></i>
                </div>
                <h3 class="text-xl font-bold mb-3">SEO Optimization</h3>
                <p class="text-gray-300 mb-4">Rank higher and get organic traffic with comprehensive on-page and off-page SEO strategies.</p>
                <p class="text-blue-500 font-bold">₹9,000/month</p>
            </div>
            
            <!-- Service 3 -->
            <div class="bg-gray-800 p-8 rounded-xl glow-card group" data-aos="fade-up" data-aos-delay="200">
                <div class="text-blue-500 mb-4 group-hover:scale-110 transition-transform duration-300">
                    <i data-feather="dollar-sign" class="w-10 h-10"></i>
                </div>
                <h3 class="text-xl font-bold mb-3">Google & Meta Ads</h3>
                <p class="text-gray-300 mb-4">Run targeted ads that bring real customers and maximize your advertising ROI.</p>
                <p class="text-blue-500 font-bold">₹12,000/month</p>
            </div>
            
            <!-- Service 4 -->
            <div class="bg-gray-800 p-8 rounded-xl glow-card group" data-aos="fade-up">
                <div class="text-blue-500 mb-4 group-hover:scale-110 transition-transform duration-300">
                    <i data-feather="layers" class="w-10 h-10"></i>
                </div>
                <h3 class="text-xl font-bold mb-3">Brand Strategy & Design</h3>
                <p class="text-gray-300 mb-4">Create a memorable brand identity with comprehensive strategy and visual design.</p>
                <p class="text-blue-500 font-bold">₹15,000/project</p>
            </div>
            
            <!-- Service 5 -->
            <div class="bg-gray-800 p-8 rounded-xl glow-card group" data-aos="fade-up" data-aos-delay="100">
                <div class="text-blue-500 mb-4 group-hover:scale-110 transition-transform duration-300">
                    <i data-feather="globe" class="w-10 h-10"></i>
                </div>
                <h3 class="text-xl font-bold mb-3">Website Support</h3>
                <p class="text-gray-300 mb-4">Framer & Webflow setup, optimization, and maintenance services.</p>
                <p class="text-blue-500 font-bold">₹10,000/project</p>
            </div>
            
            <!-- Service 6 -->
            <div class="bg-gray-800 p-8 rounded-xl glow-card group" data-aos="fade-up" data-aos-delay="200">
                <div class="text-blue-500 mb-4 group-hover:scale-110 transition-transform duration-300">
                    <i data-feather="bar-chart" class="w-10 h-10"></i>
                </div>
                <h3 class="text-xl font-bold mb-3">Analytics & Reporting</h3>
                <p class="text-gray-300 mb-4">Comprehensive performance tracking and detailed reporting for data-driven decisions.</p>
                <p class="text-blue-500 font-bold">₹5,000/month</p>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="py-20 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
        <div class="text-center mb-16">
            <h2 class="text-3xl md:text-4xl font-bold mb-4" data-aos="fade-up">My Skills</h2>
            <div class="w-20 h-1 bg-blue-600 mx-auto mb-8" data-aos="fade-up"></div>
            <p class="text-xl text-gray-300 max-w-3xl mx-auto" data-aos="fade-up">Expertise across the digital marketing spectrum</p>
        </div>
        
        <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
            <div data-aos="fade-right">
                <div class="mb-6">
                    <div class="flex justify-between mb-2">
                        <span class="text-gray-300">SEO Optimization</span>
                        <span class="text-blue-500">95%</span>
                    </div>
                    <div class="progress-bar">
                        <div class="progress-fill" style="width: 95%"></div>
                    </div>
                </div>
                
                <div class="mb-6">
                    <div class="flex justify-between mb-2">
                        <span class="text-gray-300">Social Media Marketing</span>
                        <span class="text-blue-500">90%</span>
                    </div>
                    <div class="progress-bar">
                        <div class="progress-fill" style="width: 90%"></div>
                    </div>
                </div>
                
                <div class="mb-6">
                    <div class="flex justify-between mb-2">
                        <span class="text-gray-300">Google Ads</span>
                        <span class="text-blue-500">88%</span>
                    </div>
                    <div class="progress-bar">
                        <div class="progress-fill" style="width: 88%"></div>
                    </div>
                </div>
            </div>
            
            <div data-aos="fade-left">
                <div class="mb-6">
                    <div class="flex justify-between mb-2">
                        <span class="text-gray-300">Meta Ads</span>
                        <span class="text-blue-500">92%</span>
                    </div>
                    <div class="progress-bar">
                        <div class="progress-fill" style="width: 92%"></div>
                    </div>
                </div>
                
                <div class="mb-6">
                    <div class="flex justify-between mb-2">
                        <span class="text-gray-300">Content Strategy</span>
                        <span class="text-blue-500">85%</span>
                    </div>
                    <div class="progress-bar">
                        <div class="progress-fill" style="width: 85%"></div>
                    </div>
                </div>
                
                <div class="mb-6">
                    <div class="flex justify-between mb-2">
                        <span class="text-gray-300">Analytics & Reporting</span>
                        <span class="text-blue-500">87%</span>
                    </div>
                    <div class="progress-bar">
                        <div class="progress-fill" style="width: 87%"></div>
                    </div>
                </div>
            </div>
        </div>
        
        <div class="mt-16 grid grid-cols-2 md:grid-cols-4 gap-6" data-aos="fade-up">
            <div class="bg-gray-800 p-6 rounded-xl text-center glow-card">
                <div class="text-blue-500 mb-3">
                    <i data-feather="target" class="w-10 h-10 mx-auto"></i>
                </div>
                <h3 class="font-bold mb-2">Goal-Oriented</h3>
                <p class="text-sm text-gray-300">Focused on achieving your business objectives</p>
            </div>
            
            <div class="bg-gray-800 p-6 rounded-xl text-center glow-card">
                <div class="text-blue-500 mb-3">
                    <i data-feather="trending-up" class="w-10 h-10 mx-auto"></i>
                </div>
                <h3 class="font-bold mb-2">Data-Driven</h3>
                <p class="text-sm text-gray-300">Strategies based on analytics and metrics</p>
            </div>
            
            <div class="bg-gray-800 p-6 rounded-xl text-center glow-card">
                <div class="text-blue-500 mb-3">
                    <i data-feather="clock" class="w-10 h-10 mx-auto"></i>
                </div>
                <h3 class="font-bold mb-2">Timely Delivery</h3>
                <p class="text-sm text-gray-300">Consistent meeting of deadlines</p>
            </div>
            
            <div class="bg-gray-800 p-6 rounded-xl text-center glow-card">
                <div class="text-blue-500 mb-3">
                    <i data-feather="refresh-cw" class="w-10 h-10 mx-auto"></i>
                </div>
                <h3 class="font-bold mb-2">Adaptive Approach</h3>
                <p class="text-sm text-gray-300">Flexible strategies that evolve</p>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="py-20 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
        <div class="text-center mb-16">
            <h2 class="text-3xl md:text-4xl font-bold mb-4" data-aos="fade-up">Projects</h2>
            <div class="w-20 h-1 bg-blue-600 mx-auto mb-8" data-aos="fade-up"></div>
            <p class="text-xl text-gray-300 max-w-3xl mx-auto" data-aos="fade-up">A showcase of successful digital marketing campaigns and projects</p>
        </div>
        
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
            <!-- Project 1 -->
            <div class="bg-gray-800 rounded-xl overflow-hidden glow-card group" data-aos="fade-up">
                <div class="h-48 overflow-hidden">
                    <img src="https://placehold.co/400x300/1e293b/3b82f6" alt="Tecknify.com" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500">
                </div>
                <div class="p-6">
                    <h3 class="text-xl font-bold mb-2">Tecknify.com</h3>
                    <p class="text-gray-300 mb-3">SEO → +35% traffic in 3 months</p>
                    <div class="flex justify-between items-center">
                        <span class="text-sm text-blue-500 bg-blue-500/10 px-3 py-1 rounded-full">Completed</span>
                        <a href="#" class="text-blue-500 hover:text-blue-400 transition duration-300 flex items-center">
                            View Case Study <i data-feather="arrow-right" class="ml-1 w-4 h-4"></i>
                        </a>
                    </div>
                </div>
            </div>
            
            <!-- Project 2 -->
            <div class="bg-gray-800 rounded-xl overflow-hidden glow-card group" data-aos="fade-up" data-aos-delay="100">
                <div class="h-48 overflow-hidden">
                    <img src="https://placehold.co/400x300/1e293b/3b82f6" alt="DigitizeAds.com" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500">
                </div>
                <div class="p-6">
                    <h3 class="text-xl font-bold mb-2">DigitizeAds.com</h3>
                    <p class="text-gray-300 mb-3">Google & Meta Ads → 40% lower CPL</p>
                    <div class="flex justify-between items-center">
                        <span class="text-sm text-blue-500 bg-blue-500/10 px-3 py-1 rounded-full">Completed</span>
                        <a href="#" class="text-blue-500 hover:text-blue-400 transition duration-300 flex items-center">
                            View Case Study <i data-feather="arrow-right" class="ml-1 w-4 h-4"></i>
                        </a>
                    </div>
                </div>
            </div>
            
            <!-- Project 3 -->
            <div class="bg-gray-800 rounded-xl overflow-hidden glow-card group" data-aos="fade-up" data-aos-delay="200">
                <div class="h-48 overflow-hidden">
                    <img src="https://placehold.co/400x300/1e293b/3b82f6" alt="BL215.com" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500">
                </div>
                <div class="p-6">
                    <h3 class="text-xl font-bold mb-2">BL215.com</h3>
                    <p class="text-gray-300 mb-3">U.S. streetwear brand → 3.8x ROAS</p>
                    <div class="flex justify-between items-center">
                        <span class="text-sm text-blue-500 bg-blue-500/10 px-3 py-1 rounded-full">Completed</span>
                        <a href="#" class="text-blue-500 hover:text-blue-400 transition duration-300 flex items-center">
                            View Case Study <i data-feather="arrow-right" class="ml-1 w-4 h-4"></i>
                        </a>
                    </div>
                </div>
            </div>
            
            <!-- Project 4 -->
            <div class="bg-gray-800 rounded-xl overflow-hidden glow-card group" data-aos="fade-up">
                <div class="h-48 overflow-hidden">
                    <img src="https://placehold.co/400x300/1e293b/3b82f6" alt="RogerPerron.com" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500">
                </div>
                <div class="p-6">
                    <h3 class="text-xl font-bold mb-2">RogerPerron.com</h3>
                    <p class="text-gray-300 mb-3">Google Ads → +25% conversions</p>
                    <div class="flex justify-between items-center">
                        <span class="text-sm text-blue-500 bg-blue-500/10 px-3 py-1 rounded-full">Completed</span>
                        <a href="#" class="text-blue-500 hover:text-blue-400 transition duration-300 flex items-center">
                            View Case Study <i data-feather="arrow-right" class="ml-1 w-4 h-4"></i>
                        </a>
                    </div>
                </div>
            </div>
            
            <!-- Project 5 -->
            <div class="bg-gray-800 rounded-xl overflow-hidden glow-card group" data-aos="fade-up" data-aos-delay="100">
                <div class="h-48 overflow-hidden">
                    <img src="https://placehold.co/400x300/1e293b/3b82f6" alt="ShoppersEye.co" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500">
                </div>
                <div class="p-6">
                    <h3 class="text-xl font-bold mb-2">ShoppersEye.co</h3>
                    <p class="text-gray-300 mb-3">CRO audit → bounce rate down 20%</p>
                    <div class="flex justify-between items-center">
                        <span class="text-sm text-blue-500 bg-blue-500/10 px-3 py-1 rounded-full">Completed</span>
                        <a href="#" class="text-blue-500 hover:text-blue-400 transition duration-300 flex items-center">
                            View Case Study <i data-feather="arrow-right" class="ml-1 w-4 h-4"></i>
                        </a>
                    </div>
                </div>
            </div>
            
            <!-- Project 6 -->
            <div class="bg-gray-800 rounded-xl overflow-hidden glow-card group" data-aos="fade-up" data-aos-delay="200">
                <div class="h-48 overflow-hidden">
                    <img src="https://placehold.co/400x300/1e293b/3b82f6" alt="ClickNexis.wiki" class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-500">
                </div>
                <div class="p-6">
                    <h3 class="text-xl font-bold mb-2">ClickNexis.wiki</h3>
                    <p class="text-gray-300 mb-3">Personal freelancing brand site</p>
                    <div class="flex justify-between items-center">
                        <span class="text-sm text-yellow-500 bg-yellow-500/10 px-3 py-1 rounded-full">Ongoing</span>
                        <a href="#" class="text-blue-500 hover:text-blue-400 transition duration-300 flex items-center">
                            View Project <i data-feather="arrow-right" class="ml-1 w-4 h-4"></i>
                        </a>
                    </div>
                </div>
            </div>
        </div>
        
        <div class="text-center mt-12" data-aos="fade-up">
            <a href="#contact" class="inline-flex items-center px-6 py-3 border border-blue-600 text-blue-500 rounded-full hover:bg-blue-600 hover:text-white transition duration-300">
                Start Your Project
                <i data-feather="arrow-right" class="ml-2"></i>
            </a>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section id="testimonials" class="py-20 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto bg-gray-800/50 rounded-xl">
        <div class="text-center mb-16">
            <h2 class="text-3xl md:text-4xl font-bold mb-4" data-aos="fade-up">Client Testimonials</h2>
            <div class="w-20 h-1 bg-blue-600 mx-auto mb-8" data-aos="fade-up"></div>
            <p class="text-xl text-gray-300 max-w-3xl mx-auto" data-aos="fade-up">What my clients say about working with me</p>
        </div>
        
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
            <!-- Testimonial 1 -->
            <div class="testimonial-card p-6 rounded-xl" data-aos="fade-up">
                <div class="flex items-center mb-4">
                    <div class="w-12 h-12 rounded-full bg-blue-500 flex items-center justify-center text-white font-bold mr-4">RS</div>
                    <div>
                        <h4 class="font-bold">Rahul Sharma</h4>
                        <p class="text-blue-500 text-sm">Tecknify.com</p>
                    </div>
                </div>
                <p class="text-gray-300 mb-4">"Biswanath helped us increase our organic traffic by 35% in just 3 months. His SEO strategies are effective and data-driven."</p>
                <div class="flex text-yellow-400">
                    <i data-feather="star" class="w-4 h-4 fill-current"></i>
                    <i data-feather="star" class="w-4 h-4 fill-current"></i>
                    <i data-feather="star" class="w-4 h-4 fill-current"></i>
                    <i data-feather="star" class="w-4 h-4 fill-current"></i>
                    <i data-feather="star" class="w-4 h-4 fill-current"></i>
                </div>
            </div>
            
            <!-- Testimonial 2 -->
            <div class="testimonial-card p-6 rounded-xl" data-aos="fade-up" data-aos-delay="100">
                <div class="flex items-center mb-4">
                    <div class="w-12 h-12 rounded-full bg-blue-500 flex items-center justify-center text-white font-bold mr-4">PS</div>
                    <div>
                        <h4 class="font-bold">Priya Singh</h4>
                        <p class="text-blue-500 text-sm">DigitizeAds.com</p>
                    </div>
                </div>
                <p class="text-gray-300 mb-4">"Our cost per lead decreased by 40% after implementing Biswanath's PPC strategies. He truly understands digital advertising."</p>
                <div class="flex text-yellow-400">
                    <i data-feather="star" class="w-4 h-4 fill-current"></i>
                    <i data-feather="star" class="w-4 h-4 fill-current"></i>
                    <i data-feather="star" class="w-4 h-4 fill-current"></i>
                    <i data-feather="star" class="w-4 h-4 fill-current"></i>
                    <i data-feather="star" class="w-4 h-4 fill-current"></i>
                </div>
            </div>
            
            <!-- Testimonial 3 -->
            <div class="testimonial-card p-6 rounded-xl" data-aos="fade-up" data-aos-delay="200">
                <div class="flex items-center mb-4">
                    <div class="w-12 h-12 rounded-full bg-blue-500 flex items-center justify-center text-white font-bold mr-4">AS</div>
                    <div>
                        <h4 class="font-bold">Amit Saha</h4>
                        <p class="text-blue-500 text-sm">BL215.com</p>
                    </div>
                </div>
                <p class="text-gray-300 mb-4">"We achieved 3.8x ROAS on our Meta ads campaign. Biswanath's targeting strategies were spot on for our US audience."</p>
                <div class="flex text-yellow-400">
                    <i data-feather="star" class="w-4 h-4 fill-current"></i>
                    <i data-feather="star" class="w-4 h-4 fill-current"></i>
                    <i data-feather="star" class="w-4 h-4 fill-current"></i>
                    <i data-feather="star" class="w-4 h-4 fill-current"></i>
                    <i data-feather="star" class="w-4 h-4 fill-current"></i>
                </div>
            </div>
        </div>
    </section>

    <!-- Pricing Section -->
    <section id="pricing" class="py-20 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
        <div class="text-center mb-16">
            <h2 class="text-3xl md:text-4xl font-bold mb-4" data-aos="fade-up">Pricing Plans</h2>
            <div class="w-20 h-1 bg-blue-600 mx-auto mb-8" data-aos="fade-up"></div>
            <p class="text-xl text-gray-300 max-w-3xl mx-auto" data-aos="fade-up">Flexible pricing options to suit different business needs</p>
        </div>
        
        <div class="grid grid-cols-1 lg:grid-cols-3 gap-8">
            <!-- Plan 1 -->
            <div class="bg-gray-900 p-8 rounded-xl neon-border" data-aos="fade-up">
                <h3 class="text-2xl font-bold mb-4">Starter Plan</h3>
                <div class="mb-6">
                    <span class="text-gray-400 line-through">₹18,000/month</span>
                    <p class="text-3xl font-bold text-blue-500">₹15,000<span class="text-lg text-gray-300">/month</span></p>
                </div>
                <ul class="space-y-3 mb-8">
                    <li class="flex items-center">
                        <i data-feather="check" class="w-5 h-5 text-green-500 mr-2"></i>
                        <span>Basic SEO Optimization</span>
                    </li>
                    <li class="flex items-center">
                        <i data-feather="check" class="w-5 h-5 text-green-500 mr-2"></i>
                        <span>Social Media Management (2 platforms)</span>
                    </li>
                    <li class="flex items-center text-gray-400">
                        <i data-feather="x" class="w-5 h-5 text-red-500 mr-2"></i>
                        <span>Google & Meta Ads</span>
                    </li>
                    <li class="flex items-center text-gray-400">
                        <i data-feather="x" class="w-5 h-5 text-red-500 mr-2"></i>
                        <span>Brand Strategy</span>
                    </li>
                    <li class="flex items-center text-gray-400">
                        <i data-feather="x" class="w-5 h-5 text-red-500 mr-2"></i>
                        <span>Monthly Performance Reports</span>
                    </li>
                </ul>
                <a href="#contact" class="w-full bg-blue-600 hover:bg-blue-700 text-white font-bold py-3 px-4 rounded-full inline-flex items-center justify-center transition duration-300">
                    Get Started
                </a>
            </div>
            
            <!-- Plan 2 -->
            <div class="bg-gray-900 p-8 rounded-xl neon-border transform scale-105 relative" data-aos="fade-up" data-aos-delay="100">
                <div class="absolute top-0 right-0 bg-blue-600 text-white text-xs font-bold px-3 py-1 rounded-bl-lg rounded-tr-lg">POPULAR</div>
                <h3 class="text-2xl font-bold mb-4">Growth Plan</h3>
                <div class="mb-6">
                    <span class="text-gray-400 line-through">₹30,000/month</span>
                    <p class="text-3xl font-bold text-blue-500">₹25,000<span class="text-lg text-gray-300">/month</span></p>
                </div>
                <ul class="space-y-3 mb-8">
                    <li class="flex items-center">
                        <i data-feather="check" class="w-5 h-5 text-green-500 mr-2"></i>
                        <span>Comprehensive SEO Optimization</span>
                    </li>
                    <li class="flex items-center">
                        <i data-feather="check" class="w-5 h-5 text-green-500 mr-2"></i>
                        <span>Social Media Management (4 platforms)</span>
                    </li>
                    <li class="flex items-center">
                        <i data-feather="check" class="w-5 h-5 text-green-500 mr-2"></i>
                        <span>Google & Meta Ads Management</span>
                    </li>
                    <li class="flex items-center text-gray-400">
                        <i data-feather="x" class="w-5 h-5 text-red-500 mr-2"></i>
                        <span>Brand Strategy</span>
                    </li>
                    <li class="flex items-center">
                        <i data-feather="check" class="w-5 h-5 text-green-500 mr-2"></i>
                        <span>Monthly Performance Reports</span>
                    </li>
                </ul>
                <a href="#contact" class="w-full bg-blue-600 hover:bg-blue-700 text-white font-bold py-3 px-4 rounded-full inline-flex items-center justify-center transition duration-300">
                    Get Started
                </a>
            </div>
            
            <!-- Plan 3 -->
            <div class="bg-gray-900 p-8 rounded-xl neon-border" data-aos="fade-up" data-aos-delay="200">
                <h3 class="text-2xl font-bold mb-4">Premium Plan</h3>
                <div class="mb-6">
                    <span class="text-gray-400 line-through">₹50,000/month</span>
                    <p class="text-3xl font-bold text-blue-500">₹40,000<span class="text-lg text-gray-300">/month</span></p>
                </div>
                <ul class="space-y-3 mb-8">
                    <li class="flex items-center">
                        <i data-feather="check" class="w-5 h-5 text-green-500 mr-2"></i>
                        <span>Advanced SEO Optimization</span>
                    </li>
                    <li class="flex items-center">
                        <i data-feather="check" class="w-5 h-5 text-green-500 mr-2"></i>
                        <span>Social Media Management (All platforms)</span>
                    </li>
                    <li class="flex items-center">
                        <i data-feather="check" class="w-5 h-5 text-green-500 mr-2"></i>
                        <span>Google & Meta Ads Management</span>
                    </li>
                    <li class="flex items-center">
                        <i data-feather="check" class="w-5 h-5 text-green-500 mr-2"></i>
                        <span>Comprehensive Brand Strategy</span>
                    </li>
                    <li class="flex items-center">
                        <i data-feather="check" class="w-5 h-5 text-green-500 mr-2"></i>
                        <span>Weekly Performance Reports + Consultation</span>
                    </li>
                </ul>
                <a href="#contact" class="w-full bg-blue-600 hover:bg-blue-700 text-white font-bold py-3 px-4 rounded-full inline-flex items-center justify-center transition duration-300">
                    Get Started
                </a>
            </div>
        </div>
        
        <div class="mt-12 text-center" data-aos="fade-up">
            <p class="text-gray-400">Need a custom plan? <a href="#contact" class="text-blue-500 hover:text-blue-400 transition duration-300">Contact me</a> for tailored solutions.</p>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto bg-gray-800/50 rounded-xl">
        <div class="text-center mb-16">
            <h2 class="text-3xl md:text-4xl font-bold mb-4" data-aos="fade-up">Get In Touch</h2>
            <div class="w-20 h-1 bg-blue-600 mx-auto mb-8" data-aos="fade-up"></div>
            <p class="text-xl text-gray-300 max-w-3xl mx-auto" data-aos="fade-up">Ready to grow your business? Let's discuss your project.</p>
        </div>
        
        <div class="flex flex-col md:flex-row gap-12">
            <div class="md:w-1/2" data-aos="fade-right">
                <form class="space-y-6" id="contact-form">
                    <div>
                        <label for="name" class="block text-sm font-medium text-gray-300 mb-1">Name</label>
                        <input type="text" id="name" name="name" class="w-full bg-gray-800 border border-gray-700 rounded-lg px-4 py-3 focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-transparent" placeholder="Your name" required>
                    </div>
                    <div>
                        <label for="email" class="block text-sm font-medium text-gray-300 mb-1">Email</label>
                        <input type="email" id="email" name="email" class="w-full bg-gray-800 border border-gray-700 rounded-lg px-4 py-3 focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-transparent" placeholder="Your email" required>
                    </div>
                    <div>
                        <label for="service" class="block text-sm font-medium text-gray-300 mb-1">Service Needed</label>
                        <select id="service" name="service" class="w-full bg-gray-800 border border-gray-700 rounded-lg px-4 py-3 focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-transparent">
                            <option value="">Select a service</option>
                            <option value="seo">SEO Optimization</option>
                            <option value="social">Social Media Management</option>
                            <option value="ads">Google & Meta Ads</option>
                            <option value="branding">Brand Strategy & Design</option>
                            <option value="website">Website Support</option>
                            <option value="other">Other</option>
                        </select>
                    </div>
                    <div>
                        <label for="message" class="block text-sm font-medium text-gray-300 mb-1">Message</label>
                        <textarea id="message" name="message" rows="5" class="w-full bg-gray-800 border border-gray-700 rounded-lg px-4 py-3 focus:outline-none focus:ring-2 focus:ring-blue-500 focus:border-transparent" placeholder="Tell me about your project" required></textarea>
                    </div>
                    <button type="submit" class="w-full bg-blue-600 hover:bg-blue-700 text-white font-bold py-3 px-4 rounded-full inline-flex items-center justify-center transition duration-300">
                        Send Message
                        <i data-feather="send" class="ml-2"></i>
                    </button>
                </form>
            </div>
            
            <div class="md:w-1/2" data-aos="fade-left">
                <div class="bg-gray-800 p-8 rounded-xl glow-card h-full">
                    <h3 class="text-2xl font-bold mb-6">Let's Work Together</h3>
                    <div class="space-y-6">
                        <div class="flex items-start">
                            <div class="text-blue-500 mr-4">
                                <i data-feather="mail" class="w-6 h-6"></i>
                            </div>
                            <div>
                                <h4 class="font-medium text-gray-300">Email</h4>
                                <a href="mailto:clicknexis@gmail.com" class="text-gray-400 hover:text-blue-500 transition duration-300">clicknexis@gmail.com</a>
                            </div>
                        </div>
                        <div class="flex items-start">
                            <div class="text-blue-500 mr-4">
                                <i data-feather="phone" class="w-6 h-6"></i>
                            </div>
                            <div>
                                <h4 class="font-medium text-gray-300">Phone</h4>
                                <a href="tel:+919434535978" class="text-gray-400 hover:text-blue-500 transition duration-300">+91 9434535978</a>
                            </div>
                        </div>
                        <div class="flex items-start">
                            <div class="text-blue-500 mr-4">
                                <i data-feather="map-pin" class="w-6 h-6"></i>
                            </div>
                            <div>
                                <h4 class="font-medium text-gray-300">Location</h4>
                                <p class="text-gray-400">India</p>
                            </div>
                        </div>
                        <div class="flex items-start">
                            <div class="text-blue-500 mr-4">
                                <i data-feather="clock" class="w-6 h-6"></i>
                            </div>
                            <div>
                                <h4 class="font-medium text-gray-300">Response Time</h4>
                                <p class="text-gray-400">Within 24 hours</p>
                            </div>
                        </div>
                    </div>
                    
                    <div class="mt-8">
                        <h4 class="font-medium text-gray-300 mb-4">Follow Me</h4>
                        <div class="flex space-x-4">
                            <a href="https://www.instagram.com/clicknexis/" target="_blank" class="text-gray-400 hover:text-blue-500 transition duration-300 p-3 bg-gray-700 rounded-full">
                                <i data-feather="instagram" class="w-5 h-5"></i>
                            </a>
                            <a href="https://www.facebook.com/profile.php?id=61577877973358" target="_blank" class="text-gray-400 hover:text-blue-500 transition duration-300 p-3 bg-gray-700 rounded-full">
                                <i data-feather="facebook" class="w-5 h-5"></i>
                            </a>
                            <a href="https://www.linkedin.com/company/clicknexis/" target="_blank" class="text-gray-400 hover:text-blue-500 transition duration-300 p-3 bg-gray-700 rounded-full">
                                <i data-feather="linkedin" class="w-5 h-5"></i>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- FAQ Section -->
    <section class="py-20 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto">
        <div class="text-center mb-16">
            <h2 class="text-3xl md:text-4xl font-bold mb-4" data-aos="fade-up">Frequently Asked Questions</h2>
            <div class="w-20 h-1 bg-blue-600 mx-auto mb-8" data-aos="fade-up"></div>
        </div>
        
        <div class="max-w-3xl mx-auto space-y-6" data-aos="fade-up">
            <div class="bg-gray-800 rounded-xl p-6">
                <button class="flex justify-between items-center w-full text-left font-medium text-gray-100" onclick="toggleFAQ(this)">
                    <span>How long does it take to see results from SEO?</span>
                    <i data-feather="chevron-down" class="w-5 h-5 transform transition-transform"></i>
                </button>
                <div class="mt-4 text-gray-300 hidden">
                    <p>SEO is a long-term strategy. Typically, you can expect to see initial results within 3-6 months, with significant improvements occurring after 6-12 months of consistent effort. The timeline varies based on your industry competition, website age, and the current state of your SEO.</p>
                </div>
            </div>
            
            <div class="bg-gray-800 rounded-xl p-6">
                <button class="flex justify-between items-center w-full text-left font-medium text-gray-100" onclick="toggleFAQ(this)">
                    <span>Do you work with businesses outside of India?</span>
                    <i data-feather="chevron-down" class="w-5 h-5 transform transition-transform"></i>
                </button>
                <div class="mt-4 text-gray-300 hidden">
                    <p>Yes, I work with clients globally. Digital marketing knows no boundaries, and I have experience serving clients from various countries including the US, UK, Canada, and Australia. Communication happens primarily through email, video calls, and project management tools.</p>
                </div>
            </div>
            
            <div class="bg-gray-800 rounded-xl p-6">
                <button class="flex justify-between items-center w-full text-left font-medium text-gray-100" onclick="toggleFAQ(this)">
                    <span>What's included in your social media management service?</span>
                    <i data-feather="chevron-down" class="w-5 h-5 transform transition-transform"></i>
                </button>
                <div class="mt-4 text-gray-300 hidden">
                    <p>My social media management service includes content strategy development, content creation (graphics and copy), scheduling and publishing, community engagement, performance tracking, and monthly reports. The exact scope depends on the package you choose and the number of platforms needed.</p>
                </div>
            </div>
            
            <div class="bg-gray-800 rounded-xl p-6">
                <button class="flex justify-between items-center w-full text-left font-medium text-gray-100" onclick="toggleFAQ(this)">
                    <span>Can I cancel my monthly plan anytime?</span>
                    <i data-feather="chevron-down" class="w-5 h-5 transform transition-transform"></i>
                </button>
                <div class="mt-4 text-gray-300 hidden">
                    <p>Yes, my monthly plans operate on a month-to-month basis with no long-term contracts required. I require a 30-day notice for cancellation to properly wrap up ongoing campaigns and provide a comprehensive handover if needed.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 border-t border-gray-800 py-12 px-4 sm:px-6 lg:px-8">
        <div class="max-w-7xl mx-auto">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8 mb-8">
                <div>
                    <a href="#" class="text-2xl font-bold gradient-text block mb-4">ClickNexis</a>
                    <p class="text-gray-400 mb-4">Digital marketing solutions to grow your business online.</p>
                    <div class="flex space-x-4">
                        <a href="https://www.instagram.com/clicknexis/" target="_blank" class="text-gray-400 hover:text-blue-500 transition duration-300">
                            <i data-feather="instagram" class="w-5 h-5"></i>
                        </a>
                        <a href="https://www.facebook.com/profile.php?id=61577877973358" target="_blank" class="text-gray-400 hover:text-blue-500 transition duration-300">
                            <i data-feather="facebook" class="w-5 h-5"></i>
                        </a>
                        <a href="https://www.linkedin.com/company/clicknexis/" target="_blank" class="text-gray-400 hover:text-blue-500 transition duration-300">
                            <i data-feather="linkedin" class="w-5 h-5"></i>
                        </a>
                    </div>
                </div>
                
                <div>
                    <h3 class="text-lg font-bold mb-4">Services</h3>
                    <ul class="space-y-2">
                        <li><a href="#services" class="text-gray-400 hover:text-blue-500 transition duration-300">SEO Optimization</a></li>
                        <li><a href="#services" class="text-gray-400 hover:text-blue-500 transition duration-300">Social Media Management</a></li>
                        <li><a href="#services" class="text-gray-400 hover:text-blue-500 transition duration-300">Google & Meta Ads</a></li>
                        <li><a href="#services" class="text-gray-400 hover:text-blue-500 transition duration-300">Brand Strategy</a></li>
                        <li><a href="#services" class="text-gray-400 hover:text-blue-500 transition duration-300">Website Support</a></li>
                    </ul>
                </div>
                
                <div>
                    <h3 class="text-lg font-bold mb-4">Quick Links</h3>
                    <ul class="space-y-2">
                        <li><a href="#home" class="text-gray-400 hover:text-blue-500 transition duration-300">Home</a></li>
                        <li><a href="#about" class="text-gray-400 hover:text-blue-500 transition duration-300">About</a></li>
                        <li><a href="#projects" class="text-gray-400 hover:text-blue-500 transition duration-300">Projects</a></li>
                        <li><a href="#pricing" class="text-gray-400 hover:text-blue-500 transition duration-300">Pricing</a></li>
                        <li><a href="#contact" class="text-gray-400 hover:text-blue-500 transition duration-300">Contact</a></li>
                    </ul>
                </div>
                
                <div>
                    <h3 class="text-lg font-bold mb-4">Contact Info</h3>
                    <ul class="space-y-2">
                        <li class="text-gray-400">Email: clicknexis@gmail.com</li>
                        <li class="text-gray-400">Phone: +91 9434535978</li>
                        <li class="text-gray-400">Based in India</li>
                    </ul>
                </div>
            </div>
            
            <div class="pt-8 border-t border-gray-800 flex flex-col md:flex-row justify-between items-center">
                <p class="text-gray-400 text-sm">© 2023 ClickNexis. All rights reserved.</p>
                <div class="mt-4 md:mt-0">
                    <a href="#home" class="text-gray-400 hover:text-blue-500 text-sm transition duration-300 inline-flex items-center">
                        Back to top
                        <i data-feather="arrow-up" class="ml-1 w-4 h-4"></i>
                    </a>
                </div>
            </div>
        </div>
    </footer>

    <script>
        // Mobile menu toggle
        document.getElementById('mobile-menu-button').addEventListener('click', function() {
            const menu = document.getElementById('mobile-menu');
            menu.classList.toggle('hidden');
        });

        // Close mobile menu when clicking a link
        document.querySelectorAll('#mobile-menu a').forEach(link => {
            link.addEventListener('click', function() {
                document.getElementById('mobile-menu').classList.add('hidden');
            });
        });

        // Initialize AOS
        AOS.init({
            duration: 800,
            easing: 'ease-in-out',
            once: true
        });

        // Initialize Feather Icons
        feather.replace();
        
        // Form submission
        document.getElementById('contact-form').addEventListener('submit', function(e) {
            e.preventDefault();
            // Here you would typically send the form data to a server
            alert('Thank you for your message! I will get back to you soon.');
            this.reset();
        });
        
        // FAQ toggle function
        function toggleFAQ(element) {
            const content = element.nextElementSibling;
            const icon = element.querySelector('i');
            
            content.classList.toggle('hidden');
            icon.classList.toggle('rotate-180');
        }
        
        // Navbar background on scroll
        window.addEventListener('scroll', function() {
            const nav = document.querySelector('nav');
            if (window.scrollY > 50) {
                nav.classList.add('bg-gray-900');
                nav.classList.remove('bg-gray-900/90');
            } else {
                nav.classList.remove('bg-gray-900');
                nav.classList.add('bg-gray-900/90');
            }
        });
    </script>
</body>
</html>
