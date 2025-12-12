<script lang="ts">
  import Navbar from '$lib/Navbar.svelte';
  import Footer from '$lib/Footer.svelte';
  import Button from '$lib/Button.svelte';
</script>

<div class="min-h-screen font-sans text-dark bg-white overflow-x-hidden">
  <Navbar />

  <!-- Hero Section -->
  <section class="pt-32 pb-16 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto text-center">
    <div class="mb-6">
      <span class="text-xs font-bold tracking-widest text-gray-500 uppercase">AI-Powered Coaching Apps</span>
    </div>
    <h1 class="text-5xl md:text-7xl font-serif mb-6 leading-tight">
      Transform your expertise <br class="hidden md:block" /> into a coaching app
    </h1>
    <p class="text-lg md:text-xl text-gray-600 max-w-2xl mx-auto mb-10 leading-relaxed">
      Turn your ideas and expertise into profitable app businesses with AI in minutes.
      Join world-class creators building personalized coaching experiences.
    </p>
    <div class="flex flex-col sm:flex-row items-center justify-center gap-4 mb-20">
      <Button href="#" type="primary">Get Early Access &rarr;</Button>
      <Button href="#" type="outline">See How It Works</Button>
    </div>

    <!-- Hero Image Placeholder -->
    <div class="relative w-full max-w-5xl mx-auto rounded-2xl overflow-hidden shadow-2xl border border-gray-200 bg-white aspect-[16/9] mb-16 group">
      <!-- Mock Coaching App UI -->
      <div class="absolute inset-0 bg-gradient-to-br from-gray-50 to-white p-4">
        <div class="h-full w-full bg-white rounded-xl border border-gray-200 shadow-sm p-6 flex flex-col">
            <!-- Header of Coaching App -->
            <div class="flex items-center justify-between mb-6 border-b border-gray-100 pb-4">
                <div class="flex items-center gap-3">
                    <div class="w-10 h-10 rounded-full bg-primary-100 flex items-center justify-center text-primary-600 font-bold text-sm">CP</div>
                    <div>
                      <div class="h-3 w-32 bg-gray-800 rounded mb-1 font-semibold text-xs flex items-center">Music Production</div>
                      <div class="h-2 w-24 bg-gray-200 rounded"></div>
                    </div>
                </div>
                <div class="flex gap-2">
                    <div class="h-8 px-3 bg-primary-500 text-white rounded-lg text-xs font-medium flex items-center">Start Lesson</div>
                </div>
            </div>
            <!-- Content of Coaching App -->
            <div class="flex-1 grid grid-cols-12 gap-6">
                <div class="col-span-3 space-y-3">
                    <div class="text-xs font-bold text-gray-400 mb-2">YOUR PROGRESS</div>
                    <div class="h-3 w-full bg-primary-200 rounded"></div>
                    <div class="h-3 w-3/4 bg-gray-100 rounded"></div>
                    <div class="h-3 w-5/6 bg-gray-100 rounded"></div>
                    <div class="h-3 w-2/3 bg-gray-100 rounded mt-4"></div>
                </div>
                <div class="col-span-9 bg-gradient-to-br from-primary-50 to-gray-50 rounded-lg p-4 grid grid-cols-2 gap-4">
                     <div class="bg-white p-4 rounded-lg shadow-sm h-32 border border-gray-100 flex flex-col justify-between">
                       <div class="h-2 w-16 bg-primary-300 rounded"></div>
                       <div class="space-y-1">
                         <div class="h-2 w-full bg-gray-100 rounded"></div>
                         <div class="h-2 w-3/4 bg-gray-100 rounded"></div>
                       </div>
                     </div>
                     <div class="bg-white p-4 rounded-lg shadow-sm h-32 border border-gray-100 flex flex-col justify-between">
                       <div class="h-2 w-16 bg-primary-300 rounded"></div>
                       <div class="space-y-1">
                         <div class="h-2 w-full bg-gray-100 rounded"></div>
                         <div class="h-2 w-3/4 bg-gray-100 rounded"></div>
                       </div>
                     </div>
                     <div class="bg-white p-4 rounded-lg shadow-sm h-32 border border-gray-100 flex flex-col justify-between">
                       <div class="h-2 w-16 bg-primary-300 rounded"></div>
                       <div class="space-y-1">
                         <div class="h-2 w-full bg-gray-100 rounded"></div>
                         <div class="h-2 w-3/4 bg-gray-100 rounded"></div>
                       </div>
                     </div>
                     <div class="bg-white p-4 rounded-lg shadow-sm h-32 border border-gray-100 flex flex-col justify-between">
                       <div class="h-2 w-16 bg-primary-300 rounded"></div>
                       <div class="space-y-1">
                         <div class="h-2 w-full bg-gray-100 rounded"></div>
                         <div class="h-2 w-3/4 bg-gray-100 rounded"></div>
                       </div>
                     </div>
                </div>
            </div>
        </div>
      </div>
      
      <!-- Decorative Elements -->
      <div class="absolute -left-12 bottom-12 w-24 h-24 bg-primary-400 rounded-full blur-2xl opacity-20"></div>
      <div class="absolute -right-12 top-12 w-32 h-32 bg-primary-300 rounded-full blur-2xl opacity-20"></div>
    </div>

    <!-- Creator Showcase -->
    <div class="text-center">
      <p class="text-sm text-gray-500 mb-6">Trusted by world-class creators and experts</p>
      <div class="flex flex-wrap justify-center items-center gap-6 md:gap-10 text-gray-600">
        <span class="font-semibold text-base">Charlie Puth</span>
        <span class="font-semibold text-base">Mark Rober</span>
        <span class="font-semibold text-base">David Blaine</span>
        <span class="font-semibold text-base">Casey Neistat</span>
        <span class="font-semibold text-base">Christina Tosi</span>
        <span class="font-semibold text-base">H.E.R.</span>
      </div>
    </div>
  </section>

  <!-- Stats Section -->
  <section class="py-20 bg-gray-50">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16 max-w-3xl mx-auto">
        Empowering creators with billions of combined views and streams
      </h2>
      
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8 mb-16">
        <div class="bg-white p-8 rounded-2xl text-center border border-gray-200">
          <div class="text-4xl font-serif font-medium mb-2">100B+</div>
          <div class="text-xs font-bold text-gray-400 tracking-widest uppercase">Combined Views & Streams</div>
        </div>
        <div class="bg-white p-8 rounded-2xl text-center border border-gray-200">
          <div class="text-4xl font-serif font-medium mb-2">70M+</div>
          <div class="text-xs font-bold text-gray-400 tracking-widest uppercase">Subscribers Reached</div>
        </div>
        <div class="bg-white p-8 rounded-2xl text-center border border-gray-200">
          <div class="text-4xl font-serif font-medium mb-2">Minutes</div>
          <div class="text-xs font-bold text-gray-400 tracking-widest uppercase">To Launch Your App</div>
        </div>
      </div>

      <!-- Creator Categories Carousel -->
      <div class="flex gap-4 overflow-hidden relative">
        <div class="absolute inset-y-0 left-0 w-20 bg-gradient-to-r from-gray-50 to-transparent z-10"></div>
        <div class="absolute inset-y-0 right-0 w-20 bg-gradient-to-l from-gray-50 to-transparent z-10"></div>
        
        <div class="flex gap-4 animate-scroll">
            <!-- Card 1 - Music -->
            <div class="w-64 h-80 bg-gradient-to-br from-purple-100 to-pink-100 rounded-2xl flex-shrink-0 relative overflow-hidden group">
                <div class="absolute top-4 left-4 bg-white/90 backdrop-blur px-3 py-1 rounded-full text-xs font-bold">
                    🎵 Music
                </div>
                <div class="absolute bottom-0 inset-x-0 bg-gradient-to-t from-black/70 to-transparent p-4 text-white">
                    <div class="font-bold">Charlie Puth</div>
                    <div class="text-xs opacity-80">Multi-Platinum Artist</div>
                </div>
            </div>
            <!-- Card 2 - Engineering -->
            <div class="w-64 h-80 bg-gradient-to-br from-blue-100 to-cyan-100 rounded-2xl flex-shrink-0 relative overflow-hidden group">
                <div class="absolute top-4 left-4 bg-white/90 backdrop-blur px-3 py-1 rounded-full text-xs font-bold">
                    🔧 Engineering
                </div>
                <div class="absolute bottom-0 inset-x-0 bg-gradient-to-t from-black/70 to-transparent p-4 text-white">
                    <div class="font-bold">Mark Rober</div>
                    <div class="text-xs opacity-80">70M YouTube Subscribers</div>
                </div>
            </div>
            <!-- Card 3 - Magic -->
            <div class="w-64 h-80 bg-gradient-to-br from-indigo-100 to-purple-100 rounded-2xl flex-shrink-0 relative overflow-hidden group">
                <div class="absolute top-4 left-4 bg-white/90 backdrop-blur px-3 py-1 rounded-full text-xs font-bold">
                    ✨ Magic
                </div>
                <div class="absolute bottom-0 inset-x-0 bg-gradient-to-t from-black/70 to-transparent p-4 text-white">
                    <div class="font-bold">David Blaine</div>
                    <div class="text-xs opacity-80">World's Greatest Magician</div>
                </div>
            </div>
             <!-- Card 4 - Filmmaking -->
            <div class="w-64 h-80 bg-gradient-to-br from-orange-100 to-red-100 rounded-2xl flex-shrink-0 relative overflow-hidden group">
                <div class="absolute top-4 left-4 bg-white/90 backdrop-blur px-3 py-1 rounded-full text-xs font-bold">
                    🎬 Filmmaking
                </div>
                <div class="absolute bottom-0 inset-x-0 bg-gradient-to-t from-black/70 to-transparent p-4 text-white">
                    <div class="font-bold">Casey Neistat</div>
                    <div class="text-xs opacity-80">3B+ Views</div>
                </div>
            </div>
             <!-- Card 5 - Culinary -->
            <div class="w-64 h-80 bg-gradient-to-br from-yellow-100 to-orange-100 rounded-2xl flex-shrink-0 relative overflow-hidden group">
                <div class="absolute top-4 left-4 bg-white/90 backdrop-blur px-3 py-1 rounded-full text-xs font-bold">
                    🍰 Culinary
                </div>
                <div class="absolute bottom-0 inset-x-0 bg-gradient-to-t from-black/70 to-transparent p-4 text-white">
                    <div class="font-bold">Christina Tosi</div>
                    <div class="text-xs opacity-80">James Beard Winner</div>
                </div>
            </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Creator Economy Section -->
  <section class="bg-dark text-white py-24 overflow-hidden">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-4">The creator economy <br /> is transforming education</h2>
      <p class="text-center text-gray-400 mb-16">People want to learn from real experts, not generic courses.</p>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-16 items-center">
        <!-- The Old Way -->
        <div>
          <h3 class="text-xl font-serif mb-2">Traditional Online Courses</h3>
          <p class="text-gray-400 text-sm mb-8 leading-relaxed">
            Most online courses have completion rates below 10%. They're impersonal, one-size-fits-all, and lack community engagement.
          </p>
          <div class="bg-gray-800/50 rounded-xl p-6 border border-gray-700 relative">
             <div class="flex justify-between items-end h-40 gap-2">
                <div class="w-full bg-red-500/20 rounded-t h-[90%] relative group"><div class="absolute -top-6 left-1/2 -translate-x-1/2 text-xs text-red-400">90%</div></div>
                <div class="w-full bg-red-500/40 rounded-t h-[85%] relative group"><div class="absolute -top-6 left-1/2 -translate-x-1/2 text-xs text-red-400">85%</div></div>
                <div class="w-full bg-red-500/60 rounded-t h-[92%] relative group"><div class="absolute -top-6 left-1/2 -translate-x-1/2 text-xs text-red-400">92%</div></div>
                <div class="w-full bg-red-500/80 rounded-t h-[88%] relative group"><div class="absolute -top-6 left-1/2 -translate-x-1/2 text-xs text-red-400">88%</div></div>
                <div class="w-full bg-red-500 rounded-t h-full relative group"><div class="absolute -top-6 left-1/2 -translate-x-1/2 text-xs text-red-400 font-bold">95%</div></div>
             </div>
             <div class="mt-4 flex justify-between text-xs text-gray-500">
                <span>Course A</span>
                <span>Course E</span>
             </div>
             <div class="absolute top-4 left-4 text-xs font-bold text-gray-300">Drop-off Rate</div>
          </div>
        </div>

        <!-- The New Way -->
        <div>
          <h3 class="text-xl font-serif mb-2">Studio Coaching Apps</h3>
          <p class="text-gray-400 text-sm mb-8 leading-relaxed">
            AI-powered personalization meets expert coaching. Build engaged communities around your expertise with apps that people actually complete.
          </p>
          <div class="relative h-64 flex items-center justify-center">
             <!-- Central Studio Logo -->
             <div class="relative z-10 w-20 h-20 bg-white rounded-full flex items-center justify-center">
                <svg width="48" height="48" viewBox="0 0 97 97" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M96.8438 48.3333C96.8438 75.0271 75.3534 96.6667 48.8438 96.6667C25.3046 96.6667 5.72283 79.605 1.63005 57.0928C1.61771 57.0251 1.60551 56.9572 1.59346 56.8891C1.10084 54.1121 0.84375 51.2529 0.84375 48.3333C0.84375 46.0025 1.00762 43.71 1.32439 41.4671C4.31845 20.2681 20.9721 3.49883 42.0249 0.483986C42.0602 0.478911 42.0954 0.473908 42.131 0.468905C44.3246 0.159814 46.5657 0 48.8438 0C51.8142 0 54.7216 0.271706 57.5428 0.791773C79.8997 4.91296 96.8438 24.6307 96.8438 48.3333ZM84.8438 48.3333C84.8438 68.3537 68.7261 84.5833 48.8438 84.5833C33.861 84.5833 21.0159 75.3669 15.5951 62.257C17.8219 62.6361 20.1099 62.8333 22.4438 62.8333C44.9769 62.8333 63.2438 44.4396 63.2438 21.75C63.2438 19.4 63.0479 17.096 62.6714 14.8538C75.6909 20.3123 84.8438 33.2466 84.8438 48.3333ZM49.6077 12.0913C50.6673 15.1126 51.2438 18.3635 51.2438 21.75C51.2438 37.7662 38.3495 50.75 22.4438 50.75C19.0806 50.75 15.8521 50.1695 12.8517 49.1026C12.8464 48.8469 12.8438 48.5905 12.8438 48.3333C12.8438 28.3129 28.9614 12.0833 48.8438 12.0833C49.0991 12.0833 49.3538 12.086 49.6077 12.0913Z" fill="black"/>
                </svg>
             </div>
             <!-- Orbiting Features -->
             <div class="absolute inset-0 animate-spin-slow">
                <div class="absolute top-0 left-1/2 -translate-x-1/2 -translate-y-4 bg-primary-500 text-white px-3 py-1.5 rounded-full text-xs font-medium">AI Personalization</div>
                <div class="absolute bottom-0 left-1/2 -translate-x-1/2 translate-y-4 bg-primary-500 text-white px-3 py-1.5 rounded-full text-xs font-medium">Community</div>
                <div class="absolute left-0 top-1/2 -translate-x-4 -translate-y-1/2 bg-primary-500 text-white px-3 py-1.5 rounded-full text-xs font-medium">Expert Content</div>
                <div class="absolute right-0 top-1/2 translate-x-4 -translate-y-1/2 bg-primary-500 text-white px-3 py-1.5 rounded-full text-xs font-medium">Monetization</div>
             </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Features Section 1 -->
  <section id="features" class="py-24 bg-white">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16 max-w-2xl mx-auto">
        Build your coaching app in minutes with AI
      </h2>

      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
        <!-- Card 1: AI Content Generation -->
        <div class="lg:col-span-2 bg-white rounded-3xl p-8 shadow-sm border border-gray-100 overflow-hidden relative group">
            <div class="mb-8">
                <h3 class="text-xl font-serif mb-2">AI-powered content generation</h3>
                <p class="text-gray-500 text-sm">Transform your expertise into structured coaching content instantly. Our AI helps you create personalized learning paths for your students.</p>
            </div>
            <div class="bg-primary-50 rounded-xl p-6 h-64 relative border border-primary-100">
                <!-- AI Generation Mockup -->
                <div class="bg-white rounded-lg p-3 shadow-sm mb-4">
                    <div class="flex items-center gap-2 mb-3">
                        <div class="w-6 h-6 bg-primary-500 rounded flex items-center justify-center text-white text-xs">✨</div>
                        <div class="text-xs font-medium">Generating your coaching content...</div>
                    </div>
                    <div class="h-1.5 w-full bg-gray-100 rounded-full overflow-hidden">
                        <div class="h-full w-3/4 bg-primary-500 rounded-full"></div>
                    </div>
                </div>
                <!-- Content Cards -->
                <div class="flex gap-3 justify-center">
                    <div class="bg-white p-3 rounded-xl shadow-sm w-36">
                        <div class="text-xs font-bold mb-2">Lesson 1</div>
                        <div class="h-1.5 w-full bg-gray-100 rounded mb-1"></div>
                        <div class="h-1.5 w-3/4 bg-gray-100 rounded"></div>
                    </div>
                    <div class="bg-white p-3 rounded-xl shadow-sm w-36">
                        <div class="text-xs font-bold mb-2">Lesson 2</div>
                        <div class="h-1.5 w-full bg-gray-100 rounded mb-1"></div>
                        <div class="h-1.5 w-3/4 bg-gray-100 rounded"></div>
                    </div>
                </div>
            </div>
        </div>

        <!-- Card 2: Instant Deployment -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100 overflow-hidden">
            <div class="mb-8">
                <h3 class="text-xl font-serif mb-2">Launch in minutes</h3>
                <p class="text-gray-500 text-sm">No coding required. Your coaching app is ready to share with students instantly, complete with your branding.</p>
            </div>
            <div class="bg-primary-50 rounded-xl h-48 relative overflow-hidden flex items-center justify-center">
                <div class="flex flex-col gap-2 items-center">
                    <div class="w-16 h-16 bg-primary-500 rounded-2xl flex items-center justify-center text-white text-2xl">📱</div>
                    <div class="text-xs font-bold text-gray-700">Your App</div>
                    <div class="text-[10px] text-gray-500">Ready to launch</div>
                </div>
            </div>
        </div>

        <!-- Card 3: Personalization -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100 overflow-hidden">
             <div class="h-48 bg-primary-50 rounded-xl mb-6 p-4 relative flex items-center justify-center">
                <div class="bg-white rounded-xl shadow-sm p-4 w-full max-w-[200px]">
                    <div class="flex items-center gap-2 mb-3">
                        <div class="w-8 h-8 bg-primary-200 rounded-full"></div>
                        <div class="flex-1">
                            <div class="h-2 w-16 bg-gray-200 rounded mb-1"></div>
                            <div class="h-1.5 w-12 bg-gray-100 rounded"></div>
                        </div>
                    </div>
                    <div class="space-y-2">
                        <div class="h-2 w-full bg-primary-100 rounded"></div>
                        <div class="h-2 w-4/5 bg-gray-100 rounded"></div>
                        <div class="h-2 w-3/5 bg-gray-100 rounded"></div>
                    </div>
                </div>
             </div>
             <h3 class="text-xl font-serif mb-2">Personalized learning paths</h3>
             <p class="text-gray-500 text-sm">AI adapts content to each student's pace and learning style for better outcomes.</p>
        </div>

        <!-- Card 4: Community Features -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100 overflow-hidden">
             <div class="h-48 bg-primary-50 rounded-xl mb-6 p-4 flex items-center justify-center">
                <div class="space-y-2 w-full max-w-[200px]">
                    <div class="bg-white p-2 rounded-lg shadow-sm flex items-center gap-2">
                        <div class="w-6 h-6 bg-primary-200 rounded-full"></div>
                        <div class="h-2 w-20 bg-gray-100 rounded"></div>
                    </div>
                    <div class="bg-white p-2 rounded-lg shadow-sm flex items-center gap-2">
                        <div class="w-6 h-6 bg-primary-200 rounded-full"></div>
                        <div class="h-2 w-16 bg-gray-100 rounded"></div>
                    </div>
                    <div class="bg-white p-2 rounded-lg shadow-sm flex items-center gap-2">
                        <div class="w-6 h-6 bg-primary-200 rounded-full"></div>
                        <div class="h-2 w-24 bg-gray-100 rounded"></div>
                    </div>
                </div>
             </div>
             <h3 class="text-xl font-serif mb-2">Built-in community</h3>
             <p class="text-gray-500 text-sm">Foster engagement with discussion forums, live sessions, and peer-to-peer learning.</p>
        </div>

        <!-- Card 5: Monetization -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100 overflow-hidden">
             <div class="h-48 bg-primary-50 rounded-xl mb-6 p-4 flex items-center justify-center relative">
                 <div class="bg-white p-4 rounded-xl shadow-sm w-full max-w-[200px]">
                    <div class="text-xs font-bold text-gray-700 mb-3">Revenue Dashboard</div>
                    <div class="space-y-2">
                        <div class="flex justify-between items-center">
                            <div class="h-2 w-16 bg-gray-100 rounded"></div>
                            <div class="text-xs font-bold text-primary-600">$2,450</div>
                        </div>
                        <div class="flex justify-between items-center">
                            <div class="h-2 w-12 bg-gray-100 rounded"></div>
                            <div class="text-xs font-bold text-primary-600">$1,890</div>
                        </div>
                    </div>
                 </div>
             </div>
             <h3 class="text-xl font-serif mb-2">Monetize your expertise</h3>
             <p class="text-gray-500 text-sm">Built-in payments, subscriptions, and analytics to grow your coaching business.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Testimonial 1 -->
  <section class="py-16 bg-white">
    <div class="max-w-4xl mx-auto px-4 text-center">
        <div class="flex justify-center mb-8">
            <div class="text-4xl">🎵</div>
        </div>
        <blockquote class="text-2xl md:text-3xl font-serif leading-relaxed mb-8">
            "Studio made it incredibly easy to turn my music production knowledge into a coaching app. Now I can reach aspiring artists worldwide and help them master their craft."
        </blockquote>
        <div class="flex items-center justify-center gap-4">
            <div class="w-12 h-12 rounded-full bg-primary-200"></div>
            <div class="text-left">
                <div class="font-bold text-sm">Charlie Puth</div>
                <div class="text-xs text-gray-500">Multi-Platinum Recording Artist</div>
            </div>
        </div>
    </div>
  </section>

  <!-- Features Section 2 -->
  <section id="how-it-works" class="py-24 bg-gray-50">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16">
        Everything you need to <br /> succeed as a creator
      </h2>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
        <!-- Card 1 -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100">
            <div class="bg-gradient-to-br from-primary-50 to-gray-50 rounded-xl h-64 mb-8 p-4 relative overflow-hidden flex items-center justify-center">
                <div class="bg-white rounded-xl shadow-sm p-4 w-4/5">
                    <div class="flex items-center gap-3 mb-4">
                        <div class="w-10 h-10 bg-primary-500 rounded-lg"></div>
                        <div class="flex-1">
                            <div class="h-3 w-24 bg-gray-200 rounded mb-1"></div>
                            <div class="h-2 w-16 bg-gray-100 rounded"></div>
                        </div>
                    </div>
                    <div class="space-y-2">
                        <div class="h-2 w-full bg-primary-100 rounded"></div>
                        <div class="h-2 w-4/5 bg-gray-100 rounded"></div>
                        <div class="h-2 w-3/5 bg-gray-100 rounded"></div>
                    </div>
                </div>
            </div>
            <h3 class="text-xl font-serif mb-2">Your brand, your way</h3>
            <p class="text-gray-500 text-sm">Customize your app with your colors, logo, and style. Make it uniquely yours.</p>
        </div>

        <!-- Card 2 -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100">
            <div class="bg-gradient-to-br from-primary-50 to-gray-50 rounded-xl h-64 mb-8 p-4 flex items-center justify-center">
                 <div class="space-y-3 w-4/5">
                    <div class="bg-white rounded-lg shadow-sm p-3 flex items-center gap-3">
                        <div class="w-10 h-10 bg-primary-200 rounded-full"></div>
                        <div class="flex-1">
                            <div class="h-2 w-20 bg-gray-200 rounded mb-1"></div>
                            <div class="h-1.5 w-16 bg-gray-100 rounded"></div>
                        </div>
                        <div class="text-xs font-bold text-primary-600">85%</div>
                    </div>
                    <div class="bg-white rounded-lg shadow-sm p-3 flex items-center gap-3">
                        <div class="w-10 h-10 bg-primary-200 rounded-full"></div>
                        <div class="flex-1">
                            <div class="h-2 w-24 bg-gray-200 rounded mb-1"></div>
                            <div class="h-1.5 w-20 bg-gray-100 rounded"></div>
                        </div>
                        <div class="text-xs font-bold text-primary-600">92%</div>
                    </div>
                 </div>
            </div>
            <h3 class="text-xl font-serif mb-2">Track student progress</h3>
            <p class="text-gray-500 text-sm">See how your students are doing with detailed analytics and engagement metrics.</p>
        </div>

        <!-- Card 3 -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100">
            <div class="bg-gradient-to-br from-primary-50 to-gray-50 rounded-xl h-64 mb-8 p-4 flex items-center justify-center">
                <div class="bg-white rounded-xl shadow-sm p-4 w-4/5">
                    <div class="text-xs font-bold text-gray-700 mb-3">Live Session</div>
                    <div class="bg-primary-500 rounded-lg h-32 mb-2 flex items-center justify-center text-white text-xs">
                        🎥 In Progress
                    </div>
                    <div class="flex gap-2">
                        <div class="h-6 w-6 bg-gray-100 rounded"></div>
                        <div class="h-6 w-6 bg-gray-100 rounded"></div>
                        <div class="h-6 w-6 bg-gray-100 rounded"></div>
                    </div>
                </div>
            </div>
            <h3 class="text-xl font-serif mb-2">Host live sessions</h3>
            <p class="text-gray-500 text-sm">Connect with your students through integrated video calls and live Q&A sessions.</p>
        </div>

        <!-- Card 4 -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100">
            <div class="bg-gradient-to-br from-primary-50 to-gray-50 rounded-xl h-64 mb-8 p-4 flex items-center justify-center">
                <div class="w-full max-w-sm space-y-3">
                    <div class="bg-white p-3 rounded-xl shadow-sm">
                        <div class="flex items-center gap-2 mb-2">
                            <div class="w-6 h-6 bg-primary-200 rounded-full"></div>
                            <div class="h-2 w-20 bg-gray-200 rounded"></div>
                        </div>
                        <div class="h-2 w-full bg-gray-100 rounded"></div>
                    </div>
                    <div class="bg-white p-3 rounded-xl shadow-sm">
                        <div class="flex items-center gap-2 mb-2">
                            <div class="w-6 h-6 bg-primary-200 rounded-full"></div>
                            <div class="h-2 w-16 bg-gray-200 rounded"></div>
                        </div>
                        <div class="h-2 w-4/5 bg-gray-100 rounded"></div>
                    </div>
                </div>
            </div>
            <h3 class="text-xl font-serif mb-2">Engage your community</h3>
            <p class="text-gray-500 text-sm">Foster meaningful connections with discussion boards, challenges, and peer support.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Join Studio CTA -->
  <section class="py-24 bg-white relative overflow-hidden">
    <!-- Floating Icons Background -->
    <div class="absolute inset-0 opacity-5 pointer-events-none">
        <div class="absolute top-10 left-10 text-6xl">🎵</div>
        <div class="absolute top-20 right-20 text-6xl">🎬</div>
        <div class="absolute bottom-20 left-1/3 text-6xl">🔧</div>
        <div class="absolute bottom-10 right-1/4 text-6xl">✨</div>
    </div>

    <div class="max-w-4xl mx-auto px-4 text-center relative z-10">
        <div class="inline-block bg-primary-100 text-primary-700 px-4 py-1 rounded-full text-xs font-bold mb-6">
            Invite-Only Early Access
        </div>
        <h2 class="text-4xl md:text-6xl font-serif mb-4">Join the creator <br /> economy revolution</h2>
        <p class="text-gray-500 mb-10">Turn your expertise into a thriving coaching business</p>
        
        <div class="flex justify-center gap-4">
            <Button href="#" type="primary">Get Early Access &rarr;</Button>
            <Button href="#" type="outline">Learn More</Button>
        </div>
    </div>
  </section>

  <!-- Success Stories Section -->
  <section id="creators" class="py-24 bg-gray-50">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16">
        Trusted by world-class <br /> creators and experts
      </h2>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
        <!-- Left Large Card - Mark Rober -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100 md:row-span-2 flex flex-col">
            <div class="mb-8">
                <div class="text-4xl mb-4">🔧</div>
                <h3 class="text-xl font-serif mb-2">Mark Rober</h3>
                <p class="text-gray-500 text-sm">Former NASA engineer with 70M+ YouTube subscribers teaching engineering and creativity</p>
            </div>
            <div class="flex-1 bg-gradient-to-br from-blue-50 to-cyan-50 rounded-2xl relative overflow-hidden min-h-[300px] flex items-center justify-center">
                <div class="text-center">
                    <div class="text-5xl font-serif font-bold text-primary-600 mb-2">70M+</div>
                    <div class="text-sm text-gray-600">YouTube Subscribers</div>
                    <div class="text-xs text-gray-500 mt-4">12B+ Views</div>
                </div>
            </div>
        </div>

        <!-- Right Top Card - David Blaine -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100">
            <div class="mb-6">
                <div class="text-3xl mb-3">✨</div>
                <h3 class="text-xl font-serif mb-2">David Blaine</h3>
                <p class="text-gray-500 text-sm">World's greatest living magician sharing the secrets of performance and illusion</p>
            </div>
            <div class="bg-gradient-to-br from-purple-50 to-indigo-50 rounded-xl h-32 flex items-center justify-center">
                <div class="text-center">
                    <div class="text-2xl font-serif font-bold text-primary-600">World-Class</div>
                    <div class="text-xs text-gray-500 mt-1">Magic & Performance</div>
                </div>
            </div>
        </div>

        <!-- Right Bottom Card - Christina Tosi -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100">
            <div class="mb-6">
                <div class="text-3xl mb-3">🍰</div>
                <h3 class="text-xl font-serif mb-2">Christina Tosi</h3>
                <p class="text-gray-500 text-sm">Milk Bar founder and James Beard Award winner teaching baking and pastry arts</p>
            </div>
            <div class="bg-gradient-to-br from-yellow-50 to-orange-50 rounded-xl h-32 flex items-center justify-center">
                <div class="text-center">
                    <div class="text-2xl font-serif font-bold text-primary-600">James Beard</div>
                    <div class="text-xs text-gray-500 mt-1">Award Winner</div>
                </div>
            </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Creator Categories Grid -->
  <section class="py-24 bg-white">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16 max-w-2xl mx-auto">
        Creators across every category imaginable
      </h2>

      <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-4 gap-4">
         <!-- Row 1 -->
         <div class="aspect-square bg-gradient-to-br from-purple-100 to-pink-100 rounded-2xl relative overflow-hidden group flex items-center justify-center">
            <div class="text-center">
                <div class="text-4xl mb-2">🎵</div>
                <div class="font-bold text-gray-800">Music</div>
                <div class="text-xs text-gray-600">Production & Songwriting</div>
            </div>
         </div>
         <div class="aspect-square bg-gradient-to-br from-blue-100 to-cyan-100 rounded-2xl flex items-center justify-center">
            <div class="text-center">
                <div class="text-4xl mb-2">🔧</div>
                <div class="font-bold text-gray-800">Engineering</div>
                <div class="text-xs text-gray-600">STEM & Innovation</div>
            </div>
         </div>
         <div class="col-span-2 bg-primary-50 rounded-2xl p-8 flex flex-col justify-between border border-primary-100">
            <div class="text-4xl font-serif text-primary-600">"</div>
            <p class="text-lg font-serif leading-relaxed">Studio gave me the tools to share my passion with the world. Building my coaching app was effortless, and now I'm reaching thousands of students.</p>
            <div class="flex justify-between items-end">
                <div class="text-xs">
                    <div class="font-bold">Ryan Tedder</div>
                    <div class="text-gray-500">Grammy-winning Producer</div>
                </div>
            </div>
         </div>

         <!-- Row 2 -->
         <div class="col-span-2 bg-gradient-to-br from-orange-100 to-red-100 rounded-2xl flex items-center justify-center p-8">
            <div class="text-center">
                <div class="text-5xl mb-3">🎬</div>
                <div class="text-2xl font-bold text-gray-800">Filmmaking</div>
                <div class="text-sm text-gray-600 mt-2">Storytelling & Production</div>
            </div>
         </div>
         <div class="aspect-square bg-gradient-to-br from-yellow-100 to-orange-100 rounded-2xl relative overflow-hidden group flex items-center justify-center">
             <div class="text-center">
                <div class="text-4xl mb-2">🍰</div>
                <div class="font-bold text-gray-800">Culinary</div>
                <div class="text-xs text-gray-600">Cooking & Baking</div>
            </div>
         </div>
         <div class="aspect-square bg-gradient-to-br from-indigo-100 to-purple-100 rounded-2xl relative overflow-hidden group flex items-center justify-center">
             <div class="text-center">
                <div class="text-4xl mb-2">✨</div>
                <div class="font-bold text-gray-800">Magic</div>
                <div class="text-xs text-gray-600">Performance Art</div>
            </div>
         </div>

         <!-- Row 3 -->
         <div class="col-span-2 bg-primary-50 rounded-2xl p-8 flex flex-col justify-between border border-primary-100">
            <div class="text-4xl font-serif text-primary-600">"</div>
            <p class="text-lg font-serif leading-relaxed">The AI-powered content generation saved me months of work. I can focus on what I do best - teaching - while Studio handles the rest.</p>
            <div class="flex justify-between items-end">
                <div class="text-xs">
                    <div class="font-bold">Casey Neistat</div>
                    <div class="text-gray-500">Filmmaker, 3B+ Views</div>
                </div>
            </div>
         </div>
         <div class="col-span-2 bg-gradient-to-br from-green-100 to-teal-100 rounded-2xl flex items-center justify-center p-8">
             <div class="text-center">
                <div class="text-5xl mb-3">🧘</div>
                <div class="text-2xl font-bold text-gray-800">Wellness</div>
                <div class="text-sm text-gray-600 mt-2">Mental Health & Fitness</div>
            </div>
         </div>
         
         <!-- Row 4 -->
         <div class="aspect-square bg-gradient-to-br from-pink-100 to-rose-100 rounded-2xl relative overflow-hidden group flex items-center justify-center">
             <div class="text-center">
                <div class="text-4xl mb-2">🎨</div>
                <div class="font-bold text-gray-800">Visual Arts</div>
                <div class="text-xs text-gray-600">Design & Creativity</div>
            </div>
         </div>
         <div class="aspect-square bg-gradient-to-br from-blue-100 to-indigo-100 rounded-2xl relative overflow-hidden group flex items-center justify-center">
             <div class="text-center">
                <div class="text-4xl mb-2">💼</div>
                <div class="font-bold text-gray-800">Business</div>
                <div class="text-xs text-gray-600">Leadership & Strategy</div>
            </div>
         </div>
         <div class="col-span-2 bg-white rounded-2xl flex items-center justify-center border border-gray-200 p-8">
             <div class="text-center">
                <div class="text-3xl font-bold text-gray-800 mb-2">And many more...</div>
                <div class="text-sm text-gray-500">Podcasting, Beekeeping, Tattoo Art, Sexual Health, Stoicism, Breathwork, and beyond</div>
             </div>
         </div>
      </div>
    </div>
  </section>

  <!-- Primary CTA Section -->
  <section class="bg-primary-500 py-24 relative overflow-hidden">
    <div class="max-w-4xl mx-auto px-4 text-center relative z-10">
        <h2 class="text-4xl md:text-6xl font-serif mb-8 text-white">Ready to build your <br /> coaching empire?</h2>
        
        <div class="flex flex-col md:flex-row justify-center gap-6 mb-10 text-sm font-medium text-white/90">
            <div class="flex items-center gap-2">
                <div class="bg-white text-primary-600 rounded-full p-0.5"><svg class="w-3 h-3" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="3" d="M5 13l4 4L19 7"></path></svg></div>
                Launch in minutes with AI
            </div>
            <div class="flex items-center gap-2">
                <div class="bg-white text-primary-600 rounded-full p-0.5"><svg class="w-3 h-3" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="3" d="M5 13l4 4L19 7"></path></svg></div>
                No coding required
            </div>
            <div class="flex items-center gap-2">
                <div class="bg-white text-primary-600 rounded-full p-0.5"><svg class="w-3 h-3" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="3" d="M5 13l4 4L19 7"></path></svg></div>
                Join world-class creators
            </div>
        </div>

        <div class="flex justify-center gap-4">
            <Button href="#" type="primary">Get Early Access &rarr;</Button>
            <Button href="#" type="white">Learn More</Button>
        </div>
    </div>

    <!-- Decorative Elements -->
    <div class="absolute bottom-0 left-0 right-0 h-32 opacity-10 pointer-events-none">
        <div class="absolute bottom-10 left-10 w-20 h-20 bg-white rounded-full"></div>
        <div class="absolute bottom-5 right-20 w-16 h-16 bg-white rounded-full"></div>
        <div class="absolute bottom-20 left-1/3 w-12 h-12 bg-white rounded-full"></div>
    </div>
  </section>

  <!-- Creator Success Stories -->
  <section class="py-24 bg-gray-50">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16">Creator Success Stories</h2>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
        <!-- Large Card Top - H.E.R. -->
        <div class="md:col-span-2 bg-gradient-to-br from-purple-100 to-pink-100 rounded-3xl p-10 md:p-16 flex flex-col md:flex-row items-center gap-10">
            <div class="flex-1">
                <div class="text-6xl mb-4">🎵</div>
                <div class="text-3xl font-bold text-gray-800 mb-2">H.E.R.</div>
                <div class="text-sm text-gray-600">5x Grammy Winner</div>
            </div>
            <div class="flex-1 bg-white/90 backdrop-blur rounded-2xl p-8 shadow-sm">
                <div class="text-xs font-bold text-gray-400 uppercase mb-4">Creator Story</div>
                <h3 class="text-2xl font-serif mb-4">How H.E.R. built a thriving music coaching community</h3>
                <p class="text-gray-500 text-sm mb-6">The Grammy-winning artist shares her journey of transforming her musical expertise into a personalized coaching experience for aspiring musicians worldwide...</p>
                <div class="flex justify-between items-center">
                    <span class="text-xs text-gray-400">5 min read</span>
                    <button class="bg-primary-600 text-white px-4 py-2 rounded-lg text-xs font-bold hover:bg-primary-700">Read more &rarr;</button>
                </div>
            </div>
        </div>

        <!-- Bottom Left - Simone Giertz -->
        <div class="bg-gradient-to-br from-blue-100 to-cyan-100 rounded-3xl p-8 flex flex-col justify-between h-96">
            <div class="mb-8">
                <div class="text-4xl mb-3">🔧</div>
                <div class="text-xl font-bold text-gray-800">Simone Giertz</div>
                <div class="text-xs text-gray-600">Inventor, 2.6M Subscribers</div>
            </div>
            <div class="bg-white/90 backdrop-blur rounded-2xl p-6 shadow-sm mt-auto">
                <div class="text-xs font-bold text-gray-400 uppercase mb-2">Creator Story</div>
                <h3 class="text-xl font-serif mb-4">Teaching invention and creative engineering</h3>
                <div class="flex justify-between items-center mt-4">
                    <span class="text-xs text-gray-400">4 min read</span>
                    <button class="bg-primary-600 text-white px-3 py-1.5 rounded-lg text-xs font-bold hover:bg-primary-700">Read more &rarr;</button>
                </div>
            </div>
        </div>

        <!-- Bottom Right - Claire Saffitz -->
        <div class="bg-gradient-to-br from-yellow-100 to-orange-100 rounded-3xl p-8 flex flex-col justify-between h-96">
            <div class="mb-8">
                <div class="text-4xl mb-3">🍰</div>
                <div class="text-xl font-bold text-gray-800">Claire Saffitz</div>
                <div class="text-xs text-gray-600">NYT Bestselling Author</div>
            </div>
            <div class="bg-white/90 backdrop-blur rounded-2xl p-6 shadow-sm mt-auto">
                <div class="text-xs font-bold text-gray-400 uppercase mb-2">Creator Story</div>
                <h3 class="text-xl font-serif mb-4">From cookbook to coaching app in minutes</h3>
                <div class="flex justify-between items-center mt-4">
                    <span class="text-xs text-gray-400">4 min read</span>
                    <button class="bg-primary-600 text-white px-3 py-1.5 rounded-lg text-xs font-bold hover:bg-primary-700">Read more &rarr;</button>
                </div>
            </div>
        </div>
      </div>
    </div>
  </section>

  <!-- FAQ -->
  <section class="py-24 bg-white">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif mb-16">Frequently Asked Questions</h2>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-x-12 gap-y-6">
        {#each [
            "What is Studio?",
            "Who can use Studio?",
            "How does the AI content generation work?",
            "Do I need coding skills to build my app?",
            "How long does it take to launch my coaching app?",
            "Can I customize my app's design?",
            "How do I monetize my coaching app?",
            "How do I get started with Studio?"
        ] as question}
            <div class="border-b border-gray-200 py-4 flex justify-between items-center group cursor-pointer">
                <span class="font-medium text-lg group-hover:text-primary-600 transition-colors">{question}</span>
                <div class="w-6 h-6 rounded-full bg-dark text-white flex items-center justify-center text-sm group-hover:bg-primary-600 transition-colors">+</div>
            </div>
        {/each}
      </div>
    </div>
  </section>

  <Footer />
</div>

<style>
  /* Custom Scroll Animation */
  @keyframes scroll {
    0% { transform: translateX(0); }
    100% { transform: translateX(-50%); }
  }
  .animate-scroll {
    animation: scroll 20s linear infinite;
  }
  
  @keyframes spin-slow {
    from { transform: rotate(0deg); }
    to { transform: rotate(360deg); }
  }
  .animate-spin-slow {
    animation: spin-slow 20s linear infinite;
  }
</style>

