<script>
    import Row from "./Row.svelte";
</script>

<div>
    <table class="table">
    <thead>
        <tr>
            <th class="text-center">Ladle ID</th>
            <th class="text-center">Station</th>
            <th class="text-center">Status</th>
            <th class="text-center">Entry Time</th>
            <th class="text-center">Exit Time</th>
        </tr>
    </thead>
    <tbody>
    {#each Array(100) as _, index (index)}
      <Row ladleId={index} station={"abcd"} entryTime={"abdc"} exitTime={"abdc"}/>
    {/each}
    </tbody>
    </table>
</div>