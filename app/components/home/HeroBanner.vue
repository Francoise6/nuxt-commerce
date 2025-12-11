<template>
  <div class="relative min-h-[600px]">
    <div
      class="md:flex md:flex-row-reverse md:justify-center mx-auto md:min-h-[600px]"
    >
      <div class="flex flex-col md:items-stretch md:overflow-hidden w-full bg-gray-200                  p-2                       border border-gray-300    rounded-xl                shadow-lg">
        <video
          autoplay
          loop
          muted
          playsinline
          height="600"
          width="800"          
          class="h-full object-cover object-center"
        >
          <source src="/hero-video.webm" type="video/webm">
          <source src="/hero-video.mp4" type="video/mp4">
          Your browser does not support the video tag.
        </video> 
      </div>
      <div
        class="md:flex md:flex-col md:justify-center md:items-start md:basis-2/4 text-left"
      >
        <h1 class="text-5xl md:leading-[67.5px] font-bold mt-2 mb-4 text-cyan-500">
          Colorful, Stylish, <span class="text-purple-500"> Unique You</span>
        </h1>
        <p class="text-slate-500">
          Find the perfect partner to your unique style        
        </p>
        <div class="flex flex-row gap-4 mt-6">
          <UButton
            color="warning"
            size="xl"
            to="/collection/latest-stuff"
          >
            All products
          </UButton>

          <UButton
            color="warning"
            variant="outline"
            size="xl"
            to="/about"
          >
            About
          </UButton>
        </div>
      </div>
    </div>
  </div>
</template>