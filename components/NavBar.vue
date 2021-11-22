<template>
  <div class="dark-gradient py-5">
    <div class="container mx-auto">
      <div class="flex flex-col items-center md:flex-row p-0 gap-3">
        <NuxtLink to="/">
          <Logo />
        </NuxtLink>

        <div class="justify-end flex-1 px-2 mx-2 flex">
          <div class="items-center justify-center gap-3 md:mr-10 hidden lg:flex">
            <NuxtLink to="/" class="btn btn-ghost btn-sm w-auto rounded-full text-white">Home</NuxtLink>
            <NuxtLink to="#" class="btn btn-ghost btn-sm w-auto rounded-full text-white">Earn Crypto</NuxtLink>
            <NuxtLink to="#" class="btn btn-ghost btn-sm w-auto rounded-full text-white">FAQ</NuxtLink>
            <NuxtLink
              to="#"
              class="btn btn-ghost btn-sm w-auto rounded-full text-white"
            >Login/Signup</NuxtLink>
          </div>

          <div class="flex-none">
            <NuxtLink
              to="#"
              class="btn font-chakra border-0 shadow-lg font-bold primary-gradient w-44 rounded"
            >Play Now</NuxtLink>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>