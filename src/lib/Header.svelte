<script>
  export let status = "default";
  import amarilogo from "../assets/amarilogo.svg";
  import Button from "./Button.svelte";
</script>

<header class={status}>
  <div class="container">
    <a href="/" title="inicio" rel="noreferrer" class="logo">
      <img src={amarilogo} alt="Logo amarilo" />
    </a>
    <nav class="menu">
      <ul>
        <li><Button /></li>
        <li><a href="/proyectos">Proyectos</a></li>
        <li><a href="/herramientas">Herramientas</a></li>
        <li><a href="/mi-cuenta">Mi cuenta</a></li>
      </ul>
    </nav>
  </div>
</header>

<style>
  header {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
  }
  .main {
    background: linear-gradient(to bottom, #000000ff 0%, #00000000 100%);
    backdrop-filter: blur(4px);
  }
  .main .container{
    border-color: #334488; 
    display: grid;
    grid-template-columns:1fr 7fr ;
  }
  .main .container > * {
    align-self: center;
  }
  .menu {
    display: flex;
    justify-content: flex-end;
  }
  .menu ul {
    list-style: none;
  }

  .menu ul li {
    display: inline-block;
  }
  
  .menu ul li a {
    padding: 2rem;
    color: #fff;
    
  }
  .container {
    width: 90%;
    margin: auto;
    /* border: 1px solid rgb(198, 11, 11); */
  }

  .logo img {
    max-width: 130px;
  }
</style>
