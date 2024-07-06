<script>
  import CallToActionBtn from "../components/CallToActionBtn.svelte";
</script>

<section
  class="flex flex-col h-full w-screen px-4 items-center bg-gradient-to-b from-white to-pink-200"
>
  <div class="flex flex-col my-2 justify-center items-center py-10">
    <h1 class="text-5xl text-pink-400 text-center p-5">
      Terapia Online<br />
      <span class="font-bold text-4xl text-pink-400"> para mulheres</span>
    </h1>
    <div class="w-48 flex items-center justify-center my-6 relative">
      <img
        class="z-10 md:w-auto rounded-full shadow-md border-8 border-white"
        src="/images/profileSquare.svg"
        alt="profile"
      />
      <div class="absolute text-sm -bottom-12 w-48 h-10 text-center">
        <p class="text-gray-400">Dayane Bartolomeu</p>

        <p class="text-gray-400">CRP-06/175725</p>
      </div>
    </div>
    <!-- <h1 class="text-5xl text-pink-400 text-center p-5">
      Terapia Online<br />
      <span class="font-bold text-4xl text-pink-400"> para mulheres</span>
    </h1> -->

    <h1 class="p-5 text-xl text-gray-500 text-center py-14">
      São muitos os dilemas enfrentados por nós mulheres, inevitavelmente em
      alguns momentos nos vemos confusas em nossos pensamentos e emoções, mas
      você não precisa lidar com isso sozinha, eu estou aqui para ajudar.
    </h1>

    <CallToActionBtn />
  </div>
</section>
