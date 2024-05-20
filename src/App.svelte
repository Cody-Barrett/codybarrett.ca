<script>
  import Project from "./lib/Project.svelte";
  import SVGCard from "./lib/SVGCard.svelte";
</script>

<main class="font-mono">
  <header class="z-10 sticky top-0 bg-white shadow-md px-8 py-02 border-b-black border-b">
    <div class="max-w-screen-xl mx-auto flex items-center justify-between py-2">
      <!-- Name -->
      <h1 class="font-bold text-2xl md:text-4xl drop-shadow-sm">Cody Barrett</h1>
      <!-- Links -->
      <ul class="flex space-x-1">
        <a href="https://github.com/Cody-Barrett">
          <img src="/social_icons/github.svg" alt="Github Logo" class="hover:scale-125 transition ease-in-out delay-75 drop-shadow-lg md:size-12 size-9" />
        </a>
        <a href="https://www.linkedin.com/in/cody-barrett-58657830a">
          <img src="/social_icons/linkedin.svg" alt="Linkedin Logo" class="hover:scale-125 transition ease-in-out delay-75 ml-0.5 mr-1 drop-shadow-md md:size-12 size-9" />
        </a>
        <a href="https://x.com/CodyBarrettS">
          <img src="/social_icons/twitter.svg" alt="Twitter Logo" class="hover:scale-125 transition ease-in-out delay-75 drop-shadow-lg md:size-12 size-9" />
        </a>
      </ul>
    </div>
  </header>
  <body>
    <div class="bg-gradient-to-tr from-[#CEFCBA] via-sky-500 to-fuchsia-600 text-white h-full p-16">
      <div class="text-center">
        <h2 class="text-3xl font-bold drop-shadow-lg">
          Hi, I'm <span class="underline decoration-white underline-offset-4">Cody</span>.
        </h2>
        <p class="text-lg drop-shadow-md pt-2">I'm an IT Specialist with expertise in Software Development, Network/System Administration, and Cybersecurity.</p>
      </div>
      <div class="pt-12 max-w-max mx-auto grid xl:grid-cols-7 lg:grid-cols-6 md:grid-cols-5 sm:grid-cols-3 grid-cols-2 text-black gap-4">
        <SVGCard name="Python"></SVGCard>
        <SVGCard name="C++"></SVGCard>
        <SVGCard name="NodeJS"></SVGCard>
        <SVGCard name="Selenium"></SVGCard>
        <SVGCard name="FastAPI"></SVGCard>
        <SVGCard name="PostgreSQL"></SVGCard>
        <SVGCard name="MongoDB"></SVGCard>
        <SVGCard name="Redis"></SVGCard>
        <SVGCard name="Git"></SVGCard>
        <SVGCard name="TailwindCSS"></SVGCard>
        <SVGCard name="Vite"></SVGCard>
        <SVGCard name="Svelte"></SVGCard>
        <SVGCard name="Linux"></SVGCard>
        <SVGCard name="Office"></SVGCard>
      </div>
    </div>
    <h2 class="pt-12 text-3xl font-bold drop-shadow-lg text-center">
      <span class="underline underline-offset-4 decoration-4">Projects</span>.
    </h2>
    <div class="container py-12 grid mx-auto grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4 px-10">
      <Project thumbnail="Site Preview.png" header="https://codybarrett.ca" description="My personal portfolio site made with TailwindCSS, Vite, and Svelte. Built and deployed using GitHub Actions." link="https://github.com/Cody-Barrett/codybarrett.ca" link_text="View On GitHub"></Project>
    </div>
  </body>
</main>
