<script>
  import { ParaglideJS } from '@inlang/paraglide-sveltekit';
  import { i18n } from '$lib/i18n';
  import Nav from '../components/Nav.svelte';
</script>

<ParaglideJS {i18n}>
  <Nav />
  <slot />
</ParaglideJS>
