<script>
  import CallToActionBtn from "../components/CallToActionBtn.svelte";
</script>

<section
  class="flex flex-col w-screen px-4 items-center bg-gradient-to-b from-white to-pink-200"
>
  <div class="flex flex-col my-2 justify-center items-center">
    <div class="w-48 flex items-center my-6">
      <img
        class="md:w-auto rounded-full shadow-md border-8 border-white"
        src="src/images/profileSquare.svg"
        alt="profile"
      />
    </div>
    <h1 class="text-5xl text-pink-400 text-center p-5">
      Terapia Online <br> <span class="font-bold text-4xl text-pink-400"> para mulheres</span>
    </h1>

    <h1 class="p-5 text-lg text-gray-500 text-center">
      São muitos os dilemas enfrentados por nós mulheres, inevitavelmente em
      alguns momentos nos vemos confusas em nossos pensamentos e emoções, mas
      você não precisa lidar com isso sozinha, eu estou aqui para ajudar.
    </h1>

    <CallToActionBtn />
  </div>
</section>
