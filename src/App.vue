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
            <span class="text-white">Donderdag 16 september</span> is het de Dag van de Leidster 2021. Help jij mee om van deze dag een een bijzondere gebeurtenis te maken?
          </p>
          <p class="mt-4 text-purple-100">Via onderstaande knop kan je een financiele bijdrage doen. De oudercommissie van Kindergarden Baarn zorgt dat het met hulp van jouw bijdrage een mooi cadeau wordt gekocht voor alle medewerkers.</p>
          <a href="https://tikkie.me/pay/q8r5bso1kgai3trsi37a" target="_blank" class="flex items-center justify-center p-2 mt-10 text-xl font-bold text-center text-white uppercase duration-200 bg-pink-500 border-b-4 border-pink-700 rounded-lg shadow-lg hover:bg-pink-600 transition-color leading-wide">
            <svg viewBox="-71.27719571541195 -2.754207803167244 2641.836071858428 2564.2093798273245" xmlns="http://www.w3.org/2000/svg" class="w-12 h-12 mr-2">
              <g>
                <path fill="#53beb8" stroke="#ffffff" stroke-width="100" d="M1264.45 367.33c-486.52 0-879.52 394.42-879.52 881 0 163.29 44.15 316.06 123.4 447.21v26.14c0 298.32-219.18 394.94-219.18 394.94s309.8 3.23 473.81-142h.12c1.49 0 3.36-2.2 5.49-2.2s3.94 2.13 5.42 2.13h.2c140.18 105.72 308.77 151.87 490.26 151.87 486.59 0 881-393.06 881-879.59s-394.45-879.5-881.06-879.5" />
                <path fill="#fafdfa" d="M845.83 1352.51c-34.53 0-51.12-15.3-51.12-49.89 0-29.43 16.59-47.31 51.12-47.31h1.29V1231c0-14.07 0-29.44 1.29-44.73h-2.58c-34.53 0-51.12-15.43-51.12-50 0-29.43 16.59-47.31 51.12-47.31h16.65a441.28 441.28 0 0 1 110-202.15C1058.24 796 1165.7 751.17 1295 751.17c75.52 0 142 15.36 198.28 47.37 57.57 30.72 85.71 67.77 87 110 0 55-34.53 104.89-84.42 106.18-24.33 1.29-52.47-9-84.42-28.14q-48-30.69-115.21-30.73c-72.94 0-130.51 25.63-172.72 75.52a270.34 270.34 0 0 0-35.82 57.57h195.76c32 0 51.18 17.88 51.18 47.31 0 34.53-19.17 50-51.18 50h-220.11c-1.29 15.29-2.58 30.66-2.58 44.73v24.33h148.44c30.73 0 50 17.88 50 47.31 0 34.59-19.23 50-50 50h-127.92a260.44 260.44 0 0 0 42.21 72.94c42.21 49.89 99.85 75.45 172.72 75.45 44.79 0 83.19-10.26 115.21-29.43 31.95-20.46 60.09-30.66 84.42-29.43 49.89 1.29 84.42 52.47 84.42 104.94-1.29 43.5-29.43 80.55-87 112.56-56.28 30.73-122.83 46.09-198.28 46.09-129.28 0-236.74-44.79-322.45-135.61-57.58-61.44-94.69-134.37-113.86-217.51h-12.84z" />
              </g>
            </svg>
            Doe een bijdrage
          </a>
          <div class="relative p-4 mt-2 text-sm text-center text-purple-100 bg-purple-700 rounded-lg">
            Liever contant? Er staat een donatiebox naast <br class="hidden sm:block">het koffieapparaat in de vestiging!
          </div>
        </div>
          <div class="p-8 pt-8 text-sm text-purple-200 bg-purple-800 sm:p-16 sm:rounded-b-xl">
            <h3 class="mb-2 text-lg font-bold text-purple-100">Wat gebeurt er met de bijdrage?</h3>
            <p>Het geld wordt ingezameld middels een Tikkie op rekening van Michael Teeuw, voorzitter van de oudercommissie Kindergarden Baarn. De oudercommissie zorgt voor de aanschaf van een passend cadeau. Eventueel resterend opgebracht geld wordt ter beschikking gesteld aan de medewerkers van de vestiging om gezamelijk iets leuks mee te doen.</p>
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


