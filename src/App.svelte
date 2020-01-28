<script>
  import { Router, Link, Route } from "svelte-routing";
  import Home from "./pages/Home.svelte";

  export let url = "";
</script>

<Router url="{url}">
  <div>
    <Route path="/"><Home /></Route>
  </div>
</Router>