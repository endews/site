<script>
    import { Link, Router, Route } from 'svelte-navigator'

    // page imports
    import Home from './pages/Home.svelte'
</script>

<Router>
    <Route path="/">
        <Home />
    </Route>
</Router>
