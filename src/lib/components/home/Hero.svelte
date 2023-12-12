<!-- <section class="hero">
  <h1>The <span>one</span> solution to bring your ideas <span>to life</span></h1>
  <ul>
    <li>Design</li>
    <li>Development</li>
    <li>Marketing</li>
    <li>Consulting</li>
  </ul>
  <p>Here you can find everythin you need to make your website feel alive</p>
  <h3>Let me introduce myself</h3>
  <p>I'm Robin,</p>
  
</section> -->

<section class="hero-section">
    <div class="hero container">
      <div class="hero__text">
        <h1 class="hero__hook">Being part of the web can be your best <a href="/">next step</a></h1>
        <h3>Let's build together your <span>own</span> online space you can be <span>proud of</span></h3>
        <div class="myself">
          <p>Hi!</p>
          <p>My name is</p>
          <h2>Robinson Ochoa</h2>
        </div>
        <ul>
          <li><a href="/">Designer</a></li>
          <li><a href="/">Marketer</a></li>
          <li><a href="/">Egeneer</a></li>
        </ul>
        <!-- <p>And above all those things</p>
        <p>I'm the person who wants to help your ideas comes true.</p> -->
      </div>
      <div class="hero__img">
        <img class="img" src="/Rsk8aLogoVector.png" alt="">
      </div>
  </div>

</section>

<style>
  .hero-section {
    background-image: 
    linear-gradient(rgb(149, 255, 205), transparent),
    linear-gradient(to top left, rgb(83, 178, 255), transparent),
    linear-gradient(to top right, rgb(2, 173, 2), transparent);
    background-blend-mode: screen;
    position: relative;
    z-index: 0;
  }
  .hero-section::before {
  content: "";
  background-image: url("/HeroBubleBack2.png");
  position: absolute;
  inset: 0;
  background-position: center;
  background-size: 100%;

  z-index: -2;
  mix-blend-mode: darken;
  }
  /* .hero-section::after {
    content: "";
  } */

.hero {
  width: 100%;
  display: flex;
  gap: 2rem;
  align-items: center;
  justify-content: space-around;
}
.hero::after {
  width: 100%;
  height: 100%;
  background: rgba(90, 175, 171, 0.8);
  position: absolute;
  inset: 0;
  /* mix-blend-mode: screen; */
}
  .hero__text {
    margin-top: 4rem;
    max-width: 40rem;
  }

  .hero__hook {
    font-size: 4rem;
    color: var(--dark01);
    font-weight: 900;
    text-transform: uppercase;
  }
  .hero__hook a {
    color: rgb(54, 119, 98);
    padding-right: 0.6rem;
    padding-left: 0.6rem;
    margin-left: -0.5rem;
  }
  .hero__hook a:hover {
    background-color: rgba(14, 68, 61, 0.4);
    border-radius: 0.6rem;
    color: aqua;
    transform: scale(1.05);

  }

  h3 {
    font-size: 2rem;
    margin: 1rem 2rem 1rem 0.6rem;
    padding: 0.4rem 1rem;
    color: var(--dark02);
    border-left: solid 0.4rem orange;
    background-color: rgba(255, 255, 255, 0.2);
    border-radius: 0 1rem 1rem 0;
  }
  h3 span {
    color: orange;
  }

  .myself {
    color: var(--dark01);
    display: grid;
    grid-template-columns: 1fr 3fr;
    grid-template-rows: 1fr 2fr;
    margin-top: 2rem;
    margin-left: 2rem;
  }

  .myself p:nth-child(1) {
    font-size: 7rem;
    font-weight: 600;
    grid-column: 1;
    grid-row: 1/3;
    margin: -1.2rem 0;
  }
  .myself p:nth-child(2) {
    font-size: 1.4rem;
    font-weight: 600;
    grid-column: 2;
    grid-row: 1;
    letter-spacing: 0.1rem;
  }

  h2 {
    font-size: 3.2rem;
    color: var(--dark02);
    grid-row: 2;
    grid-column: 2;
  }

  ul {
    display: flex;
    justify-content: center;
    gap: 2rem;
    margin-top: 1.2rem;
    margin-bottom: 3rem;
    margin-right: 2rem;
  }

  li a {
    color: var(--dark01);
    font-size: 1.2rem;
    font-weight: 600;
    background-color: rgb(127, 255, 255);
    padding: 0.4rem 1rem;
    border-radius: 0.3rem;
    display: inline-block;
    margin: 0.4rem;
    margin-left:1rem;
  }

  .img {
    height: 30rem;
    width: 30rem;
    mix-blend-mode: exclusion;
  }

</style>