<script>
  import {onMount} from 'svelte'
  import {goto} from '$app/navigation'

  onMount(async () => {
      await goto(`/hexagonal/5`)
  })
</script>
<div class="container">
  <p> This should redirect to a random puzzle page soon. </p>
</div>

<style>
p {
  text-align: center;
}
</style>