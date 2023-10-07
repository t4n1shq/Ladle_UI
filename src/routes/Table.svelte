<script>
    import Row from "./Row.svelte";
</script>

<div>
    <table class="table">
    <thead>
        <tr>
            <th>Ladle ID</th>
            <th>Station</th>
            <th>Status</th>
            <th>Entry Time</th>
            <th>Exit Time</th>
        </tr>
    </thead>
    <tbody>
    {#each Array(100) as _, index (index)}
      <Row ladleId={2} station={"abcd"} entryTime={"abdc"} exitTime={"abdc"}/>
    {/each}
    </tbody>
    </table>
</div>