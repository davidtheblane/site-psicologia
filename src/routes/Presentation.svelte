<script>
  import CallToActionBtn from "../components/CallToActionBtn.svelte";
</script>

<section
  class="flex flex-col w-screen px-4 items-center bg-gradient-to-b from-white to-pink-200"
>
  <div class="flex flex-col my-2 justify-center items-center">
     
    <div class="w-48 flex items-center justify-center my-6 relative">
      <img
        class="z-10 md:w-auto rounded-full shadow-md border-8 border-white"
        src="/profileSquare.svg"
        alt="profile"
      />
      <div class="absolute w-48 h-10 text-center border-8 rounded-full border-pink-400 -bottom-8 bg-pink-400">
        <p class="text-white">CRP-00099909</p>
    </div>
    </div>
    <h1 class="text-5xl text-pink-400 text-center p-5">
      Terapia Online<br />
      <span class="font-bold text-4xl text-pink-400"> para mulheres</span>
    </h1>

    <h1 class="p-5 text-lg text-gray-500 text-center">
      São muitos os dilemas enfrentados por nós mulheres, inevitavelmente em
      alguns momentos nos vemos confusas em nossos pensamentos e emoções, mas
      você não precisa lidar com isso sozinha, eu estou aqui para ajudar.
    </h1>

    <CallToActionBtn />
  </div>
</section>
