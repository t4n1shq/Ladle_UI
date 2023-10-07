<script>
    import Status from "./Status.svelte";
    export let ladleId, station, entryTime, exitTime;
</script>

<tr class="hover">
    <th class="text-center">{ladleId}</th>
    <td class="text-center">{station}</td>
    <td class="flex justify-center"><Status status={"Active"}/></td>
    <td class="text-center">{entryTime}</td>
    <td class="text-center">{exitTime}</td>
</tr>
