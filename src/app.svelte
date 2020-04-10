<script>
  import Router from 'svelte-spa-router'
  import Section from './section'
  import SidePanel from './comps/sidePanel'

  const routes = {
    '/section': Section
  }

  let rightVisible = true
</script>

<SidePanel bind:rightVisible={rightVisible} />


<h1>hello world</h1>
<h2>helo helo okay</h2>

<a href="#/section">Click</a>
<Router {routes} />