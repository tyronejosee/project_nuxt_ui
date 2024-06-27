<template>
  <Navbar />
  <div class="max-w-8xl mx-auto px-4 sm:px-6 md:px-8">
    <!-- <Sidebar /> -->
    <div class="pl-0 lg:pl-[20.5rem] flex flex-col min-h-[650px]">
      <slot />
      <!-- <CategoriesList /> -->
      <Footer />
    </div>
  </div>
</template>
