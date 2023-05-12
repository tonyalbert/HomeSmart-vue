<script>
import Dots from '../assets/img/dots.svg'
import Partner1 from '../assets/img/partner1.svg'
import Partner2 from '../assets/img/partner2.svg'
import Partner3 from '../assets/img/partner3.svg'
import Partner4 from '../assets/img/partner4.svg'
import Partner5 from '../assets/img/partner5.svg'
import Partner6 from '../assets/img/partner6.svg'
import Partner7 from '../assets/img/partner7.svg'
import Table from '../assets/img/table.png'
import Lamp from '../assets/img/lamp.png'
import App from '../assets/img/app.svg';


export default {
    data() {
        return{
            dots: Dots,
            partner1: Partner1,
            partner2: Partner2,
            partner3: Partner3,
            partner4: Partner4,
            partner5: Partner5,
            partner6: Partner6,
            partner7: Partner7,
            table: Table,
            lamp: Lamp,
            app: App
        }

    }
}
</script>

<template>
    <div class="grid gap-12 sm:gap-16 md:gap-24 lg:gap-32 px-8 overflow-hidden">

        <a href="github.com/tonyalbert" target="_blank" class="
        py-2
        px-6
        bg-amber-400
        mx-auto
        my-12
        flex
        gap-2
        shadow-xl
        dark:text-neutral-900
        focus:outline-none
        focus-visible:ring-4
        ring-neutral-900
        rounded-sm
        ring-offset-4
        ring-offset-white
        ">
            <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
            <path stroke-linecap="round" stroke-linejoin="round" d="M3 16.5v2.25A2.25 2.25 0 005.25 21h13.5A2.25 2.25 0 0021 18.75V16.5M16.5 12L12 16.5m0 0L7.5 12m4.5 4.5V3" />
            </svg>

            <span>Baixe os appss</span>
        </a>

    <section aria-labelledby="qualities" class="relative">
    <img :src="dots" 
      class="
      hidden
      lg:block
      absolute
      top-1/2
      -translate-y-1/2
      -left-24
      xl:-left-7
      " 
      alt="dots" aria-hidden="true">
    <img :src="dots" 
      class="
      hidden
      lg:block
      absolute
      top-1/2
      -translate-y-1/2
      -right-24
      xl:-right-7
      "
      alt="dots" aria-hidden="true">
    <h2 id="qualities" class="sr-only">Our Qualities</h2>
    <div
      class="container
        mx-auto
        max-w-5xl
        flex
        gap-12
        flex-wrap
        items-start
        justify-center
        md:justify-between
      ">
      <div 
        class="
        grid
        gap-4
        justify-items-center
        text-center
        md:flex-1
      ">
        <div 
          class="
            rounded-full
            border-8
            border-amber-400
            p-4
          ">
          <svg xmlns="http://www.w3.org/2000/svg" class="h-14 w-14" fill="none" viewBox="0 0 24 24" stroke="currentColor"
            stroke-width="2">
            <path stroke-linecap="round" stroke-linejoin="round"
              d="M12 15v2m-6 4h12a2 2 0 002-2v-6a2 2 0 00-2-2H6a2 2 0 00-2 2v6a2 2 0 002 2zm10-10V7a4 4 0 00-8 0v4h8z" />
          </svg>
        </div>
        <h3 class="text-3xl font-bold">Seguro</h3>
        <p>Nossos produtos são seguros e privados desde o início</p>
      </div>
      <div
      class="
        grid
        gap-4
        justify-items-center
        text-center
        md:flex-1
        ">
        <div 
          class="
          rounded-full
          border-8
          border-amber-400
          p-4
          ">
          <svg xmlns="http://www.w3.org/2000/svg" class="h-14 w-14" fill="none" viewBox="0 0 24 24" stroke="currentColor"
            stroke-width="2">
            <path stroke-linecap="round" stroke-linejoin="round" d="M13 10V3L4 14h7v7l9-11h-7z" />
          </svg>
        </div>
        <h3 class="text-3xl font-bold">Eficaz</h3>
        <p>
          Sinta-se bem com sua carteira e com o meio ambiente
        </p>
      </div>
      <div 
        class="
        grid
        gap-4
        justify-items-center
        text-center
        md:flex-1
        ">
        <div 
          class="
          rounded-full
          border-8
          border-amber-400
          p-4
          ">
          <svg xmlns="http://www.w3.org/2000/svg" class="h-14 w-14" fill="none" viewBox="0 0 24 24" stroke="currentColor"
            stroke-width="2">
            <path stroke-linecap="round" stroke-linejoin="round"
              d="M9 12l2 2 4-4M7.835 4.697a3.42 3.42 0 001.946-.806 3.42 3.42 0 014.438 0 3.42 3.42 0 001.946.806 3.42 3.42 0 013.138 3.138 3.42 3.42 0 00.806 1.946 3.42 3.42 0 010 4.438 3.42 3.42 0 00-.806 1.946 3.42 3.42 0 01-3.138 3.138 3.42 3.42 0 00-1.946.806 3.42 3.42 0 01-4.438 0 3.42 3.42 0 00-1.946-.806 3.42 3.42 0 01-3.138-3.138 3.42 3.42 0 00-.806-1.946 3.42 3.42 0 010-4.438 3.42 3.42 0 00.806-1.946 3.42 3.42 0 013.138-3.138z" />
          </svg>
        </div>
        <h3 class="text-3xl font-bold">Comprovado</h3>
        <p>
          Liderando o mundo Smart Home por 10 anos
        </p>
      </div>
    </div>
  </section>
  <section aria-labelledby="partners" class="text-center grid gap-8 place-items-center">
    <div class="grid gap-4">
      <h2 id="partners" class="text-4xl font-bold text-amber-400">Nossos Parceiros</h2>
      <p class="w-full max-w-lg">Fizemos parceria com centenas de marcas de casas inteligentes para ajudá-lo a criar uma casa inteligente que atenda às suas necessidades e não o prenda.</p>
    </div>
    <div class="flex flex-wrap justify-center gap-8 md:gap-x-16 max-w-2xl mx-auto">
      <div class="p-4 bg-white dark:bg-neutral-600 shadow-md dark:shadow-xl rounded-md">
        <img :src="partner1" alt="Partner" class="h-16 w-16">
      </div>
      <div class="p-4 bg-white dark:bg-neutral-600 shadow-md dark:shadow-xl rounded-md">
        <img :src="partner2" alt="Partner" class="h-16 w-16">
      </div>
      <div class="p-4 bg-white dark:bg-neutral-600 shadow-md dark:shadow-xl rounded-md">
        <img :src="partner3" alt="Partner" class="h-16 w-16">
      </div>
      <div class="p-4 bg-white dark:bg-neutral-600 shadow-md dark:shadow-xl rounded-md">
        <img :src="partner4" alt="Partner" class="h-16 w-16">
      </div>
      <div class="p-4 bg-white dark:bg-neutral-600 shadow-md dark:shadow-xl rounded-md">
        <img :src="partner5" alt="Partner" class="h-16 w-16">
      </div>
      <div class="p-4 bg-white dark:bg-neutral-600 shadow-md dark:shadow-xl rounded-md">
        <img :src="partner6" alt="Partner" class="h-16 w-16">
      </div>
      <div class="p-4 bg-white dark:bg-neutral-600 shadow-md dark:shadow-xl rounded-md">
        <img :src="partner7" alt="Partner" class="h-16 w-16">
      </div>
    </div>
  </section>
  <section aria-labelledby="home" class="relative">
    <div class="flex flex-wrap-reverse gap-8 justify-center">
      <div class="flex gap-6 flex-wrap flex-col items-start lg:justify-center">
        <div class="flex flex-wrap flex-col items-start gap-2">
          <h2 class="text-4xl font-bold">Relaxe, você está em casa!</h2>
          <p class="max-w-md">Todo os nossos produtos inclui entradas tradicionais para que você possa integrar nossos produtos em sua casa da melhor maneira para todos.</p>
        </div>
        <a href="#" 
          class="
            py-2
            px-6
            bg-amber-400
            dark:text-neutral-900
            flex
            gap-2
            shadow-xl
            hover:shadow-none
            transition-shadow
            focus:outline-none
            focus-visible:ring-4
            ring-neutral-900
            rounded-md
            ring-offset-4
            ring-offset-white
            dark:ring-amber-400
            dark:ring-offset-neutral-800
        ">
          Saiba mais
        </a>
      </div>
      <img :src="table" alt="Table">
    </div>
    <div 
      class="
        absolute
        -bottom-6
        -right-32
        -z-10
        aspect-square
        md:border-8
        border-amber-400
        rounded-full
        md:w-64
        lg:w-96
        xl:max-w-lg
    "></div>
    <div 
      class="
        bg-teal-900
        h-24
        xl:h-48
        -mx-8 
        mt-12
        xl:mt-0
        xl:absolute
        w-screen
        -bottom-8
        -z-10
    "></div>
  </section>
  <section aria-labelledby="contact" class="container mx-auto px-8 overflow-hidden">
      <div class="flex flex-wrap justify-center gap-12 md:gap-6 lg:gap-20">
        <div class="md:flex-1 md:max-w-sm relative">
          <img :src="lamp" alt="Lamp" class="mx-auto">
          <a href="#" 
            class="
              py-2
              px-6
              bg-amber-400
              dark:text-neutral-900
              w-max
              mx-auto
              mt-12
              md:mb-12
              flex
              gap-2
              shadow-xl
              hover:shadow-none
              transition-shadow
              focus:outline-none
              focus-visible:ring-4
              ring-neutral-900
              rounded-md
              ring-offset-4
              ring-offset-white
              dark:ring-amber-400
              dark:ring-offset-neutral-800
            ">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor"
              stroke-width="2">
              <path stroke-linecap="round" stroke-linejoin="round"
                d="M4 16v1a3 3 0 003 3h10a3 3 0 003-3v-1m-4-4l-4 4m0 0l-4-4m4 4V4" />
            </svg>
            <span>Baixe o app</span>
          </a>
          <img :src="app" alt="app" width="240" class="hidden md:block drop-shadow-xl absolute left-1/2 -translate-x-1/2 max-w-16 xl:max-w-xs">
          <div 
            class="
              absolute
              -bottom-18
              left-1/2
              -translate-x-1/2
              -z-10
              aspect-square
              md:border-8
              border-amber-400
              rounded-full
              md:w-72
              lg:w-96
            ">
          </div>
        </div>
        <form 
          class="
            relative
            border-8
            border-neutral-900
            p-6
            rounded-lg
            grid
            gap-8
            md:flex-1
            md:max-w-lg
            my-4
            md:my-12
            lg:my-16
            bg-white
            dark:bg-neutral-800
            w-full
        ">
      <h2 id="contact" class="text-3xl font-bold">Vamos nos conectar</h2>
      <div class="relative">
        <input type="text" id="name" 
          class="
            peer
            form-input
            w-full
            border-4
            border-amber-400
            rounded-md
            focus:ring-4
            dark:focus:ring-offset-2
            focus:ring-amber-400
            focus:border-amber-400
            focus:outline-none
            dark:bg-amber-400
            dark:text-neutral-900
            placeholder-transparent
        " 
        placeholder="Your Name"
        >
        <label for="name" 
        class="
          text-neutral-500
          text-sm
          font-bold
          uppercase
          absolute
          -top-4
          left-2
          -translate-y-1/2
          transition-all
          peer-placeholder-shown:left-4
          peer-placeholder-shown:top-1/2
          peer-placeholder-shown:text-neutral-900
          peer-focus:-top-4
          peer-focus:left-2
          peer-focus:text-neutral-600
          dark:peer-focus:text-neutral-300
        ">
          Seu Nome
        </label>
      </div>
      <div class="relative">
        <input type="email" id="email" 
          class="
            peer
            form-input
            w-full
            border-4
            border-amber-400
            rounded-md
            focus:ring-4
            dark:focus:ring-offset-2
            focus:ring-amber-400
            focus:border-amber-400
            focus:outline-none
            dark:bg-amber-400
            dark:text-neutral-900
            placeholder-transparent
          " 
        placeholder="Your Email">
        <label for="email" 
          class="
          text-neutral-500
          text-sm
          font-bold
          uppercase
          absolute
          -top-4
          left-2
          -translate-y-1/2
          transition-all
          peer-placeholder-shown:left-4
          peer-placeholder-shown:top-1/2
          peer-placeholder-shown:text-neutral-900
          peer-focus:-top-4
          peer-focus:left-2
          peer-focus:text-neutral-600
          dark:peer-focus:text-neutral-300
        ">
        Seu Email
        </label>
      </div>
      <div class="relative">
        <textarea name="content" id="content" cols="20" rows="5" 
        class="
          peer
          form-textarea
          resize-none
          w-full
          border-4
          border-amber-400
          rounded-md
          focus:ring-4
          dark:focus:ring-offset-2
          focus:ring-amber-400
          focus:border-amber-400
          focus:outline-none
          dark:bg-amber-400
          dark:text-neutral-900
          placeholder-transparent
        " 
        placeholder="How can we help?"></textarea>
        <label for="content" 
          class="
            text-neutral-500
            text-sm
            font-bold
            uppercase
            absolute
            -top-3
            left-2
            -translate-y-1/2
            transition-all
            peer-placeholder-shown:left-4
            peer-placeholder-shown:top-6
            peer-placeholder-shown:text-neutral-900
            peer-focus:-top-4
            peer-focus:left-2
            peer-focus:text-neutral-600
            dark:peer-focus:text-neutral-300
          ">
            Como podemos ajudar?
        </label>
      </div>
      <a role="menuitem" 
        class="
          py-2
          px-6
          bg-neutral-900
          text-white
          w-max
          shadow-xl
          hover:shadow-none
          transition-shadow
          focus:outline-none
          focus-visible:ring-4
          ring-neutral-900
          rounded-md
          ring-offset-4
          ring-offset-white
          dark:ring-offset-amber-400
        " 
        href="/"
        >
        Enviar
        </a>
      </form>
      </div>
    </section>

    </div>
</template>