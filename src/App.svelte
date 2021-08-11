<script>

    import Navbar from "./Navbar.components.svelte";
    import FileUploadButton from "./FileUploadButton.components.svelte";
import Home from "./views/Home.view.svelte";
</script>

<!-- svelte-ignore missing-declaration -->
<Router routes={
    {'/#/': Home}
} />