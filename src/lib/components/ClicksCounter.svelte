<script>
let {initialCount:count=0} = $props ()
    let doubled = $derived(count * 2)
</script>

<h3>Clicks Counter</h3>

<button onclick={()=>count++}>
    Clicks:{count}
</button>

<span>doubled is {doubled}</span>