<script>
    import { onMount } from 'svelte';
    onMount(async () => {
        import ('img-comparison-slider');
    });
</script>

<img-comparison-slider value="70" direction="vertical">
    <img
            slot="first"
            style="width: 100%"
            src="https://img-comparison-slider.sneas.io/demo/images/before.webp"
    />
    <img
            slot="second"
            style="width: 100%"
            src="https://img-comparison-slider.sneas.io/demo/images/after.webp"
    />
</img-comparison-slider>
