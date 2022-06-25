<script lang='ts'>
  export let itemName: string;
  export let href: string;

</script>
<div>
  <a 
    href="{`#${href}`}" 
    class='text-xl border-b-2 border-transparent hover:border-green-400 rounded font-bold text-gray-200 hover:text-green-400 transition uppercase'
  >
    {itemName}
  </a>
</div>