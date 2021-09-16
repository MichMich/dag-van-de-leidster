<template>
<div class="flex flex-col min-h-screen">
  <div class="items-center justify-center flex-1 w-screen bg-purple-700 sm:flex sm:bg-gray-200">
    <div class="relative sm:my-16">
      <div class="absolute hidden w-full h-full transform bg-pink-300 -rotate-6 rounded-xl sm:block" />
      <div class="relative text-white bg-purple-600 sm:max-w-xl sm:rounded-xl sm:shadow-xl">
        <div class="p-8 pb-8 sm:p-16">
          <h2 class="text-xl font-semibold text-purple-200 sm:text-2xl">Kindergarden Baarn</h2>
          <h1 class="mb-8 text-3xl font-extrabold sm:text-4xl">Dag van de Leidster</h1>
          <p class="text-lg text-purple-50">
            De Dag van de Leidster 2021 was ook dit keer mede dankzij jouw bijdrage een groot succes. Bedankt namens alle medewerkers van Kindergarden Baarn!
          </p>

        </div>
          <div class="p-8 pt-8 text-sm text-purple-200 bg-purple-800 sm:p-16 sm:rounded-b-xl">
            <h3 class="mb-2 text-lg font-bold text-purple-100">Wat gebeurt er met de bijdrage?</h3>
            <p>De oudercommissie Kindergarden Baarn heeft gezorgd voor de aanschaf van een passend cadeau. Het resterende opgebrachte geld is ter beschikking gesteld aan de medewerkers van de vestiging om gezamelijk iets leuks mee te doen.</p>
            <h3 class="mt-4 mb-2 text-lg font-bold text-purple-100">Heb je een vraag?</h3>
            <p>Stuur gerust een email naar <a href="mailto:ockgbaarn@gmail.com" class="font-bold text-white hover:underline">ockgbaarn@gmail.com</a>. <br class="hidden sm:block">We beantwoorden je vragen graag!</p>
          </div>
      </div>
    </div>
  </div>
  <div class="py-4 text-xs text-center text-purple-300 sm:text-gray-400">
    &copy;{{(new Date()).getFullYear()}} Oudercommissie Kindergarden Baarn
  </div>
</div>
</template>


