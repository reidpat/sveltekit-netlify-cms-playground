<script>  
  // import {routes} from '../metadata'

  console.log(routes)
  
  export let title
</script>

<svelte:head>
  <title>{title}</title>
</svelte:head>

<nav>
  <ul>
    <!-- {#each routes as route}
      <li>
        {route.path}
        <a href={route.label}>{route.label}</a>
      </li>
    {/each} -->
  </ul>
</nav>

<slot />