<script>
  import { Card } from "flowbite-svelte";
  import CallToActionBtn from "../components/CallToActionBtn.svelte";
</script>

<h2 class="text-4xl text-pink-400 text-center px-5 py-10">
  Essas são algumas das áreas que posso te ajudar
</h2>
<Card padding="none" size="xl" class="grid md:grid-cols-2 gap-4 mx-auto">
  <figure
    class="flex flex-col p-8 text-center bg-white rounded-t-lg md:rounded-t-none md:rounded-tl-lg"
  >
    <blockquote
      class="mb-4 max-w-2xl bg-pink-100 rounded-md p-6 text-gray-500 dark:text-gray-400"
    >
      <h3 class="text-lg font-semibold text-pink-500 dark:text-white">
        Ansiedade
      </h3>
      <p class="p-4 text-lg text-wrap text-gray-500 text-justify">
        Sabe aquela sensação de que algo ruim pode acontecer? Ou aquele
        turbilhão de pensamentos negativos que muitas vezes desencadeiam um medo
        e preocupação inexplicável?
      </p>
      <div class="text-gray-500">
        <a href="/">ler mais...</a>
      </div>
    </blockquote>
    <!-- <figcaption
      class="flex justify-center items-center space-x-3 rtl:space-x-reverse"
    > -->
    <!-- <img
        class="w-9 h-9 rounded-full"
        src="src/images/profileSquare.svg"
        alt="profile"
      /> -->
    <!-- <div class="text-pink-300">
        <a href="/">ler mais...</a>
      </div>
    </figcaption> -->
  </figure>
  <figure
    class="flex flex-col p-8 text-center bg-white rounded-t-lg md:rounded-t-none md:rounded-tl-lg"
  >
    <blockquote
      class="mb-4 max-w-2xl bg-pink-100 rounded-md p-6 text-gray-500 dark:text-gray-400"
    >
      <h3 class="text-lg font-semibold text-pink-500 dark:text-white">
        Depressão
      </h3>
      <p class="p-4 text-lg text-wrap text-gray-500 text-justify">
        A depressão é uma condição complexa que causa uma sensação profunda de
        desesperança e desamparo. O indivíduo sente uma tristeza e vazio
        contínuo durante a maior parte do dia.
      </p>
      <div class="text-pink-300">
        <a href="/">ler mais...</a>
      </div>
    </blockquote>
    <!-- <figcaption
      class="flex  justify-center items-center space-x-3 rtl:space-x-reverse"
    > -->
    <!-- <img
        class="w-9 h-9 rounded-full"
        src="src/images/profileSquare.svg"
        alt="profile"
      /> -->
    <!-- <div class="text-pink-300">
        <a href="/">ler mais...</a>
      </div>
    </figcaption> -->
  </figure>
  <figure
    class="flex flex-col p-8 text-center bg-white rounded-t-lg md:rounded-t-none md:rounded-tl-lg"
  >
    <blockquote
      class="mb-4 max-w-2xl bg-pink-100 rounded-md p-6 text-gray-500 dark:text-gray-400"
    >
      <h3 class="text-lg font-semibold text-pink-500 dark:text-white">
        Relacionamentos
      </h3>
      <p class="p-4 text-lg text-wrap text-gray-500 text-justify">
        Pode ser um desafio e tanto estabelecer relações interpessoais. Seja no
        campo afetivo, profissional, familiar os conflitos podem ser
        inevitáveis. Terminar um relacionamento amoroso, pode desencadear muita
        dor e emoções confusas.
      </p>
      <div class="text-pink-300">
        <a href="/">ler mais...</a>
      </div>
    </blockquote>
    <!-- <figcaption
      class="flex justify-center items-center space-x-3 rtl:space-x-reverse"
    > -->
    <!-- <img
    class="w-9 h-9 rounded-full"
    src="src/images/profileSquare.svg"
    alt="profile"
  /> -->
    <!-- <div class="text-pink-300">
        <a href="/">ler mais...</a>
      </div> -->
    <!-- </figcaption> -->
  </figure>
  <figure
    class="flex flex-col p-8 text-center bg-white rounded-t-lg md:rounded-t-none md:rounded-tl-lg"
  >
    <blockquote
      class="mb-4 max-w-2xl bg-pink-100 rounded-md p-6 text-gray-500 dark:text-gray-400"
    >
      <h3 class="text-lg font-semibold text-pink-500 dark:text-white">
        Autoestima
      </h3>
      <p class="p-4 text-lg text-wrap text-gray-500 text-justify">
        Você gostaria de ter uma relação melhor consigo mesma? Ao longo da vida
        podemos passar por experiências que nos fazem acreditar que não somos
        boas o suficiente, que somos ruins ou indignas de amor.
      </p>
      <div class="text-pink-300">
        <a href="/">ler mais...</a>
      </div>
    </blockquote>
    <!-- <figcaption
      class="flex justify-center items-center space-x-3 rtl:space-x-reverse"
    > -->
    <!-- <img
    class="w-9 h-9 rounded-full"
    src="src/images/profileSquare.svg"
    alt="profile"
  /> -->
    <!-- <div class="text-pink-300">
        <a href="/">ler mais...</a>
      </div> -->
    <!-- </figcaption> -->
  </figure>
</Card>
<div class="flex justify-center p-10">
  <CallToActionBtn />
</div>
