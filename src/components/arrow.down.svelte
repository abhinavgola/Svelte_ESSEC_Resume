<script lang='ts'>
  export let href: string;
</script>
<div class='absolute right-0 left-0 bottom-20 fadeInDown'>
  <a href={`#${href}`}> 
    <i class=" text-gray-300 fas fa-arrow-circle-down text-5xl animate-bounce cursor-pointer hover:text-green-500 transition-colors" />
  </a>
</div>