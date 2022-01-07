<script>
    import {Button, Icon} from 'svelte-chota';
    import {mdiFishOff} from '@mdi/js';

    let world;
</script>

<div class="content">
    <div class="button-container">
        <Button class="bg-dark text-light" on:click={() => world = 'World !'}>Say Hello to the world</Button>
    </div>

    <div class="text-grey">
        Hello { world || '' }
        <Icon src={mdiFishOff} color="var(--color-primary)" size="1"></Icon>
    </div>
</div>

<style lang="scss">
  @import "src/styles/variables";

  .content {
    margin: 2em;
    display: flex;
    align-items: center;
    gap: $padding-normal;
  }
</style>