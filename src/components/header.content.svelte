
<script lang='ts'>
  export let title: string;
  export let description: string;
</script>
<div class=' flex flex-col justify-start pt-10 lg:pt-20 h-full items-center '>
  <div class='text-shadow px-10 absolute top-1/2  transform  -translate-y-1/2 fadeIn max-w-3xl'>
    <div>
      <div class='transition select-none' href='https://github.com/narzaut?tab=repositories'>
        <i class="animate-wiggle text-gray-200 pb-4 fab fa-github text-9xl  cursor-pointer hover:text-green-500 transition-colors" />
      </div>
      <h1 class=' text-gray-200 text-5xl pt-6 md:text-6xl lg:text-7xl'>
        {title}
      </h1>	
      <p class='py-10 text-md lg:text-2xl text-gray-300'>
        {description}
      </p>
    </div>	
  </div>
</div>