<template>
  <div class="about">
    <div class="max-w-4xl flex items-center flex-wrap mx-auto my-32 lg:my-0">
      <div
        id="profile"
        class="w-full rounded-lg lg:rounded-l-lg lg:rounded-r-none shadow-2xl bg-white opacity-75 mx-6 lg:mx-0"
      >
        <div class="p-4 md:p-12 text-center lg:text-left">
          <div
            class="block lg:hidden rounded-full shadow-xl mx-auto -mt-16 h-48 w-48 bg-cover bg-center"
            style="background-image: url('https://source.unsplash.com/MP0IUfwrn0A')"
          ></div>

          <h1 class="text-3xl font-bold pt-8 lg:pt-0">NViser | About</h1>
          <div class="mx-auto lg:mx-0 w-4/5 pt-3 border-b-2 border-teal-500 opacity-25"></div>
          <h1 class="text-2xl font-bold pt-8 lg:pt-0">Hi,</h1>
          <p>NViser (Next Generation Adviser) is an information technology company based in Turkey and having over 10 years of experience in software development across different domains including industrial automation, business-to-business integration, managed electronic data interchange services, business intelligence and artificial intelligence.</p>

          <div class="pt-12 pb-8">
            <a href="http://nviser.com"
              class="bg-teal-700 hover:bg-teal-900 text-white font-bold py-2 px-4 rounded-full"
            >Get In Touch</a>
          </div>
          <SocialFooter></SocialFooter>
          
        </div>
      </div>

      <div class="absolute top-0 right-0 h-12 w-18 p-4">
        <button class="js-change-theme focus:outline-none">🌙</button>
      </div>
    </div>
  </div>
</template> 


<script> 
// @ is an alias to /src
import SocialFooter from "@/components/SocialFooter.vue";

export default {
  name: "About",
  components: {
    SocialFooter
  }
};
</script>
