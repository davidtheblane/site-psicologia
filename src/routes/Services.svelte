<script>
  import CallToActionBtn from "../components/CallToActionBtn.svelte";
  const services = [
    {
      name: "Ansiedade",
      text: "Sabe aquela sensação de que algo ruim pode acontecer? Ou aquele         turbilhão de pensamentos negativos que muitas vezes desencadeiam um medo        e preocupação inexplicável? Pois é, isso pode ser ansiedade. Além desses        sintomas a ansiedade também pode se manifestar de forma física com        tremores, coração acelerado, respiração ofegante e sudorese. Na        psicoterapia você poderá aprender técnicas e habilidades para lidar com        esses sintomas e trabalhar as causas da sua ansiedade visando a redução        e maior controle de si mesma.",
      icon: "fa-solid fa-person-walking fa-3x",
    },
    {
      name: "Depressão",
      text: "A depressão é uma condição complexa que causa uma sensação profunda de         desesperança e desamparo. O indivíduo sente uma tristeza e vazio         contínuo durante a maior parte do dia. A sensação é de que nada poderá         mudar essa situação. Contudo, atualmente há formas de lidar com a         depressão, a psicoterapia poderá te munir de ferramentas para atravessar        esse período difícil, ressignificar sua vida e te devolver a alegria de         viver.",
      icon: "fa-solid fa-face-frown-open fa-3x translate-y-1",
    },
    {
      name: "Relacionamentos",
      text: "Pode ser um desafio e tanto estabelecer relações interpessoais. Seja no         campo afetivo, profissional, familiar os conflitos podem ser         inevitáveis. Terminar um relacionamento amoroso, pode desencadear muita         dor e emoções confusas. A psicoterapia pode cumprir um papel crucial em         te ajudar a desenvolver habilidades interpessoais para lidar com as         relações da sua vida.",
      icon: "fa-solid fa-users-rays fa-3x translate-y-1 -translate-x-0.5",
    },
    {
      name: "Autoestima",
      text: "Você gostaria de ter uma relação melhor consigo mesma? Ao longo da vida         podemos passar por experiências que nos fazem acreditar que não somos         boas o suficiente, que somos ruins ou indignas de amor. Deixamos de         reconhecer o nosso valor e perdemos a capacidade de nos amar. O processo         psicoterapêutico poderá te ajudar a olhar com mais carinho para si         mesma, reconhecer suas potencialidades, construir autoconfiança e         respeitar a pessoa que você é.",
      icon: "fa-solid fa-arrow-trend-up fa-3x translate-y-1",
    },
  ];
</script>

<div class="md:lg:xl:px-40 py-5 bg-opacity-10">
  <h2 id="servicos" class="section-title">
    Essas são algumas das áreas em que posso te ajudar
  </h2>
  {#each services as service}
    <div class="grid grid-cols-1 md:lg:grid-cols-2 xl:2xl:grid-cols-4 group">
      <div
        class="p-10 flex flex-col items-center text-center group md:lg:xl:border-r md:lg:xl:border-b"
      >
        <span
          class="inline-block p-5 w-24 h-24 rounded-full bg-pink-400 text-white shadow-lg shadow-gray-300"
        >
          <i class={service.icon}></i>
        </span>
        <p class="p-4 text-2xl text-wrap font-medium text-pink-400 mt-3">
          {service.name}
        </p>
        <p class="p-4 text-lg text-justify text-gray-400">
          {service.text}
        </p>
      </div>
    </div>
  {/each}
</div>
<div class="flex justify-center p-5">
  <CallToActionBtn />
</div>
