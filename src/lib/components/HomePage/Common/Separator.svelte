<script lang="ts">

</script>

<div class="separator"><span></span></div>

<style>
    div {
        line-height: 0.5;
        text-align: center;
        margin: 30px 0 30px 0;
    }

    div span {
        height: 5px;
        width: 5px;
        border-radius: 5px;
        background-color: var(--accent);
        display: inline-block;
        position: relative;
    }

    div span:before,
    div span:after {
        content: "";
        position: absolute;
        border-bottom: 1px solid rgba(255, 255, 255, 0.15);
        width: 300px;
        top: 2px;
    }

    div span:before {
        right: 100%;
        margin-right: 15px;
    }

    div span:after {
        left: 100%;
        margin-left: 15px;
    }
</style>