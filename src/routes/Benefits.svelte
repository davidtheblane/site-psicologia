<script>
  const benefits = [
    {
      title: "Acessibilidade",
      text: "A psicoterapia online permite que pessoas que moram em áreas             remotas, rurais e distantes da cidade possam ter acesso a cuidados             de saúde mental. Além disso, pessoas com mobilidade reduzida podem             se beneficiar da conveniência de ter um acompanhamento             psicoterapêutico sem sair de casa.",
      position: { cx: "12", cy: "7", r: "4" },
      path: "M20 21v-2a4 4 0 00-4-4H8a4 4 0 00-4 4v2",
    },
    {
      title: "Flexibilidade e Economia de tempo",
      text: " A psicoterapia online permite maior flexibilidade, podendo atender             melhor a rotina do cliente. Como não precisa se deslocar até o             consultório, o cliente evita o gasto de tempo, e o estresse do             trânsito e transporte.",
      position: { cx: "12", cy: "5", r: "3" },
      path: "M12 22V8M5 12H2a10 10 0 0020 0h-3",
    },
    {
      title: "Privacidade e Conforto",
      text: "O cliente tem a possibilidade de fazer as sessões do conforto do seu             lar, e isso pode contribuir para se sentirem mais à vontade para             falar sobre suas questões. É uma ótima opção para quem não quer             fazer o acompanhamento com um profissional da sua cidade.",
      position: { cx: "0", cy: "0", r: "0" },
      path: "M22 12h-4l-3 9L9 3l-3 9H2",
    },
    {
      title: "Custo",
      text: "Ao não precisar se deslocar até o consultório, o cliente economiza             em transporte, gasolina e estacionamento. Ao final do mês essa pode             ser uma boa economia.",
      position: { cx: "12", cy: "5", r: "3" },
      path: "M22 12h-4l-3 9L9 3l-3 9H2",
    },
  ];
</script>

<section id="beneficios" class="text-gray-600">
  <div class="container px-5 py-12 mx-auto justify-center flex flex-wrap">
    <div class="items-center">
      <h2 class="section-title">Vantagens</h2>
      <p class="text-gray-400 text-lg text-center py-6">
        A psicoterapia online pode oferecer uma série de vantagens em comparação
        com a presencial.
      </p>
    </div>

    {#each benefits as { title, text, position, path }, index}
      <div class="flex relative pt-10 pb-20 mx-auto">
        <div
          class="h-full w-6 absolute inset-0 flex items-center justify-center"
        >
          <div class="h-full w-1 bg-gray-200 pointer-events-none"></div>
        </div>
        <div
          class="flex-shrink-0 w-6 h-6 rounded-full mt-10 sm:mt-0 inline-flex items-center justify-center bg-pink-400 text-white relative z-10"
        >
          {index + 1}
        </div>
        <div
          class="flex-grow md:pl-8 pl-6 flex sm:items-center items-start flex-col sm:flex-row"
        >
          <div
            class="flex-shrink-0 w-24 h-24 bg-pink-100 text-pink-400 rounded-full inline-flex items-center justify-center"
          >
            <svg
              fill="none"
              stroke="currentColor"
              stroke-linecap="round"
              stroke-linejoin="round"
              stroke-width="2"
              class="w-12 h-12"
              viewBox="0 0 24 24"
            >
              <path d={path}></path>
              <circle cx={position.cx} cy={position.cy} r={position.r}></circle>
            </svg>
          </div>
          <div class="flex-grow sm:pl-6 mt-6 sm:mt-0">
            <h2 class="text-xl font-bold text-pink-400 mb-1">{title}</h2>
            <p class="leading-relaxed text-gray-400 text-lg text-justify">
              {text}
            </p>
          </div>
        </div>
      </div>
    {/each}
  </div>
</section>
<hr class="mx-20 py-10" />
