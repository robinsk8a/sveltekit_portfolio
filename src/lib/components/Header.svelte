<header class="header">
  <div class="branding">
    <a href="/"><img class="logo" src="/Rsk8aLogoVector.png" alt=""></a>
    <a class="text-logo" href="/">RobinSk8a</a>
  </div>
  <nav class="nav">
    <ul>
      <li>
        <a href="/">Home</a>
      </li>
      <li>
        <a href="/about">About</a>
      </li>
      <li>
        <a href="/contact">Contact</a>
      </li>
    </ul>
  </nav>
</header>

<style>
  .header {
    background-image: linear-gradient(to right, rgb(14, 83, 95), rgb(14, 65, 95));
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
    color: skyblue;
    font-weight: 600;
    font-size: 1.4rem;
  }
  .text-logo:hover {
    transform: scale(1.05);
    transition: 0.3s;
    color: aquamarine;
  }
  .nav {
    display: flex;
    align-items: center;
    gap: 	1rem;
  }
  ul{
    display: flex;
    align-items: center;
  }

  li {
    padding: 1rem 1rem;
    height: 100%;
    color: skyblue;
    font-weight: 600;
    font-size: 1.2rem;
    transition: 0.3s;
  }
  li:hover {
    color: aquamarine;
    transform: scale(1.05);
    background-color: rgba(21, 175, 221, 0.15);
  }
</style>