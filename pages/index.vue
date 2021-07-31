<template>
  <div>
    <NavBar />

    <div class="cover">
      <div class="container py-24 mx-auto">
        <h1 class="cover-heading text-white text-6xl md:text-9xl">
          PLAY
          <br />CHESS
          <br />EARN
          <br />CRYPTO
        </h1>
      </div>
    </div>

    <div class="second-section bg-offwhite py-16 overflow-hidden">
      <div class="container mx-auto flex flex-col lg:flex-row items-center gap-10">
        <div class="form dark-gradient rounded-xl flex-1 p-10">
          <div class="relative z-10 flex items-center flex-col gap-6">
            <h3 class="text-white text-3xl font-extrabold">Start Playing Now</h3>
            <input class="input w-full" type="text" placeholder="First Name" />
            <input class="input w-full" type="email" placeholder="Email" />
            <input class="input w-full" type="password" placeholder="Password" />
            <input class="input w-full" type="text" placeholder="Username" />
            <label for="agree" class="text-white w-full">
              <input type="checkbox" name="agree" id="agree" /> I accept the terms and privacy policies
            </label>
            <input
              type="submit"
              class="btn text-xl primary-gradient w-full"
              value="register and Play Now"
            />
          </div>
        </div>

        <div class="flex-1 p-10">
          <h3 class="text-3xl text-center text-tertiary font-extrabold">
            Join The Game Played By
            <br />600 Million People Worldwide
          </h3>
          <img class="mx-auto max-w-sm -mb-10" src="~/assets/img/chess-board.png" />
          <h3
            class="text-3xl text-center text-tertiary font-extrabold md:mb-10"
          >And Earn Crypto Just By Playing!</h3>
        </div>
      </div>
    </div>

    <div class="third-section bg-dark relative">
      <div class="max-w-2xl text-white py-20 mx-auto px-5 md:px-0 lg:pl-10 relative z-10">
        <h2 class="text-5xl text-white leading-normal mb-10">Earn Crypto By Playing Online Chess!</h2>
        <ul class="p-0 m-0 flex flex-col gap-8">
          <li class="flex items-center text-3xl gap-8">
            <img src="~/assets/icon/strategy.svg" alt />
            Compete and play chess online
          </li>
          <li class="flex items-center text-3xl gap-8">
            <img src="~/assets/icon/console.svg" alt />
            Blitz games, daily games and more
          </li>
          <li class="flex items-center text-3xl gap-8">
            <img src="~/assets/icon/bitcoin.svg" alt />
            Earn Crypto while you play!
          </li>
        </ul>
      </div>
    </div>

    <div class="fourth-section bg-offwhite">
      <div class="container mx-auto py-16">
        <h2 class="text-4xl text-center mb-10">Online Play, Chess Tournaments & More</h2>
        <div class="flex flex-col lg:flex-row gap-5">
          <div
            class="flex-1 justify-between content bg-white flex items-center flex-col p-5 rounded-lg shadow-lg"
          >
            <img src="~/assets/icon/hand.svg" class="mb-3" alt />
            <h3 class="text-xl text-tertiary mb-3">Online Pay</h3>
            <p
              class="text-center"
            >Play fast or slow. We have lots of different game timer options. Challenge your friends or random opponents</p>
            <div class="divider mb-0"></div>
          </div>
          <div
            class="flex-1 justify-between content-2 text-center flex items-center flex-col p-5 rounded-lg shadow-lg"
          >
            <img style="max-height: 170px;" src="~/assets/icon/chess-badge.svg" alt />
            <h3 class="text-xl text-center text-white">Tournaments coming soon</h3>
          </div>
          <div
            class="flex-1 justify-between content bg-white flex items-center flex-col p-5 rounded-lg shadow-lg"
          >
            <img src="~/assets/icon/bitcoin-color.svg" class="mb-3" alt />
            <h3 class="text-xl text-tertiary mb-3">Earn Crypto</h3>
            <p
              class="text-center"
            >ChessHD is launching a cryptocurrency! The first 1,000 Chess lovers to sign up get premium allocations</p>
            <div class="divider mb-0"></div>
          </div>
          <div
            class="flex-1 justify-between content-4 text-center flex items-start flex-col p-5 rounded-lg shadow-lg relative"
          >
            <h3 class="text-4xl leading-normal text-white ml-5 mt-3">
              Win
              <br />Chess
              <br />NFTs
            </h3>
          </div>
        </div>
      </div>
    </div>

    <div class="fifth-section relative">
      <div class="container mx-auto py-16 relative z-10">
        <h2 class="text-5xl text-white leading-normal mb-10">How To Earn Crypto With ChessHD</h2>
        <div class="flex-col md:flex-row flex items-center gap-10">
          <div class="flex-1">
            <h3 class="text-xl text-white mb-5">How do I earn crypto?</h3>
            <p class="mb-5 text-white">
              You can earn crypto with every game of Chess you play. Simply sign
              up and start playing. You’ll be notified when crypto earning starts
            </p>
            <h3 class="text-xl text-white mb-5">Is it free to sign up?</h3>
            <p class="mb-5 text-white">
              Yes! It’s currently free to sign up and play chess. Every
              user that signs up now will get the chance to earn crypto
            </p>
            <h3 class="text-xl text-white mb-5">What crypto can I earn? Is there an ICO?</h3>
            <p class="mb-5 text-white">
              Yes! We will be launching an ICO, So be among the
              first users to sign up and you’ll get exclusive ICO access
            </p>
          </div>
          <div class="flex-1">
            <img
              style="max-width: 400px;"
              class="mx-auto -mt-10"
              src="~/assets/img/fifth-right-img.svg"
              alt
            />
          </div>
        </div>
      </div>
    </div>

    <div class="cta dark-gradient">
      <div class="container mx-auto py-16">
        <div class="flex flex-col xl:flex-row items-center justify-between gap-10">
          <div class="content">
            <h2 class="text-4xl text-white">FIRST 1,000 USERS GET BONUS CRYTPO!</h2>
          </div>
          <div class="content">
            <NuxtLink
              to="#"
              class="btn border-0 font-chakra font-bold primary-gradient px-8 text-2xl rounded"
            >SIGN UP & Play Now!</NuxtLink>
          </div>
        </div>
      </div>
    </div>

    <Footer />
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.cover {
  background: url("~/assets/img/cover-bg.png") no-repeat top -20px center/cover;
}
.cover-heading {
  background: linear-gradient(
    255.14deg,
    #00dff5 8.37%,
    rgba(0, 98, 245, 0.56) 94.18%
  );
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-stroke: 4px transparent;
  color: white;
}

.second-section {
  background: url(~/assets/img/second-section-bg.svg) no-repeat bottom 10px
    center / 70%;
}
.form {
  position: relative;
  box-shadow: 10px 10px 40px 0px #000000b2;
}
.form:after {
  content: "";
  display: block;
  position: absolute;
  background: linear-gradient(
    269.61deg,
    rgba(104, 137, 253, 0.4) 29.02%,
    rgba(104, 199, 253, 0) 106.46%
  );
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  border-radius: 0.5rem;
}

.input {
  background: linear-gradient(
    102.12deg,
    rgba(255, 255, 255, 0.6) 4.34%,
    rgba(255, 255, 255, 0) 135.14%
  );
  border-radius: 5px;
  color: white;
  border: 0;
}
.input::placeholder {
  color: rgba(255, 255, 255, 0.9);
}

@media (min-width: 1024px) {
  .third-section:after,
  .third-section:before {
    content: "";
    width: 100%;
    height: 100%;
    position: absolute;
    top: 0;
    left: 0;
    display: block;
    background: url(~/assets/img/purple-chess-board.svg) no-repeat left
      center/contain;
  }
  .third-section:before {
    height: calc(100% - 60px);
    top: 20px;
  }
  .third-section:after {
    background: url(~/assets/img/homepage-hero-sm-chess.svg) no-repeat right
      center/contain;
    top: 30px;
    height: calc(100% - 30px);
  }
}

.divider {
  width: 74px;
  height: 4px;
  border-radius: 10px;
  background: linear-gradient(
    165.81deg,
    #7c00d9 48.55%,
    #4600b1 77.52%,
    #141778 99.8%
  );
}
.fourth-section .content-2,
.fourth-section .content-4 {
  background: linear-gradient(
    192.35deg,
    #7c00d9 21.06%,
    #4600b1 85.6%,
    #141778 135.22%
  );
}
.fourth-section .content-4:after {
  content: "";
  width: 100%;
  height: 100%;
  display: block;
  position: absolute;
  background: url(~/assets/icon/chess-winner.svg) no-repeat center/125%;
  top: 0;
  left: 0;
}

.fifth-section {
  background: #080027;
}
.fifth-section:after {
  content: "";
  width: 100%;
  height: 100%;
  display: block;
  position: absolute;
  background: url(~/assets/img/fifth-bg.svg) no-repeat bottom center/contain;
  top: 0;
  left: 0;
}
</style>
