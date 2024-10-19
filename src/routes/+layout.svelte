<script>import "../app.css";
// @ts-ignore
import Header from "$components/header.svelte"
// @ts-ignore
import Footer from "$components/footer.svelte"</script>

<div class="container items-center">
  <Header></Header>
  <slot class="container"></slot>
  <Footer></Footer>
</div>


<style>
</style>
