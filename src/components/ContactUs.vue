<template>
    <section class="py-32 px-8 bg-white text-black mb-0">
      <div class="container mx-auto text-center">
        <h2 class="text-4xl font-bold mb-12 opacity-90 inline-block border-b-2 border-black pb-2">Contact Us</h2>
  
        <div class="grid grid-cols-1 sm:grid-cols-2 gap-8">
          <!-- Contact Form -->
          <div class="p-6 rounded-lg shadow-2xl bg-gray-200">
            <h3 class="text-2xl font-semibold mb-4 opacity-90">Get In Touch</h3>
            <form @submit.prevent="handleSubmit">
              <div class="mb-4">
                <label for="name" class="block text-left font-medium">Name</label>
                <input type="text" id="name" v-model="name" placeholder="Enter your name" class="w-full p-3 border border-gray-300 rounded-lg mt-2" required />
              </div>
              <div class="mb-4">
                <label for="email" class="block text-left font-medium">Email</label>
                <input type="email" id="email" v-model="email" placeholder="Enter your email" class="w-full p-3 border border-gray-300 rounded-lg mt-2" required />
              </div>
              <div class="mb-4">
                <label for="message" class="block text-left font-medium">Message</label>
                <textarea id="message" placeholder="Write your message" v-model="message" class="w-full p-3 border border-gray-300 rounded-lg mt-2" required></textarea>
              </div>
              <button type="submit" class="w-full bg-black text-white py-3 rounded-lg hover:bg-gray-800">Send Message</button>
            </form>
          </div>
  
          <!-- Contact Info -->
          <div class="p-6 rounded-lg shadow-2xl bg-gray-200">
            <h3 class="text-2xl font-semibold mb-4 opacity-90">Our Info</h3>
            <p class="text-left mb-4"><strong>Address:</strong> 1234 Street, City, Country</p>
            <p class="text-left mb-4"><strong>Phone:</strong> +123 456 789</p>
            <p class="text-left mb-4"><strong>Email:</strong> info@example.com</p>
  
            <div class="flex justify-center gap-4 mt-4">
              <a href="https://facebook.com" class="text-black text-2xl"><i class="fab fa-facebook"></i></a>
              <a href="#" class="text-black text-2xl"><i class="fab fa-twitter"></i></a>
              <a href="#" class="text-black text-2xl"><i class="fab fa-instagram"></i></a>
            </div>
          </div>
        </div>
      </div>
    </section>
  
    <!-- Footer Section -->
    <footer class="bg-black text-white text-center py-8">
      <p>&copy; 2024 Elite Footprints. All rights reserved.</p>
    </footer>
  </template>
  
  <script>
  export default {
    data() {
      return {
        name: '',
        email: '',
        message: ''
      };
    },
    methods: {
      handleSubmit() {
        // Handle form submission logic
        alert(`Message sent by ${this.name}`);
      }
    }
  };
  </script>
  
  <style scoped>
  /* Optional: Customize the styles for ContactUs.vue here if needed */
  </style>
  