<script>
  import CallToActionBtn from "../components/CallToActionBtn.svelte";
</script>

<section class="flex flex-col w-screen px-4 items-center">
  <div class="flex flex-col my-4 justify-center items-center">
    <h1 class="text-4xl text-pink-400 text-center px-5 py-10">
      Terapia online para mulheres
    </h1>
    <div class="w-52 flex items-center my-6">
      <img
        class="md:w-auto rounded-full"
        src="src/images/profileSquare.svg"
        alt="profile"
      />
    </div>
    <h1 class="p-4 text-lg text-wrap text-gray-500 text-justify">
      São muitos os dilemas enfrentados por nós mulheres, inevitavelmente em
      alguns momentos nos vemos confusas em nossos pensamentos e emoções, mas
      você não precisa lidar com isso sozinha, eu estou aqui para ajudar.
    </h1>
  
    <CallToActionBtn/>
  </div>
</section>
