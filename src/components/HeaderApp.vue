<script>
import Couch from '../assets/img/couch.png';
import App from '../assets/img/app.svg';

export default {
    data() {
        return {
            couch: Couch,
            app: App
        }
    }
}
</script>

<template>
    <header class="relative pt-16 md:pt-24 lg:pt-48">
        <div class="
        absolute
        inset-0
        bottom-8
        md:bottom-24
        xl:bottom-32
        -z-10
        bg-gradient-to-b
        from-amber-400
        to-amber-600
        "></div>
        <div class="container 
        mx-auto
        grid
        grid-rows-1
        place-items-end
        px-2
        ">
            <img :src="couch" class="
                row-start-1
                row-end-2
                col-start-1
                col-end-2
                mx-auto
            " alt="couch">
            <img :src="app" class="
                row-start-1
                row-end-2
                col-start-1
                col-end-2
                mx-auto
                w-40
                sm:w-52
                md:w-64
                lg:w-72
            " alt="app">
        </div>
    </header>
</template>