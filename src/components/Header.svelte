<script>
  export let y;

  let tabs = [
    { name: "Serviços", link: "#servicos" },
    { name: "Como Funciona", link: "#funcionamento" },
    { name: "Benefícios", link: "#benefits" },
    { name: "Sobre mim", link: "#sobre" },
    // { name: "Contato", link: "#contato" },
  ];
</script>

<header
  class={"sticky z-[10] top-0 duration-200 px-6 flex items-center justify-between border border-solid " +
    (y > 0
      ? "py-4 bg-slate-950 border-violet-950"
      : "py-6 bg-transparent border-transparent")}
>
  <h1 class="font-medium">
    <div class="foto_perfil flex">
      <img
        src="images/logoDayanePNG.png"
        alt="Logo"
        class="w-10 mx-4 flex justify-center"
      />
      <a href="/" class="hover:text-rose-400">
        <b class="font-bold poppins flex justify-center">Dayane</b> Bartolomeu
      </a>
    </div>
  </h1>

  <div class="sm:flex ml-auto pr-4 items-center gap-4 hidden">
    {#each tabs as tab, index}
      <a href={tab.link} class="duration-200 hover:text-rose-400">
        <p>{tab.name}</p>
      </a>
    {/each}
  </div>
  <a
    href="#contato"
    target="_blank"
    class="blueShadow relative overflow-hidden px-5 py-2 group rounded-full bg-rose-400 text-white"
  >
    <div
      class="absolute top-0 right-full w-full h-full bg-white opacity-20 group-hover:translate-x-full z-0 duration-200"
    />
    <h4 class="relative z-9">
      <a href="https://wa.me/5511947922772" target="_blank">
        Entre em contato
      </a>
    </h4>
  </a>
</header>
