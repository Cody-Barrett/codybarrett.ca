<script>
  export let thumbnail;
  export let header;
  export let description;
  export let link;
  export let link_text;
</script>

<div class="col-span-1 mx-auto max-w-lg rounded-xl w-full drop-shadow-lg hover:drop-shadow-2xl transition duration-500 bg-white border hover:border-black p-3">
  <img class="mx-auto w-full h-40 rounded-xl object-center object-cover border border-slate-300" src={thumbnail} alt="Project Thumbnail" />
  <div class="px-2 py-4">
    <div class="font-bold md:text-xl sm:text-md text-sm mb-2">{header}</div>
    <p class="text-gray-700 sm:text-md text-sm">{description}</p>
  </div>
  <a href={link} class="block">
    <div class="p-4 drop-shadow-sm bg-gray-100 text-center rounded-xl text-blue-500 hover:text-blue-900 hover:bg-slate-200 transition duration-500 hover:shadow-inner border-black">
      <span class="inline-flex items-center">{link_text}</span>
    </div>
  </a>
</div>
