<template>
  <div class="bg-black text-white font-sans">
  
    <!-- Hero Section -->
    <section class="h-screen bg-cover bg-center relative" style="background-image: url('src/assets/images/aboutUsBanner.jpg');">
      <div class="absolute inset-0 bg-black opacity-50"></div>
      <div class="relative z-10 flex flex-col items-center justify-center h-full text-center">
        <h1 class="text-5xl sm:text-7xl font-extrabold leading-tight mb-6">About Us</h1>
        <p class="text-xl sm:text-2xl font-medium max-w-2xl mx-auto opacity-80">We bring you the rarest shoes that redefine style.</p>
      </div>
    </section>
  
    <!-- Our Story Section -->
    <section class="py-20 px-8 bg-black text-white mt-12">
      <div class="container mx-auto text-center sm:text-left flex flex-col sm:flex-row items-center justify-between">
        <!-- Image on the left -->
        <div class="w-full sm:w-1/2 flex justify-center mb-8 sm:mb-0">
          <img class="w-full sm:w-96 rounded-lg shadow-xl" src="../assets/images/ourStoryPic.jpg" alt="Rare Kicks Story">
        </div>
        <div class="w-full sm:w-1/2 sm:px-8">
          <h2 class="text-4xl font-bold mb-6 opacity-90 inline-block border-b-2 border-white pb-2">Our Story</h2>
          <p class="text-sm sm:text-base max-w-3xl mx-auto leading-relaxed opacity-80 text-justify">
            At <span class="font-bold">Elite Footprints</span>, we are not just about shoes; we are about finding rare, exclusive, and highly sought-after footwear from every corner of the globe. Our collection brings together the best of the sneaker world—limited edition releases, classic vintage pairs, and collaborations with renowned designers. We cater to sneakerheads, collectors, and anyone passionate about footwear, offering rare gems that you won’t find anywhere else.
            <br><br>
            Over the years, we have built a trusted community of enthusiasts who share our passion for exclusive kicks. Whether you're hunting for your next prized possession or looking to add to your collection, our team is dedicated to offering the finest, most sought-after shoes. Our journey began with a simple idea: to curate a selection of shoes that aren't just about trends, but about quality, rarity, and the love for craftsmanship.
          </p>
        </div>
      </div>
    </section>
    
    <!-- Our Values Section -->
    <section class="py-20 px-8 bg-black text-white">
      <div class="container mx-auto text-center">
        <h2 class="text-4xl font-bold mb-12 opacity-90 inline-block border-b-2 border-white pb-2">Our Values</h2>
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
          <!-- Quality Card -->
          <div class="bg-white text-black p-6 rounded-lg shadow-xl hover:shadow-2xl transition duration-300 transform hover:scale-105 max-w-xs mx-auto">
            <div class="mb-4">
              <svg xmlns="http://www.w3.org/2000/svg" class="w-12 h-12 text-purple-600 mx-auto" fill="none" stroke="currentColor" viewBox="0 0 24 24" stroke-width="2"><path stroke-linecap="round" stroke-linejoin="round" d="M12 8V4m0 12v-4m0 0a4 4 0 110-8m0 8a4 4 0 110-8m0 8a4 4 0 010-8" /></svg>
            </div>
            <h3 class="text-xl font-semibold mb-4 opacity-90">Quality</h3>
            <p class="text-sm opacity-80">
              We only sell high-quality, authentic shoes. Our rare collection is handpicked to meet the highest standards.
            </p>
          </div>
          <!-- Passion Card -->
          <div class="bg-white text-black p-6 rounded-lg shadow-xl hover:shadow-2xl transition duration-300 transform hover:scale-105 max-w-xs mx-auto">
            <div class="mb-4">
              <svg xmlns="http://www.w3.org/2000/svg" class="w-12 h-12 text-red-600 mx-auto" fill="none" stroke="currentColor" viewBox="0 0 24 24" stroke-width="2"><path stroke-linecap="round" stroke-linejoin="round" d="M12 8V4m0 12v-4m0 0a4 4 0 110-8m0 8a4 4 0 110-8m0 8a4 4 0 010-8" /></svg>
            </div>
            <h3 class="text-xl font-semibold mb-4 opacity-90">Passion</h3>
            <p class="text-sm opacity-80">
              We are passionate about footwear and strive to bring the best to our customers. Each pair tells a unique story.
            </p>
          </div>
          <!-- Exclusivity Card -->
          <div class="bg-white text-black p-6 rounded-lg shadow-xl hover:shadow-2xl transition duration-300 transform hover:scale-105 max-w-xs mx-auto">
            <div class="mb-4">
              <svg xmlns="http://www.w3.org/2000/svg" class="w-12 h-12 text-yellow-600 mx-auto" fill="none" stroke="currentColor" viewBox="0 0 24 24" stroke-width="2"><path stroke-linecap="round" stroke-linejoin="round" d="M12 8V4m0 12v-4m0 0a4 4 0 110-8m0 8a4 4 0 110-8m0 8a4 4 0 010-8" /></svg>
            </div>
            <h3 class="text-xl font-semibold mb-4 opacity-90">Exclusivity</h3>
            <p class="text-sm opacity-80">
              Our collection features limited edition and rare shoes you won’t find anywhere else. Only the best for our customers.
            </p>
          </div>
        </div>
      </div>
    </section>

        <!-- Team Section -->
        <section class="py-32 px-8 bg-white text-black">
        <div class="container mx-auto text-center">
            <h2 class="text-4xl font-bold mb-12 opacity-90 inline-block border-b-2 border-black pb-2">Meet the Team</h2>
            <div class="grid grid-cols-1 sm:grid-cols-3 gap-6">
            <!-- Team Member 1 -->
            <div class="p-6 rounded-lg shadow-2xl bg-gray-100">
                <div class="w-48 h-48 bg-gray-400 rounded-lg mx-auto mb-6">
                    <img class="w-full h-full object-cover rounded-lg" src="https://via.placeholder.com/150" alt="Team member 1">
                </div>
                <h3 class="text-xl font-semibold mb-2 opacity-90">Roman Osorio</h3>
                <!-- Social Icons -->
                <div class="flex justify-center gap-4 mt-4">
                    <a href="https://facebook.com" target="_blank"><i class="fa fa-facebook"></i></a>
                    <a href="https://twitter.com" target="_blank"><i class="fa fa-twitter"></i></a>
                    <a href="https://instagram.com" target="_blank"><i class="fa fa-instagram"></i></a>
                </div>
            </div>

            <!-- Team Member 2 -->
            <div class="p-6 rounded-lg shadow-2xl bg-gray-100">
                <div class="w-48 h-48 bg-gray-400 rounded-lg mx-auto mb-6">
                <img class="w-full h-full object-cover rounded-lg" src="https://via.placeholder.com/150" alt="Team member 2">
                </div>
                <h3 class="text-xl font-semibold mb-2 opacity-90">Reyhan Cris Florida</h3>
                <!-- Social Icons -->
                <div class="flex justify-center gap-4 mt-4">
                    <a href="https://facebook.com" target="_blank"><i class="fa fa-facebook"></i></a>
                    <a href="https://twitter.com" target="_blank"><i class="fa fa-twitter"></i></a>
                    <a href="https://instagram.com" target="_blank"><i class="fa fa-instagram"></i></a>
                </div>
            </div>

            <!-- Team Member 3 -->
            <div class="p-6 rounded-lg shadow-2xl bg-gray-100">
                <div class="w-48 h-48 bg-gray-400 rounded-lg mx-auto mb-6">
                <img class="w-full h-full object-cover rounded-lg" src="../assets/images/frezzie.jpg" alt="Team member 3">
                </div>
                <h3 class="text-xl font-semibold mb-2 opacity-90">Frezzie Catamora</h3>
                <!-- Social Icons -->
                <div class="flex justify-center gap-4 mt-4">
                    <a href="https://facebook.com" target="_blank"><i class="fa fa-facebook"></i></a>
                    <a href="https://twitter.com" target="_blank"><i class="fa fa-twitter"></i></a>
                    <a href="https://instagram.com" target="_blank"><i class="fa fa-instagram"></i></a>
                </div>
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
  </div>
</template>

<script>
export default {
  name: 'AboutUs',
};
</script>

<style scoped>
h2, h3 {
  font-family: 'Roboto', sans-serif;
  font-weight: 700;
  letter-spacing: 1px;
}

h1 {
  font-family: 'Roboto', sans-serif;
  font-weight: 800;
  letter-spacing: 1.5px;
}
</style>
