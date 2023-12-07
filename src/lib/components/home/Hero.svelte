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
  <ul>
    <li>Designer</li>
    <li>Egeneer</li>
    <li>Marketer</li>
  </ul>
  
</section> -->

<section class="hero container">
  <div class="hero__text">
    <h1>¿Thinking about getting your business to the next level?</h1>
    <h2>¿why not to go online?</h2>
    <p>Design with us a website you can be proud of</p>
  </div>
  <div class="hero__img">
    <img class="img" src="/Rsk8aLogoVector.png" alt="">
  </div>
</section>

<style>
  .hero {
    display: flex;
    align-items: center;

  }
  .hero__text {
    flex: 3;
  }
  .hero__img {
    flex: 1;
  }
  .img {
    height: 20rem;
    width: 20rem;
  }
  h1 {
    font-size: 3rem;
  }
  h2 {
    font-size: 2em;
  }

  /* 4 point gradient */

  section {
    background:
        linear-gradient(red, transparent),
        linear-gradient(to top left, lime, transparent),
        linear-gradient(to top right, blue, transparent);
    background-blend-mode: screen;
}
</style>