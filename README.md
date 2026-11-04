# instructional-designer-portfolio
Transforming complex business needs into engaging, AI-driven learning experiences. Senior Instructional Designer with 9+ years of expertise in workforce capability, digital learning, compliance, and performance-focused solutions that deliver measurable organizational impact.
<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Abhishek Daida | Senior Instructional Designer & AI Learning Strategist</title>
    <meta name="description" content="Portfolio of Abhishek Daida - Senior Instructional Designer, Learning Experience Designer, eLearning Developer, and AI-Powered Learning Strategist.">
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    colors: {
                        navy: '#0A192F',
                        navyLight: '#112240',
                        tealAccent: '#64FFDA',
                        slateLight: '#8892B0',
                        lightBg: '#F8FAFC',
                        cardLight: '#FFFFFF',
                    }
                }
            }
        }
    </script>
    <link rel="stylesheet" href="css/styles.css">
    <!-- FontAwesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body class="bg-lightBg text-slate-800 dark:bg-navy dark:text-gray-200 font-sans transition-colors duration-300">

    <!-- Header Navigation -->
    <header class="fixed w-full top-0 z-50 backdrop-blur-md bg-white/80 dark:bg-navy/80 border-b border-gray-200 dark:border-gray-800">
        <div class="max-w-7xl mx-auto px-6 py-4 flex justify-between items-center">
            <a href="#home" class="text-xl font-bold tracking-tight text-navy dark:text-white">
                Abhishek Daida <span class="text-teal-600 dark:text-tealAccent">.ID</span>
            </a>
            <nav class="hidden md:flex space-x-8 text-sm font-medium">
                <a href="#about" class="hover:text-teal-600 dark:hover:text-tealAccent transition">About</a>
                <a href="#skills" class="hover:text-teal-600 dark:hover:text-tealAccent transition">Skills</a>
                <a href="#process" class="hover:text-teal-600 dark:hover:text-tealAccent transition">Process</a>
                <a href="#portfolio" class="hover:text-teal-600 dark:hover:text-tealAccent transition">Portfolio</a>
                <a href="#casestudies" class="hover:text-teal-600 dark:hover:text-tealAccent transition">Case Studies</a>
                <a href="#impact" class="hover:text-teal-600 dark:hover:text-tealAccent transition">Impact</a>
                <a href="#contact" class="hover:text-teal-600 dark:hover:text-tealAccent transition">Contact</a>
            </nav>
            <div class="flex items-center space-x-4">
                <button id="themeToggle" class="p-2 rounded-full hover:bg-gray-200 dark:hover:bg-navyLight transition" aria-label="Toggle Theme">
                    <i class="fas fa-moon dark:hidden text-navy"></i>
                    <i class="fas fa-sun hidden dark:block text-tealAccent"></i>
                </button>
                <button id="mobileMenuBtn" class="md:hidden text-xl focus:outline-none">
                    <i class="fas fa-bars"></i>
                </button>
            </div>
        </div>
        <!-- Mobile Navigation Menu -->
        <div id="mobileMenu" class="hidden md:hidden bg-white dark:bg-navyLight border-b border-gray-200 dark:border-gray-800 px-6 py-4 space-y-3">
            <a href="#about" class="block hover:text-teal-600 dark:hover:text-tealAccent">About</a>
            <a href="#skills" class="block hover:text-teal-600 dark:hover:text-tealAccent">Skills</a>
            <a href="#process" class="block hover:text-teal-600 dark:hover:text-tealAccent">Process</a>
            <a href="#portfolio" class="block hover:text-teal-600 dark:hover:text-tealAccent">Portfolio</a>
            <a href="#casestudies" class="block hover:text-teal-600 dark:hover:text-tealAccent">Case Studies</a>
            <a href="#impact" class="block hover:text-teal-600 dark:hover:text-tealAccent">Impact</a>
            <a href="#contact" class="block hover:text-teal-600 dark:hover:text-tealAccent">Contact</a>
        </div>
    </header>

    <!-- Home Section -->
    <section id="home" class="min-h-screen flex items-center pt-24 px-6 max-w-7xl mx-auto">
        <div class="grid md:grid-cols-2 gap-12 items-center w-full">
            <div class="space-y-6">
                <div class="inline-block px-3 py-1 rounded-full text-xs font-semibold bg-teal-100 text-teal-800 dark:bg-tealAccent/10 dark:text-tealAccent">
                    AI-Driven Learning Specialist
                </div>
                <h1 class="text-4xl sm:text-6xl font-extrabold tracking-tight text-navy dark:text-white leading-tight">
                    Abhishek Daida
                </h1>
                <h2 class="text-xl sm:text-2xl font-semibold text-teal-600 dark:text-tealAccent">
                    Senior Instructional Designer | Learning Experience Designer | eLearning Developer | AI-Powered Learning Strategist
                </h2>
                <p class="text-gray-600 dark:text-slateLight text-lg max-w-xl">
                    Instructional Designer with 9+ years of expertise in AI-driven learning solutions and modern instructional design methodologies[cite: 1]. Proven track record of designing and delivering 500+ digital learning programs for 50,000+ global learners, enhancing engagement by 40%, reducing development time by 30%, and accelerating skill acquisition[cite: 1].
                </p>
                <div class="flex flex-wrap gap-4 pt-4">
                    <a href="#portfolio" class="px-6 py-3 rounded-lg bg-navy text-white dark:bg-tealAccent dark:text-navy font-semibold shadow-lg hover:opacity-90 transition">
                        View Work
                    </a>
                    <a href="assets/docs/Abhishek_Daida_Resume.pdf" download class="px-6 py-3 rounded-lg border-2 border-navy text-navy dark:border-tealAccent dark:text-tealAccent font-semibold hover:bg-navy hover:text-white dark:hover:bg-tealAccent/10 transition">
                        Download Resume
                    </a>
                    <a href="#contact" class="px-6 py-3 rounded-lg border border-gray-300 dark:border-gray-700 font-semibold hover:bg-gray-100 dark:hover:bg-navyLight transition">
                        Contact Me
                    </a>
                </div>
            </div>
            <div class="flex justify-center">
                <div class="relative w-72 h-72 sm:w-80 sm:h-80 rounded-2xl overflow-hidden shadow-2xl border-4 border-white dark:border-navyLight">
                    <img src="assets/images/profile.jpg" alt="Abhishek Daida" class="w-full h-full object-cover" onerror="this.onerror=null; this.src='https://via.placeholder.com/400x400?text=Abhishek+Daida';">
                </div>
            </div>
        </div>
    </section>

    <!-- About Me Section -->
    <section id="about" class="py-24 px-6 max-w-7xl mx-auto border-t border-gray-200 dark:border-gray-800">
        <h2 class="text-3xl font-bold text-navy dark:text-white mb-2 text-center">About Me</h2>
        <p class="text-center text-gray-600 dark:text-slateLight mb-16 max-w-2xl mx-auto">
            My career journey, expertise across regulated industries, and what makes my learning design approach unique.
        </p>

        <div class="grid md:grid-cols-2 gap-12 mb-16">
            <div class="space-y-4 text-gray-600 dark:text-slateLight leading-relaxed">
                <h3 class="text-2xl font-bold text-navy dark:text-white">Background & Journey</h3>
                <p>
                    I specialize in end-to-end instructional design, eLearning development, curriculum architecture, performance consulting, learning analytics, and content localization in 16 languages[cite: 1]. Adept at aligning learning strategies with organizational goals to drive capability development, compliance, productivity, and measurable business outcomes[cite: 1].
                </p>
                <p>
                    From classroom lecturing in engineering to leading global compliance learning initiatives at pharmaceutical giants like Novartis, my journey has been centered on simplifying complex technical/regulatory information into engaging, high-impact digital learning[cite: 1, 2].
                </p>
            </div>
            <div class="space-y-4">
                <h3 class="text-2xl font-bold text-navy dark:text-white">What Makes Me Unique</h3>
                <div class="bg-white dark:bg-navyLight p-6 rounded-xl border border-gray-200 dark:border-gray-800 shadow-sm space-y-3">
                    <div class="flex items-start space-x-3">
                        <i class="fas fa-robot text-teal-600 dark:text-tealAccent mt-1"></i>
                        <p class="text-sm"><strong class="text-navy dark:text-white">AI Integration:</strong> Leveraging Copilot, ChatGPT, Synthesia, and Mindsmith to accelerate development effort by up to 40%[cite: 2].</p>
                    </div>
                    <div class="flex items-start space-x-3">
                        <i class="fas fa-globe text-teal-600 dark:text-tealAccent mt-1"></i>
                        <p class="text-sm"><strong class="text-navy dark:text-white">Global Scale & Localization:</strong> Deployed 800+ learning assets across 16 languages for 50,000+ global learners[cite: 1].</p>
                    </div>
                    <div class="flex items-start space-x-3">
                        <i class="fas fa-shield-alt text-teal-600 dark:text-tealAccent mt-1"></i>
                        <p class="text-sm"><strong class="text-navy dark:text-white">Regulated & Compliance Focus:</strong> Expert in healthcare/pharma SOP compliance and audit-ready documentation[cite: 1].</p>
                    </div>
                </div>
            </div>
        </div>

        <!-- Career Timeline -->
        <h3 class="text-2xl font-bold text-navy dark:text-white mb-8 text-center">Career Timeline</h3>
        <div class="relative border-l-2 border-teal-500/30 ml-4 md:ml-32 space-y-8">
            <div class="relative pl-8">
                <div class="absolute -left-[9px] top-1.5 w-4 h-4 rounded-full bg-teal-500"></div>
                <span class="text-xs font-semibold text-teal-600 dark:text-tealAccent">Dec 2024 - Present</span>
                <h4 class="text-lg font-bold text-navy dark:text-white">Instructional Designer - Global Compliance & Capability Learning</h4>
                <p class="text-sm text-gray-500 dark:text-slateLight">Novartis Healthcare Pvt. Ltd. | Hyderabad, India[cite: 1]</p>
                <p class="text-sm text-gray-600 dark:text-slateLight mt-2">Led enterprise AI initiatives (Microsoft Copilot), built 600+ web-based trainings, and managed four consecutive enterprise releases on schedule[cite: 1, 2].</p>
            </div>
            <div class="relative pl-8">
                <div class="absolute -left-[9px] top-1.5 w-4 h-4 rounded-full bg-teal-500"></div>
                <span class="text-xs font-semibold text-teal-600 dark:text-tealAccent">Jan 2023 - Dec 2024</span>
                <h4 class="text-lg font-bold text-navy dark:text-white">Design Engineer - Learning Content & eLearning Development</h4>
                <p class="text-sm text-gray-500 dark:text-slateLight">RIGTCOM Geo Services LLP | Hyderabad, India[cite: 2]</p>
                <p class="text-sm text-gray-600 dark:text-slateLight mt-2">Translated complex business/technical content into scenario-based practice using ADDIE, Bloom's Taxonomy, and Kirkpatrick evaluations[cite: 2].</p>
            </div>
            <div class="relative pl-8">
                <div class="absolute -left-[9px] top-1.5 w-4 h-4 rounded-full bg-teal-500"></div>
                <span class="text-xs font-semibold text-teal-600 dark:text-tealAccent">May 2021 - Nov 2021</span>
                <h4 class="text-lg font-bold text-navy dark:text-white">Design Specialist - Learning Solutions</h4>
                <p class="text-sm text-gray-500 dark:text-slateLight">Cyient Limited | Hyderabad, India[cite: 2]</p>
                <p class="text-sm text-gray-600 dark:text-slateLight mt-2">Built targeted learning solutions aligned to stated business objectives to improve client-facing performance[cite: 2].</p>
            </div>
            <div class="relative pl-8">
                <div class="absolute -left-[9px] top-1.5 w-4 h-4 rounded-full bg-teal-500"></div>
                <span class="text-xs font-semibold text-teal-600 dark:text-tealAccent">Jul 2018 - May 2021</span>
                <h4 class="text-lg font-bold text-navy dark:text-white">Senior Executive Training & Compliance</h4>
                <p class="text-sm text-gray-500 dark:text-slateLight">Jio Infocom Limited | Hyderabad, India[cite: 2]</p>
                <p class="text-sm text-gray-600 dark:text-slateLight mt-2">Facilitated site safety, regulatory compliance, data protection, and new hire onboarding programs[cite: 2].</p>
            </div>
            <div class="relative pl-8">
                <div class="absolute -left-[9px] top-1.5 w-4 h-4 rounded-full bg-teal-500"></div>
                <span class="text-xs font-semibold text-teal-600 dark:text-tealAccent">Aug 2016 - Jun 2018</span>
                <h4 class="text-lg font-bold text-navy dark:text-white">Lecturer</h4>
                <p class="text-sm text-gray-500 dark:text-slateLight">Sana Engineering College | Hyderabad, India[cite: 2]</p>
                <p class="text-sm text-gray-600 dark:text-slateLight mt-2">Designed complete curricula, assignments, and facilitated discussion-led sessions[cite: 2].</p>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="py-24 px-6 max-w-7xl mx-auto border-t border-gray-200 dark:border-gray-800">
        <h2 class="text-3xl font-bold text-navy dark:text-white mb-2 text-center">Skills & Competencies</h2>
        <p class="text-center text-gray-600 dark:text-slateLight mb-16 max-w-2xl mx-auto">Categorized overview of my ID methodologies, authoring tools, and AI techniques.</p>

        <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-6">
            <!-- Instructional Design -->
            <div class="bg-white dark:bg-navyLight p-6 rounded-xl border border-gray-200 dark:border-gray-800 shadow-sm hover:shadow-md transition">
                <div class="w-12 h-12 rounded-lg bg-teal-100 dark:bg-tealAccent/10 text-teal-600 dark:text-tealAccent flex items-center justify-center text-xl mb-4">
                    <i class="fas fa-brain"></i>
                </div>
                <h3 class="text-xl font-bold text-navy dark:text-white mb-3">Instructional Design</h3>
                <ul class="space-y-2 text-sm text-gray-600 dark:text-slateLight">
                    <li>• ADDIE & SAM Frameworks[cite: 1]</li>
                    <li>• Bloom's Taxonomy & Gagné[cite: 1]</li>
                    <li>• Adult Learning Principles</li>
                    <li>• Performance Consulting[cite: 1]</li>
                    <li>• Kirkpatrick Evaluation[cite: 1]</li>
                </ul>
            </div>

            <!-- Learning Development -->
            <div class="bg-white dark:bg-navyLight p-6 rounded-xl border border-gray-200 dark:border-gray-800 shadow-sm hover:shadow-md transition">
                <div class="w-12 h-12 rounded-lg bg-teal-100 dark:bg-tealAccent/10 text-teal-600 dark:text-tealAccent flex items-center justify-center text-xl mb-4">
                    <i class="fas fa-layer-group"></i>
                </div>
                <h3 class="text-xl font-bold text-navy dark:text-white mb-3">Learning Development</h3>
                <ul class="space-y-2 text-sm text-gray-600 dark:text-slateLight">
                    <li>• Storyboarding & Prototypes[cite: 1]</li>
                    <li>• WBT / CBT Development[cite: 1]</li>
                    <li>• VILT & Blended Learning[cite: 1]</li>
                    <li>• Microlearning & Job Aids[cite: 1]</li>
                    <li>• Content Localization (16 Languages)[cite: 1]</li>
                </ul>
            </div>

            <!-- Authoring Tools -->
            <div class="bg-white dark:bg-navyLight p-6 rounded-xl border border-gray-200 dark:border-gray-800 shadow-sm hover:shadow-md transition">
                <div class="w-12 h-12 rounded-lg bg-teal-100 dark:bg-tealAccent/10 text-teal-600 dark:text-tealAccent flex items-center justify-center text-xl mb-4">
                    <i class="fas fa-tools"></i>
                </div>
                <h3 class="text-xl font-bold text-navy dark:text-white mb-3">Tools & Software</h3>
                <ul class="space-y-2 text-sm text-gray-600 dark:text-slateLight">
                    <li>• Articulate Storyline 360 & Rise 360[cite: 1]</li>
                    <li>• Vyond (Animation)[cite: 1]</li>
                    <li>• Camtasia & Clipchamp[cite: 1]</li>
                    <li>• Adobe Captivate & Mindsmith[cite: 1]</li>
                    <li>• LMS Administration</li>
                </ul>
            </div>

            <!-- AI for Learning -->
            <div class="bg-white dark:bg-navyLight p-6 rounded-xl border border-gray-200 dark:border-gray-800 shadow-sm hover:shadow-md transition">
                <div class="w-12 h-12 rounded-lg bg-teal-100 dark:bg-tealAccent/10 text-teal-600 dark:text-tealAccent flex items-center justify-center text-xl mb-4">
                    <i class="fas fa-magic"></i>
                </div>
                <h3 class="text-xl font-bold text-navy dark:text-white mb-3">AI for Learning</h3>
                <ul class="space-y-2 text-sm text-gray-600 dark:text-slateLight">
                    <li>• Microsoft Copilot & ChatGPT[cite: 1]</li>
                    <li>• Synthesia & Articulate AI[cite: 2]</li>
                    <li>• AI Storyboarding & Scripting[cite: 2]</li>
                    <li>• Automated Assessment Design[cite: 2]</li>
                    <li>• AI Governance & Adoption[cite: 1]</li>
                </ul>
            </div>
        </div>
    </section>

    <!-- My Process Section -->
    <section id="process" class="py-24 px-6 max-w-7xl mx-auto border-t border-gray-200 dark:border-gray-800">
        <h2 class="text-3xl font-bold text-navy dark:text-white mb-2 text-center">My Instructional Design Process</h2>
        <p class="text-center text-gray-600 dark:text-slateLight mb-16 max-w-2xl mx-auto">A structured, ADDIE & SAM aligned workflow enhanced by AI efficiency.</p>

        <div class="grid md:grid-cols-5 gap-4">
            <div class="bg-white dark:bg-navyLight p-6 rounded-xl border border-gray-200 dark:border-gray-800 text-center relative group hover:-translate-y-1 transition">
                <div class="text-xs font-bold text-teal-600 dark:text-tealAccent mb-2">STEP 01</div>
                <h3 class="font-bold text-lg text-navy dark:text-white mb-2">Analysis</h3>
                <p class="text-xs text-gray-500 dark:text-slateLight">Audience profiling, SME alignment, learning needs analysis & ROI definition[cite: 2].</p>
            </div>
            <div class="bg-white dark:bg-navyLight p-6 rounded-xl border border-gray-200 dark:border-gray-800 text-center relative group hover:-translate-y-1 transition">
                <div class="text-xs font-bold text-teal-600 dark:text-tealAccent mb-2">STEP 02</div>
                <h3 class="font-bold text-lg text-navy dark:text-white mb-2">Design</h3>
                <p class="text-xs text-gray-500 dark:text-slateLight">Storyboarding, curriculum mapping, AI prompt design & visual prototypes[cite: 1, 2].</p>
            </div>
            <div class="bg-white dark:bg-navyLight p-6 rounded-xl border border-gray-200 dark:border-gray-800 text-center relative group hover:-translate-y-1 transition">
                <div class="text-xs font-bold text-teal-600 dark:text-tealAccent mb-2">STEP 03</div>
                <h3 class="font-bold text-lg text-navy dark:text-white mb-2">Development</h3>
                <p class="text-xs text-gray-500 dark:text-slateLight">Storyline/Rise build, Vyond video production & AI localization[cite: 1, 2].</p>
            </div>
            <div class="bg-white dark:bg-navyLight p-6 rounded-xl border border-gray-200 dark:border-gray-800 text-center relative group hover:-translate-y-1 transition">
                <div class="text-xs font-bold text-teal-600 dark:text-tealAccent mb-2">STEP 04</div>
                <h3 class="font-bold text-lg text-navy dark:text-white mb-2">Implementation</h3>
                <p class="text-xs text-gray-500 dark:text-slateLight">LMS deployment, SCORM/xAPI verification & global release management[cite: 1, 2].</p>
            </div>
            <div class="bg-white dark:bg-navyLight p-6 rounded-xl border border-gray-200 dark:border-gray-800 text-center relative group hover:-translate-y-1 transition">
                <div class="text-xs font-bold text-teal-600 dark:text-tealAccent mb-2">STEP 05</div>
                <h3 class="font-bold text-lg text-navy dark:text-white mb-2">Evaluation</h3>
                <p class="text-xs text-gray-500 dark:text-slateLight">Kirkpatrick model analytics, learner feedback & continuous iteration[cite: 1, 2].</p>
            </div>
        </div>
    </section>

    <!-- Portfolio / Work Samples Section -->
    <section id="portfolio" class="py-24 px-6 max-w-7xl mx-auto border-t border-gray-200 dark:border-gray-800">
        <h2 class="text-3xl font-bold text-navy dark:text-white mb-2 text-center">Portfolio & Work Samples</h2>
        <p class="text-center text-gray-600 dark:text-slateLight mb-16 max-w-2xl mx-auto">Explore interactive samples, storyboards, and multimedia eLearning assets.</p>

        <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-6">
            <!-- Sample 1 -->
            <div class="bg-white dark:bg-navyLight rounded-xl border border-gray-200 dark:border-gray-800 overflow-hidden flex flex-col justify-between">
                <div>
                    <img src="assets/images/thumbnails/wbt-sample.jpg" alt="WBT Sample" class="w-full h-40 object-cover" onerror="this.onerror=null; this.src='https://via.placeholder.com/300x160?text=WBT+Sample';">
                    <div class="p-5">
                        <h3 class="font-bold text-lg text-navy dark:text-white mb-2">WBT Sample</h3>
                        <p class="text-xs text-gray-600 dark:text-slateLight mb-4">[ADD CONTENT HERE - Brief summary of web-based training interactive module]</p>
                        <div class="text-xs text-teal-600 dark:text-tealAccent font-semibold mb-1">Skills: Scenario-Based Design</div>
                        <div class="text-xs text-gray-500 dark:text-slateLight mb-4">Tech: Articulate Storyline 360</div>
                    </div>
                </div>
                <div class="p-5 pt-0">
                    <a href="assets/projects/wbt-sample/index.html" target="_blank" class="block text-center py-2 px-4 rounded bg-navy text-white dark:bg-tealAccent dark:text-navy text-xs font-bold hover:opacity-90 transition">View Project</a>
                </div>
            </div>

            <!-- Sample 2 -->
            <div class="bg-white dark:bg-navyLight rounded-xl border border-gray-200 dark:border-gray-800 overflow-hidden flex flex-col justify-between">
                <div>
                    <img src="assets/images/thumbnails/storyboard-sample.jpg" alt="Storyboard Sample" class="w-full h-40 object-cover" onerror="this.onerror=null; this.src='https://via.placeholder.com/300x160?text=Storyboard+Sample';">
                    <div class="p-5">
                        <h3 class="font-bold text-lg text-navy dark:text-white mb-2">Storyboard Sample</h3>
                        <p class="text-xs text-gray-600 dark:text-slateLight mb-4">[ADD CONTENT HERE - Visual script and interaction design blueprint]</p>
                        <div class="text-xs text-teal-600 dark:text-tealAccent font-semibold mb-1">Skills: Instructional Scripting</div>
                        <div class="text-xs text-gray-500 dark:text-slateLight mb-4">Tech: MS Copilot / Word</div>
                    </div>
                </div>
                <div class="p-5 pt-0">
                    <a href="assets/docs/Storyboard_Sample.pdf" target="_blank" class="block text-center py-2 px-4 rounded bg-navy text-white dark:bg-tealAccent dark:text-navy text-xs font-bold hover:opacity-90 transition">View Project</a>
                </div>
            </div>

            <!-- Sample 3 -->
            <div class="bg-white dark:bg-navyLight rounded-xl border border-gray-200 dark:border-gray-800 overflow-hidden flex flex-col justify-between">
                <div>
                    <img src="assets/images/thumbnails/rise-course.jpg" alt="Rise Course" class="w-full h-40 object-cover" onerror="this.onerror=null; this.src='https://via.placeholder.com/300x160?text=Rise+360+Course';">
                    <div class="p-5">
                        <h3 class="font-bold text-lg text-navy dark:text-white mb-2">Rise 360 Course</h3>
                        <p class="text-xs text-gray-600 dark:text-slateLight mb-4">[ADD CONTENT HERE - Responsive modular eLearning course]</p>
                        <div class="text-xs text-teal-600 dark:text-tealAccent font-semibold mb-1">Skills: Mobile-First Microlearning</div>
                        <div class="text-xs text-gray-500 dark:text-slateLight mb-4">Tech: Articulate Rise 360</div>
                    </div>
                </div>
                <div class="p-5 pt-0">
                    <a href="assets/projects/rise-course/index.html" target="_blank" class="block text-center py-2 px-4 rounded bg-navy text-white dark:bg-tealAccent dark:text-navy text-xs font-bold hover:opacity-90 transition">View Project</a>
                </div>
            </div>

            <!-- Sample 4 -->
            <div class="bg-white dark:bg-navyLight rounded-xl border border-gray-200 dark:border-gray-800 overflow-hidden flex flex-col justify-between">
                <div>
                    <img src="assets/images/thumbnails/storyline-course.jpg" alt="Storyline Course" class="w-full h-40 object-cover" onerror="this.onerror=null; this.src='https://via.placeholder.com/300x160?text=Storyline+Course';">
                    <div class="p-5">
                        <h3 class="font-bold text-lg text-navy dark:text-white mb-2">Storyline Course</h3>
                        <p class="text-xs text-gray-600 dark:text-slateLight mb-4">[ADD CONTENT HERE - Advanced gamified eLearning module]</p>
                        <div class="text-xs text-teal-600 dark:text-tealAccent font-semibold mb-1">Skills: Advanced Variables & Logic</div>
                        <div class="text-xs text-gray-500 dark:text-slateLight mb-4">Tech: Storyline 360</div>
                    </div>
                </div>
                <div class="p-5 pt-0">
                    <a href="assets/projects/storyline-course/index.html" target="_blank" class="block text-center py-2 px-4 rounded bg-navy text-white dark:bg-tealAccent dark:text-navy text-xs font-bold hover:opacity-90 transition">View Project</a>
                </div>
            </div>

            <!-- Sample 5 -->
            <div class="bg-white dark:bg-navyLight rounded-xl border border-gray-200 dark:border-gray-800 overflow-hidden flex flex-col justify-between">
                <div>
                    <img src="assets/images/thumbnails/compliance-training.jpg" alt="Compliance Training" class="w-full h-40 object-cover" onerror="this.onerror=null; this.src='https://via.placeholder.com/300x160?text=Compliance+Training';">
                    <div class="p-5">
                        <h3 class="font-bold text-lg text-navy dark:text-white mb-2">Compliance Training</h3>
                        <p class="text-xs text-gray-600 dark:text-slateLight mb-4">[ADD CONTENT HERE - Pharma audit-ready compliance course]</p>
                        <div class="text-xs text-teal-600 dark:text-tealAccent font-semibold mb-1">Skills: SOP & Regulatory Learning</div>
                        <div class="text-xs text-gray-500 dark:text-slateLight mb-4">Tech: Rise 360 / Storyline</div>
                    </div>
                </div>
                <div class="p-5 pt-0">
                    <a href="#" class="block text-center py-2 px-4 rounded bg-navy text-white dark:bg-tealAccent dark:text-navy text-xs font-bold hover:opacity-90 transition">View Project</a>
                </div>
            </div>

            <!-- Sample 6 -->
            <div class="bg-white dark:bg-navyLight rounded-xl border border-gray-200 dark:border-gray-800 overflow-hidden flex flex-col justify-between">
                <div>
                    <img src="assets/images/thumbnails/microlearning.jpg" alt="Microlearning" class="w-full h-40 object-cover" onerror="this.onerror=null; this.src='https://via.placeholder.com/300x160?text=Microlearning';">
                    <div class="p-5">
                        <h3 class="font-bold text-lg text-navy dark:text-white mb-2">Microlearning</h3>
                        <p class="text-xs text-gray-600 dark:text-slateLight mb-4">[ADD CONTENT HERE - Bite-sized performance support asset]</p>
                        <div class="text-xs text-teal-600 dark:text-tealAccent font-semibold mb-1">Skills: Just-in-Time Learning</div>
                        <div class="text-xs text-gray-500 dark:text-slateLight mb-4">Tech: Mindsmith / Canva</div>
                    </div>
                </div>
                <div class="p-5 pt-0">
                    <a href="#" class="block text-center py-2 px-4 rounded bg-navy text-white dark:bg-tealAccent dark:text-navy text-xs font-bold hover:opacity-90 transition">View Project</a>
                </div>
            </div>

            <!-- Sample 7 -->
            <div class="bg-white dark:bg-navyLight rounded-xl border border-gray-200 dark:border-gray-800 overflow-hidden flex flex-col justify-between">
                <div>
                    <img src="assets/images/thumbnails/vyond-animation.jpg" alt="Vyond Animation" class="w-full h-40 object-cover" onerror="this.onerror=null; this.src='https://via.placeholder.com/300x160?text=Vyond+Animation';">
                    <div class="p-5">
                        <h3 class="font-bold text-lg text-navy dark:text-white mb-2">Vyond Animation</h3>
                        <p class="text-xs text-gray-600 dark:text-slateLight mb-4">[ADD CONTENT HERE - Animated scenario video for learner engagement]</p>
                        <div class="text-xs text-teal-600 dark:text-tealAccent font-semibold mb-1">Skills: Visual Storytelling</div>
                        <div class="text-xs text-gray-500 dark:text-slateLight mb-4">Tech: Vyond / Camtasia</div>
                    </div>
                </div>
                <div class="p-5 pt-0">
                    <a href="#" class="block text-center py-2 px-4 rounded bg-navy text-white dark:bg-tealAccent dark:text-navy text-xs font-bold hover:opacity-90 transition">View Project</a>
                </div>
            </div>

            <!-- Sample 8 -->
            <div class="bg-white dark:bg-navyLight rounded-xl border border-gray-200 dark:border-gray-800 overflow-hidden flex flex-col justify-between">
                <div>
                    <img src="assets/images/thumbnails/ai-learning.jpg" alt="AI Learning Project" class="w-full h-40 object-cover" onerror="this.onerror=null; this.src='https://via.placeholder.com/300x160?text=AI+Learning+Project';">
                    <div class="p-5">
                        <h3 class="font-bold text-lg text-navy dark:text-white mb-2">AI-Powered Project</h3>
                        <p class="text-xs text-gray-600 dark:text-slateLight mb-4">[ADD CONTENT HERE - Generative AI adoption training program]</p>
                        <div class="text-xs text-teal-600 dark:text-tealAccent font-semibold mb-1">Skills: AI-Assisted ID</div>
                        <div class="text-xs text-gray-500 dark:text-slateLight mb-4">Tech: MS Copilot / ChatGPT</div>
                    </div>
                </div>
                <div class="p-5 pt-0">
                    <a href="#" class="block text-center py-2 px-4 rounded bg-navy text-white dark:bg-tealAccent dark:text-navy text-xs font-bold hover:opacity-90 transition">View Project</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Case Studies Section -->
    <section id="casestudies" class="py-24 px-6 max-w-7xl mx-auto border-t border-gray-200 dark:border-gray-800">
        <h2 class="text-3xl font-bold text-navy dark:text-white mb-2 text-center">Featured Case Studies</h2>
        <p class="text-center text-gray-600 dark:text-slateLight mb-16 max-w-2xl mx-auto">In-depth breakdowns of complex learning solutions and business outcomes.</p>

        <div class="space-y-12">
            <!-- Case Study 1 -->
            <div class="bg-white dark:bg-navyLight p-8 rounded-xl border border-gray-200 dark:border-gray-800 shadow-sm">
                <div class="flex flex-col md:flex-row justify-between items-start md:items-center mb-6">
                    <div>
                        <span class="text-xs font-bold text-teal-600 dark:text-tealAccent uppercase tracking-wider">Enterprise AI Adoption</span>
                        <h3 class="text-2xl font-bold text-navy dark:text-white">Global Microsoft Copilot & GenAI Upskilling Program</h3>
                    </div>
                    <span class="mt-2 md:mt-0 px-3 py-1 bg-gray-100 dark:bg-navy text-xs rounded text-gray-600 dark:text-slateLight">Healthcare / Pharma[cite: 1]</span>
                </div>
                <div class="grid md:grid-cols-2 gap-6 text-sm text-gray-600 dark:text-slateLight mb-6">
                    <div>
                        <strong class="text-navy dark:text-white block mb-1">Challenge:</strong>
                        Accelerating GenAI and Microsoft Copilot adoption across global teams within strict regulatory governance boundaries[cite: 1].
                    </div>
                    <div>
                        <strong class="text-navy dark:text-white block mb-1">Solution:</strong>
                        Designed governance-aligned training modules, job aids, and AI-assisted storyboards using Copilot and ChatGPT[cite: 1, 2].
                    </div>
                </div>
                <div class="grid md:grid-cols-3 gap-4 text-xs bg-gray-50 dark:bg-navy p-4 rounded-lg mb-6">
                    <div><strong class="text-navy dark:text-white">Design Process:</strong> SAM Iterative Sprints</div>
                    <div><strong class="text-navy dark:text-white">Tools Used:</strong> Copilot, ChatGPT, Articulate Rise[cite: 1]</div>
                    <div><strong class="text-navy dark:text-white">Business Impact:</strong> Reduced development effort by 40%[cite: 2]</div>
                </div>
                <div class="p-4 border border-dashed border-gray-300 dark:border-gray-700 rounded text-center text-xs text-gray-400">
                    [ADD CONTENT HERE - Insert Project Screenshots & Media]
                </div>
            </div>

            <!-- Case Study 2 -->
            <div class="bg-white dark:bg-navyLight p-8 rounded-xl border border-gray-200 dark:border-gray-800 shadow-sm">
                <div class="flex flex-col md:flex-row justify-between items-start md:items-center mb-6">
                    <div>
                        <span class="text-xs font-bold text-teal-600 dark:text-tealAccent uppercase tracking-wider">Compliance & Finance</span>
                        <h3 class="text-2xl font-bold text-navy dark:text-white">Global Procurement On-Demand Digital Training Ecosystem</h3>
                    </div>
                    <span class="mt-2 md:mt-0 px-3 py-1 bg-gray-100 dark:bg-navy text-xs rounded text-gray-600 dark:text-slateLight">Enterprise Scale[cite: 2]</span>
                </div>
                <div class="grid md:grid-cols-2 gap-6 text-sm text-gray-600 dark:text-slateLight mb-6">
                    <div>
                        <strong class="text-navy dark:text-white block mb-1">Challenge:</strong>
                        Eliminating repetitive live SME training sessions for global finance/procurement across multiple time zones[cite: 2].
                    </div>
                    <div>
                        <strong class="text-navy dark:text-white block mb-1">Solution:</strong>
                        Built and deployed 600+ web-based trainings localized into 16 languages for on-demand access[cite: 1, 2].
                    </div>
                </div>
                <div class="grid md:grid-cols-3 gap-4 text-xs bg-gray-50 dark:bg-navy p-4 rounded-lg mb-6">
                    <div><strong class="text-navy dark:text-white">Design Process:</strong> ADDIE & Gagné's 9 Events[cite: 1]</div>
                    <div><strong class="text-navy dark:text-white">Tools Used:</strong> Storyline 360, Vyond, LMS[cite: 1]</div>
                    <div><strong class="text-navy dark:text-white">Business Impact:</strong> 100% On-time enterprise release[cite: 1]</div>
                </div>
                <div class="p-4 border border-dashed border-gray-300 dark:border-gray-700 rounded text-center text-xs text-gray-400">
                    [ADD CONTENT HERE - Insert Project Screenshots & Media]
                </div>
            </div>

            <!-- Case Study 3 -->
            <div class="bg-white dark:bg-navyLight p-8 rounded-xl border border-gray-200 dark:border-gray-800 shadow-sm">
                <div class="flex flex-col md:flex-row justify-between items-start md:items-center mb-6">
                    <div>
                        <span class="text-xs font-bold text-teal-600 dark:text-tealAccent uppercase tracking-wider">Safety & Onboarding</span>
                        <h3 class="text-2xl font-bold text-navy dark:text-white">High-Stakes Workplace & Technical Safety Training</h3>
                    </div>
                    <span class="mt-2 md:mt-0 px-3 py-1 bg-gray-100 dark:bg-navy text-xs rounded text-gray-600 dark:text-slateLight">Telecommunications[cite: 2]</span>
                </div>
                <div class="grid md:grid-cols-2 gap-6 text-sm text-gray-600 dark:text-slateLight mb-6">
                    <div>
                        <strong class="text-navy dark:text-white block mb-1">Challenge:</strong>
                        Reducing time-to-readiness for new hires while enforcing non-negotiable safety and regulatory standards[cite: 2].
                    </div>
                    <div>
                        <strong class="text-navy dark:text-white block mb-1">Solution:</strong>
                        Created realistic scenario-based practice modules and simplified technical manuals[cite: 2].
                    </div>
                </div>
                <div class="grid md:grid-cols-3 gap-4 text-xs bg-gray-50 dark:bg-navy p-4 rounded-lg mb-6">
                    <div><strong class="text-navy dark:text-white">Design Process:</strong> Bloom's Taxonomy & Kirkpatrick[cite: 1]</div>
                    <div><strong class="text-navy dark:text-white">Tools Used:</strong> Blended ILT & eLearning[cite: 1, 2]</div>
                    <div><strong class="text-navy dark:text-white">Business Impact:</strong> Shortened time-to-readiness[cite: 2]</div>
                </div>
                <div class="p-4 border border-dashed border-gray-300 dark:border-gray-700 rounded text-center text-xs text-gray-400">
                    [ADD CONTENT HERE - Insert Project Screenshots & Media]
                </div>
            </div>
        </div>
    </section>

    <!-- Results & Impact Section -->
    <section id="impact" class="py-24 px-6 max-w-7xl mx-auto border-t border-gray-200 dark:border-gray-800">
        <h2 class="text-3xl font-bold text-navy dark:text-white mb-2 text-center">Results & Business Impact</h2>
        <p class="text-center text-gray-600 dark:text-slateLight mb-16 max-w-2xl mx-auto">Quantifiable outcomes driven across global enterprise learning initiatives.</p>

        <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-6 gap-4">
            <div class="bg-white dark:bg-navyLight p-6 rounded-xl border border-gray-200 dark:border-gray-800 text-center">
                <div class="text-3xl font-extrabold text-teal-600 dark:text-tealAccent mb-1">50K+</div>
                <div class="text-xs text-gray-500 dark:text-slateLight font-semibold">Global Learners[cite: 1]</div>
            </div>
            <div class="bg-white dark:bg-navyLight p-6 rounded-xl border border-gray-200 dark:border-gray-800 text-center">
                <div class="text-3xl font-extrabold text-teal-600 dark:text-tealAccent mb-1">800+</div>
                <div class="text-xs text-gray-500 dark:text-slateLight font-semibold">Learning Assets[cite: 1]</div>
            </div>
            <div class="bg-white dark:bg-navyLight p-6 rounded-xl border border-gray-200 dark:border-gray-800 text-center">
                <div class="text-3xl font-extrabold text-teal-600 dark:text-tealAccent mb-1">40%</div>
                <div class="text-xs text-gray-500 dark:text-slateLight font-semibold">Dev Effort Saved[cite: 2]</div>
            </div>
            <div class="bg-white dark:bg-navyLight p-6 rounded-xl border border-gray-200 dark:border-gray-800 text-center">
                <div class="text-3xl font-extrabold text-teal-600 dark:text-tealAccent mb-1">16</div>
                <div class="text-xs text-gray-500 dark:text-slateLight font-semibold">Languages Localized[cite: 1]</div>
            </div>
            <div class="bg-white dark:bg-navyLight p-6 rounded-xl border border-gray-200 dark:border-gray-800 text-center">
                <div class="text-3xl font-extrabold text-teal-600 dark:text-tealAccent mb-1">100%</div>
                <div class="text-xs text-gray-500 dark:text-slateLight font-semibold">On-Time Releases[cite: 1]</div>
            </div>
            <div class="bg-white dark:bg-navyLight p-6 rounded-xl border border-gray-200 dark:border-gray-800 text-center">
                <div class="text-3xl font-extrabold text-teal-600 dark:text-tealAccent mb-1">9+</div>
                <div class="text-xs text-gray-500 dark:text-slateLight font-semibold">Years Experience[cite: 1]</div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section class="py-24 px-6 max-w-7xl mx-auto border-t border-gray-200 dark:border-gray-800">
        <h2 class="text-3xl font-bold text-navy dark:text-white mb-2 text-center">Testimonials</h2>
        <p class="text-center text-gray-600 dark:text-slateLight mb-16 max-w-2xl mx-auto">Feedback from stakeholders and learning leaders.</p>

        <div class="grid md:grid-cols-2 gap-8">
            <div class="bg-white dark:bg-navyLight p-6 rounded-xl border border-gray-200 dark:border-gray-800 italic text-gray-600 dark:text-slateLight text-sm relative">
                "[ADD CONTENT HERE - Add stakeholder review here]"
                <div class="mt-4 not-italic font-bold text-navy dark:text-white text-xs text-right">— [ADD CONTENT HERE - Stakeholder Name / Title]</div>
            </div>
            <div class="bg-white dark:bg-navyLight p-6 rounded-xl border border-gray-200 dark:border-gray-800 italic text-gray-600 dark:text-slateLight text-sm relative">
                "[ADD CONTENT HERE - Add stakeholder review here]"
                <div class="mt-4 not-italic font-bold text-navy dark:text-white text-xs text-right">— [ADD CONTENT HERE - Stakeholder Name / Title]</div>
            </div>
        </div>
    </section>

    <!-- Certifications Section -->
    <section class="py-24 px-6 max-w-7xl mx-auto border-t border-gray-200 dark:border-gray-800">
        <h2 class="text-3xl font-bold text-navy dark:text-white mb-2 text-center">Certifications & Education</h2>
        <p class="text-center text-gray-600 dark:text-slateLight mb-16 max-w-2xl mx-auto">Academic background and professional certifications.</p>

        <div class="grid md:grid-cols-3 gap-6">
            <div class="bg-white dark:bg-navyLight p-6 rounded-xl border border-gray-200 dark:border-gray-800">
                <div class="text-xs font-bold text-teal-600 dark:text-tealAccent mb-1">Degree</div>
                <h3 class="font-bold text-navy dark:text-white">B.Tech - Civil Engineering</h3>
                <p class="text-xs text-gray-500 dark:text-slateLight mt-1">JNTU Hyderabad (SVEC) | 2015[cite: 2]</p>
            </div>
            <div class="bg-white dark:bg-navyLight p-6 rounded-xl border border-gray-200 dark:border-gray-800">
                <div class="text-xs font-bold text-teal-600 dark:text-tealAccent mb-1">Certification</div>
                <h3 class="font-bold text-navy dark:text-white">[ADD CONTENT HERE - Certification Title]</h3>
                <p class="text-xs text-gray-500 dark:text-slateLight mt-1">[ADD CONTENT HERE - Issuing Organization / Year]</p>
            </div>
            <div class="bg-white dark:bg-navyLight p-6 rounded-xl border border-gray-200 dark:border-gray-800">
                <div class="text-xs font-bold text-teal-600 dark:text-tealAccent mb-1">Certification</div>
                <h3 class="font-bold text-navy dark:text-white">[ADD CONTENT HERE - Certification Title]</h3>
                <p class="text-xs text-gray-500 dark:text-slateLight mt-1">[ADD CONTENT HERE - Issuing Organization / Year]</p>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-24 px-6 max-w-7xl mx-auto border-t border-gray-200 dark:border-gray-800">
        <h2 class="text-3xl font-bold text-navy dark:text-white mb-2 text-center">Get In Touch</h2>
        <p class="text-center text-gray-600 dark:text-slateLight mb-16 max-w-2xl mx-auto">Open to strategic learning design opportunities, consulting, and collaboration.</p>

        <div class="max-w-xl mx-auto bg-white dark:bg-navyLight p-8 rounded-xl border border-gray-200 dark:border-gray-800 text-center space-y-6">
            <div class="flex items-center justify-center space-x-3 text-gray-600 dark:text-slateLight">
                <i class="fas fa-envelope text-teal-600 dark:text-tealAccent"></i>
                <a href="mailto:Abhishek.da101@gmail.com" class="hover:underline">Abhishek.da101@gmail.com</a>[cite: 1]
            </div>
            <div class="flex items-center justify-center space-x-3 text-gray-600 dark:text-slateLight">
                <i class="fas fa-phone text-teal-600 dark:text-tealAccent"></i>
                <span>+91 70133 20962</span>[cite: 1]
            </div>
            <div class="flex items-center justify-center space-x-3 text-gray-600 dark:text-slateLight">
                <i class="fas fa-map-marker-alt text-teal-600 dark:text-tealAccent"></i>
                <span>Hyderabad, India</span>[cite: 1]
            </div>
            <div class="flex items-center justify-center space-x-3 text-gray-600 dark:text-slateLight">
                <i class="fab fa-linkedin text-teal-600 dark:text-tealAccent"></i>
                <a href="[ADD CONTENT HERE - LinkedIn URL]" target="_blank" class="hover:underline">LinkedIn Profile</a>
            </div>
            <div class="pt-4 border-t border-gray-200 dark:border-gray-800">
                <a href="assets/docs/Abhishek_Daida_Resume.pdf" download class="inline-block px-8 py-3 rounded-lg bg-teal-600 text-white dark:bg-tealAccent dark:text-navy font-bold hover:opacity-90 transition">
                    Download Full Resume
                </a>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="py-8 text-center text-xs text-gray-500 dark:text-slateLight border-t border-gray-200 dark:border-gray-800">
        © 2026 Abhishek Daida. Built with HTML5, CSS3, Tailwind CSS & JavaScript. Hosted on GitHub Pages.
    </footer>

    <script src="js/script.js"></script>
</body>
</html>
