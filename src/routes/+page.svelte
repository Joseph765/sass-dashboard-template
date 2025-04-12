<script>
  import { Button, Heading, Flex, Section } from "$lib/components";
</script>

<Section>
  <Heading size="2xl">Welcome to Sass Dashboard</Heading>
</Section>
<Section>
  <Flex>
    <div class="box" style="background: var(--gray-2);">

    </div>
  </Flex>
</Section>
<!-- <Button>Click Here</Button> -->

<style>
  .box {
    height: 124px;
    width: 124px;
    border: 1px solid var(--color-border);
  }
</style>