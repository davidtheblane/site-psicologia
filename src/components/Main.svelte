<script>
  import Step from "./Step.svelte";

  let step = [
    { name: "Ansiedade", icon: "fa-solid fa-list-check" },
    { name: "Autoestima", icon: "fa-solid fa-list-check" },
    { name: "Depressão", icon: "fa-solid fa-list-check" },
    { name: "Relacionamento", icon: "fa-solid fa-list-check" },
  ];

  let benefits = [
    {
      name: "Dayane Bartolomeu de Oliveira Santos Bernardo",
      description: "CRP: 06/175725",
    },
    {
      name: "Formação",
      description: "Psicóloga formada pela universidade de Mogi das Cruzes.",
    },
    {
      name: "Abordagem",
      description:
        "Minha principal abordagem é a 'Terapia Cognitiva Comportamental'",
    },
  ];
</script>

<main class="flex flex-col flex-1 p-4">
  <section
    id="introPage"
    class="grid grid-cols-1 lg-grid-cols-2 gap-10 py-8 sm:py-14"
  >
    <div
      class="flex flex-col lg:justify-center text-center lg:text-left gap-6 md:gap-8 lg:gap-10"
    >
      <h2 class="font-semibold text-4xl sm:text-5xl md:text-6xl">
        Olá! <br /> Eu sou
        <span class="poppins text-violet-400" text-violet-400> Dayane</span>
        Bartolomeu
        <br />
        Psicóloga <span class="poppins text-violet-400"> Clínica</span>
      </h2>

      <p class="text-base sm:text-lg md:text-xl">
        Pode contar comigo para tratar questões de <span class="text-violet-400"
          >Ansiedade, Autoestima, Depressão, Relacionamento</span
        > e muito mais...
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
      </a>
    </div>

    <div class="relative shadow-2xl grid place-items-center">
      <img
        src={"images/profile.png"}
        alt="Foto Perfil Dayane"
        class="object-cover z-[2] max-[70vh]"
      />
    </div>
  </section>

  <section id="servicos" class="py-20 lg:py-32 flex flex-col gap-24">
    <div class="flex flex-col gap2 text-center">
      <h6 class="text-lg sm:text-xl md:text-2xl">...</h6>
      <h3 class="font-semibold text-3xl sm:text-4xl md:text-5xl">
        <span class="poppins text-violet-400">Posso te ajudar?</span>
      </h3>
      <p>Veja abaixo algumas das questões que posso te ajudar a tratar.</p>
    </div>
    <!-- <a
      href=""
      target="_blank"
      class="mx-auto px-4 py-2 rounded-md border border-solid border-white flex items-center gap-2 -mb-4 sm:-mb-0 -mt-10 hover:border-violet-700 duration-200"
    >
      <i class="fa-regular fa-circle-play" />
      <p>Sobre Ansiedade</p>
    </a> -->
    <div class="grid grid-cols-1 lg:grid-cols-3 gap12 lg:gap-10">
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
  </section>

  <section
    id="sobre"
    class="py-20 pt-10 lg:pt-16 lg:py-32 flex flex-col gap-16 sm:gap-20 md:gap-24 relative"
  >
    <div
      class="flex flex-col gap-2 text-center relative before:absolute before:top-0 before:left-0 before:w-2/3 before:h-1.5 before:bg-violet-700 after:absolute after:bottom-0 after:right-0 after:w-2/3 after:h-1.5 after:bg-violet-700 py-4"
    >
      <h6 class="text-lg sm:text-xl md:text-2xl">Quer me conhecer melhor?</h6>
      <h3 class="font-semibold text-3xl sm:text-4xl md:text-5xl">
        Um <span class="poppins text-violet-400"> pouco mais </span> sobre mim.
      </h3>
    </div>
    <p class="mx-auto poppins font-semibold text-lg sm:text-xl md:text-2xl">
      Eu sou...
    </p>
    <div class="flex flex-col gap-20 w-full mx-auto max-w-[800px]">
      {#each benefits as benefit, index}
        <div class="flex gap-6 sm:gap-8">
          <p
            class="poppins text-4xl sm:text-5xl md:text-6xl text-slate-500 font-semibold"
          >
            0{index + 1}
          </p>
          <div class="flex flex-col gap-6 sm:gap-8">
            <h3 class="text-2xl sm:text-3xl md:text-5xl">
              {benefit.name}
            </h3>
            <p>{benefit.description}</p>
          </div>
        </div>
      {/each}
    </div>
    <h5 class="text-2xl sm:text-3xl font-semibold text-center poppins">
      O Pacote <span class="text-violet-400 poppins">completo</span>
    </h5>
    <div
      class="flex flex-col overflow-x-scroll gap-10 max-w-[800px] mx-auto w-full"
    >
      <table class="bg-white text-slate-700 rounded text-center">
        <thead class="border-b border-solid border-slate-200">
          <tr class="">
            <th />
            <th class="whitespace-nowrap p-2 px-4">Candidato 1</th>
            <th class="whitespace-nowrap p-2 px-4">Candidato 1</th>
            <th class="whitespace-nowrap p-2 px-4">Candidato 1</th>
            <th class="whitespace-nowrap bg-violet-700 text-white p-4 px-8"
              >Me</th
            >
          </tr>
        </thead>
        <tbody>
          <tr class="border-b border-solid border-slate-200">
            <td
              class="border-r border-solid border-white pl-4 pr-8 py-4 font-semibold text-sm whitespace-nowrap"
              >Dedication</td
            >
            <td><i class="fa-solid fa-xmark text-slate-500" /></td>
            <td><i class="fa-solid fa-check text-slate-500" /></td>
            <td><i class="fa-solid fa-check text-slate-500" /></td>
            <td><i class="fa-solid fa-check text-green-500" /></td>
          </tr>
          <tr class="border-b border-solid border-slate-200">
            <td
              class="border-r border-solid border-white pl-4 pr-8 py-4 font-semibold text-sm whitespace-nowrap"
              >Critical Thoughts</td
            >
            <td><i class="fa-solid fa-xmark text-slate-500" /></td>
            <td><i class="fa-solid fa-check text-slate-500" /></td>
            <td><i class="fa-solid fa-xmark text-slate-500" /></td>
            <td><i class="fa-solid fa-check text-green-500" /></td>
          </tr>
          <tr class="border-b border-solid border-slate-200">
            <td
              class="border-r border-solid border-white pl-4 pr-8 py-4 font-semibold text-sm whitespace-nowrap"
              >Interpersonal Skills</td
            >
            <td><i class="fa-solid fa-check text-slate-500" /></td>
            <td><i class="fa-solid fa-xmark text-slate-500" /></td>
            <td><i class="fa-solid fa-xmark text-slate-500" /></td>
            <td><i class="fa-solid fa-check text-green-500" /></td>
          </tr>
          <tr class="border-b border-solid border-slate-200">
            <td
              class="border-r border-solid border-white pl-4 pr-8 py-4 font-semibold text-sm whitespace-nowrap"
              >Programming Ability</td
            >
            <td><i class="fa-solid fa-check text-slate-500" /></td>
            <td><i class="fa-solid fa-xmark text-slate-500" /></td>
            <td><i class="fa-solid fa-xmark text-slate-500" /></td>
            <td><i class="fa-solid fa-check text-green-500" /></td>
          </tr>
        </tbody>
      </table>
    </div>
    <div class="mx-auto -mt-12 italic sm:hidden opacity-50">
      <p>Role para o lado e veja mais &rarr;</p>
    </div>
  </section>
</main>

<!-- 2 -->
<!-- parei em 1h02min -->
