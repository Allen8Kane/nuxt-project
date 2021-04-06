<template>
<html>
  <head>
    <link href="https://unpkg.com/tailwindcss/dist/tailwind.min.css" rel="stylesheet"/>
    <link href="https://unpkg.com/@tailwindcss/custom-forms/dist/custom-forms.min.css" rel="stylesheet"/>
    <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
  </head>
  <body class="topnav">
    <nav>
      <div class="w-full container mx-auto flex flex-wrap items-center justify-between mt-0 px-2 py-2 lg:py-6">
        <div class="pl-4 flex items-center">
          <a class="text-white no-underline hover:no-underline text-2xl lg:text-4xl" href="#">Ask.Me</a>
        </div>
        <div>
          <ul class="list-reset lg:flex justify-end flex-1 items-center">
            <li class="mr-3"><NuxtLink to="/" class="inline-block text-gray-400 no-underline hover:text-purple-700 hover:text-underline py-2 px-4" href="#">Главная</Nuxtlink></li>
            <li class="mr-3"><a class="inline-block py-2 px-4 text-white no-underline" href="#">О нас</a></li>
            <li class="mr-3"><NuxtLink to="/contact" class="inline-block text-gray-400 no-underline hover:text-purple-700 hover:text-underline py-2 px-4" href="#">Контакты</Nuxtlink></li>
          </ul>
        </div>
      </div>
    </nav>

    <section class="bg-purple-700 border-b py-12 ">
      <div class="container mx-auto flex flex-wrap items-center justify-between pb-22">
        <h2 class="select-none w-full my-8 text-5xl text-center text-white">Кто мы?</h2>
        <div class="flex flex-1 flex-wrap max-w-4xl mx-auto items-center justify-between text-xl text-gray-200 font-bold">
        </div>
      </div>
    </section>

    <section class="bg-gray-100 border-b py-8">
      <div class="container max-w-5xl mx-auto m-8">
        <h2 class="select-none w-full my-2 text-5xl leading-tight text-center text-gray-800">Ask.Me</h2>
        <div class="w-full mb-4">
          <div class="h-1 mx-auto gradient w-64 opacity-25 my-0 py-0 rounded-t"></div>
        </div>
        <div class="flex flex-wrap">
          <div class="w-2/6 sm:w-1/2 p-9">
            <h3 class="select-none text-3xl text-gray-800 font-bold leading-none mb-6">Люди с желанием помочь!</h3>
            <p class="select-none text-gray-600 mb-8">
              Юная команда энтузиастов, готовых помочь с любым вопросом касающимся работы, учёбы или жизни.
            </p>
            <p class="select-none text-gray-600 mb-8">
              Хоть на рынке мы недавно, но вы можете убедиться в нашей надёжности благодаря многочисленным отзывом довольных пользователей услуг.
            </p>
            <p class="select-none text-gray-600 mb-8">
              С пламенем в глазах и апельсиновым соком в животах мы жаждем помогать людям не только по Республике Казахстан, но и по всем странам СНГ!
            </p>
          </div>
          <div class="select-none w-full py-8 sm:w-1/2 p-">
            <img class="select-none" src="https://www.victorianchamber.com.au/-/media/images/vcci/training/training-campaign-2019-icons-and-illustrations/vcci-training-illustration-3.png?la=en&hash=900158A06FD67B7A1CACE9B76783EBBD25EBB5C7" alt="">
          </div>
        </div>
      </div>
    </section>

    <section class="bg-purple-700 w-full mx-auto text-center pt-6 pb-12">
      <h2 class="w-full my-2 text-5xl leading-tight text-center text-white">
      Хотите узнать подробности?
      </h2>
      <h3 class="my-4 text-gray-300 text-2xl">Нажмите на кнопку и мы с вами свяжемся!</h3>
      <button class="shadow-xl animate-pulse hover:text-gray-200 hover:bg-gray-800 mx-auto lg:mx-0 bg-white hover-gray-200 text-gray-800 font-bold rounded my-6 py-4 px-8 transform hover:scale-125 transition delay-50 duration-500 ease-in-out">
      Связаться
      </button>
    </section>

    <footer class="bg-black ">
      <div class="container mx-auto mt-8 px-8">
        <div class="w-full flex flex-col md:flex-row py-6">
          <div class="flex-1 mb-6"><a class="text-white no-underline text-2xl lg:text-4xl" href="#">Ask.Me</a></div>

          <div class="flex-1"><p class="text-2xl font-bold text-gray-200 md:mb-6">Остались вопросы?</p>
            <ul class="list-reset mb-6">
              <li class="mt-2 inline-block mr-2 md:block md:mr-0">
                <input class="block appearance-none placeholder-gray-500 border border-emerald-400 rounded-md w-full py-3 px-4 text-gray-700 leading-5 focus:outline-none focus:ring-2 focus:ring-emerald-200" placeholder="email@example.com">
                <br>
              <textarea class="block appearance-none placeholder-gray-500 border border-purple-800 rounded-md w-full py-3 px-4 text-gray-700 leading-5 focus:outline-none focus:ring-2 focus:ring-purple-800" placeholder="Ваше сообщение"></textarea>
              <button class="hover:text-gray-200 hover:bg-gray-800 bg-purple-800 mx-auto lg:mx-0 gradient2 text-white font-extrabold rounded my-6 py-4 px-8 shadow-lg">
                Отправить
              </button>
              </li>
            </ul>
          </div>
          <div class="flex-1">
            <p class="uppercase font-extrabold text-gray-200 md:mb-6"></p>
            <ul class="list-reset mb-6">
            </ul>
          </div>
          <div class="flex-1">
            <p class="text-xl font-bold text-gray-200 md:mb-6">Соц. сети</p>
            <ul class="list-reset mb-6">
              <li class="mt-2 inline-block mr-2 md:block md:mr-0"><a href="#" class="font-light no-underline text-gray-300 hover:text-purple-700">Фейсбук</a>
              </li>
              <li class="mt-2 inline-block mr-2 md:block md:mr-0"><a href="#" class="font-light no-underline text-gray-300 hover:text-purple-700">Вконтакте</a>
              </li>
               <li class="mt-2 inline-block mr-2 md:block md:mr-0"><a href="#" class="font-light no-underline text-gray-300 hover:text-purple-700">Инстаграм</a>
              </li>
              <li class="mt-2 inline-block mr-2 md:block md:mr-0"><a href="#" class="font-light no-underline text-gray-300 hover:text-purple-700">Твиттер</a>
              </li>
            </ul>
          </div>
          <div class="flex-1">
            <p class="text-xl font-bold text-gray-200 md:mb-6">О компании</p>
            <ul class="list-reset mb-6"><li class="mt-2 inline-block mr-2 md:block md:mr-0">
              <a href="#" class="font-light no-underline hover:underline text-gray-300 hover:text-purple-700">Блог</a>
              </li><li class="mt-2 inline-block mr-2 md:block md:mr-0"><a href="#" class="font-light no-underline hover:underline text-gray-300 hover:text-purple-700">О нас</a>
              </li><li class="mt-2 inline-block mr-2 md:block md:mr-0"><a href="#" class="font-light no-underline hover:underline text-gray-300 hover:text-purple-700">Контакты</a>
              </li>
            </ul>
          </div>
          <p class="text-sm py-1 text-gray-300">© 2021 ООО «Ask.Me»</p>
        </div>
      </div>
    </footer>
  </body>
</html>
</template>

<script>

</script>

<style scoped>

       .topnav{
       background-color: rgb(10, 10, 10);
      }

      .browser-mockup {
        border-top: 2em solid rgba(230, 230, 230, 0.7);
        position: relative;
        height: 60vh;
      }
    
</style>
