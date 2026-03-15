<script>
  const links = [
    {
      name: "Twitch",
      url: "https://www.twitch.tv/mrbroky",
      tooltip: "Rocket League, Minecraft, Phasmophobia, and more.",
      color: "#9146ff",
      icon: `<path d="M11.571 4.714h1.715v5.143H11.57zm4.715 0H18v5.143h-1.714zM6 0L1.714 4.286v15.428h5.143V24l4.286-4.286h3.428L22.286 12V0zm14.571 11.143l-3.428 3.428h-3.429l-3 3v-3H6.857V1.714h13.714Z"/>`,
    },
    {
      name: "YouTube",
      url: "https://www.youtube.com/mrbroky",
      tooltip: "Videos, Highlights, Shorts and Vlogs",
      color: "#ff0000",
      icon: `<path d="M23.498 6.186a3.016 3.016 0 0 0-2.122-2.136C19.505 3.545 12 3.545 12 3.545s-7.505 0-9.377.505A3.017 3.017 0 0 0 .502 6.186C0 8.07 0 12 0 12s0 3.93.502 5.814a3.016 3.016 0 0 0 2.122 2.136c1.871.505 9.376.505 9.376.505s7.505 0 9.377-.505a3.015 3.015 0 0 0 2.122-2.136C24 15.93 24 12 24 12s0-3.93-.502-5.814zM9.545 15.568V8.432L15.818 12z"/>`,
    },
    {
      name: "Instagram",
      url: "https://www.instagram.com/mrbroky/",
      tooltip: "Posts, Clips, Reactions, Stories and DMs",
      color: "#e4405f",
      icon: `<path d="M12 0C8.74 0 8.333.015 7.053.072 5.775.132 4.905.333 4.14.63c-.789.306-1.459.717-2.126 1.384S.935 3.35.63 4.14C.333 4.905.131 5.775.072 7.053.012 8.333 0 8.74 0 12s.015 3.667.072 4.947c.06 1.277.261 2.148.558 2.913.306.788.717 1.459 1.384 2.126.667.666 1.336 1.079 2.126 1.384.766.296 1.636.499 2.913.558C8.333 23.988 8.74 24 12 24s3.667-.015 4.947-.072c1.277-.06 2.148-.262 2.913-.558.788-.306 1.459-.718 2.126-1.384.666-.667 1.079-1.335 1.384-2.126.296-.765.499-1.636.558-2.913.06-1.28.072-1.687.072-4.947s-.015-3.667-.072-4.947c-.06-1.277-.262-2.149-.558-2.913-.306-.789-.718-1.459-1.384-2.126C21.319 1.347 20.651.935 19.86.63c-.765-.297-1.636-.499-2.913-.558C15.667.012 15.26 0 12 0zm0 2.16c3.203 0 3.585.016 4.85.071 1.17.055 1.805.249 2.227.415.562.217.96.477 1.382.896.419.42.679.819.896 1.381.164.422.36 1.057.413 2.227.057 1.266.07 1.646.07 4.85s-.015 3.585-.074 4.85c-.061 1.17-.256 1.805-.421 2.227-.224.562-.479.96-.899 1.382-.419.419-.824.679-1.38.896-.42.164-1.065.36-2.235.413-1.274.057-1.649.07-4.859.07-3.211 0-3.586-.015-4.859-.074-1.171-.061-1.816-.256-2.236-.421-.569-.224-.96-.479-1.379-.899-.421-.419-.69-.824-.9-1.38-.165-.42-.359-1.065-.42-2.235-.045-1.26-.061-1.649-.061-4.844 0-3.196.016-3.586.061-4.861.061-1.17.255-1.814.42-2.234.21-.57.479-.96.9-1.381.419-.419.81-.689 1.379-.898.42-.166 1.051-.361 2.221-.421 1.275-.045 1.65-.06 4.859-.06l.045.03zm0 3.678a6.162 6.162 0 1 0 0 12.324 6.162 6.162 0 1 0 0-12.324zM12 16c-2.21 0-4-1.79-4-4s1.79-4 4-4 4 1.79 4 4-1.79 4-4 4zm7.846-10.405a1.441 1.441 0 1 1-2.88 0 1.441 1.441 0 0 1 2.88 0z"/>`,
    },
    {
      name: "Facebook",
      url: "https://www.facebook.com/mrbroky",
      color: "#1877f2",
      icon: `<path d="M24 12.073c0-6.627-5.373-12-12-12s-12 5.373-12 12c0 5.99 4.388 10.954 10.125 11.854v-8.385H7.078v-3.47h3.047V9.43c0-3.007 1.792-4.669 4.533-4.669 1.312 0 2.686.235 2.686.235v2.953H15.83c-1.491 0-1.956.925-1.956 1.874v2.25h3.328l-.532 3.47h-2.796v8.385C19.612 23.027 24 18.062 24 12.073z"/>`,
    },
    {
      name: "TikTok",
      url: "https://www.tiktok.com/@mrbroky",
      color: "#00f2ea",
      icon: `<path d="M12.525.02c1.31-.02 2.61-.01 3.91-.02.08 1.53.63 3.09 1.75 4.17 1.12 1.11 2.7 1.62 4.24 1.79v4.03c-1.44-.05-2.89-.35-4.2-.97-.57-.26-1.1-.59-1.62-.93-.01 2.92.01 5.84-.02 8.75-.08 1.4-.54 2.79-1.35 3.94-1.31 1.92-3.58 3.17-5.91 3.21-1.43.08-2.86-.31-4.08-1.03-2.02-1.19-3.44-3.37-3.65-5.71-.02-.5-.03-1-.01-1.49.18-1.9 1.12-3.72 2.58-4.96 1.66-1.44 3.98-2.13 6.15-1.72.02 1.48-.04 2.96-.04 4.44-.99-.32-2.15-.23-3.02.37-.63.41-1.11 1.04-1.36 1.75-.21.51-.15 1.07-.14 1.61.24 1.64 1.82 3.02 3.5 2.87 1.12-.01 2.19-.66 2.77-1.61.19-.33.4-.67.41-1.06.1-1.79.06-3.57.07-5.36.01-4.03-.01-8.05.02-12.07z"/>`,
    },
    {
      name: "X / Twitter",
      url: "https://www.twitter.com/Mr_Broky",
      color: "#ffffff",
      icon: `<path d="M18.901 1.153h3.68l-8.04 9.19L24 22.846h-7.406l-5.8-7.584-6.638 7.584H.474l8.6-9.83L0 1.154h7.594l5.243 6.932ZM17.61 20.644h2.039L6.486 3.24H4.298Z"/>`,
    },
    {
      name: "Email",
      url: "mailto:mrbrokygames@gmail.com",
      tooltip: "mrbrokygames@gmail.com",
      color: "#34d399",
      icon: `<path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5" d="M21.75 6.75v10.5a2.25 2.25 0 0 1-2.25 2.25h-15a2.25 2.25 0 0 1-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0 0 19.5 4.5h-15a2.25 2.25 0 0 0-2.25 2.25m19.5 0v.243a2.25 2.25 0 0 1-1.07 1.916l-7.5 4.615a2.25 2.25 0 0 1-2.36 0L3.32 8.91a2.25 2.25 0 0 1-1.07-1.916V6.75"/>`,
    },
  ];

  const paypal = "https://www.paypal.me/mrbroky";
  const currentYear = new Date().getFullYear();
</script>

<div class="gradient-bg">
  <div class="min-h-screen flex flex-col items-center justify-center px-4 py-6">
    <div class="glass-card w-full max-w-md px-5 py-5 flex flex-col items-center gap-3 fade-in">

      <!-- Avatar + Name -->
      <div class="flex flex-col items-center gap-2">
        <div class="avatar-glow">
          <div class="w-16 h-16 rounded-full overflow-hidden ring-2 ring-white/20">
            <img src={`${import.meta.env.BASE_URL}broki.png`} alt="Mr Broky" class="w-full h-full object-cover" />
          </div>
        </div>
        <div class="text-center">
          <h1 class="text-xl font-bold gradient-text leading-tight">Mr Broky</h1>
          <p class="text-white/50 text-xs tracking-wide">Just a guy with a dream.</p>
        </div>
      </div>

      <!-- Social Links -->
      <div class="w-full flex flex-col gap-2">
        {#each links as link, i}
          <a
            href={link.url}
            target="_blank"
            rel="noopener noreferrer"
            class="social-link"
            style="--brand: {link.color}; animation-delay: {i * 80}ms"
            title={link.tooltip || link.name}
          >
            <svg
              class="w-5 h-5 shrink-0"
              viewBox="0 0 24 24"
              fill={link.name === 'Email' ? 'none' : 'currentColor'}
              stroke={link.name === 'Email' ? 'currentColor' : 'none'}
              xmlns="http://www.w3.org/2000/svg"
            >
              {@html link.icon}
            </svg>
            <span>{link.name}</span>
          </a>
        {/each}
      </div>

      <!-- Support -->
      <div class="w-full pt-2 border-t border-white/10">
        <p class="text-white/40 text-[10px] uppercase tracking-widest mb-2 text-center">Support</p>
        <div class="flex flex-col gap-2">
          <a
            href={paypal}
            target="_blank"
            rel="noopener noreferrer"
            class="social-link"
            style="--brand: #0070ba"
          >
            <svg class="w-5 h-5 shrink-0" viewBox="0 0 24 24" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
              <path d="M7.076 21.337H2.47a.641.641 0 0 1-.633-.74L4.944.901C5.026.382 5.474 0 5.998 0h7.46c2.57 0 4.578.543 5.69 1.81 1.01 1.15 1.304 2.42 1.012 4.287-.023.143-.047.288-.077.437-.983 5.05-4.349 6.797-8.647 6.797h-2.19c-.524 0-.968.382-1.05.9l-1.12 7.106zm14.146-14.42a3.35 3.35 0 0 0-.607-.541c-.013.076-.026.175-.041.254-.93 4.778-4.005 7.201-9.138 7.201h-2.19a.563.563 0 0 0-.556.479l-1.187 7.527h-.506l-.24 1.516a.56.56 0 0 0 .554.647h3.882c.46 0 .85-.334.922-.788.06-.26.76-4.852.816-5.09a.932.932 0 0 1 .923-.788h.58c3.76 0 6.705-1.528 7.565-5.946.36-1.847.174-3.388-.777-4.471z"/>
            </svg>
            <span>PayPal</span>
          </a>
          <a
            href="https://www.epicgames.com/id/login?redirectUrl=https://store.epicgames.com/en-US/redeem-creator?code=mrBroky"
            target="_blank"
            rel="noopener noreferrer"
            class="social-link"
            style="--brand: #a3a3a3"
          >
            <svg class="w-5 h-5 shrink-0" viewBox="0 0 256 256" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
              <path d="M49.8 0C24 0 14.4 9.4 14.4 35v186c0 25.6 9.6 35 35.4 35h156.4c25.8 0 35.4-9.4 35.4-35V35c0-25.6-9.6-35-35.4-35ZM96 56h64v24h-40v28h36v24h-36v32h40v24H96Z"/>
            </svg>
            <span>Epic Games (<span class="epic-code">mrBroky</span>)</span>
          </a>
        </div>
      </div>

      <!-- Footer -->
      <footer class="pt-2 text-center flex flex-col gap-0.5">
        <p class="text-white/30 text-xs">
          &copy; {currentYear} MrBroky &mdash; All rights reserved
        </p>
        <p class="text-white/20 text-[10px]">
          Made with &hearts; by
          <a href="https://jethzabell.com" class="hover:text-white/40 transition-colors">Jethzabell Medina</a>
        </p>
      </footer>
    </div>
  </div>
</div>

<style>
  /* Animated gradient background */
  .gradient-bg {
    min-height: 100vh;
    background: linear-gradient(-45deg, #0f0c29, #302b63, #24243e, #1a1a2e, #16213e, #0f3460);
    background-size: 400% 400%;
    animation: gradientShift 15s ease infinite;
  }

  @keyframes gradientShift {
    0% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
  }

  /* Glassmorphism card */
  .glass-card {
    background: rgba(255, 255, 255, 0.05);
    backdrop-filter: blur(20px);
    -webkit-backdrop-filter: blur(20px);
    border: 1px solid rgba(255, 255, 255, 0.08);
    border-radius: 1.5rem;
    box-shadow: 0 8px 32px rgba(0, 0, 0, 0.3);
  }

  /* Fade-in entrance */
  .fade-in {
    animation: fadeInUp 0.6s ease-out both;
  }

  @keyframes fadeInUp {
    from {
      opacity: 0;
      transform: translateY(24px);
    }
    to {
      opacity: 1;
      transform: translateY(0);
    }
  }

  /* Avatar glow ring */
  .avatar-glow {
    position: relative;
    border-radius: 9999px;
    padding: 3px;
    background: linear-gradient(135deg, #667eea, #764ba2, #f093fb);
    background-size: 200% 200%;
    animation: glowRotate 4s ease infinite;
  }

  .avatar-glow::after {
    content: '';
    position: absolute;
    inset: -6px;
    border-radius: 9999px;
    background: linear-gradient(135deg, #667eea, #764ba2, #f093fb);
    background-size: 200% 200%;
    animation: glowRotate 4s ease infinite;
    filter: blur(14px);
    opacity: 0.4;
    z-index: -1;
  }

  @keyframes glowRotate {
    0% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
  }

  /* Gradient text */
  .gradient-text {
    background: linear-gradient(135deg, #e0e7ff, #c4b5fd, #f9a8d4);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-clip: text;
  }

  /* Social link buttons */
  .social-link {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 0.6rem;
    width: 100%;
    padding: 0.6rem 1rem;
    border-radius: 0.6rem;
    background: rgba(255, 255, 255, 0.06);
    border: 1px solid rgba(255, 255, 255, 0.08);
    color: rgba(255, 255, 255, 0.85);
    font-weight: 500;
    font-size: 0.875rem;
    letter-spacing: 0.02em;
    text-decoration: none;
    transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
    animation: slideIn 0.5s ease-out both;
  }

  .epic-code {
    color: #facc15;
    font-weight: 600;
  }

  .social-link:hover {
    background: rgba(255, 255, 255, 0.12);
    border-color: var(--brand, rgba(255, 255, 255, 0.2));
    color: var(--brand, #fff);
    transform: translateY(-2px);
    box-shadow: 0 4px 20px color-mix(in srgb, var(--brand, #fff) 25%, transparent);
  }

  @keyframes slideIn {
    from {
      opacity: 0;
      transform: translateX(-16px);
    }
    to {
      opacity: 1;
      transform: translateX(0);
    }
  }
</style>
