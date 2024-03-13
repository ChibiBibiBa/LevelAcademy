<script lang="ts">
  import Separator from "$lib/components/HomePage/Common/Separator.svelte";
  import SectionHeader from "../Common/SectionHeader.svelte";
</script>

<section id="whatWeDo">
  <SectionHeader>WHAT WE DO</SectionHeader>
  <Separator></Separator>

  <section class="development-area">
    <div class="development-card">
      <h2>DEVELOP AS A <span class="distinctWord">PRO</span></h2>
      <p>
        Our resources have been instrumental in developing the training programs
        used by the world elite. We have tailored our approach to maximize
        participant development, promoting physical exercise, good nutrition,
        and a healthy lifestyle.
      </p>
      <img
        src="https://levelacademy.com.mt/wp-content/uploads/2022/04/pro-300x300.jpg"
        alt="Develop as a Pro"
      />
    </div>
    <div class="development-card">
      <h2>DEVELOP AS A <span class="distinctWord">PLAYER</span></h2>
      <p>
        Learning to develop as a player is a lot about learning how to
        strategize your own development, understand your goals and your own
        opportunities. We provide our participants with the tools to work
        autonomously, socially, and engaged.
      </p>
      <img
        src="https://levelacademy.com.mt/wp-content/uploads/2022/04/player-300x300.jpg"
        alt="Develop as a Player"
      />
    </div>
    <div class="development-card">
      <h2>DEVELOP AS A <span class="distinctWord">PERSON</span></h2>
      <p>
        Mentoring is one of our strongest tools. We have well-known esports
        profiles that create role models and drive positive values and actions.
        We work actively to promote diversity and inclusion and counteract
        sexism, racism, and bullying.
      </p>
      <img
        src="https://levelacademy.com.mt/wp-content/uploads/2022/04/person-300x300.jpg"
        alt="Develop as a Person"
      />
    </div>
  </section>
</section>

<style>
  #whatWeDo {
    width: 100%;
    height: 70vh;

    padding-top: var(--sectionPadding);
    padding-top: var(--sectionPadding);

    background-color: var(--background);
  }
  .distinctWord {
    color: var(--accent);
  }

  :root {
    --accent: #fb5304;
    font-family: Comic;
  }

  .development-area {
    display: flex;
    justify-content: space-between;
    color: white;
  }

  .development-card {
    width: 30%;
    margin: 10px;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
    padding: 20px;
  }

  .development-card img {
    max-width: 50%;
    height: auto;
    display: block;
    margin-top: 10px;
  }

  .development-card h2 {
    font-size: 1.5em;
  }

  .development-card p {
    font-size: 1em;
    line-height: 1.6;
  }
</style>
