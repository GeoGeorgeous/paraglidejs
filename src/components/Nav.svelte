<script>
  const links = [
    {
      name: 'Home',
      path: '/'
    },
    {
      name: 'Info',
      path: '/info'
    }
  ];
</script>

<nav>
  <div
    style="display: flex; flex-direction: row; align-items: center; justify-content: center; gap: 1rem; padding: 2rem">
    {#each links as link}
      <a href={link.path}>{link.name}</a>
    {/each}
  </div>
</nav>
