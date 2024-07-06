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
  <NavBrand class="flex" href="/">
    <img
      src="/images/logo2.svg"
      class="mx-4 h-10 sm:h-16 scale-110 -translate-y-1"
      alt="Logotipo"
    />
    <span class=" text-base text-pink-400 justify-center translate-y-1"
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
