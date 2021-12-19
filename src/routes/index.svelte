<script>
    let location="";
    let temperature="";
    let description="";
</script>
<h1>Welcome to SvelteKit</h1>
<form on:submit|preventDefault={getWeather}>
    <label for="location">Location:</label>
    <input id="location" bind:value={location} type="text" />
    <button type="submit">Check</button>
</form>
