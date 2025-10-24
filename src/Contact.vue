<template>
    <section class="flex items-center justify-center min-h-screen px-6 py-12 bg-black/90">
  <div class="grid w-full max-w-6xl grid-cols-1 border-gray-300 border-none md:grid-cols-2">
    
    <div class="flex flex-col justify-center p-10 text-gray-800 border-r border-gray-300 dark:text-gray-100 ">
      <h2 class="mb-10 font-serif text-5xl font-light tracking-wide text-gray-500 uppercase">CALL OR VISIT</h2>
      <h2 class="mb-4 text-3xl font-light tracking-wide uppercase">Send a message</h2>
      <h2 class="mb-4 font-serif text-lg tracking-wide uppercase">Marci Metzger - THE RIDGE REALTY GROUP</h2>
      <ul class="space-y-3 text-sm font-light">
        <li class="flex items-center gap-1">
          <span>info@company.com</span>
        </li>
        <li class="flex items-center gap-1">   
          <span>(206) 919-6886</span>
        </li>
        <li class="flex items-center gap-1">
          <span>3190 HW-160, Suite F, Pahrump, Nevada 89048, United States</span>
        </li>
      </ul>


      <ul class="space-y-2 text-sm font-light mt-9">
        <h1 class="text-lg font-semibold">Office hours</h1>
        <li class="flex items-center gap-3">
          <span> <strong>Open today </strong> 08:00 am – 07:00 pm</span>
        </li>

        <li class="flex items-center gap-3">   
          <span> <strong>Open daily </strong> 08:00 am – 07:00 pm</span>
        </li>

        <li class="flex items-center gap-3">
          <strong>Appointments outside office hours available upon request. Just call!</strong>
        </li>
      </ul>
    </div>

    <!-- ⚫ Right: Contact Form -->
    <div class="p-10 font-light dark:text-gray-100">
        <button class="flex items-center justify-center gap-2 px-5 py-2 mb-5 text-white transition border-1 hover:bg-gray-800">
            Message us on WhatsApp
            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 432 432"><path fill="#ffffff" d="M364.5 65Q427 127 427 214.5T364.5 364T214 426q-54 0-101-26L0 429l30-109Q2 271 2 214q0-87 62-149T214 3t150.5 62zM214 390q73 0 125-51.5T391 214T339 89.5T214 38T89.5 89.5T38 214q0 51 27 94l4 6l-18 65l67-17l6 3q42 25 90 25zm97-132q9 5 10 7q4 6-3 25q-3 8-15 15.5t-21 9.5q-18 2-33-2q-17-6-30-11q-8-4-15.5-8.5t-14.5-9t-13-9.5t-11.5-10t-10.5-10.5t-8.5-9.5t-7-8.5t-5.5-7t-3.5-5L128 222q-22-29-22-55q0-24 19-44q6-7 14-7q6 0 10 1q8 0 12 9q2 3 6 13l7 17.5l3 8.5q3 5 1 9q-3 7-5 9l-3 3l-3 3.5l-2 2.5q-6 6-3 11q13 22 30 37q13 11 43 26q7 3 11-1q12-15 17-21q4-6 12-3q6 3 36 17z"/></svg>
        </button>

      <form class="space-y-6">
        <div>
          <label for="name" class="block mb-1 text-sm font-medium uppercase">Name</label>
          <input type="text" id="name" placeholder="John"
            class="w-full p-3 text-sm bg-transparent border border-gray-400 focus:outline-none focus:border-black dark:border-gray-600 dark:focus:border-white" required>
        </div>

        <div>
          <label for="email" class="block mb-1 text-sm font-medium uppercase"> Email</label>
          <input type="email" id="email" placeholder="name@company.com"
            class="w-full p-3 text-sm bg-transparent border border-gray-400 focus:outline-none focus:border-black dark:border-gray-600 dark:focus:border-white" required>
        </div>

        <div>
          <label for="subject" class="block mb-1 text-sm font-medium uppercase">Subject</label>
          <input type="text" id="subject" placeholder="Let us know how we can help"
            class="w-full p-3 text-sm bg-transparent border border-gray-400 focus:outline-none focus:border-black dark:border-gray-600 dark:focus:border-white" required>
        </div>

        <div>
          <label for="message" class="block mb-1 text-sm font-medium uppercase"> Message</label>
          <textarea id="message" rows="5" placeholder="Write your message..."
            class="w-full p-3 text-sm bg-transparent border border-gray-400 focus:outline-none focus:border-black dark:border-gray-600 dark:focus:border-white"></textarea>
        </div>

        <button type="submit"
          class="w-full py-3 font-light text-white uppercase transition-color outline-1 hover:bg-gray-800 focus:outline-none focus:ring-2 focus:ring-gray-600">
          Send Message
        </button>
      </form>
    </div>
  </div>
</section>


</template>