<script>
  let navbarLinks = [
    {"name": "Home", "link": "/"},
    {"name": "About", "link": "/about"},
    {"name": "Contact", "link": "/contact"},
    // {"name": "Portfolio", "link": "/portfolio"},
  ];
  
</script>

<header class="header">
  <div class="branding">
    <a href="/"><img class="logo" src="/Rsk8aLogoVector.png" alt=""></a>
    <a class="text-logo" href="/">RobinSk8a</a>
  </div>
  <nav class="nav">
    <ul class="nav-list">
      {#each navbarLinks as {name, link}}
        <li class="list__item">
          <a href={link}>{name}</a>
        </li>
      {/each}
      <li class="list__buton">
        <a href="/portfolio">Portfolio</a>
      </li>
    </ul>
  </nav>
</header>

<style>
  .header {
    background-image: linear-gradient(to right, var(--dark02), var(--dark01), var(--dark02));
    padding: 0 4rem;
    display: flex;
    align-items: center;
    justify-content: space-between;

  }
  .branding {
    display: flex;
    align-items: center;
    gap: 0.8rem;
  }
  .logo {
    height: 2rem;
    width: 2rem;
    transition: 0.3s;
  }
  .logo:hover {
    transform: scale(1.08);
    transition: 0.3s;
  }
  .text-logo {
    
    height: 100%;
    color: aquamarine;
    font-weight: 600;
    font-size: 1.4rem;
  }
  .text-logo:hover {
    transform: scale(1.05);
    transition: 0.3s;
    color: skyblue;
  }
  .nav {
    display: flex;
    align-items: center;
    gap: 	1rem;
  }
  .nav-list{
    display: flex;
    align-items: center;
  }

  .list__item {
    padding: 1rem 1rem;
    height: 100%;
    color: skyblue;
    font-weight: 600;
    font-size: 1.2rem;
    transition: 0.3s;
  }
  .list__item:hover {
    color: aquamarine;
    transform: scale(1.05);
    background-color: rgba(21, 175, 221, 0.15);
  }
  .list__buton {
    padding: 0.25rem 1rem;
    background-color: aquamarine;
    color: var(--dark02);
    border-radius: 0.4rem;
    font-weight: 600;
    font-size: 1.2rem;
    transition: 0.3s;
    margin-left: 0.6rem;
  }
  .list__buton:hover {
    box-shadow: 0 0.1rem 0.4rem 0.2rem var(--dark01);
    transform: scale(1.05);
  }
  </style>