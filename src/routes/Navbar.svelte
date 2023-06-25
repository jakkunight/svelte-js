<script>
    import { base } from "$app/paths";
</script>
<style>
    div{
        background-color: darkslategray;
        height: auto;
        width: 100%;
        color: aquamarine;
        margin: 0px;
        padding: 5%;
    }
    a{
        text-decoration: none;
    }
</style>
<div>
    <a href="{base}/">
        <button>
            Home
        </button>
    </a>
        <a href="{base}/blog">
        <button>
            Blog
        </button>
    </a>
        <a href="{base}/about">
        <button>
            Acerca de...
        </button>
    </a>
</div>