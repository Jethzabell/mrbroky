<script>

  let instagram = "https://www.instagram.com/mrbroky/";
  let payPal = "https://www.paypal.me/mrbroky";
  let youtube = "https://www.youtube.com/mrbroky";
  let twitch = "https://www.twitch.tv/mrbroky";
  let twitter = "https://www.twitter.com/Mr_Broky";
  let tiktok = "https://www.tiktok.com/@mrbroky";
  let facebook = "https://www.instagram.com/mrbroky";
  // let youtubeClip1 = "https://www.youtube.com/embed/PVJs596rp2o?start=335"
  let tooltipTwitch = "Rocket League, Minecraft, Phasmophobia, and more."
  let tooltipYoutube = "Videos, Hightlights, Shorts and Vlogs(coming soon)"
  let tooltipInstagram = "Posts, Clips, Reactions, Stories and Direct Message(DM)"
  let email = "mrbrokygames@gmail.com";
  let description = "Just a guy with a dream."
  let logo1 = "/logo1.png"
  let logo2 = "/logo2.png"
  let logo3 = "/logo3.png"
</script>

<main>
  <!-- <div class="bg-gradient-to-r from-cyan-500 to-blue-500 ..."> -->
  <div class="flex flex-col h-screen">
    <div class="flex-grow pt-4">
      <div class="tooltip tooltip-bottom">
        <div class="avatar">
          <div class="w-24 rounded-full">
            <img src={logo1} alt="mrbroky" />
          </div>
          <div class="w-24 rounded-full">
            <img src={logo2} alt="mrbroky" />
          </div>
          <div class="w-24 rounded-full">
            <img src={logo3} alt="mrbroky" />
          </div>
        </div>
      </div>

      <div class="intro">
        <p> {description} </p>
      </div>
 

      
      <div class="grid gap-4 grid-cols-1">
        <div  class="tooltip" data-tip={tooltipTwitch}>
          <a href={twitch}><button class="btn btn-block">twitch</button></a>
        </div>
        <div class="tooltip" data-tip={tooltipYoutube}>
          <a href={youtube}><button class="btn btn-block">youtube</button></a>
        </div>
        <div  class="tooltip" data-tip={tooltipInstagram}>
          <a href={instagram}><button class="btn btn-block">Instagram</button></a>
        </div>
        <div>
          <a href={facebook}><button class="btn btn-block">facebook</button></a>
        </div>
        <div>
          <a href={tiktok}><button class="btn btn-block">tiktok</button></a>
        </div>
        <div>
          <a href={twitter}><button class="btn btn-block">twitter</button></a>
        </div>
        <div class="tooltip" data-tip={email}>
          <a type="email" href="mailto:{email}"><button class="btn btn-block">Email</button></a>
        </div>       
      </div>

      <div class="flex payments pt-4">
        <p>Donations:</p>
      </div>
      <div class="flex">
        <a href={payPal}>
          <svg
            class="h-8 w-8 text-blue-500"
            width="24"
            height="24"
            viewBox="0 0 24 24"
            stroke-width="2"
            stroke="currentColor"
            fill="none"
            stroke-linecap="round"
            stroke-linejoin="round"
          >
            <path stroke="none" d="M0 0h24v24H0z" />
            <path
              d="M10 13l2.538-.003c2.46 0 4.962-2.497 4.962-4.997 0-3-1.89-5-4.962-5H7c-.5 0-1 .5-1 1L4 18c0 .5.5 1 1 1h2.846L9 14c.089-.564.43-1 1-1zm7.467-5.837C19.204 8.153 20 10 20 12c0 2.467-2.54 4.505-5 4.505h.021-2.629l-.576 3.65a.998.998 0 01-.988.844l-2.712-.002a.5.5 0 01-.494-.578L7.846 19"
            /></svg
          >
        </a>
      </div>
    </div>
    <footer>
      <div class="items-center grid-flow-col pt-4 text-gray-400">
        <p>
          © 2022 <a
            class="link"
            href="https://jethzabell.com"
            >Jethzabell Medina</a
          > - All right reserved
        </p>
      </div>
    </footer>
  </div>
</main>

<style>
  :root {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen,
      Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
  }

  main {
    text-align: center;
    padding-left: 2em;
    padding-right: 2em;
    margin: 0 auto;
  }
  .intro {
    text-align: center;
    padding-bottom: 1.5rem;
    margin: 0 auto;
    font-size: 18px;
  }

  .payments {
    text-align: center;
    margin: 0 auto;
    font-size: 18px;
  }
</style>
