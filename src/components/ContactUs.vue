<template>
  <section class="py-32 px-8 bg-white text-black mb-0">
    <div class="container mx-auto text-center">
      <h2 class="text-4xl font-bold mb-12 opacity-90 inline-block border-b-2 border-black pb-2">Contact Us</h2>

      <div class="grid grid-cols-1 sm:grid-cols-2 gap-8">
        <!-- Contact Form -->
        <div class="p-6 rounded-lg shadow-2xl bg-gray-200">
          <h3 class="text-2xl font-semibold mb-4 opacity-80">Get In Touch</h3>
          <form @submit.prevent="handleSubmit">
            <div class="mb-4">
              <label for="name" class="block text-left font-medium opacity-70">Name</label>
              <input
                type="text"
                id="name"
                v-model="name"
                placeholder="Enter your name"
                class="w-full p-3 border border-gray-300 rounded-lg mt-2"
                required
              />
            </div>
            <div class="mb-4">
              <label for="email" class="block text-left font-medium opacity-70">Email</label>
              <input
                type="email"
                id="email"
                v-model="email"
                placeholder="Enter your email"
                class="w-full p-3 border border-gray-300 rounded-lg mt-2"
                required
              />
            </div>
            <div class="mb-4">
              <label for="message" class="block text-left font-medium opacity-70">Message</label>
              <textarea
                id="message"
                placeholder="Write your message"
                v-model="message"
                class="w-full p-3 border border-gray-300 rounded-lg mt-2"
                required
              ></textarea>
            </div>
            <button type="submit" class="w-full bg-black text-white py-3 rounded-lg hover:bg-gray-900">Send Message</button>
          </form>
        </div>

        <!-- Contact Info -->
      <div class="p-6 rounded-lg shadow-2xl bg-gray-200 flex flex-col">
          <h3 class="text-2xl font-semibold mb-4 opacity-80">Find Us</h3>

          <iframe
            class="w-full h-full rounded-lg border border-gray-300"
            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d6353923.972621374!2d121.15741893535583!3d7.831231121073893!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x32f552fc1d482cdd%3A0x14c5088d630e63f7!2sMindanao%2C%20Philippines!5e0!3m2!1sen!2sus!4v1631234567890!5m2!1sen!2sus"
            allowfullscreen=""
            loading="lazy"
          ></iframe>
        </div>
      </div>
    </div>
  </section>

  <!--Footer-->
  <footer class="bg-black text-white py-8">
    <div class="container mx-auto px-6">
      <div class="grid grid-cols-1 md:grid-cols-4 gap-8 opacity-80 text-sm">
        <!-- ABOUT ELITE FOOTPRINTS -->
        <div>
          <h3 class="font-semibold mb-3">ABOUT ELITE FOOTPRINTS</h3>
          <p>
            At Elite Footprints, we take pride in crafting exceptional footwear that blends style, comfort, and durability. Our mission is to provide you with shoes that leave an unforgettable mark on the world.
          </p>
          <div class="flex space-x-3 mt-4">
            <a href="https://facebook.com" target="_blank"><i class="fa fa-facebook"></i></a>
            <a href="https://twitter.com" target="_blank"><i class="fa fa-twitter"></i></a>
            <a href="https://instagram.com" target="_blank"><i class="fa fa-instagram"></i></a>
          </div>
        </div>

        <!-- CUSTOMER CARE -->
        <div>
          <h3 class="font-semibold mb-3">CUSTOMER CARE</h3>
          <ul class="space-y-2">
            <li>Contact</li>
            <li>Returns/Exchange</li>
            <li>Gift Voucher</li>
            <li>Wishlist</li>
            <li>Special</li>
            <li>Customer Services</li>
            <li>Site Maps</li>
          </ul>
        </div>

        <!-- INFORMATION -->
        <div>
          <h3 class="font-semibold mb-3">INFORMATION</h3>
          <ul class="space-y-2">
            <li>About Us</li>
            <li>Delivery Information</li>
            <li>Privacy Policy</li>
            <li>Support</li>
            <li>Order Tracking</li>
          </ul>
        </div>

        <!-- CONTACT INFORMATION -->
        <div>
          <h3 class="font-semibold mb-3">CONTACT INFORMATION</h3>
          <p>123 Street, Butuan City, Philippines</p>
          <p class="mt-2">+1235 2355 98</p>
          <p class="mt-2">cats@elitefootprints.com</p>
          <p class="mt-2">elitefootprints.com</p>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  data() {
    return {
      name: '',
      email: '',
      message: '',
    };
  },
  methods: {
    handleSubmit() {
      // Handle form submission logic
      alert(`Message sent by ${this.name}`);
    },
  },
};
</script>

<style scoped>
/* Optional: Customize the styles for ContactUs.vue here if needed */
</style>
