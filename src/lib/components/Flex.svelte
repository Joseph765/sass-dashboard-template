<script>
  /** @type {'row' | 'column'} */
  export let direction = "row";
</script>

<div class="flex is-direction-{direction}">
  <slot />
</div>