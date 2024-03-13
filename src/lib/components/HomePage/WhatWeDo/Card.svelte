<script lang="ts">
  export let header: string;
  export let img: string;
  export let alt: string;
</script>

<div>
  <h3>{header}</h3>
  <div class="content">
    <slot />
  </div>
  <img src={img} {alt} />
</div>
