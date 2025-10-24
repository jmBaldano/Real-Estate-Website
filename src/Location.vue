    <template>
  <div class="flex flex-col min-h-screen text-gray-900 bg-gray-100">
    <!-- MAP SECTION -->
    <main class="flex-grow">
      <div class="w-full h-[80vh]">
        <iframe
          src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d26645.429592029174!2d-116.0561558!3d36.201052!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x80c90c7c6f63a3f5%3A0x76fa9374dd7cc5a6!2s3190%20NV-160%2C%20Suite%20F%2C%20Pahrump%2C%20NV%2089048%2C%20USA!5e0!3m2!1sen!2sph!4v1698564460000!5m2!1sen!2sph"
          width="100%"
          height="100%"
          style="border:0;"
          loading="lazy"
        ></iframe>
      </div>
    </main>

    <!-- FOOTER -->
    <footer class="py-6 text-center text-gray-300 bg-gray-900">
      <div class="flex justify-center mb-4 space-x-6">
        <!-- Instagram -->
        <a
          href="https://www.instagram.com"
          target="_blank"
          class="hover:text-white"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="currentColor"
            class="w-6 h-6"
            viewBox="0 0 24 24"
          >
            <path
              d="M7.5 2C4.46 2 2 4.46 2 7.5v9C2 19.54 4.46 22 7.5 22h9c3.04 0 5.5-2.46 5.5-5.5v-9C22 4.46 19.54 2 16.5 2h-9zM12 7.25a4.75 4.75 0 1 1 0 9.5a4.75 4.75 0 0 1 0-9.5zm6.25-.75a.75.75 0 1 1 0 1.5a.75.75 0 0 1 0-1.5zM12 9a3 3 0 1 0 0 6a3 3 0 0 0 0-6z"
            />
          </svg>
        </a>

        <!-- Facebook -->
        <a
          href="https://www.facebook.com"
          target="_blank"
          class="hover:text-white"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="currentColor"
            class="w-6 h-6"
            viewBox="0 0 24 24"
          >
            <path
              d="M22 12a10 10 0 1 0-11.5 9.9v-7h-2v-3h2v-2.3c0-2 1.2-3.1 3-3.1c.9 0 1.8.2 1.8.2v2h-1c-1 0-1.3.6-1.3 1.2V12h2.3l-.4 3h-1.9v7A10 10 0 0 0 22 12z"
            />
          </svg>
        </a>

        <!-- LinkedIn -->
        <a
          href="https://www.linkedin.com"
          target="_blank"
          class="hover:text-white"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="currentColor"
            class="w-6 h-6"
            viewBox="0 0 24 24"
          >
            <path
              d="M19 0h-14a5 5 0 0 0-5 5v14a5 5 0 0 0 5 5h14a5 5 0 0 0 5-5v-14a5 5 0 0 0-5-5zm-11 19h-3v-9h3v9zm-1.5-10.3a1.7 1.7 0 1 1 0-3.4a1.7 1.7 0 0 1 0 3.4zm13.5 10.3h-3v-4.7c0-1.1 0-2.6-1.6-2.6s-1.8 1.2-1.8 2.5v4.8h-3v-9h2.8v1.2h.1a3.1 3.1 0 0 1 2.8-1.5c3 0 3.6 2 3.6 4.6v4.7z"
            />
          </svg>
        </a>

        <!-- Yelp -->
        <a href="https://www.yelp.com" target="_blank" class="hover:text-white">
          <svg
            xmlns="http://www.w3.org/2000/svg"
            fill="currentColor"
            class="w-6 h-6"
            viewBox="0 0 24 24"
          >
            <path
              d="M14.63 10.37l4.96-.6c1.43-.18 1.65 1.83.23 2.02l-4.96.6a.78.78 0 0 1-.23-1.53zM9.35 12.18l-4.35 2.6c-1.26.75-2.23-1.03-.97-1.78l4.35-2.6a.78.78 0 0 1 .97 1.78zm.08-2.62L5.08 6.77c-1.2-.87.06-2.43 1.26-1.56l4.35 2.8a.78.78 0 0 1-.97 1.56zm5.22.02l2.44-4.4c.69-1.26 2.38-.26 1.69 1l-2.44 4.4a.78.78 0 1 1-1.69-1zm-.88 2.91l1.26 4.83c.33 1.4-1.65 1.83-1.98.43l-1.26-4.83a.78.78 0 0 1 1.98-.43z"
            />
          </svg>
        </a>
      </div>
      <p class="text-sm text-gray-500 font-extralight">
        &copy; Copyright © 2023 Marci METZGER Homes - All Rights Reserved


      </p>
    </footer>
  </div>
</template>

<script setup>
// No JS logic needed for this static page
</script>

<style scoped>
/* Optional: add smooth scrolling for aesthetic */
html {
  scroll-behavior: smooth;
}
</style>
