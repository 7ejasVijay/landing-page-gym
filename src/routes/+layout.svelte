<script>
  let { children } = $props();
  import "../app.css";
  import Footer from "../components/Footer.svelte";
</script>

{@render children()}
<Footer />

<!-- 
header
hero
product description
user reviews
faq
conversion
footer 
-->
