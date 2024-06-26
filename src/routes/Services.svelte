<script>
  import { Card } from "flowbite-svelte";
  import CallToActionBtn from "../components/CallToActionBtn.svelte";
</script>

<h2 class="text-3xl text-pink-400 text-center px-6 py-10">
  Essas são algumas das áreas em que posso te ajudar
</h2>
<div
  class="px-3 md:lg:xl:px-40 border-t border-b py-20 bg-opacity-10"
  style="background-image: url('https://www.toptal.com/designers/subtlepatterns/uploads/dot-grid.png');"
>
  <div
    class="grid grid-cols-1 md:lg:grid-cols-2 xl:grid-cols-3 group bg-white shadow-xl shadow-neutral-100 border"
  >
    <div
      class="p-10 flex flex-col items-center text-center group md:lg:xl:border-r md:lg:xl:border-b hover:bg-slate-50 cursor-pointer"
    >
      <span
        class="p-5 rounded-full bg-pink-400 text-white shadow-lg shadow-gray-300"
        ><svg
          xmlns="http://www.w3.org/2000/svg"
          class="h-10 w-10"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
          stroke-width="1.5"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M12 4.354a4 4 0 110 5.292M15 21H3v-1a6 6 0 0112 0v1zm0 0h6v-1a6 6 0 00-9-5.197M13 7a4 4 0 11-8 0 4 4 0 018 0z"
          />
        </svg></span
      >
      <p class="p-4 text-2xl text-wrap font-medium text-pink-400 mt-3">
        Ansiedade
      </p>
      <p class="p-4 text-lg text-justify text-gray-400">
        Sabe aquela sensação de que algo ruim pode acontecer? Ou aquele
        turbilhão de pensamentos negativos que muitas vezes desencadeiam um medo
        e preocupação inexplicável? Pois é, isso pode ser ansiedade. Além desses
        sintomas a ansiedade também pode se manifestar de forma física com
        tremores, coração acelerado, respiração ofegante e sudorese. Na
        psicoterapia você poderá aprender técnicas e habilidades para lidar com
        esses sintomas e trabalhar as causas da sua ansiedade visando a redução
        e maior controle de si mesma.
      </p>
    </div>

    <div
      class="p-10 flex flex-col items-center text-center group md:lg:xl:border-r md:lg:xl:border-b hover:bg-slate-50 cursor-pointer"
    >
      <span
        class="p-5 rounded-full bg-pink-400 text-white shadow-lg shadow-gray-200"
        ><svg
          xmlns="http://www.w3.org/2000/svg"
          class="h-10 w-10"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
          stroke-width="1.5"
        >
          <path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"
          ></path>
          <polyline points="14 2 14 8 20 8"></polyline>
          <line x1="16" y1="13" x2="8" y2="13"></line>
          <line x1="16" y1="17" x2="8" y2="17"></line>
          <polyline points="10 9 9 9 8 9"></polyline>
        </svg></span
      >
      <p class="p-4 text-2xl text-wrap font-medium text-pink-400 mt-3">
        Depressão
      </p>
      <p class="p-4 text-lg text-justify text-gray-400">
        A depressão é uma condição complexa que causa uma sensação profunda de
        desesperança e desamparo. O indivíduo sente uma tristeza e vazio
        contínuo durante a maior parte do dia. A sensação é de que nada poderá
        mudar essa situação. Contudo, atualmente há formas de lidar com a
        depressão, a psicoterapia poderá te munir de ferramentas para atravessar
        esse período difícil, ressignificar sua vida e te devolver a alegria de
        viver.
      </p>
    </div>

    <div
      class="p-10 flex flex-col items-center text-center group md:lg:xl:border-b hover:bg-slate-50 cursor-pointer"
    >
      <span
        class="p-5 rounded-full bg-pink-400 text-white shadow-lg shadow-gray-200"
        ><svg
          xmlns="http://www.w3.org/2000/svg"
          class="h-10 w-10"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
          stroke-width="1.5"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M17 8h2a2 2 0 012 2v6a2 2 0 01-2 2h-2v4l-4-4H9a1.994 1.994 0 01-1.414-.586m0 0L11 14h4a2 2 0 002-2V6a2 2 0 00-2-2H5a2 2 0 00-2 2v6a2 2 0 002 2h2v4l.586-.586z"
          />
        </svg></span
      >
      <p class="p-4 text-2xl text-wrap font-medium text-pink-400 mt-3">
        Relacionamentos
      </p>
      <p class="p-4 text-lg text-justify text-gray-400">
        Pode ser um desafio e tanto estabelecer relações interpessoais. Seja no
        campo afetivo, profissional, familiar os conflitos podem ser
        inevitáveis. Terminar um relacionamento amoroso, pode desencadear muita
        dor e emoções confusas. A psicoterapia pode cumprir um papel crucial em
        te ajudar a desenvolver habilidades interpessoais para lidar com as
        relações da sua vida.
      </p>
    </div>

    <div
      class="p-10 flex flex-col items-center text-center group md:lg:xl:border-r hover:bg-slate-50 cursor-pointer"
    >
      <span
        class="p-5 rounded-full bg-pink-400 text-white shadow-lg shadow-gray-200"
        ><svg
          xmlns="http://www.w3.org/2000/svg"
          class="h-10 w-10"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
          stroke-width="1.5"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M13 7h8m0 0v8m0-8l-8 8-4-4-6 6"
          />
        </svg></span
      >
      <p class="p-4 text-2xl text-wrap font-medium text-pink-400 mt-3">
        Autoestima
      </p>
      <p class="p-4 text-lg text-justify text-gray-400">
        Você gostaria de ter uma relação melhor consigo mesma? Ao longo da vida
        podemos passar por experiências que nos fazem acreditar que não somos
        boas o suficiente, que somos ruins ou indignas de amor. Deixamos de
        reconhecer o nosso valor e perdemos a capacidade de nos amar. O processo
        psicoterapêutico poderá te ajudar a olhar com mais carinho para si
        mesma, reconhecer suas potencialidades, construir autoconfiança e
        respeitar a pessoa que você é.
      </p>
    </div>
  </div>
</div>
<div class="flex justify-center p-10">
  <CallToActionBtn />
</div>
