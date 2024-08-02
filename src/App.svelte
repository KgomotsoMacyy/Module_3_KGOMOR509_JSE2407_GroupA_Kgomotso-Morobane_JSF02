<script>
  import { Router, Route } from "svelte-routing"
  import Header from "./components/NavBar.svelte";
  import Home from "./pages/Home.svelte";
  import ProductPreview from "./pages/ProductPreview.svelte";
</script>

<Header />
<Router>
  <Route path="/" component={Home} />
  <Route path="products/:id" component={ProductPreview} />
</Router>
 
<style></style>
