<template>
  <main class="container mx-auto px-4 mt-28 md:mt-20 h-screen">
    <h1
      class="text-4xl mb-6 tracking-tight font-extrabold text-gray-900 sm:text-5xl md:text-6xl"
    >
      Videos
    </h1>

    <div class="prose">
      <h2>Treadmill Mission</h2>
      <h5>Our first completion of the Treadmill Mission!</h5>
      <iframe
        width="560"
        height="315"
        src="https://www.youtube.com/embed/MzFvb-Wradk"
        frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen
      >
      </iframe>
    </div>
  </main>
</template>
<script>
export default {
  head() {
    return {
      title: `Videos - Exploding Bricks`
    };
  }
};
</script>
