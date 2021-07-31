<template>
  <div class="footer">
    <div class="container mx-auto pt-10">
      <div class="flex flex-col md:flex-row items-start gap-10 pb-10">
        <div class="flex-1">
          <Logo class="-ml-5 mb-5" />
          <p
            class="text-white mt-3 leading-loose"
          >The world’s first online chess game that pays you in crypto to play</p>
        </div>
        <div class="flex-1 md:mt-10 lg:pl-24">
          <ul class="m-0 p-0 text-white flex flex-col gap-3">
            <li>
              <NuxtLink to="/">Home</NuxtLink>
            </li>
            <li>
              <NuxtLink to="#">Earn Crypto</NuxtLink>
            </li>
            <li>
              <NuxtLink to="#">FAQ</NuxtLink>
            </li>
          </ul>
        </div>
        <div class="flex-1 md:mt-10">
          <ul class="m-0 p-0 text-white flex flex-col gap-3">
            <li>
              <NuxtLink to="#">Sign Up</NuxtLink>
            </li>
            <li>
              <NuxtLink to="#">Login</NuxtLink>
            </li>
            <li>
              <NuxtLink to="#">Contact</NuxtLink>
            </li>
          </ul>
        </div>
        <div class="flex-1 md:mt-10">
          <h3 class="text-white mb-3 font-normal">Socialize with us</h3>
          <ul class="m-0 p-0 flex flex-row gap-3">
            <li>
              <NuxtLink to="#">
                <img src="~/assets/icon/instagram.svg" alt />
              </NuxtLink>
            </li>
            <li>
              <NuxtLink to="#">
                <img src="~/assets/icon/facebook.svg" alt />
              </NuxtLink>
            </li>
            <li>
              <NuxtLink to="#">
                <img src="~/assets/icon/snapchat.svg" alt />
              </NuxtLink>
            </li>
            <li>
              <NuxtLink to="#">
                <img src="~/assets/icon/linkedin.svg" alt />
              </NuxtLink>
            </li>
          </ul>
        </div>
      </div>
      <div class="pt-3 pb-6 text-center">
        <p class="text-white opacity-50">© Copyright Game Explode</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.footer {
  background-color: #3a0c6a;
}
</style>