<script lang="ts">
  import Separator from "../../Separator.svelte";
  import SectionHeader from "../Common/SectionHeader.svelte";
</script>

<section class="iframesContainer" id="AFKseries">
  <SectionHeader>Going afk series - level academy</SectionHeader>
  <Separator></Separator>
  <div class="iframesGridContainer">
    <iframe
      title=""
      loading="lazy"
      src="https://www.youtube.com/embed/PewDgSE_XM0?feature=oembed"
    >
    </iframe>
    <iframe
      title=""
      loading="lazy"
      src="https://www.youtube.com/embed/DmkVtCk05sM?feature=oembed"
    >
    </iframe>
    <iframe
      title=""
      loading="lazy"
      src="https://www.youtube.com/embed/uTaafZum59E?feature=oembed"
    >
    </iframe>
    <iframe
      title=""
      loading="lazy"
      src="https://www.youtube.com/embed/QD5ywvpLye0?feature=oembed"
    >
    </iframe>
  </div>
  <Separator></Separator>
</section>

<style>
  .iframesContainer {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-evenly;

    height: 95vh;
    width: 100%;

    padding-top: var(--sectionPadding);
    padding-bottom: var(--sectionPadding);
  }

  .iframesGridContainer {
    width: 75%;
    height: 100%;

    margin-top: 5vh;

    display: grid;
    grid-template-columns: repeat(2, 1fr);
    grid-template-rows: repeat(2, 1fr);
    grid-column-gap: 30px;
    grid-row-gap: 40px;
    padding-bottom: 5vh;
  }

  .iframesGridContainer iframe {
    width: 555px;
    height: 312px;

    justify-self: center;

    border: 0;
  }
</style>
