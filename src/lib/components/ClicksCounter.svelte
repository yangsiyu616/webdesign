<script>
    let count = $state(2)
    let doubled = $derived (count * 2)
</script>

<h3>Clicks Counter</h3>

<button onclick={()=>count++}>
    clicks:{count}
</button>

<span>doubled is {doubled}</span>