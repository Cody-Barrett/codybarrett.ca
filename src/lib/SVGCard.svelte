<script>
  export let name;
</script>

<div class="w-full col-span-1 transition ease-in-out sm:hover:scale-105 delay-25">
  <div class="flex flex-col items-center px-1 pt-6 pb-3 bg-white rounded-md shadow-sm shadow-slate-700">
    <img src={"/techstack/" + name + ".svg"} alt={name + " Logo"} class="drop-shadow-lg md:size-14 size-9" />
    <h3 class="mt-2 text-xs font-bold text-nowrap sm:text-sm">{name}</h3>
  </div>
</div>
