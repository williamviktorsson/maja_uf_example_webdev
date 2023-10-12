<script>
  /** @type {import('./$types').LayoutData} */
  export let data
</script>

<nav >
  <a href="/">Hem</a>
  <a href="/recept">Recept</a>
</nav>

<slot />

<style>
    nav{
        display: flex;
        gap: 20px;
        background-color: grey;
        padding: 20px;
    }
</style>