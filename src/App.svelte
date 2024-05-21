<script>
  import Project from "./lib/Project.svelte";
  import SVGCard from "./lib/SVGCard.svelte";
</script>

<main class="font-mono">
  <header class="sticky top-0 z-10 px-8 bg-white border-b shadow-md py-02 border-b-black">
    <div class="flex items-center justify-between max-w-screen-xl py-2 mx-auto">
      <!-- Name -->
      <h1 class="text-2xl font-bold md:text-4xl drop-shadow-sm">Cody Barrett</h1>
      <!-- Links -->
      <ul class="flex space-x-1">
        <a href="https://github.com/Cody-Barrett">
          <img src="/social_icons/github.svg" alt="Github Logo" class="transition ease-in-out delay-75 hover:scale-125 drop-shadow-lg md:size-12 size-9" />
        </a>
        <a href="https://www.linkedin.com/in/cody-barrett-58657830a">
          <img src="/social_icons/linkedin.svg" alt="Linkedin Logo" class="hover:scale-125 transition ease-in-out delay-75 ml-0.5 mr-1 drop-shadow-md md:size-12 size-9" />
        </a>
        <a href="https://x.com/CodyBarrettS">
          <img src="/social_icons/twitter.svg" alt="Twitter Logo" class="transition ease-in-out delay-75 hover:scale-125 drop-shadow-lg md:size-12 size-9" />
        </a>
      </ul>
    </div>
  </header>
  <body>
    <div class="bg-gradient-to-tr from-[#CEFCBA] via-sky-500 to-fuchsia-600 text-white h-full py-16">
      <div class="text-center">
        <h2 class="text-3xl font-bold drop-shadow-lg">
          Hi, I'm <span class="underline decoration-white underline-offset-4">Cody</span>.
        </h2>
        <p class="px-10 pt-2 text-lg drop-shadow-md text-balance">I'm an IT Specialist with expertise in Software Development, Network/System Administration, and Cybersecurity.</p>
      </div>
      <div class="pt-12 px-2 max-w-max mx-auto grid xl:grid-cols-7 lg:grid-cols-6 md:grid-cols-5 sm:grid-cols-4 min-[320px]:grid-cols-3 grid-cols-2 text-black gap-2">
        <SVGCard name="Python"></SVGCard>
        <SVGCard name="C++"></SVGCard>
        <SVGCard name="NodeJS"></SVGCard>
        <SVGCard name="Selenium"></SVGCard>
        <SVGCard name="FastAPI"></SVGCard>
        <SVGCard name="PostgreSQL"></SVGCard>
        <SVGCard name="MongoDB"></SVGCard>
        <SVGCard name="Redis"></SVGCard>
        <SVGCard name="Linux"></SVGCard>
        <SVGCard name="AWS"></SVGCard>
        <SVGCard name="Docker"></SVGCard>
        <SVGCard name="Git"></SVGCard>
        <SVGCard name="Github Actions"></SVGCard>
        <SVGCard name="TailwindCSS"></SVGCard>
        <SVGCard name="Svelte"></SVGCard>
        <SVGCard name="Vite"></SVGCard>
        <SVGCard name="Office"></SVGCard>
      </div>
    </div>
    <h2 class="pt-12 text-3xl font-bold text-center drop-shadow-lg">
      <span class="underline underline-offset-4 decoration-4">Projects</span>.
    </h2>
    <div class="container grid grid-cols-1 gap-4 px-10 py-12 mx-auto place-items-center md:grid-cols-2 lg:grid-cols-3">
      <Project thumbnail="Site Preview.png" header="https://codybarrett.ca" description="My personal portfolio site made with TailwindCSS, Vite, and Svelte. Built and deployed using GitHub Actions." link="https://github.com/Cody-Barrett/codybarrett.ca" link_text="View On GitHub"></Project>
      <Project thumbnail="LoremIpsum.png" header="Lorem Ipsum" description="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut lacinia tincidunt libero non tempus. Nunc viverra rhoncus diam nec laoreet. Aliquam urna orci, eleifend nec metus nec, ullamcorper molestie purus." link="https://codybarrett.ca" link_text="Lorem ipsum"></Project>
      <Project thumbnail="LoremIpsum.png" header="Lorem Ipsum" description="Lorem ipsum dolor sit amet, consectetur adipiscing elit. Praesent porta varius congue. Nullam id dui ullamcorper massa placerat egestas." link="https://codybarrett.ca" link_text="Lorem ipsum"></Project>
    </div>
  </body>
  <footer class="flex flex-col items-center justify-center w-full py-12 space-y-10 bg-[#002244] md:flex-row md:justify-around md:space-y-0 md:space-x-2">
    <div class="flex items-center space-x-2">
      <img src="Email Icon.svg" alt="Mail Icon" class="md:size-14 size-9" />
      <h1 class="text-[#C0C0C0] text-lg sm:text-xl lg:text-2xl">contact@codybarrett.ca</h1>
    </div>
    <div class="flex items-center space-x-2">
      <img src="Phone.svg" alt="Mail Icon" class="md:size-14 size-9" />
      <h1 class="text-[#C0C0C0] sm:text-xl lg:text-2xl text-lg">902-218-9383</h1>
    </div>
  </footer>
</main>
