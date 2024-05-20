<script>
  export let name;
</script>

<div class="col-span-1 w-full hover:scale-110 transition ease-in-out delay-25">
  <div class="shadow-sm rounded-md px-4 pt-6 pb-3 bg-white shadow-slate-700 flex flex-col items-center">
    <img src={"/techstack/" + name + ".svg"} alt={name + " Logo"} class="drop-shadow-lg size-14" />
    <h3 class="text-sm font-bold mt-2">{name}</h3>
  </div>
</div>
