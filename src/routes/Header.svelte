<script>
  import {
    Navbar,
    NavBrand,
    NavLi,
    NavUl,
    NavHamburger,
  } from "flowbite-svelte";
</script>

<Navbar id="inicio">
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
    <NavLi href="#artigos">Artigos</NavLi>
    <NavLi href="#beneficios">Benefícios</NavLi>
    <NavLi href="#depoimentos">Depoimentos</NavLi>
    <NavLi href="#sobre">Sobre</NavLi>
    <NavLi href="#faq">FAQ</NavLi>
    <NavLi href="#servicos">Servicos</NavLi>
    <NavLi href="#contato">Contato</NavLi>
  </NavUl>
</Navbar>
