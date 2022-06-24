<script lang="ts">
  export let label;
</script>

<svelte:options tag="aotw-input" />

{#if label}
<label for="input">{label}</label>
{/if}
<input type="text" id="input" />

<style lang="scss" src="./Input.scss"></style>
