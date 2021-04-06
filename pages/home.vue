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
            <li class="mr-3"><a class="inline-block py-2 px-4 text-white no-underline" href="#">Главная</a></li>
            <li class="mr-3"><NuxtLink to="/about" class="inline-block text-gray-400 no-underline hover:text-purple-700 hover:text-underline py-2 px-4" href="#">О нас</NuxtLink></li>
            <li class="mr-3"><NuxtLink to="/contact" class="inline-block text-gray-400 no-underline hover:text-purple-700 hover:text-underline py-2 px-4" href="#">Контакты</Nuxtlink></li>
          </ul>
        </div>
      </div>
    </nav>

    <section class="bg-purple-700 border-b py-12 ">
      <div class="container mx-auto flex flex-wrap items-center justify-between pb-22">
        <h2 class="select-none w-full my-8 text-5xl text-center text-white">Где мы можем вам помочь?</h2>
        <div class="flex flex-1 flex-wrap max-w-4xl mx-auto items-center justify-between text-xl text-gray-200 font-bold">

          <span class="select-none w-1/2 p-18 md:w-auto items-center transform hover:scale-125 transition delay-50 duration-300 ease-in-out"><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1" d="M21 13.255A23.931 23.931 0 0112 15c-3.183 0-6.22-.62-9-1.745M16 6V4a2 2 0 00-2-2h-4a2 2 0 00-2 2v2m4 6h.01M5 20h14a2 2 0 002-2V8a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" />
          </svg>Работа</span>
          
          <span class="select-none w-1/2 p-8 md:w-auto items-center transform hover:scale-125 transition delay-50 duration-300 ease-in-out"><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1" d="M12 6.253v13m0-13C10.832 5.477 9.246 5 7.5 5S4.168 5.477 3 6.253v13C4.168 18.477 5.754 18 7.5 18s3.332.477 4.5 1.253m0-13C13.168 5.477 14.754 5 16.5 5c1.747 0 3.332.477 4.5 1.253v13C19.832 18.477 18.247 18 16.5 18c-1.746 0-3.332.477-4.5 1.253" />
          </svg>Обучение</span>

          <span class="select-none w-1/2 p-18 md:w-auto items-center transform hover:scale-125 transition delay-50 duration-300 ease-in-out"><svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1" d="M3.055 11H5a2 2 0 012 2v1a2 2 0 002 2 2 2 0 012 2v2.945M8 3.935V5.5A2.5 2.5 0 0010.5 8h.5a2 2 0 012 2 2 2 0 104 0 2 2 0 012-2h1.064M15 20.488V18a2 2 0 012-2h3.064M21 12a9 9 0 11-18 0 9 9 0 0118 0z" />
          </svg>Жизнь</span>

        </div>
      </div>
    </section>

    <section class="bg-gray-100 border-b py-8">
      <div class="container max-w-5xl mx-auto m-8">
        <h2 class="select-none w-full my-2 text-5xl leading-tight text-center text-gray-800">Быстро и просто!</h2>
        <div class="w-full mb-4">
          <div class="h-1 mx-auto gradient w-64 opacity-25 my-0 py-0 rounded-t"></div>
        </div>
        <div class="flex flex-wrap">
          <div class="w-2/6 sm:w-1/2 p-9">
            <h3 class="select-none text-3xl text-gray-800 font-bold leading-none mb-6">Справимся с любой задачей</h3>
            <p class="select-none text-gray-600 mb-8">
              Вы пишете дипломную работу? Завал на работе? Не беда!
              Мы поможем вам с любой задачей, стоит лишь написать сотрудникам и в ближайшее время получить наилучшее решение проблемы.
            </p>
          </div>
          <div class="select-none w-full sm:w-1/2 p-6">
            <img class="select-none" src="https://tavanasho.com/wp-content/uploads/2019/12/teamwork1.png" alt="">
          </div>
        </div>
      </div>
    </section>

    <section class="bg-gray-200 border-b py-8">
      <div class="container mx-auto flex flex-wrap pt-4 pb-12">
        <h2 class="select-none w-full my-2 text-5xl leading-tight text-center text-gray-800">Приступим</h2>
        <div class="select-none w-full mb-4">
          <div class="h-1 mx-auto gradient w-64 opacity-25 my-0 py-0 rounded-t"></div>
        </div>

        <div class="w-full md:w-1/3 p-6 flex flex-col flex-grow flex-shrink">
          <div class="flex-1 bg-white rounded-t rounded-b-none overflow-hidden shadow">
            <a href="#" class="flex flex-wrap no-underline hover:no-underline">
              <p class="w-full text-gray-600 text-xs md:text-sm px-6 mt-6"></p>
              <div class="w-full font-bold text-xl text-gray-800 px-6">Помощь в работе</div>
              <p class="text-gray-600 text-base px-6 py-2 mb-5">
                Напряжённый график? сдают нервы? Не понимаешь что происходит? Рабочее место в крошках от печенья?
                Не беда, наша команда сделает всё за вас.
              </p>
            </a>
          </div>
          <div class="flex-none mt-auto bg-white rounded-b rounded-t-none overflow-hidden shadow p-6">
            <div class="flex items-center justify-center">
              <button class="hover:text-gray-200 hover:bg-gray-800 bg-purple-800 mx-auto lg:mx-0 gradient2 text-white font-extrabold rounded my-6 py-4 px-8 shadow-lg transform hover:scale-125 transition delay-50 duration-300 ease-in-out">
                Выбрать
              </button>
            </div>
          </div>
        </div>

        <div class="w-full md:w-1/3 p-6 flex flex-col flex-grow flex-shrink">
          <div class="flex-1 bg-white rounded-t rounded-b-none overflow-hidden shadow">
            <a href="#" class="flex flex-wrap no-underline hover:no-underline">
              <p class="w-full text-gray-600 text-xs md:text-sm px-6 mt-6"></p>
              <div class="w-full font-bold text-xl text-gray-800 px-6">
                Помощь в обучении
              </div>
              <p class="text-gray-600 text-base px-6 py-2 mb-5">
                Экзамены? Дипломная работа? Сгорели учебники? Школа скукота? Друзья не делятся с вами жвачкой?  &#4448;
                Не беда, позвольте нам помочь.
              </p>
            </a>
          </div>
          <div class="flex-none mt-auto bg-white rounded-b rounded-t-none overflow-hidden shadow p-6">
            <div class="flex items-center justify-center">
              <button class="hover:text-gray-200 hover:bg-gray-800 bg-purple-800 mx-auto lg:mx-0 gradient2 text-white font-extrabold rounded my-6 py-4 px-8 shadow-lg transform hover:scale-125 transition delay-50 duration-300 ease-in-out">
                Выбрать
              </button>
            </div>
          </div>
        </div>

        <div class="w-full md:w-1/3 p-6 flex flex-col flex-grow flex-shrink">
          <div class="flex-1 bg-white rounded-t rounded-b-none overflow-hidden shadow">
            <a href="#" class="flex flex-wrap no-underline hover:no-underline">
              <p class="w-full text-gray-600 text-xs md:text-sm px-6 mt-6"></p>
              <div class="w-full font-bold text-xl text-gray-800 px-6">Помощь в жизни
              </div><p class=" text-gray-600 text-base px-6 mb-5">
                Болит рука? Болит вторая рука? И даже третья? Покусал кабан-мутант?
                Не беда, давайте посмотрим что можно с этим сделать.
              </p>
            </a>
          </div>
          <div class="flex-none mt-auto bg-white rounded-b rounded-t-none overflow-hidden shadow p-6">
            <div class="flex items-center justify-center">
              <button class="hover:text-gray-200 hover:bg-gray-800 bg-purple-800 mx-auto lg:mx-0 gradient2 text-white font-extrabold rounded my-6 py-4 px-8 shadow-lg transform hover:scale-125 transition delay-50 duration-300 ease-in-out">
                Выбрать
              </button>
            </div>
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
