<script lang='ts'>
  import Header from '../components/header.svelte'
  import About from '../components/about.svelte'
  import Footer from '../components/footer.svelte'
  import Resume from '../components/resume.svelte';
  import Portfolio from '../components/portfolio.svelte'
  import data from '../lang/spanish.json'
</script>
<div class="">
  <Header data = {data.header}/>
  <About data = {data.about}/>
 
</div>
