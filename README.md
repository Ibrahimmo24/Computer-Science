
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My IBM SkillBuild Journey | Software Development</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        /* Custom gradient text */
        .gradient-text {
            background: linear-gradient(90deg, #0062FF, #00D1FF);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
        }
        
        /* IBM color scheme */
        .ibm-blue {
            background-color: #0062FF;
        }
        
        .ibm-light-blue {
            background-color: #00D1FF;
        }
        
        /* Custom card hover effect */
        .learning-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1), 0 10px 10px -5px rgba(0, 0, 0, 0.04);
        }
        
        /* Smooth transitions */
        .smooth-transition * {
            transition: all 0.3s ease;
        }
    </style>
</head>
<body class="smooth-transition bg-gray-50 text-gray-800 min-h-screen">
    <!-- Navigation -->
    <nav class="bg-white shadow-lg sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-16">
                <div class="flex items-center">
                    <span class="text-xl font-bold gradient-text">IBM SkillBuild Journey</span>
                </div>
                <div class="hidden md:flex items-center space-x-8">
                    <a href="#overview" class="hover:text-blue-600 transition">Overview</a>
                    <a href="#learning" class="hover:text-blue-600 transition">My Learning</a>
                    <a href="#projects" class="hover:text-blue-600 transition">Projects</a>
                    <a href="#reflections" class="hover:text-blue-600 transition">Reflections</a>
                </div>
                <div class="md:hidden flex items-center">
                    <button id="mobileMenuButton" class="p-2 rounded-md hover:bg-gray-100">
                        <i class="fas fa-bars"></i>
                    </button>
                </div>
            </div>
        </div>
        
        <!-- Mobile menu -->
        <div id="mobileMenu" class="hidden md:hidden bg-white pb-4 px-4">
            <div class="flex flex-col space-y-2">
                <a href="#overview" class="block px-3 py-2 rounded-md hover:bg-gray-100">Overview</a>
                <a href="#learning" class="block px-3 py-2 rounded-md hover:bg-gray-100">My Learning</a>
                <a href="#projects" class="block px-3 py-2 rounded-md hover:bg-gray-100">Projects</a>
                <a href="#reflections" class="block px-3 py-2 rounded-md hover:bg-gray-100">Reflections</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <header class="py-20 px-4 sm:px-6 lg:px-8 ibm-blue text-white">
        <div class="max-w-7xl mx-auto text-center">
            <h1 class="text-4xl md:text-6xl font-extrabold mb-6">
                A Walk Through of <span class="gradient-text">Software Development</span>
            </h1>
            <p class="text-xl md:text-2xl opacity-90 mb-8 max-w-3xl mx-auto">
                My learning journey through IBM SkillBuild's Software Development curriculum
            </p>
            <div class="flex justify-center space-x-4">
                <a href="#learning" class="px-6 py-3 bg-white text-blue-600 hover:bg-gray-100 rounded-lg font-medium transition">
                    Explore My Learning
                </a>
                <a href="#projects" class="px-6 py-3 border border-white hover:bg-white hover:bg-opacity-10 rounded-lg font-medium transition">
                    View Projects
                </a>
            </div>
            <div class="mt-16 flex justify-center">
                <img src="https://upload.wikimedia.org/wikipedia/commons/5/51/IBM_logo.svg" 
                     alt="IBM Logo" 
                     class="h-16 opacity-90">
            </div>
        </div>
    </header>

    <!-- Overview Section -->
    <section id="overview" class="py-20 px-4 sm:px-6 lg:px-8 bg-white">
        <div class="max-w-7xl mx-auto">
            <h2 class="text-3xl md:text-4xl font-bold text-center mb-12">
                <span class="gradient-text">Program Overview</span>
            </h2>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8 mb-12">
                <div class="p-6 rounded-lg shadow-md border-t-4 border-blue-500">
                    <div class="text-blue-500 mb-4">
                        <i class="fas fa-laptop-code text-4xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-2">Comprehensive Curriculum</h3>
                    <p class="text-gray-600">
                        IBM SkillBuild covers all aspects of modern software development from fundamentals to advanced concepts.
                    </p>
                </div>
                
                <div class="p-6 rounded-lg shadow-md border-t-4 border-blue-500">
                    <div class="text-blue-500 mb-4">
                        <i class="fas fa-hands-helping text-4xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-2">Hands-on Learning</h3>
                    <p class="text-gray-600">
                        Practical exercises and real-world projects to apply theoretical knowledge in practical scenarios.
                    </p>
                </div>
                
                <div class="p-6 rounded-lg shadow-md border-t-4 border-blue-500">
                    <div class="text-blue-500 mb-4">
                        <i class="fas fa-certificate text-4xl"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-2">Industry Recognition</h3>
                    <p class="text-gray-600">
                        Skills and certifications recognized by industry leaders and employers worldwide.
                    </p>
                </div>
            </div>
            
            <div class="bg-blue-50 p-8 rounded-xl">
                <h3 class="text-2xl font-bold mb-4 text-blue-800">About My Journey</h3>
                <div class="prose max-w-none text-gray-700">
                    <p class="mb-4">
                        [Here you can write a brief introduction about your experience with the IBM SkillBuild program. Mention when you started, what motivated you, and your overall impressions.]
                    </p>
                    <p>
                        [You might want to include specific details about the Software Development track you followed and any specializations or focus areas.]
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Learning Section -->
    <section id="learning" class="py-20 px-4 sm:px-6 lg:px-8 bg-gray-50">
        <div class="max-w-7xl mx-auto">
            <h2 class="text-3xl md:text-4xl font-bold text-center mb-12">
                <span class="gradient-text">Key Learnings</span> from the Program
            </h2>
            
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <!-- Learning Card 1 -->
                <div class="learning-card bg-white rounded-xl shadow-md p-6 transition duration-300 hover:shadow-xl">
                    <div class="flex items-center mb-4">
                        <div class="p-3 rounded-lg bg-blue-100 text-blue-600">
                            <i class="fas fa-code text-2xl"></i>
                        </div>
                        <h3 class="text-xl font-bold ml-4">Programming Fundamentals</h3>
                    </div>
                    <div class="prose max-w-none text-gray-600 mb-4">
                        <p>[Describe what you learned about programming basics. You might include:]</p>
                        <ul class="list-disc pl-5 mt-2">
                            <li>Core programming concepts like variables, loops, and functions</li>
                            <li>Algorithmic thinking and problem-solving approaches</li>
                            <li>Programming paradigms covered in the course</li>
                        </ul>
                        <p class="mt-4">[Add any additional thoughts or insights about this learning area.]</p>
                    </div>
                </div>
                
                <!-- Learning Card 2 -->
                <div class="learning-card bg-white rounded-xl shadow-md p-6 transition duration-300 hover:shadow-xl">
                    <div class="flex items-center mb-4">
                        <div class="p-3 rounded-lg bg-blue-100 text-blue-600">
                            <i class="fas fa-globe text-2xl"></i>
                        </div>
                        <h3 class="text-xl font-bold ml-4">Web Development</h3>
                    </div>
                    <div class="prose max-w-none text-gray-600 mb-4">
                        <p>[Detail your web development learnings. You might include:]</p>
                        <ul class="list-disc pl-5 mt-2">
                            <li>HTML, CSS, and JavaScript fundamentals</li>
                            <li>Frontend frameworks or libraries covered</li>
                            <li>Responsive design principles</li>
                            <li>Web accessibility standards</li>
                        </ul>
                        <p class="mt-4">[Add any additional thoughts or insights about this learning area.]</p>
                    </div>
                </div>
                
                <!-- Learning Card 3 -->
                <div class="learning-card bg-white rounded-xl shadow-md p-6 transition duration-300 hover:shadow-xl">
                    <div class="flex items-center mb-4">
                        <div class="p-3 rounded-lg bg-blue-100 text-blue-600">
                            <i class="fas fa-server text-2xl"></i>
                        </div>
                        <h3 class="text-xl font-bold ml-4">Backend Development</h3>
                    </div>
                    <div class="prose max-w-none text-gray-600 mb-4">
                        <p>[Explain your backend development learnings. You might include:]</p>
                        <ul class="list-disc pl-5 mt-2">
                            <li>Server-side programming languages covered</li>
                            <li>Database management and design</li>
                            <li>API development and REST principles</li>
                            <li>Authentication and security practices</li>
                        </ul>
                        <p class="mt-4">[Add any additional thoughts or insights about this learning area.]</p>
                    </div>
                </div>
                
                <!-- Learning Card 4 -->
                <div class="learning-card bg-white rounded-xl shadow-md p-6 transition duration-300 hover:shadow-xl">
                    <div class="flex items-center mb-4">
                        <div class="p-3 rounded-lg bg-blue-100 text-blue-600">
                            <i class="fas fa-cloud text-2xl"></i>
                        </div>
                        <h3 class="text-xl font-bold ml-4">Cloud & DevOps</h3>
                    </div>
                    <div class="prose max-w-none text-gray-600 mb-4">
                        <p>[Describe your cloud and DevOps learnings. You might include:]</p>
                        <ul class="list-disc pl-5 mt-2">
                            <li>Cloud computing concepts and platforms</li>
                            <li>Containerization and orchestration tools</li>
                            <li>CI/CD pipelines</li>
                            <li>Infrastructure as code</li>
                        </ul>
                        <p class="mt-4">[Add any additional thoughts or insights about this learning area.]</p>
                    </div>
                </div>
                
                <!-- Learning Card 5 -->
                <div class="learning-card bg-white rounded-xl shadow-md p-6 transition duration-300 hover:shadow-xl">
                    <div class="flex items-center mb-4">
                        <div class="p-3 rounded-lg bg-blue-100 text-blue-600">
                            <i class="fas fa-shield-alt text-2xl"></i>
                        </div>
                        <h3 class="text-xl font-bold ml-4">Software Security</h3>
                    </div>
                    <div class="prose max-w-none text-gray-600 mb-4">
                        <p>[Explain your security learnings. You might include:]</p>
                        <ul class="list-disc pl-5 mt-2">
                            <li>Secure coding practices</li>
                            <li>Common vulnerabilities and how to prevent them</li>
                            <li>Encryption techniques</li>
                            <li>Security testing methodologies</li>
                        </ul>
                        <p class="mt-4">[Add any additional thoughts or insights about this learning area.]</p>
                    </div>
                </div>
                
                <!-- Learning Card 6 -->
                <div class="learning-card bg-white rounded-xl shadow-md p-6 transition duration-300 hover:shadow-xl">
                    <div class="flex items-center mb-4">
                        <div class="p-3 rounded-lg bg-blue-100 text-blue-600">
                            <i class="fas fa-users text-2xl"></i>
                        </div>
                        <h3 class="text-xl font-bold ml-4">Team Collaboration</h3>
                    </div>
                    <div class="prose max-w-none text-gray-600 mb-4">
                        <p>[Detail your collaboration learnings. You might include:]</p>
                        <ul class="list-disc pl-5 mt-2">
                            <li>Version control with Git</li>
                            <li>Agile methodologies</li>
                            <li>Code review practices</li>
                            <li>Documentation standards</li>
                        </ul>
                        <p class="mt-4">[Add any additional thoughts or insights about this learning area.]</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="py-20 px-4 sm:px-6 lg:px-8 bg-white">
        <div class="max-w-7xl mx-auto">
            <h2 class="text-3xl md:text-4xl font-bold text-center mb-12">
                <span class="gradient-text">Projects</span> & Practical Applications
            </h2>
            
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-8">
                <!-- Project 1 -->
                <div class="bg-gray-50 rounded-xl shadow-lg overflow-hidden border border-gray-200">
                    <div class="h-48 bg-gradient-to-r from-blue-500 to-blue-600 flex items-center justify-center">
                        <i class="fas fa-project-diagram text-white text-6xl"></i>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2">Project Name 1</h3>
                        <p class="text-gray-600 mb-4">
                            [Brief description of the project and its purpose]
                        </p>
                        <div class="mb-4">
                            <h4 class="font-semibold text-blue-600 mb-2">What I Learned:</h4>
                            <div class="prose max-w-none text-gray-700">
                                <p>[Describe the key learnings from this project. Be specific about technologies used and challenges overcome.]</p>
                            </div>
                        </div>
                        <div class="flex flex-wrap gap-2 mb-4">
                            <span class="px-2 py-1 bg-blue-100 text-blue-600 rounded-full text-xs">Technology 1</span>
                            <span class="px-2 py-1 bg-blue-100 text-blue-600 rounded-full text-xs">Technology 2</span>
                            <span class="px-2 py-1 bg-blue-100 text-blue-600 rounded-full text-xs">Technology 3</span>
                        </div>
                    </div>
                </div>
                
                <!-- Project 2 -->
                <div class="bg-gray-50 rounded-xl shadow-lg overflow-hidden border border-gray-200">
                    <div class="h-48 bg-gradient-to-r from-blue-400 to-blue-500 flex items-center justify-center">
                        <i class="fas fa-laptop-code text-white text-6xl"></i>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2">Project Name 2</h3>
                        <p class="text-gray-600 mb-4">
                            [Brief description of the project and its purpose]
                        </p>
                        <div class="mb-4">
                            <h4 class="font-semibold text-blue-600 mb-2">What I Learned:</h4>
                            <div class="prose max-w-none text-gray-700">
                                <p>[Describe the key learnings from this project. Be specific about technologies used and challenges overcome.]</p>
                            </div>
                        </div>
                        <div class="flex flex-wrap gap-2 mb-4">
                            <span class="px-2 py-1 bg-blue-100 text-blue-600 rounded-full text-xs">Technology 1</span>
                            <span class="px-2 py-1 bg-blue-100 text-blue-600 rounded-full text-xs">Technology 2</span>
                            <span class="px-2 py-1 bg-blue-100 text-blue-600 rounded-full text-xs">Technology 3</span>
                        </div>
                    </div>
                </div>
                
                <!-- Project 3 -->
                <div class="bg-gray-50 rounded-xl shadow-lg overflow-hidden border border-gray-200">
                    <div class="h-48 bg-gradient-to-r from-blue-600 to-blue-700 flex items-center justify-center">
                        <i class="fas fa-mobile-alt text-white text-6xl"></i>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2">Project Name 3</h3>
                        <p class="text-gray-600 mb-4">
                            [Brief description of the project and its purpose]
                        </p>
                        <div class="mb-4">
                            <h4 class="font-semibold text-blue-600 mb-2">What I Learned:</h4>
                            <div class="prose max-w-none text-gray-700">
                                <p>[Describe the key learnings from this project. Be specific about technologies used and challenges overcome.]</p>
                            </div>
                        </div>
                        <div class="flex flex-wrap gap-2 mb-4">
                            <span class="px-2 py-1 bg-blue-100 text-blue-600 rounded-full text-xs">Technology 1</span>
                            <span class="px-2 py-1 bg-blue-100 text-blue-600 rounded-full text-xs">Technology 2</span>
                            <span class="px-2 py-1 bg-blue-100 text-blue-600 rounded-full text-xs">Technology 3</span>
                        </div>
                    </div>
                </div>
                
                <!-- Project 4 -->
                <div class="bg-gray-50 rounded-xl shadow-lg overflow-hidden border border-gray-200">
                    <div class="h-48 bg-gradient-to-r from-blue-700 to-blue-800 flex items-center justify-center">
                        <i class="fas fa-database text-white text-6xl"></i>
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2">Project Name 4</h3>
                        <p class="text-gray-600 mb-4">
                            [Brief description of the project and its purpose]
                        </p>
                        <div class="mb-4">
                            <h4 class="font-semibold text-blue-600 mb-2">What I Learned:</h4>
                            <div class="prose max-w-none text-gray-700">
                                <p>[Describe the key learnings from this project. Be specific about technologies used and challenges overcome.]</p>
                            </div>
                        </div>
                        <div class="flex flex-wrap gap-2 mb-4">
                            <span class="px-2 py-1 bg-blue-100 text-blue-600 rounded-full text-xs">Technology 1</span>
                            <span class="px-2 py-1 bg-blue-100 text-blue-600 rounded-full text-xs">Technology 2</span>
                            <span class="px-2 py-1 bg-blue-100 text-blue-600 rounded-full text-xs">Technology 3</span>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="mt-12 bg-blue-50 p-8 rounded-xl">
                <h3 class="text-2xl font-bold mb-4 text-blue-800">Project Development Insights</h3>
                <div class="prose max-w-none text-gray-700">
                    <p>[Here you can add overall reflections on your project work. Discuss how these projects helped solidify your understanding of software development concepts, any particular challenges you faced, and how you overcame them.]</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Reflections Section -->
    <section id="reflections" class="py-20 px-4 sm:px-6 lg:px-8 bg-gray-50">
        <div class="max-w-7xl mx-auto">
            <h2 class="text-3xl md:text-4xl font-bold text-center mb-12">
                <span class="gradient-text">Personal Reflections</span> on the Journey
            </h2>
            
            <div class="bg-white rounded-xl shadow-md overflow-hidden">
                <div class="p-8">
                    <h3 class="text-2xl font-bold mb-6 text-blue-600">Growth as a Developer</h3>
                    <div class="prose max-w-none text-gray-700 mb-8">
                        <p>[Write about how your skills and understanding have evolved through this program. You might discuss:]</p>
                        <ul class="list-disc pl-5 mt-2">
                            <li>Your starting point and how far you've come</li>
                            <li>Breakthrough moments in your learning</li>
                            <li>How your approach to problem-solving has changed</li>
                            <li>New perspectives on software development</li>
                        </ul>
                    </div>
                    
                    <h3 class="text-2xl font-bold mb-6 text-blue-600">Challenges Overcome</h3>
                    <div class="prose max-w-none text-gray-700 mb-8">
                        <p>[Discuss the challenges you faced during the program and how you addressed them. This could include:]</p>
                        <ul class="list-disc pl-5 mt-2">
                            <li>Technical difficulties and how you solved them</li>
                            <li>Time management strategies</li>
                            <li>Learning curves for specific concepts</li>
                            <li>Resources that helped you overcome obstacles</li>
                        </ul>
                    </div>
                    
                    <h3 class="text-2xl font-bold mb-6 text-blue-600">Future Applications</h3>
                    <div class="prose max-w-none text-gray-700">
                        <p>[Share how you plan to apply what you've learned. Consider:]</p>
                        <ul class="list-disc pl-5 mt-2">
                            <li>Career aspirations and how this program supports them</li>
                            <li>Areas you want to explore further</li>
                            <li>Projects you'd like to build with your new skills</li>
                            <li>How you'll continue your learning journey</li>
                        </ul>
                    </div>
                </div>
            </div>
            
            <div class="mt-12 bg-blue-600 text-white p-8 rounded-xl">
                <h3 class="text-2xl font-bold mb-4">Final Thoughts</h3>
                <div class="prose max-w-none text-blue-100">
                    <p>[Conclude with your overall thoughts on the IBM SkillBuild Software Development program. What did it mean to you? How has it impacted your personal and professional development?]</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-gray-300 py-12 px-4 sm:px-6 lg:px-8">
        <div class="max-w-7xl mx-auto">
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div>
                    <h3 class="text-white font-bold text-lg mb-4">IBM SkillBuild Journey</h3>
                    <p class="mb-4">
                        Documenting my path through IBM's Software Development curriculum and sharing my learnings.
                    </p>
                    <div class="flex space-x-4">
                        <a href="#" class="hover:text-white"><i class="fab fa-linkedin-in"></i></a>
                        <a href="#" class="hover:text-white"><i class="fab fa-github"></i></a>
                        <a href="#" class="hover:text-white"><i class="fab fa-twitter"></i></a>
                    </div>
                </div>
                <div>
                    <h4 class="text-white font-bold mb-4">Navigation</h4>
                    <ul class="space-y-2">
                        <li><a href="#overview" class="hover:text-white">Overview</a></li>
                        <li><a href="#learning" class="hover:text-white">My Learning</a></li>
                        <li><a href="#projects" class="hover:text-white">Projects</a></li>
                        <li><a href="#reflections" class="hover:text-white">Reflections</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="text-white font-bold mb-4">IBM Resources</h4>
                    <ul class="space-y-2">
                        <li><a href="https://skillsbuild.org" target="_blank" class="hover:text-white">IBM SkillBuild Website</a></li>
                        <li><a href="https://www.ibm.com/training" target="_blank" class="hover:text-white">IBM Training</a></li>
                        <li><a href="https://developer.ibm.com" target="_blank" class="hover:text-white">IBM Developer</a></li>
                    </ul>
                </div>
            </div>
            <div class="border-t border-gray-700 mt-8 pt-8 text-center">
                <p>&copy; 2023 My IBM SkillBuild Journey. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <!-- Back to top button -->
    <button id="backToTop" class="fixed bottom-8 right-8 bg-blue-600 hover:bg-blue-700 text-white p-3 rounded-full shadow-lg hidden">
        <i class="fas fa-arrow-up"></i>
    </button>

    <script>
        // Mobile menu toggle
        const mobileMenuButton = document.getElementById('mobileMenuButton');
        const mobileMenu = document.getElementById('mobileMenu');
        
        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });
        
        // Back to top button
        const backToTopButton = document.getElementById('backToTop');
        
        window.addEventListener('scroll', () => {
            if (window.pageYOffset > 300) {
                backToTopButton.classList.remove('hidden');
            } else {
                backToTopButton.classList.add('hidden');
            }
        });
        
        backToTopButton.addEventListener('click', () => {
            window.scrollTo({ top: 0, behavior: 'smooth' });
        });
        
        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                
                const targetId = this.getAttribute('href');
                if (targetId === '#') return;
                
                const targetElement = document.querySelector(targetId);
                if (targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop - 80,
                        behavior: 'smooth'
                    });
                    
                    // Close mobile menu if open
                    mobileMenu.classList.add('hidden');
                }
            });
        });
    </script>
</body>
</html>
