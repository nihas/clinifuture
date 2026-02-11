<template>
  <div class="smooth-scroll">
    <Navbar />

    <!-- Hero Section -->
    <section class="relative h-screen w-full overflow-hidden">
      
      <!-- Background Video -->
      <video
        autoplay
        muted
        loop
        playsinline
        class="absolute inset-0 w-full h-full object-cover"
      >
        <source src="/clinidna.mp4" type="video/mp4" />
      </video>

      <!-- Overlay -->
      <div class="absolute inset-0 bg-black/60"></div>

      <!-- Content -->
      <div
        class="relative z-10 flex items-center h-full max-w-7xl mx-auto px-6"
      >
        <div class="max-w-3xl text-white">
          <h1 class="text-4xl md:text-6xl font-bold leading-tight">
            Empower Your Future with
            <span class="text-indigo-400">CLINIFUTURE</span>
          </h1>

          <p class="mt-6 text-lg md:text-xl text-gray-200">
            Unlock Your Path to Top Online Certification Courses
          </p>

          <p class="mt-4 text-gray-300">
            Explore highly rated online certification programs built for real-world success. Whether you're looking to enhance your skills or begin a new career journey, CliniFuture delivers industry-focused courses with certifications that help you stay competitive in today’s rapidly evolving digital landscape.
          </p>

          <p class="mt-4 font-medium">
            Start your learning journey today with most trusted e-learning platform!
          </p>

          <!-- Buttons -->
          <div class="mt-8 flex flex-col sm:flex-row gap-4">
            <button
              href="#courses"
              class="px-8 py-3 rounded-lg bg-indigo-500 hover:bg-indigo-600 transition font-semibold"
            >
              Explore Courses
            </button>

            <button
              class="px-8 py-3 rounded-lg border border-white hover:bg-white hover:text-black transition font-semibold"
            >
              Talk to an Expert
            </button>
          </div>
        </div>
      </div>
    </section>




    <!-- Featured Courses Section -->
<section id="courses" class="bg-gray-50 py-20">
  <div class="max-w-7xl mx-auto px-6">

    <!-- Section Header -->
    <div class="text-center max-w-3xl mx-auto">
      <h2 class="text-3xl md:text-4xl font-bold text-gray-900">
        Featured Courses
      </h2>
      <p class="mt-4 text-lg text-gray-600">
        Our Most In-Demand Programs
      </p>
    </div>

    <!-- Courses Grid -->
    <div class="mt-14 grid gap-8 md:grid-cols-3">
      
      <!-- Course Card -->
      <div class="group bg-white rounded-xl overflow-hidden shadow-md hover:shadow-xl transition">
        <img
          src="/clinical-research.jpg"
          alt="Clinical Research"
          class="h-52 w-full object-cover group-hover:scale-105 transition"
        />
        <div class="p-6">
          <h3 class="text-xl font-semibold text-gray-900">
            Clinical Research
          </h3>
          <p class="mt-3 text-gray-600">
            Gain practical knowledge and certifications to build a career in
            clinical trials and research.
          </p>
          <button
            class="mt-5 text-indigo-600 font-semibold hover:underline"
          >
            Learn More →
          </button>
        </div>
      </div>

      <!-- Course Card -->
      <div class="group bg-white rounded-xl overflow-hidden shadow-md hover:shadow-xl transition">
        <img
          src="/medical_coding.jpg"
          alt="Medical Coding"
          class="h-52 w-full object-cover group-hover:scale-105 transition"
        />
        <div class="p-6">
          <h3 class="text-xl font-semibold text-gray-900">
            Medical Coding
          </h3>
          <p class="mt-3 text-gray-600">
            Master medical coding standards and prepare for high-demand
            healthcare IT roles.
          </p>
          <button
            class="mt-5 text-indigo-600 font-semibold hover:underline"
          >
            Learn More →
          </button>
        </div>
      </div>

      <!-- Course Card -->
      <div class="group bg-white rounded-xl overflow-hidden shadow-md hover:shadow-xl transition">
        <img
          src="/hospital-administration.jpg"
          alt="Hospital Administration"
          class="h-52 w-full object-cover group-hover:scale-105 transition"
        />
        <div class="p-6">
          <h3 class="text-xl font-semibold text-gray-900">
            Hospital Administration
          </h3>
          <p class="mt-3 text-gray-600">
            Develop leadership and management skills for hospital and healthcare
            administration roles.
          </p>
          <button
            class="mt-5 text-indigo-600 font-semibold hover:underline"
          >
            Learn More →
          </button>
        </div>
      </div>

    </div>
  </div>
</section>


<!-- Learning Experience Section -->
<section class="py-20 bg-white">
  <div
    class="max-w-7xl mx-auto px-6 grid gap-12 items-center md:grid-cols-2"
  >
    <!-- Left Content -->
    <div>
      <h2 class="text-3xl md:text-4xl font-bold text-gray-900">
        Shaping the Future of Learning
      </h2>

      <p class="mt-6 text-lg text-gray-600">
        Our mission is to redefine education by building a dynamic and inclusive learning environment. Through premium online courses and guidance from experienced industry experts, CliniFuture supports learners from every background in unlocking their potential, reaching their goals, and succeeding in their careers.
      </p>

      <!-- Feature Points -->
      <div class="mt-8 space-y-5">
        
        <!-- Point -->
        <div class="flex items-start gap-4">
          <div
            class="flex h-12 w-12 items-center justify-center rounded-lg bg-indigo-100 text-indigo-600"
          >
            📍
          </div>
          <div>
            <h4 class="text-lg font-semibold text-gray-900">
              Learn Anytime, Anywhere
            </h4>
            <p class="text-gray-600">
              Study at your convenience with flexible access to courses from any location.
            </p>
          </div>
        </div>

        <!-- Point -->
        <div class="flex items-start gap-4">
          <div
            class="flex h-12 w-12 items-center justify-center rounded-lg bg-indigo-100 text-indigo-600"
          >
            🎓
          </div>
          <div>
            <h4 class="text-lg font-semibold text-gray-900">
              Guidance from Industry Experts
            </h4>
            <p class="text-gray-600">
              Gain insights and practical knowledge from professionals with real-world experience.
            </p>
          </div>
        </div>

        <!-- Point -->
        <div class="flex items-start gap-4">
          <div
            class="flex h-12 w-12 items-center justify-center rounded-lg bg-indigo-100 text-indigo-600"
          >
            🚀
          </div>
          <div>
            <h4 class="text-lg font-semibold text-gray-900">
              Career-Ready Skills
            </h4>
            <p class="text-gray-600">
              Develop the in-demand skills that today’s employers value most.
            </p>
          </div>
        </div>

      </div>
    </div>

    <!-- Right Image -->
    <div class="relative">
      <img
        src="/elearning.jpg"
        alt="Learning Experience"
        class="rounded-2xl shadow-lg"
      />
      <!-- Decorative Accent -->
      <div
        class="absolute -bottom-6 -left-6 h-24 w-24 rounded-2xl bg-indigo-500/20 blur-xl"
      ></div>
    </div>
  </div>
</section>


<!-- Talk to Our Experts Section -->
<section class="relative overflow-hidden py-20">
  
  <!-- Animated Background -->
  <div class="absolute inset-0 bg-gradient-to-r from-indigo-600 via-purple-600 to-pink-600 animate-gradient"></div>

  <!-- Overlay -->
  <div class="absolute inset-0 bg-black/30"></div>

  <!-- Content -->
  <div class="relative z-10 max-w-4xl mx-auto px-6 text-center text-white">
    <h2 class="text-3xl md:text-4xl font-bold">
      Talk to Our Experts
    </h2>

    <p class="mt-4 text-xl font-semibold">
      Unsure Which Course Is Right for You?
    </p>

    <p class="mt-4 text-lg text-gray-200">
      Our experienced advisors are ready to guide you in selecting the ideal program tailored to your goals, interests, and background.
    </p>

    <!-- CTA Button -->
    <div class="mt-5">
      <button
        class="px-10 py-4 text-lg font-semibold rounded-full bg-white text-indigo-600 hover:bg-gray-100 transition shadow-lg"
      >
        Talk to an Expert
      </button>
    </div>
  </div>
</section>


  </div>
</template>

<script setup>
import Navbar from '~/components/Navbar.vue'
</script>