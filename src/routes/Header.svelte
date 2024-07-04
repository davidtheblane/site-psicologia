<script>
  import {
    Navbar,
    NavBrand,
    NavLi,
    NavUl,
    NavHamburger,
  } from "flowbite-svelte";
</script>

<Navbar>
  <NavBrand class="" href="/">
    <img src="src/images/logo.png" class="mx-4 h-10 sm:h-16" alt="Logotipo" />
    <span class="self-center text-pink-400 justify-center items-center"
      >Dayane Bartolomeu
    </span>
  </NavBrand>
  <NavHamburger />
  <NavUl>
    <NavLi href="/">Inicio</NavLi>
    <NavLi href="/about">Sobre</NavLi>
    <NavLi href="/docs/components/navbar">Servicos</NavLi>
    <NavLi href="/pricing">Benefícios</NavLi>
    <NavLi href="/pricing">Depoimentos</NavLi>
    <NavLi href="/contact">Contato</NavLi>
  </NavUl>
</Navbar>
