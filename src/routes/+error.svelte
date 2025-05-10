<script>
  export let error;
  export let status;
  const is404 = status === 404;
</script>

<div class="error">
  <h1>{status}</h1>
  <p>{is404 ? "Page not found." : error.message}</p>
  <a href="/">Go Home</a>
</div>

<style>
  .error {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    height: 100vh;
  }
</style>
