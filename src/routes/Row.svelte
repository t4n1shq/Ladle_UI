<script>
    import Status from "./Status.svelte";
    export let ladleId, station, entryTime, exitTime;
</script>

<tr class="hover">
    <th>{ladleId}</th>
    <td>{station}</td>
    <td><Status status={"Active"} color={"green"}/></td>
    <td>{entryTime}</td>
    <td>{exitTime}</td>
</tr>
