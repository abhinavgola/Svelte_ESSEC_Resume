<script lang='ts'>
  import NavItem from '../components/nav.item.svelte'
</script>


<nav class="select-none relative glass text-shadow shadow-lg fadeInDown pt-12 pb-8 lg:py-12 lg:items-center  w-full flex md:flex-row lg:flex-row  justify-around ">
  <div class='gap-20 w-full flex mx-10 max-w-lg justify-around' id='nav' >
    <NavItem href='home' itemName='HOME'/>
    <NavItem href='about' itemName='ABOUT'/>
    <NavItem href='curriculum' itemName='CURRICULUM'/>
    <NavItem href='portfolio' itemName='PORTFOLIO'/>
  </div>
</nav>
