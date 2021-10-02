<script lang="ts">
  import '@fontsource/geo'
  import '@fontsource/bodoni-moda'
  import '@fontsource/league-spartan'
  import { ogVintage, toString } from "./lib/palettes";
  import ogVintageLogo from "./assets/svg/ogVintageLogo.svg"
</script>
<main style="background-color: {toString(ogVintage.dark)}">
  <img src={ogVintageLogo} alt="Project Logo in a Vintage Style">
</main>
  <div class="title">
    <h1>
      Logography
    </h1>
    <p>
      Vintage segmented alphabets with a simple bitmap encoding.
    </p>

  </div>

<style>
  :root {
    --dark: #161616;
    --cool: #346751;
    --warm: #c84b31;
    --lite: #ecdbba;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  
    background-color: var(--dark); 
  }
  h1 {
    margin: 0;
    padding: 0;

    color: var(--cool);
    font-family: Geo;
    font-size: 10rem;
    text-shadow: 5px 5px 0px var(--dark), 10px 10px 0px var(--warm);

  }
  main {
    margin: 0;
    padding: 0;
    width: 60vh;
    height: 60vh;
    margin: auto;
  }

  p {
    /* font-family: bodoni moda; */
    font-family: league spartan;
    color: var(--lite);
    font-size: 2rem;

  }
  .title {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    margin: auto;
    width: 60vh;
    padding: 0;
  }
</style>

