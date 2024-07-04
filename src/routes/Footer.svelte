<script>
  const sections = [
    {name: 'Artigos',     link: '#artigos'},
    {name: 'Beneficios',  link: '#beneficios'},
    {name: 'Depoimentos', link: '#depoimentos'},
    {name: 'FAQ',         link: '#faq'},
    {name: 'Servicos',    link: '#servicos'},
    {name: 'Sobre',       link: '#sobre'},
]

const contactForms = [
  {name: 'Email', link: 'mailto:psy.dayanebartolomeu@gmail.com', icon: "fa-regular fa-envelope-open"},
  {name: 'Instagram', link: 'https://www.instagram.com/psi.dayanebartolomeu/', icon: "fab fa-instagram"},
  {name: 'Whatsapp', link: 'https://wa.me/5511947922772', icon: "fa-brands fa-whatsapp"},

]
</script>

<footer class="relative bg-pink-100 pt-8 pb-6">
  <div class="container mx-auto px-4">
    <div class="flex flex-wrap text-left lg:text-left">
      <div class="w-full lg:w-6/12 px-4">
        <h4 class="text-3xl fonat-semibold text-gray-700">Entre em contato</h4>
        <h5 class="text-lg mt-0 mb-2 text-gray-500">
          Você consegue me encontrar nas plataformas abaixo.
        </h5>
        <div class="mt-6 lg:mb-0 mb-6">
          {#each contactForms as contact}
          <button class="bg-white text-lightBlue-400 shadow-lg font-normal h-10 w-10 items-center justify-center align-center rounded-full outline-none focus:outline-none mr-2" type="button">
            <a href={contact.link} target="_blank"> 
              <i class={contact.icon}></i>
            </a>
          </button>
         {/each}
        </div>
      </div>
      <div class="w-full lg:w-6/12 px-4">
        <div class="flex flex-wrap items-top mb-6">
          <div class="w-full lg:w-4/12 px-4 ml-auto">
            <span class="block uppercase text-gray-500 text-sm font-semibold mb-2">Navegue</span>
            <ul class="list-unstyled">
              {#each sections as section}
              <li>
                <a class="text-gray-400 hover:text-pink-500 font-semibold block pb-2 text-sm" href={section.link}>{section.name}</a>
              </li>
             {/each}
            </ul>
          </div>
        </div>
      </div>
    </div>
    <hr class="my-6">
    <div class="flex flex-wrap items-center md:justify-between justify-center">
      <div class="w-full px-4 mx-auto text-center">
        <div class="text-sm text-gray-500 py-1">
            <p>Copyright © <span id="get-current-year">2024 </span> - Todos os direitos reservados</p>
          <a href="/" class="text-gray-500">Dayane Bartolomeu | CRP 06/175725</a>.
        </div>
      </div>
    </div>
  </div>
</footer>
