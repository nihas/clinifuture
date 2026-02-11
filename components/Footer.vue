<template>
  <footer class="bg-white-900 text-black">
    <div class="max-w-7xl mx-auto px-6 py-14">
      <div class="grid gap-10 md:grid-cols-3">

        <!-- Left: Logo + Description -->
        <div>
          <div class="flex items-center text-black text-xl font-bold">
        <img src="/clinifuture_logo.png" alt="Tek-Z Logo" class="h-8 mr-2">
        CLINI<span class="text-indigo-400">FUTURE</span>
      </div>
          <p class="mt-4 text-gray-600">
            Platform designed to help organizations, educators, and learners
            manage, deliver, and track learning and training activities.
          </p>

          <!-- Social Icons -->
          <div class="mt-6 flex gap-4">
            <!-- <a href="#" class="hover:text-indigo-400">
              <i class="fa-brands fa-facebook-f"></i>
            </a> -->
            <a href="https://www.instagram.com/clini_future_/" class="hover:text-indigo-400">
              <i class="fa-brands fa-instagram"></i>
            </a>
            <!-- <a href="#" class="hover:text-indigo-400">
              <i class="fa-brands fa-linkedin-in"></i>
            </a> -->
          </div>
        </div>

        <!-- Center: Useful Links -->
        <div class="text-center md:text-left">
          <h3 class="font-semibold text-lg">Useful Links</h3>
          <ul class="mt-4 space-y-3 text-gray-600">
            <li><a href="#" class="hover:text-indigo-400">Home</a></li>
            <li><a href="#" class="hover:text-indigo-400">About Us</a></li>
            <li><a href="#" class="hover:text-indigo-400">Courses</a></li>
            <li><a href="#" class="hover:text-indigo-400">Contact Us</a></li>
          </ul>
        </div>

        <!-- Right: Newsletter -->
        <div class="text-center md:text-left">
          <h3 class="font-semibold text-lg">Subscribe to Newsletters</h3>
          <p class="mt-3 text-gray-600">
            Get the latest course updates and offers.
          </p>

          <div class="mt-4 flex flex-col sm:flex-row gap-3">
            <input
              type="email"
              placeholder="Enter your email"
              class="w-full sm:w-auto flex-1 px-4 py-3 rounded-lg bg-white border border-gray-700 focus:outline-none focus:border-indigo-400"
            />
            <button class="px-6 py-3 rounded-lg bg-indigo-500 hover:bg-indigo-600 transition font-semibold">
              Subscribe
            </button>
          </div>
        </div>

      </div>
    </div>

    <!-- Bottom Row -->
    <div class="border-t border-gray-800">
      <div class="max-w-7xl mx-auto px-6 py-6 flex flex-col md:flex-row items-center justify-between gap-4">
        
        <!-- Left: Copyright -->
        <div class="text-gray-500 text-sm">
          Copyright 2026 © CLINIFUTURE. All right reserved.
        </div>

        <!-- Center: Policies -->
        <div class="flex flex-col md:flex-row gap-4 text-gray-400 text-sm">
          <a href="#" class="hover:text-black">Privacy Policy</a>
          <a href="#" class="hover:text-black">Terms & Conditions</a>
         <!--  <a href="#" class="hover:text-white">Refund Policy</a> -->
        </div>

        <!-- Right: Social Icons -->
        <div class="flex gap-4">
          <!-- <a href="#" class="hover:text-indigo-400">
            <i class="fa-brands fa-facebook-f"></i>
          </a> -->
          <a href="https://www.instagram.com/clini_future_/" class="hover:text-indigo-400">
            <i class="fa-brands fa-instagram"></i>
          </a>
          <!-- <a href="#" class="hover:text-indigo-400">
            <i class="fa-brands fa-linkedin-in"></i>
          </a> -->
        </div>
      </div>
    </div>
  </footer>
</template>