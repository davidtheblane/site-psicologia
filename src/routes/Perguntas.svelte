<script>
  import CallToActionBtn from "../components/CallToActionBtn.svelte";
</script>

<div class="max-w-screen-xl mx-auto px-10 bg-white">
  <div class="flex flex-col items-center">
    <h2 class="text-pink-400 text-4xl mt-5">FAQ</h2>
  </div>
  <div class="grid divide-y divide-neutral-200 max-w-xxl mx-auto mt-8">
    <div class="py-5">
      <details class="group">
        <summary
          class="flex justify-between items-center font-medium cursor-pointer list-none"
        >
          <span> Como funciona a psicoterapia online?</span>
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
        <p class="text-neutral-600 mt-3 group-open:animate-fadeIn">
          As sessões online são realizadas por meio de uma plataforma de
          videoconferência segura, que pode ser acessada por meio de um
          computador, tablet ou celular. Tem duração de 50 minutos e respeita o
          código de proteção de dados.
        </p>
      </details>
    </div>
    <div class="py-5">
      <details class="group">
        <summary
          class="flex justify-between items-center font-medium cursor-pointer list-none"
        >
          <span>Quanto tempo dura um processo psicoterapêutico?</span>
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
        <p class="text-neutral-600 mt-3 group-open:animate-fadeIn">
          Não é possível estimar com exatidão o tempo de duração de um processo
          psicoterapêutico, pois cada pessoa responde de uma maneira única a
          esse processo. Isso vai depender do seu contexto histórico, objetivos
          e envolvimento no processo.
        </p>
      </details>
    </div>
    <div class="py-5">
      <details class="group">
        <summary
          class="flex justify-between items-center font-medium cursor-pointer list-none"
        >
          <span>Qual é o valor da sessão?</span>
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
        <p class="text-neutral-600 mt-3 group-open:animate-fadeIn">
          De acordo com o código de ética do psicólogo, é vedada a divulgação do
          valor da sessão como forma de propaganda para os seus serviços.
          Contudo, clicando no botão abaixo você poderá falar comigo e tirar
          essa e outras dúvidas que tiver.
        </p>
      </details>
    </div>
    <div class="flex justify-center p-10">
      <CallToActionBtn />
    </div>
  </div>
</div>
