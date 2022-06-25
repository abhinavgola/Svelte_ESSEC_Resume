


<script lang='ts'>
  export let name: string;
  export let percentage: number;
  export let icon: string;
  
  $: percent = 0
  const multiplier: number = 2  
  const animation = async () => {
    for (let i=0; i < percentage/multiplier; i++){
      await (async () => {
        return new Promise((resolve, reject) => {
          setTimeout(() => resolve(percent = percent + multiplier), 10)
        })
      })()
    }

  }
  animation()
</script>
<div class='py-5'>
  <p class='py-1 text-xl text-gray-700 font-semibold'>{name}</p>
  <div class='w-full h-10 rounded bg-gray-300 '>
    <div class='h-full flex items-center pl-2 rounded bg-gradient-to-r from-green-300 to-green-500 border-l-4 border-green-600' style={`width: ${percent-multiplier}%`}; >
      <i class={`${icon} pr-2 text-xl`}/>
    </div>
  </div>
</div>
