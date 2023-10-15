<img
    src="/img/mainPage1.png"
    alt=""
    class="absolute -z-10 bg-primary-col h-screen w-screen"
/>
<main class="w-screen h-screen flex items-center">
    <div class=" w-1/2 m-[2%]">
        <h1 class="text-white font-extrabold text-8xl tracking-widest m-5">
            AGRIWASTE
        </h1>
        <p
            class="text-white text-3xl w-[90%] tracking-wider [word-spacing:5px;] m-5 leading-10 py-5"
        >
            Join us in our mission to transform agricultural waste into valuable
            resources. Discover how our platform empowers farmers, fuels
            industries, and champions environmental sustainability. Be a part of
            the change today!
        </p>
        <button
            class="transition-all hover:scale-110 px-10 py-3 m-5 text-xl font-medium cursor-pointer border-2 rounded-md border-white bg-white text-primary-col"
            >As A Farmer</button
        >
        <button
            class="transition-all hover:scale-110 px-10 py-3 m-5 text-xl font-medium cursor-pointer border-2 rounded-md border-white bg-primary-col text-white"
            >As A Industrialist</button
        >
    </div>
    <div class=" w-[40%] m-[2%]">
        <img src="/img/mobileManMain.png" id="hoverImg" alt="" srcset="" />
    </div>
</main>

<style>
    #hoverImg {
        animation: hovering 5s linear infinite;
    }
    @keyframes hovering {
        0% {
            transform: translateY(-30px);
        }
        50% {
            transform: translateY(30px);
        }
        100% {
            transform: translateY(-30px);
        }
    }
</style>
