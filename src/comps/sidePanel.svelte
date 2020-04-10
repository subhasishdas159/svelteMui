<script>
    export let rightVisible = false;

    import { Sidepanel } from 'svelte-mui';
</script>

<Sidepanel right bind:visible={rightVisible}>
    <div class="logo" style="padding-left: 1rem;">Subhasish Das</div>
    <p>
        <i style="padding: 12px;">Menu 1</i>
    </p>
</Sidepanel>