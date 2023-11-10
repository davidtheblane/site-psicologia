<script>
  import Step from "./Step.svelte";

  let step = [
    { name: "Ansiedade", icon: "fa-solid fa-list-check" },
    { name: "Autoestima", icon: "fa-solid fa-list-check" },
    { name: "Depressão", icon: "fa-solid fa-list-check" },
    { name: "Relacionamento", icon: "fa-solid fa-list-check" },
  ];

  let Benefits = [
    { name: "Paz Interior", icon: "fa-solid fa-list-check" },
    { name: "Relacionamentos Saudáveis", icon: "fa-solid fa-list-check" },
    { name: "Autodescoberta", icon: "fa-solid fa-list-check" },
    { name: "Saúde Mental", icon: "fa-solid fa-list-check" },
  ];

  let abouts = [
    {
      name: "Nome Completo",
      description: "Dayane Bartolomeu de Oliveira Santos Bernardo",
    },
    {
      name: "Formação",
      description: "Universidade de Mogi das Cruzes. -  CRP: 06/175725",
    },
    {
      name: "Abordagem",
      description: "TCC - Terapia Cognitiva Comportamental",
    },
    {
      name: "Método de Atendimento",
      description: "100% Online",
    },
  ];

  let howTo = [
    {
      name: "Agendamento",
      description: "Entre em contato comigo e agende sua sessão.",
    },
    {
      name: "Primeira Sessão",
      description: "Chegue com uma mente aberta.",
    },
    {
      name: "Sessões Subsequentes",
      description:
        "Se quiser continuar, agendaremos sessões subsequentes de acordo com a sua disponibilidade.",
    },
    {
      name: "Crescer Juntos",
      description:
        "Juntos, vamos trabalhar para atingir seus objetivos e superar desafios.",
    },
  ];
</script>

<main class="flex flex-col flex-1 p-4">
  <section
    id="introPage"
    class="grid grid-cols-1 lg-grid-cols-2 gap-10 py-8 sm:py-14"
  >
    <div
      class="grid grid-cols-1 lg:justify-center text-center lg:text-left gap-6 md:gap-8 lg:gap-10"
    >
      <h2
        class="font-semibold text-4xl/tight sm:text-5xl/tight md:text-6xl/tight lg:text-7xl/tight"
      >
        Olá! <br /> Eu sou
        <span class="poppins text-rose-400" text-violet-400> Dayane</span>
        Bartolomeu
        <br />
        Psicóloga <span class="poppins text-rose-400"> Clínica</span>
      </h2>

      <!-- <p class="text-base sm:text-lg md:text-xl">
        Está precisando de ajuda com <br />
        <span class="text-rose-300"
          >Ansiedade, Autoestima, Depressão e Relacionamento</span
        > ?
      </p>
      <a
        href="https://wa.me/5511947922772"
        target="_blank"
        class="blueShadow mx-auto lg:mr-auto lg:ml-0 text-base sm:text-lg md:text-xl poppins relative overflow-hidden px-6 py-3 group rounded-full bg-white text-slate-950"
      >
        <div
          class="absolute top-0 right-full w-full h-full bg-violet-400 opacity-20 group-hover:translate-x-full z-0 duration-200"
        />
        <h4 class="relative z-9">Vamos conversar &rarr;</h4>
      </a> -->
    </div>
  </section>

  <section id="servicos" class="py-20 lg:py-32 flex flex-col gap-24">
    <div class="flex flex-col gap2 text-center">
      <!-- <h6 class="text-lg sm:text-xl md:text-2xl">Posso te ajudar?</h6> -->
      <h3 class="font-semibold text-3xl sm:text-4xl md:text-5xl">
        <span class="poppins text-rose-400">Posso te ajudar?</span>
      </h3>
      <!-- <p>Veja abaixo algumas das questões que posso te ajudar a tratar.</p> -->
    </div>
    <!-- <a
      href=""
      target="_blank"
      class="mx-auto px-4 py-2 rounded-md border border-solid border-white flex items-center gap-2 -mb-4 sm:-mb-0 -mt-10 hover:border-violet-700 duration-200"
    >
      <i class="fa-regular fa-circle-play" />
      <p>Sobre Ansiedade</p>
    </a> -->
    <div
      class="grid grid-cols-1 gap12 md:grid-cols-2 lg:grid-cols-4 md:gap-5 lg:gap-10"
    >
      <Step step={step[0]}>
        <p>
          Preocupação excessiva ou constante de que algo negativo vai acontecer.
        </p>
      </Step>

      <Step step={step[1]}>
        <p>
          Autoestima está relacionada com a forma como nos valorizamos, com o
          nosso bem-estar e como nos percebemos no mundo.
        </p>
      </Step>
      <Step step={step[2]}>
        <p>
          Tristeza profunda, falta de apetite, desânimo, pessimismo, entre
          outros sintomas.
        </p>
      </Step>
      <Step step={step[3]}>
        <p>
          Um relacionamento de verdade não se constrói apenas de gostar, mas sim
          com confiança e sinceridade.
        </p>
      </Step>
    </div>

    <a
      href="https://wa.me/5511947922772"
      target="_blank"
      class="blueShadow mx-auto lg:mr-auto text-base sm:text-lg md:text-xl poppins relative overflow-hidden px-6 py-3 group rounded-full bg-rose-400 text-white"
    >
      <div
        class="absolute top-0 right-full w-full h-full bg-white opacity-20 group-hover:translate-x-full z-0 duration-200"
      />
      <h4 class="relative z-9">Entre em contato</h4>
    </a>
  </section>

  <section
    id="funcionamento"
    class="py-20 pt-10 lg:pt-16 lg:py-32 flex flex-col gap-16 sm:gap-20 md:gap-24 relative"
  >
    <div
      class="flex flex-col gap-2 text-center relative before:absolute before:top-0 before:left-0 before:w-2/3 before:h-1.5 before:bg-rose-400 after:absolute after:bottom-0 after:right-0 after:w-2/3 after:h-1.5 after:bg-rose-400 py-6"
    >
      <h6 class="text-lg sm:text-xl md:text-2xl">Quer saber como Funciona o</h6>
      <h3 class="font-semibold text-3xl sm:text-4xl md:text-5xl">
        <span class="poppins text-rose-400">Atendimento Psicológico? </span>
      </h3>
    </div>

    <div class="flex flex-col gap-20 w-full mx-auto max-w-[800px]">
      {#each howTo as how, index}
        <div class="flex gap-6 sm:gap-8">
          <p
            class="poppins text-4xl sm:text-5xl md:text-6xl text-rose-300 font-semibold"
          >
            0{index + 1}
          </p>
          <div class="flex flex-col gap-6 sm:gap-8">
            <h3 class="text-2xl sm:text-3xl md:text-5xl">
              {how.name}
            </h3>
            <p class="text-base md:text-2xl lg:text-2xl">
              {how.description}
            </p>
          </div>
        </div>
      {/each}
    </div>
  </section>

  <section id="benefits" class="py-20 lg:py-32 flex flex-col gap-24">
    <div class="flex flex-col gap2 text-center">
      <!-- <h6 class="text-lg sm:text-xl md:text-2xl">Posso te ajudar?</h6> -->
      <h3 class="font-semibold text-3xl sm:text-4xl md:text-5xl">
        <span class="poppins text-rose-400">Benefícios</span>
      </h3>
    </div>
    <!-- <a
      href=""
      target="_blank"
      class="mx-auto px-4 py-2 rounded-md border border-solid border-white flex items-center gap-2 -mb-4 sm:-mb-0 -mt-10 hover:border-violet-700 duration-200"
    >
      <i class="fa-regular fa-circle-play" />
      <p>Sobre Ansiedade</p>
    </a> -->
    <div
      class="grid grid-cols-1 gap12 md:grid-cols-2 lg:grid-cols-4 md:gap-5 lg:gap-10"
    >
      <Step step={Benefits[0]}>
        <p>Aprenda a gerenciar suas emoções e encontrar paz interior.</p>
      </Step>

      <Step step={Benefits[1]}>
        <p>
          Melhore seus relacionamentos e construa amizades autênticas e
          saudáveis.
        </p>
      </Step>
      <Step step={Benefits[2]}>
        <p>Aprenda mais sobre si mesmo e descubra suas forças e fraquezas.</p>
      </Step>
      <Step step={Benefits[3]}>
        <p>
          Melhore sua saúde mental e encontre maneiras de lidar com o estresse e
          a ansiedade.
        </p>
      </Step>
    </div>

    <!-- <a
      href="https://wa.me/5511947922772"
      target="_blank"
      class="blueShadow mx-auto lg:mr-auto text-base sm:text-lg md:text-xl poppins relative overflow-hidden px-6 py-3 group rounded-full bg-rose-400 text-white"
    >
      <div
        class="absolute top-0 right-full w-full h-full bg-white opacity-20 group-hover:translate-x-full z-0 duration-200"
      />
      <h4 class="relative z-9">Entre em contato</h4>
    </a> -->
  </section>

  <section
    id="sobre"
    class="py-20 pt-2 lg:pt-16 lg:py-32 flex flex-col gap-16 sm:gap-20 md:gap-24"
  >
    <div
      class="flex flex-col gap-2 text-center relative before:absolute before:top-0 before:left-0 before:w-2/3 before:h-1.5 before:bg-rose-400 after:absolute after:bottom-0 after:right-0 after:w-2/3 after:h-1.5 after:bg-rose-400 py-4"
    >
      <h6 class="text-lg sm:text-xl md:text-2xl">Quer saber mais</h6>
      <h3 class="font-semibold text-3xl sm:text-4xl md:text-5xl">
        <span class="poppins text-rose-400">Sobre mim? </span>
      </h3>
    </div>

    <!-- // incluir esse conteudo
  https://gamma.app/docs/Ideia-de-Site-Dayane-zpvsdt4szqtst75?mode=doc -->

    <!-- <div class="relative grid place-items-center">
    <img
      src={"images/profile.png"}
      alt="Foto Perfil Dayane"
      class="object-cover z-[2] max-[70vh]"
    />
    <p class="mx-auto poppins font-semibold text-lg sm:text-xl md:text-2xl">
      Eu sou...
    </p>
  </div> -->
    <div
      class="flex flex-col gap-20 w-full justify-center mx-auto max-w-[800px]"
    >
      <div class="foto_perfil flex justify-center m-0 p-0">
        <img
          src="images/fotoPerfil2.png"
          alt="Foto de Perfil"
          class="w-40 md:w-64 rounded-r-full shadow-xl ring-0 ring-gray-400/10"
        />
      </div>

      {#each abouts as about, index}
        <div class="flex gap-6 sm:gap-8">
          <!-- <p
            class="poppins text-4xl sm:text-5xl md:text-6xl text-rose-300 font-semibold"
          >
            0{index + 1}
          </p> -->
          <div class="flex flex-col gap-6 sm:gap-8">
            <h3 class="text-2xl sm:text-3xl md:text-5xl poppins text-rose-400">
              {about.name}
            </h3>
            <p class="text-base md:text-2xl lg:text-2xl">
              {about.description}
            </p>
          </div>
        </div>
      {/each}
    </div>
  </section>
</main>

<!-- 2 -->
<!-- parei em 1h02min -->
