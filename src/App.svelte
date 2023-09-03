<script lang="ts">
  import { Router, Route, links } from 'svelte-routing'
  import Landing from 'src/lib/Landing.svelte'
</script>

<main use:links>
  <Router>
    <Route path="/" component={Landing} />
    <Route>
      <p>Not found</p>
      <a href="/">Go back</a>
    </Route>
  </Router>
</main>
