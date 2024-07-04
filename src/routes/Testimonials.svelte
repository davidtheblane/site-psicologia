<script>
    const starNumber = [1, 2, 3, 4, 5];
    const testimonials = [
        {
            text: "Eu tinha preconceito com terapia online, achava que seria impessoal, mas me surpreendi de uma forma muito gratificante. A Dayane é uma profissional muito acolhedora, que me fez esquecer que estava conversando através de uma tela. Me ajudou a reduzir os meus sintomas de ansiedade. Quando comecei a terapia com ela, eu tomava 3 tipos de medicação diferente para a minha ansiedade, hoje não tomo mais nenhuma.",
            author: "B",
        },
        {
            text: "Eu lembro da minha primeira sessão com ela, eu chorava tanto que mal conseguia falar, mas ela só ficou ali e acolheu minha dor. Eu estava completamente perdida sobre o que iria fazer da minha vida, agora eu tenho objetivos e trabalhamos muito para que eu possa alcançá-los.",
            author: "L",
        },
        {
            text: "Antes de conhecer a Dayane eu já tinha passado com outros psicólogos, mas nunca ficava mais do que 3 meses, ás vezes bem menos tempo, mas com ela foi diferente, eu senti que estava realmente sendo ouvida, e atualmente estamos trabalhando juntas há pouco mais de 1 ano, e sem previsão para encerrar, porque eu realmente gosto muito do meu tempo com ela.",
            author: "J",
        },
        {
            text: "Uma ótima profissional, tem me ajudado muito nas minhas questões. Eu indico o seu trabalho porque acredito que ela possa ajudar outras pessoas, como tem me ajudado.",
            author: "H",
        },
        {
            text: "Quando eu conheci a Dayane eu estava muito fragilizada, tinha acabado de sair de um relacionamento de anos, e não acreditava que seria possível seguir em frente, sei que ainda tem coisas a serem trabalhadas, mas posso dizer hoje que é possível seguir em frente. Deixei a dependência emocional para trás e tornei a mim mesma minha prioridade.",
            author: "A",
        },
        {
            text: "Meu principal critério era fazer terapia com uma psicóloga preta, e quando eu conheci a Dayane, tive certeza de que seria ela. É bom poder falar com alguém que entende intimamente o que eu sinto e falar sobre gênero e raça é algo importante para mim, porque é o que me atravessa. Só tenho a agradecer por essa profissional atenciosa que ela é.",
            author: "R",
        },
        {
            text: "Não há nada que pague pelo alívio que eu sinto hoje, antes vivia me sentindo sobrecarregada e sem saber como mudar essa situação. Aprendi na terapia a dizer 'não' e não me sentir culpada por isso. A Dayane foi a profissional que me ajudou nesse processo, ela é atenciosa, empática e me tratou com muito respeito e paciência.",
            author: "A",
        },
    ];
</script>

<section id="depoimentos" class="mx-auto px-10">
    <h2 class="section-title">Depoimentos</h2>
    <swiper-container
        class="flex flex-col w-full py-10 justify-center items-center gap-8"
        pagination="true"
        pagination-type="progressbar"
        navigation="true"
    >
        {#each testimonials as testimonial}
            <swiper-slide
                class="swiper-slide items-center justify-center group bg-white border border-solid border-gray-200 rounded-2xl p-6 transition-all duration-500 w-full hover:border-gray-400 slide-active:border-gray-300"
            >
                <div
                    class="flex flex-row my-6 pl-12 gap-2 text-amber-500 transition-all duration-500 group-hover:text-pink-400 swiper-slide-active:text-indigo-600"
                >
                    {#each starNumber as star}
                        <i class="fa-solid fa-star" style="color: #f4bd00;"></i>
                        <!-- <svg
                            class="w-5 h-5"
                            viewBox="0 0 18 17"
                            fill="none"
                            xmlns="http://www.w3.org/2000/svg"
                        >
                            <path
                                d="M8.10326 1.31699C8.47008 0.57374 9.52992 0.57374 9.89674 1.31699L11.7063 4.98347C11.8519 5.27862 12.1335 5.48319 12.4592 5.53051L16.5054 6.11846C17.3256 6.23765 17.6531 7.24562 17.0596 7.82416L14.1318 10.6781C13.8961 10.9079 13.7885 11.2389 13.8442 11.5632L14.5353 15.5931C14.6754 16.41 13.818 17.033 13.0844 16.6473L9.46534 14.7446C9.17402 14.5915 8.82598 14.5915 8.53466 14.7446L4.91562 16.6473C4.18199 17.033 3.32456 16.41 3.46467 15.5931L4.15585 11.5632C4.21148 11.2389 4.10393 10.9079 3.86825 10.6781L0.940384 7.82416C0.346867 7.24562 0.674378 6.23765 1.4946 6.11846L5.54081 5.53051C5.86652 5.48319 6.14808 5.27862 6.29374 4.98347L8.10326 1.31699Z"
                                fill="currentColor"
                            />
                        </svg> -->
                    {/each}
                </div>
                <p
                    class="text-base text-justify text-gray-400 leading-6 h-full mx-12 my-6"
                >
                    "{testimonial.text}"
                </p>
                <div class="flex flex-row pr-12 justify-end gap-5">
                    <div class="patient">
                        <h5
                            class="text-gray-400 font-medium transition-all duration-500 group-hover:text-pink-400 swiper-slide-active:text-indigo-600"
                        >
                            {testimonial.author}
                        </h5>
                        <span
                            class="text-sm leading-6 text-gray-400 transition-all duration-500 group-hover:text-pink-400"
                            >Paciente</span
                        >
                    </div>
                    <img
                        class="w-12"
                        src="/src/images/avatar1.svg"
                        alt="avatar"
                    />
                </div>
            </swiper-slide>
        {/each}
    </swiper-container>
</section>

<style>
    /* .swiper-scrollbar-horizontal {
        --swiper-scrollbar-bg-color: rgba(0, 0, 0, 0.1);
    } */
    /* .swiper-pagination-progressbar {
        background-color: gray;
    }
    .swiper-pagination-progressbar-fill {
        background-color: pink;
    }

    .swiper-notification {
        background-color: brown;
    } */

    /* swiper-slide::part(container)::part(pagination) {
        #swiper-pagination-progressbar {
        background-color: gray;
    } */
    /* .swiper-pagination-horizontal, */
</style>
