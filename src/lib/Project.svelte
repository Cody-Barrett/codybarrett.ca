<script>
  export let thumbnail;
  export let header;
  export let description;
  export let link;
  export let link_text;
</script>

<div class="col-span-1 mx-auto max-w-sm rounded-xl w-full drop-shadow-lg hover:drop-shadow-2xl transition duration-500 bg-white border p-3">
  <img class="w-full h-40 object-cover rounded-xl p-1" src={thumbnail} alt="Project Thumbnail" />
  <div class="px-2 py-4 min-h-max">
    <div class="font-bold md:text-xl text-md mb-2">{header}</div>
    <p class="text-gray-700 text-md">{description}</p>
  </div>
  <a href={link} class="block">
    <div class="p-4 mx-1 drop-shadow-sm bg-gray-100 text-center rounded-xl text-blue-500 hover:text-blue-900 hover:bg-slate-200 transition duration-500 hover:shadow-inner border-black">
      <span class="inline-flex items-center">{link_text}</span>
    </div>
  </a>
</div>
