<script>
  import CallToActionBtn from "../components/CallToActionBtn.svelte";

  const faqs = [
    {
      question: "Como funciona a psicoterapia online?",
      text: "As sessões online são realizadas por meio de uma plataforma de           videoconferência segura, que pode ser acessada por meio de um           computador, tablet ou celular. Tem duração de 50 minutos e respeita o           código de proteção de dados.",
    },
    {
      question: "Quanto tempo dura um processo psicoterapêutico?",
      text: "Não é possível estimar com exatidão o tempo de duração de um processo           psicoterapêutico, pois cada pessoa responde de uma maneira única a           esse processo. Isso vai depender do seu contexto histórico, objetivos           e envolvimento no processo.",
    },
    {
      question: "Qual é o valor da sessão?",
      text: "De acordo com o código de ética do psicólogo, é vedada a divulgação do           valor da sessão como forma de propaganda para os seus serviços.           Contudo, clicando no botão abaixo você poderá falar comigo e tirar           essa e outras dúvidas que tiver.",
    },
  ];
</script>

<div id="faq" class="max-w-screen-xl mx-auto px-10">
  <div class="flex flex-col items-center">
    <h2 class="section-title">FAQ</h2>
  </div>
  <div class="grid divide-y divide-neutral-200 max-w-2xl mx-auto mt-8">
    {#each faqs as faq}
      <div class="py-5">
        <details class="group text-gray-400 text-xl">
          <summary
            class="flex justify-between items-center font-medium cursor-pointer list-none"
          >
            <span>{faq.question}</span>
            <span class="transition group-open:rotate-180">
              <svg
                fill="none"
                height="24"
                shape-rendering="geometricPrecision"
                stroke="currentColor"
                stroke-linecap="round"
                stroke-linejoin="round"
                stroke-width="1.5"
                viewBox="0 0 24 24"
                width="24"
                ><path d="M6 9l6 6 6-6"></path>
              </svg>
            </span>
          </summary>
          <p
            class="text-gray-400 mt-3 text-lg text-justify group-open:animate-fadeIn"
          >
            {faq.text}
          </p>
        </details>
      </div>
    {/each}

    <div class="flex justify-center p-10">
      <CallToActionBtn />
    </div>
  </div>
</div>
