<script setup>
</script>

<template>
  <main class="flex flex-col lg:flex-row items-center justify-center w-full sm:w-1/2 lg:w-2/3">
    <div class="bg-[#013243] flex flex-col items-center justify-between w-full sm:w-11/12 h-full text-white rounded sm:rounded-none lg:rounded-l-lg">
      <div class="py-11">
        <h1 class="text-4xl font-bold text-center">Gradie</h1>
        <p class=" text-[#86bfd3]">Beautiful gradients in seconds</p>
      </div>
      <div>
        <img src="./assets/iPhone Mockup.png" alt="">
      </div>
    </div>
    <div class="flex flex-col justify-center p-14 bg-white border border-gray-400 rounded sm:rounded-t-none lg:rounded-l-none lg:rounded-r-lg w-full sm:w-11/12 h-full">
      <p class="text-4xl font-bold mb-5">Login</p>
      <div class="input-container mb-5">
        <label for="email">Email</label>
        <input type="text" placeholder="john@example.com">
      </div>
      <div class="input-container mb-5">
        <label for="password">Password</label>
        <input type="password" placeholder="At least 8 characters">
      </div>
      <div class="flex items-start gap-2 mb-5">
        <input type="checkbox" name="terms">
        <p class="text-lg max-w-[25ch] lg:max-w-sm">By creating an account, you agree to the <a href="#"
            class="text-[#013243] font-extrabold underline decoration-[#013243] decoration-2">Terms & Conditions.</a></p>
      </div>
      <button class="bg-[#013243] text-white h-16 rounded-md w-full">Create an Account</button>
    </div>
  </main>
</template>

<style lang="postcss">
:root {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  font-family: Inter, Avenir, Helvetica, Arial, sans-serif;
  font-size: 14px;
}

html,
body {
  height: 100%;
}

#app {
  @apply flex flex-col justify-center items-center h-full bg-cover;
  background-image: url(assets/Background.png);
}

.input-container {
  @apply flex flex-col gap-1;
}

label {
  @apply font-semibold;
}

input {
  @apply border border-zinc-300 rounded-lg p-4;
}
</style>
