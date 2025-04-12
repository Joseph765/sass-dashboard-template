<script>
  /** @type {'xs' | 's' | 'm' | 'l' | 'xl' | '2xl'} */
  export let size = "m";
</script>

<h1 class="heading is-size-{size}">
  <slot />
</h1>