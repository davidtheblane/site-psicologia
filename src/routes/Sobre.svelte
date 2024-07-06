<script>
  import CallToActionBtn from "../components/CallToActionBtn.svelte";
</script>

<div id="sobre" class="flex flex-col px-6 items-center">
  <h2 class="section-title">Sobre mim</h2>

  <!-- <span class="font-bold text-4xl text-gray-400">Olá!</span> <br /> -->

  <div class="w-48 flex flex-row items-center my-6">
    <img
      class="md:w-auto rounded-full shadow-md border-8 border-white"
      src="/images/profileSquare.svg"
      alt="profile"
    />
  </div>

  <p class="pt-10 py-4 font-bold text-gray-500 text-4xl">Olá!</p>
  <p class="p-4 text-lg text-wrap text-gray-400 text-justify">
    Me chamo <span class="font-semibold text-pink-400">
      Dayane Bartolomeu
    </span>
    e sou psicóloga clínica formada na Universidade de Mogi das Cruzes, cadastrada
    no <span class="font-semibold text-base text-pink-400">CRP-06/175725</span>.
  </p>

  <p class="p-4 text-lg text-wrap text-gray-400 text-justify">
    Minha jornada começou há muitos anos quando decidi fazer faculdade de
    Recursos Humanos, ouvir as demandas dos trabalhadores em relação às suas
    condições de trabalho me acendeu o alerta de que estudar Psicologia poderia
    melhorar a minha performance como profissional.
  </p>

  <p class="p-4 text-lg text-wrap text-gray-400 text-justify">
    Além disso, sempre tive uma curiosidade enorme sobre o comportamento humano,
    a pergunta que me acompanhava era “Porque as pessoas fazem o que fazem?” O
    interesse em entender o funcionamento do ser humano foi o meu maior ímpeto
    para estudar psicologia.
  </p>

  <p class="p-4 text-lg text-wrap text-gray-400 text-justify">
    Escolhi atender mulheres, porque entendo que vivenciamos demandas muito
    específicas de ser mulher no mundo. Sinto um prazer enorme em poder ajudar
    outras mulheres a alcançarem seus objetivos.
  </p>

  <p class="p-4 text-lg text-wrap text-gray-400 text-justify">
    Atualmente trabalhando como psicóloga clínica, o meu objetivo é poder ser
    uma facilitadora na vida das minhas pacientes. Ajudá-las a enxergar o seu
    potencial, e se tornarem mulheres mais felizes, independentes, saudáveis e
    autoconfiantes.
  </p>

  <p class="p-4 text-lg text-wrap text-gray-400 text-justify">
    Acredito fielmente no poder da psicoterapia, e acredito ainda mais no
    potencial individual que cada uma tem para mudar e ressignificar a sua
    história. Sendo assim, te convido a agendar uma consulta e começar uma
    jornada rumo a uma vida mais autêntica.
  </p>

  <div class="flex justify-center p-10">
    <CallToActionBtn />
  </div>
</div>
