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
            <li class="mr-3"><NuxtLink to="/about" class="inline-block text-gray-400 no-underline hover:text-purple-700 hover:text-underline py-2 px-4" href="#">О нас</Nuxtlink></li>
            <li class="mr-3"><a class="inline-block py-2 px-4 text-white no-underline" href="#">Контакты</a></li>
          </ul>
        </div>
      </div>
    </nav>

    <section class="bg-purple-700 border-b py-12 ">
      <div class="container mx-auto flex flex-wrap items-center justify-between pb-22">
        <h2 class="select-none w-full my-1 text-4xl text-center text-white">Наши специалисты известны по всему миру</h2>
        <h2 class="select-none w-full my-1 text-2xl text-center text-gray-300">Ты можешь проконсультироваться прямо сейчас!</h2>
        </div>
    </section>

    <section class="bg-gray-100 border-b py-8">
        <h2 class="select-none w-full my-2 text-3xl text-center text-black">Свяжись с нами:</h2>
      <div class="body">
        <br/>
        <span>
            <div v-for="user in users" :key="user.id">
          <div href="" class="group cursor-pointer group-hover:text-white hover:bg-purple-800 p-5 max-w-sm mx-auto bg-white rounded-xl shadow-md flex items-center space-x-5 m-4 transform hover:scale-110 transition delay-50 duration-300 ease-in-out">
            <div class="flex-shrink-0 "><img class="h-14 w-14 rounded-full" :src="user.avatar" alt="ChitChat Logo" />
            </div>
            <div>
              <div class="group-hover:text-white text-xl font-medium text-black">{{ user.first_name }} {{ user.last_name }}</div>
              <p class="group-hover:text-white text-gray-500">Ведущий специалист</p>
            </div> 
          </div>
        </div>
        </span>
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
                <input class="block appearance-none placeholder-gray-500 border border-purple-800 rounded-md w-full py-3 px-4 text-gray-700 leading-5 focus:outline-none focus:ring-2 focus:ring-purple-800" placeholder="email@example.com">
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
import axios from "axios";
export default {
  data() {
    return {
      users: [],
    };
  },
  async mounted() {
    const { status, data } = await axios.get(
      "https://reqres.in/api/users?page=1"
    );
    this.users = data.data;
  },
};
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
