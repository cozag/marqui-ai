<template>
  <div>
    <h1 class="text-center text-6xl pb-4">marq<span class="rainbow-text font-bold">ui</span>.ai</h1>
    <h2 class="text-center text-xl text-slate-600">AI-powered user interface tools for creatives, designers, and developers.</h2>
  </div>
</template>

<script>
export default {
    name: 'HomePage',
}
</script>

<style scoped>
.rainbow-text {
  background: linear-gradient(
    to right,
    #ff6b6b,
    #4ecdc4,
    #45b7d1,
    #96c93d,
    #e056fd
  );
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
  animation: rainbow-wave 8s linear infinite;
  background-size: 500% 100%;
}

@keyframes rainbow-wave {
  0% {
    background-position: 0% 50%;
  }
  50% {
    background-position: 100% 50%;
  }
  100% {
    background-position: 0% 50%;
  }
}
</style>