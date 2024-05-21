<script>
  export let thumbnail;
  export let header;
  export let description;
  export let link;
  export let link_text;
</script>

<div class="w-full h-full max-w-lg col-span-1 p-3 mx-auto transition duration-500 bg-white border rounded-xl drop-shadow-lg sm:hover:drop-shadow-2xl sm:hover:border-black">
  <img class="object-cover object-center w-full h-40 mx-auto border rounded-xl border-slate-300" src={thumbnail} alt="Project Thumbnail" />
  <div class="px-2 pt-4 h-36">
    <div class="mb-2 text-sm font-bold md:text-xl sm:text-md">{header}</div>
    <p class="overflow-hidden text-sm text-gray-700 text-ellipsis line-clamp-4 sm:text-md">{description}</p>
  </div>
  <a href={link} class="block m-auto">
    <div class="p-4 text-center text-blue-500 transition duration-500 bg-gray-100 border-black drop-shadow-sm rounded-xl sm:hover:text-blue-900 sm:hover:bg-slate-200 md:hover:shadow-inner">
      <span class="inline-flex items-center">{link_text}</span>
    </div>
  </a>
</div>
