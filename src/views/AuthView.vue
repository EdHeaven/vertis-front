<template>
  <body class="h-screen bg-gray-100">
    <div class="" width="400">
      <div class="flex justify-center items-center h-screen w-full">
        <div class="block p-6 rounded-xl shadow-lg bg-white max-w-sm">
          <form>
            <div class="form-group mb-6">
              <label for="exampleInputEmail2" class="form-label inline-block mb-2 text-gray-700">Логин</label>
              <input type="email" class="form-control
                block
                w-full
                px-3
                py-1.5
                text-base
                font-normal
                text-gray-700
                bg-white bg-clip-padding
                border border-solid border-gray-300
                rounded-xl
                transition
                ease-in-out
                m-0
                focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none" id="exampleInputEmail2"
                aria-describedby="emailHelp" placeholder="Почта">
            </div>
            <div class="form-group mb-6">
              <label for="exampleInputPassword2" class="form-label inline-block mb-2 text-gray-700">Пароль</label>
              <input type="password" class="form-control block
                w-full
                px-3
                py-1.5
                text-base
                font-normal
                text-gray-700
                bg-white bg-clip-padding
                border border-solid border-gray-300
                rounded-xl
                transition
                ease-in-out
                m-0
                focus:text-gray-700 focus:bg-white focus:border-blue-600 focus:outline-none" id="exampleInputPassword2"
                placeholder="Пароль">
            </div>
            <div class="flex justify-between items-center mb-6">
              <div class="form-group form-check">
                <input type="checkbox"
                  class="form-check-input appearance-none h-4 w-4 border border-gray-300 rounded-sm bg-white checked:bg-blue-600 checked:border-blue-600 focus:outline-none transition duration-200 mt-1 align-top bg-no-repeat bg-center bg-contain float-left mr-2 cursor-pointer"
                  id="exampleCheck2">
                <label class="form-check-label inline-block text-gray-800" for="exampleCheck2">Запомнить пароль</label>
              </div>
              <a href="#!"
                class="text-blue-600 hover:text-blue-700 focus:text-blue-700 transition duration-200 ease-in-out ml-4">Забыли пароль?</a>
            </div>
            <a href="/new">
            <button type="submit" class="
              w-full
              px-6
              py-2.5
              bg-blue-800
              text-white
              font-medium
              text-xs
              leading-tight
              uppercase
              rounded-xl
              shadow-md
              hover:bg-blue-700 hover:shadow-lg
              focus:bg-blue-700 focus:shadow-lg focus:outline-none focus:ring-0
              active:bg-blue-800 active:shadow-lg
              transition
              duration-150
              ease-in-out">Войти</button></a>
            <p class="text-gray-800 mt-6 text-center">Нет аккаунта на Vertis? <a href="/reg"
                class="text-blue-600 hover:text-blue-700 focus:text-blue-700 transition duration-200 ease-in-out">Регистрация</a>
            </p>
          </form>
        </div>
        </div>
      </div>
  </body>
</template>
