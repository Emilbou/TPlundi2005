<template>
  <header>
    <div class="flex justify-between p-3 ring-1 ring-black">
      <div class="flex">
        <icon-logo />

        <nav>
          <RouterLink to="/" class="m-3 text-center font-bold text-black">ESTATERY</RouterLink>
        </nav>
      </div>
      <div class="mr-[400px] hidden lg:flex">
        <p class="mx-3">Buy</p>
        <p class="mx-3">Sell</p>
        <p class="mx-3">Manage proprety</p>
        <p class="mx-3">Ressources</p>
        <p class="mx-3">Rent</p>
      </div>
      <div class="lg:hidden">
        <svg
          width="24"
          height="24"
          viewBox="0 0 24 24"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
          class="relative h-6 w-6"
          preserveAspectRatio="xMidYMid meet"
        >
          <path d="M3 8H21" stroke="#111827" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"></path>
          <path d="M3 16H21" stroke="#111827" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"></path>
        </svg>
      </div>
      <div class="float-right hidden lg:flex">
        <button class="mx-7 rounded-md p-1 font-bold text-blue-500 ring-1">login</button>
        <button class="rounded-md bg-blue-500 p-1 font-bold text-white ring-1">SignUp</button>
      </div>
    </div>

    <div class="flex w-full flex-col items-start justify-start gap-2.5 sm:hidden md:hidden lg:hidden xl:hidden 2xl:hidden">
      <div class="relative flex flex-shrink-0 flex-grow-0 flex-col items-start justify-start gap-8 self-stretch">
        <p class="w-[343px] flex-shrink-0 flex-grow-0 self-stretch text-center text-4xl font-bold text-[#000929]">
          Search properties to rent
        </p>
        <div
          class="
            flex flex-shrink-0 flex-grow-0 flex-col
            items-center
            justify-center
            gap-2.5
            self-stretch
            rounded-lg
            border-[1.5px] border-indigo-100
            bg-white
            px-4
            py-3
          "
        >
          <div class="relative flex flex-shrink-0 flex-grow-0 items-center justify-between self-stretch">
            <p class="flex-shrink-0 flex-grow-0 text-left text-base font-medium text-gray-900 opacity-70">Search with Search Bar</p>
            <svg
              width="20"
              height="20"
              viewBox="0 0 20 20"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              class="h-5 w-5 flex-shrink-0 flex-grow-0"
              preserveAspectRatio="xMidYMid meet"
            >
              <circle cx="10" cy="10" r="10" fill="#E0E7FF"></circle>
              <path
                d="M6.5 8.25L10 11.75L13.5 8.25"
                stroke="#6366F1"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"
              ></path>
            </svg>
          </div>
        </div>
        <div class="relative h-16 flex-shrink-0 flex-grow-0 self-stretch">
          <div class="absolute left-[-1px] top-[-1px] h-16 w-[343px] rounded-lg bg-white"></div>
          <p class="absolute left-4 top-5 text-left text-base font-medium text-gray-500">Search location</p>
          <div class="absolute left-[286px] top-[7px] flex items-center justify-center gap-2 rounded-lg bg-indigo-500 p-3.5">
            <svg
              width="20"
              height="20"
              viewBox="0 0 20 20"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              class="relative h-5 w-5 flex-shrink-0 flex-grow-0"
              preserveAspectRatio="none"
            >
              <path
                d="M9.58341 17.5C13.9557 17.5 17.5001 13.9556 17.5001 9.58333C17.5001 5.21108 13.9557 1.66667 9.58341 1.66667C5.21116 1.66667 1.66675 5.21108 1.66675 9.58333C1.66675 13.9556 5.21116 17.5 9.58341 17.5Z"
                stroke="white"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"
              ></path>
              <path
                d="M18.3334 18.3333L16.6667 16.6667"
                stroke="white"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"
              ></path>
            </svg>
          </div>
        </div>
      </div>
    </div>

    <div class="hidden w-full flex-col items-start justify-start gap-2.5 sm:flex md:hidden lg:hidden xl:hidden 2xl:hidden">
      <div class="relative flex flex-shrink-0 flex-grow-0 flex-col items-start justify-start gap-8 self-stretch">
        <p class="w-[608px] flex-shrink-0 flex-grow-0 self-stretch text-center text-4xl font-bold text-[#000929]">
          Search properties to rent
        </p>
        <div
          class="
            flex flex-shrink-0 flex-grow-0 flex-col
            items-center
            justify-center
            gap-2.5
            self-stretch
            rounded-lg
            border-[1.5px] border-indigo-100
            bg-white
            px-4
            py-3
          "
        >
          <div class="relative flex flex-shrink-0 flex-grow-0 items-center justify-between self-stretch">
            <p class="flex-shrink-0 flex-grow-0 text-left text-base font-medium text-gray-900 opacity-70">Search with Search Bar</p>
            <svg
              width="20"
              height="20"
              viewBox="0 0 20 20"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              class="h-5 w-5 flex-shrink-0 flex-grow-0"
              preserveAspectRatio="xMidYMid meet"
            >
              <circle cx="10" cy="10" r="10" fill="#E0E7FF"></circle>
              <path
                d="M6.5 8.25L10 11.75L13.5 8.25"
                stroke="#6366F1"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"
              ></path>
            </svg>
          </div>
        </div>
        <div class="relative h-16 flex-shrink-0 flex-grow-0 self-stretch">
          <div class="absolute left-[-1px] top-[-1px] h-16 w-[608px] rounded-lg bg-white"></div>
          <p class="absolute left-4 top-5 text-left text-base font-medium text-gray-500">Search location</p>
          <div class="absolute left-[551px] top-[7px] flex items-center justify-center gap-2 rounded-lg bg-indigo-500 p-3.5">
            <svg
              width="20"
              height="20"
              viewBox="0 0 20 20"
              fill="none"
              xmlns="http://www.w3.org/2000/svg"
              class="relative h-5 w-5 flex-shrink-0 flex-grow-0"
              preserveAspectRatio="none"
            >
              <path
                d="M9.58329 17.5C13.9555 17.5 17.5 13.9556 17.5 9.58333C17.5 5.21108 13.9555 1.66666 9.58329 1.66666C5.21104 1.66666 1.66663 5.21108 1.66663 9.58333C1.66663 13.9556 5.21104 17.5 9.58329 17.5Z"
                stroke="white"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"
              ></path>
              <path
                d="M18.3333 18.3333L16.6666 16.6667"
                stroke="white"
                stroke-width="2"
                stroke-linecap="round"
                stroke-linejoin="round"
              ></path>
            </svg>
          </div>
        </div>
      </div>
    </div>
  </header>

  <div class="hidden w-full flex-col items-start justify-start gap-2.5 sm:hidden md:flex lg:hidden xl:hidden 2xl:hidden">
    <div class="relative flex flex-shrink-0 flex-grow-0 flex-col items-start justify-start gap-8 self-stretch">
      <p class="w-[736px] flex-shrink-0 flex-grow-0 self-stretch text-center text-4xl font-bold text-[#000929]">
        Search properties to rent
      </p>
      <div
        class="
          flex flex-shrink-0 flex-grow-0 flex-col
          items-center
          justify-center
          gap-2.5
          self-stretch
          rounded-lg
          border-[1.5px] border-indigo-100
          bg-white
          px-4
          py-3
        "
      >
        <div class="relative flex flex-shrink-0 flex-grow-0 items-center justify-between self-stretch">
          <p class="flex-shrink-0 flex-grow-0 text-left text-base font-medium text-gray-900 opacity-70">Search with Search Bar</p>
          <svg
            width="20"
            height="20"
            viewBox="0 0 20 20"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
            class="h-5 w-5 flex-shrink-0 flex-grow-0"
            preserveAspectRatio="xMidYMid meet"
          >
            <circle cx="10" cy="10" r="10" fill="#E0E7FF"></circle>
            <path d="M6.5 8.25L10 11.75L13.5 8.25" stroke="#6366F1" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"></path>
          </svg>
        </div>
      </div>
      <div class="relative h-16 flex-shrink-0 flex-grow-0 self-stretch">
        <div class="absolute left-[-1px] top-[-1px] h-16 w-[736px] rounded-lg bg-white"></div>
        <p class="absolute left-4 top-5 text-left text-base font-medium text-gray-500">Search location</p>
        <div class="absolute left-[679px] top-[7px] flex items-center justify-center gap-2 rounded-lg bg-indigo-500 p-3.5">
          <svg
            width="20"
            height="20"
            viewBox="0 0 20 20"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
            class="relative h-5 w-5 flex-shrink-0 flex-grow-0"
            preserveAspectRatio="none"
          >
            <path
              d="M9.58335 17.5C13.9556 17.5 17.5 13.9556 17.5 9.58333C17.5 5.21108 13.9556 1.66666 9.58335 1.66666C5.2111 1.66666 1.66669 5.21108 1.66669 9.58333C1.66669 13.9556 5.2111 17.5 9.58335 17.5Z"
              stroke="white"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
            ></path>
            <path
              d="M18.3334 18.3333L16.6667 16.6667"
              stroke="white"
              stroke-width="2"
              stroke-linecap="round"
              stroke-linejoin="round"
            ></path>
          </svg>
        </div>
      </div>
    </div>
  </div>

  <div class="relative hidden w-full flex-col items-start justify-start gap-10 sm:hidden md:hidden lg:flex xl:hidden 2xl:hidden">
    <div class="relative flex flex-shrink-0 flex-grow-0 items-start justify-start gap-8 self-stretch">
      <br />
      <p class="w-[608px] flex-grow text-left text-4xl font-bold text-[#000929]">Search properties to rent</p>
      <div
        class="
          flex
          w-[352px]
          flex-shrink-0 flex-grow-0 flex-col
          items-center
          justify-center
          gap-2.5
          rounded-lg
          border-[1.5px] border-indigo-100
          bg-white
          px-4
          py-3
        "
      >
        <div class="relative flex flex-shrink-0 flex-grow-0 items-center justify-between self-stretch">
          <p class="flex-shrink-0 flex-grow-0 text-left text-base font-medium text-gray-900 opacity-70">Search with Search Bar</p>
          <svg
            width="20"
            height="20"
            viewBox="0 0 20 20"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
            class="h-5 w-5 flex-shrink-0 flex-grow-0"
            preserveAspectRatio="xMidYMid meet"
          >
            <circle cx="10" cy="10" r="10" fill="#E0E7FF"></circle>
            <path d="M6.5 8.25L10 11.75L13.5 8.25" stroke="#6366F1" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"></path>
          </svg>
        </div>
      </div>
    </div>
    <div class="relative h-[104px] flex-shrink-0 flex-grow-0 self-stretch">
      <div class="absolute left-[-1px] top-[-1px] h-[104px] w-[992px] rounded-tr-lg rounded-bl-lg rounded-br-lg bg-white"></div>
      <div
        class="absolute left-[31px] top-[23px] flex w-[928px] items-center justify-center gap-8 rounded-tr-lg rounded-bl-lg rounded-br-lg"
      >
        <div class="relative flex flex-grow flex-col items-start justify-start gap-1">
          <p class="flex-shrink-0 flex-grow-0 text-left text-base font-medium text-gray-900 opacity-50">Location</p>
          <p class="h-7 w-[180px] flex-shrink-0 flex-grow-0 text-left text-lg font-bold text-gray-900">New York, USA</p>
        </div>
        <svg
          width="2"
          height="44"
          viewBox="0 0 2 44"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
          class="flex-shrink-0 flex-grow-0"
          preserveAspectRatio="xMidYMid meet"
        >
          <line x1="1.16669" y1="2.18557e-8" x2="1.16669" y2="44" stroke="#E0E7FF"></line>
        </svg>
        <div class="relative flex flex-grow flex-col items-start justify-start gap-1">
          <p class="flex-shrink-0 flex-grow-0 text-left text-base font-medium text-gray-900 opacity-50">When</p>
          <p class="h-7 w-[180px] flex-shrink-0 flex-grow-0 text-left text-lg font-bold text-gray-900">Select Move-in Date</p>
        </div>
        <svg
          width="2"
          height="44"
          viewBox="0 0 2 44"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
          class="flex-shrink-0 flex-grow-0"
          preserveAspectRatio="xMidYMid meet"
        >
          <line x1="0.833374" y1="2.18557e-8" x2="0.833372" y2="44" stroke="#E0E7FF"></line>
        </svg>
        <div class="relative flex flex-grow flex-col items-start justify-start gap-1">
          <p class="flex-shrink-0 flex-grow-0 text-left text-base font-medium text-gray-900 opacity-50">Price</p>
          <p class="flex-shrink-0 flex-grow-0 text-left text-lg font-bold text-gray-900">$500-$2,500</p>
        </div>
        <svg
          width="1"
          height="44"
          viewBox="0 0 1 44"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
          class="flex-shrink-0 flex-grow-0"
          preserveAspectRatio="xMidYMid meet"
        >
          <line x1="0.500061" y1="2.18557e-8" x2="0.500059" y2="44" stroke="#E0E7FF"></line>
        </svg>
        <div
          class="
            relative
            flex flex-shrink-0 flex-grow-0
            items-center
            justify-center
            gap-2.5
            overflow-hidden
            rounded-lg
            bg-indigo-500
            px-8
            py-4
          "
        >
          <p class="flex-shrink-0 flex-grow-0 text-center text-base font-bold text-white">Search</p>
        </div>
      </div>
    </div>
  </div>

  <div class="relative hidden w-full flex-col items-start justify-start gap-10 sm:hidden md:hidden lg:hidden xl:flex 2xl:hidden">
    <div class="relative flex flex-shrink-0 flex-grow-0 items-start justify-start gap-8 self-stretch">
      <p class="w-[864px] flex-grow text-left text-4xl font-bold text-[#000929]">Search properties to rent</p>
      <div
        class="
          flex
          w-[352px]
          flex-shrink-0 flex-grow-0 flex-col
          items-center
          justify-center
          gap-2.5
          rounded-lg
          border-[1.5px] border-indigo-100
          bg-white
          px-4
          py-3
        "
      >
        <div class="relative flex flex-shrink-0 flex-grow-0 items-center justify-between self-stretch">
          <p class="flex-shrink-0 flex-grow-0 text-left text-base font-medium text-gray-900 opacity-70">Search with Search Bar</p>
          <svg
            width="20"
            height="20"
            viewBox="0 0 20 20"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
            class="h-5 w-5 flex-shrink-0 flex-grow-0"
            preserveAspectRatio="xMidYMid meet"
          >
            <circle cx="10" cy="10" r="10" fill="#E0E7FF"></circle>
            <path d="M6.5 8.25L10 11.75L13.5 8.25" stroke="#6366F1" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"></path>
          </svg>
        </div>
      </div>
    </div>
    <div class="relative h-[104px] flex-shrink-0 flex-grow-0 self-stretch">
      <div class="absolute left-[-1px] top-[-1px] h-[104px] w-[1248px] rounded-tr-lg rounded-bl-lg rounded-br-lg bg-white"></div>
      <div
        class="absolute left-[31px] top-[23px] flex w-[1184px] items-center justify-center gap-8 rounded-tr-lg rounded-bl-lg rounded-br-lg"
      >
        <div class="relative flex flex-grow flex-col items-start justify-start gap-1">
          <p class="flex-shrink-0 flex-grow-0 text-left text-base font-medium text-gray-900 opacity-50">Location</p>
          <p class="h-7 w-[180px] flex-shrink-0 flex-grow-0 text-left text-lg font-bold text-gray-900">New York, USA</p>
        </div>
        <svg
          width="1"
          height="44"
          viewBox="0 0 1 44"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
          class="flex-shrink-0 flex-grow-0"
          preserveAspectRatio="xMidYMid meet"
        >
          <line x1="0.5" y1="2.18557e-8" x2="0.499998" y2="44" stroke="#E0E7FF"></line>
        </svg>
        <div class="relative flex flex-grow flex-col items-start justify-start gap-1">
          <p class="flex-shrink-0 flex-grow-0 text-left text-base font-medium text-gray-900 opacity-50">When</p>
          <p class="h-7 w-[180px] flex-shrink-0 flex-grow-0 text-left text-lg font-bold text-gray-900">Select Move-in Date</p>
        </div>
        <svg
          width="1"
          height="44"
          viewBox="0 0 1 44"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
          class="flex-shrink-0 flex-grow-0"
          preserveAspectRatio="xMidYMid meet"
        >
          <line x1="0.5" y1="2.18557e-8" x2="0.499998" y2="44" stroke="#E0E7FF"></line>
        </svg>
        <div class="relative flex flex-grow flex-col items-start justify-start gap-1">
          <p class="flex-shrink-0 flex-grow-0 text-left text-base font-medium text-gray-900 opacity-50">Price</p>
          <p class="flex-shrink-0 flex-grow-0 text-left text-lg font-bold text-gray-900">$500-$2,500</p>
        </div>
        <svg
          width="1"
          height="44"
          viewBox="0 0 1 44"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
          class="flex-shrink-0 flex-grow-0"
          preserveAspectRatio="xMidYMid meet"
        >
          <line x1="0.5" y1="2.18557e-8" x2="0.499998" y2="44" stroke="#E0E7FF"></line>
        </svg>
        <div
          class="
            relative
            flex flex-shrink-0 flex-grow-0
            items-center
            justify-center
            gap-2.5
            overflow-hidden
            rounded-lg
            bg-indigo-500
            px-8
            py-4
          "
        >
          <p class="flex-shrink-0 flex-grow-0 text-center text-base font-bold text-white">Search</p>
        </div>
      </div>
    </div>
  </div>

  <div class="relative hidden w-full flex-col items-start justify-start gap-10 sm:hidden md:hidden lg:hidden xl:hidden 2xl:flex">
    <div class="relative flex flex-shrink-0 flex-grow-0 items-start justify-start gap-8 self-stretch">
      <p class="w-[864px] flex-grow text-left text-4xl font-bold text-[#000929]">Search properties to rent</p>
      <div
        class="
          flex
          w-[352px]
          flex-shrink-0 flex-grow-0 flex-col
          items-center
          justify-center
          gap-2.5
          rounded-lg
          border-[1.5px] border-indigo-100
          bg-white
          px-4
          py-3
        "
      >
        <div class="relative flex flex-shrink-0 flex-grow-0 items-center justify-between self-stretch">
          <p class="flex-shrink-0 flex-grow-0 text-left text-base font-medium text-gray-900 opacity-70">Search with Search Bar</p>
          <svg
            width="20"
            height="20"
            viewBox="0 0 20 20"
            fill="none"
            xmlns="http://www.w3.org/2000/svg"
            class="h-5 w-5 flex-shrink-0 flex-grow-0"
            preserveAspectRatio="xMidYMid meet"
          >
            <circle cx="10" cy="10" r="10" fill="#E0E7FF"></circle>
            <path d="M6.5 8.25L10 11.75L13.5 8.25" stroke="#6366F1" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"></path>
          </svg>
        </div>
      </div>
    </div>
    <div class="relative h-[104px] flex-shrink-0 flex-grow-0 self-stretch">
      <div class="absolute left-[-1px] top-[-1px] h-[104px] w-[1248px] rounded-tr-lg rounded-bl-lg rounded-br-lg bg-white"></div>
      <div
        class="absolute left-[31px] top-[23px] flex w-[1184px] items-center justify-center gap-8 rounded-tr-lg rounded-bl-lg rounded-br-lg"
      >
        <div class="relative flex flex-grow flex-col items-start justify-start gap-1">
          <p class="flex-shrink-0 flex-grow-0 text-left text-base font-medium text-gray-900 opacity-50">Location</p>
          <p class="h-7 w-[180px] flex-shrink-0 flex-grow-0 text-left text-lg font-bold text-gray-900">New York, USA</p>
        </div>
        <svg
          width="1"
          height="44"
          viewBox="0 0 1 44"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
          class="flex-shrink-0 flex-grow-0"
          preserveAspectRatio="xMidYMid meet"
        >
          <line x1="0.5" y1="2.18557e-8" x2="0.499998" y2="44" stroke="#E0E7FF"></line>
        </svg>
        <div class="relative flex flex-grow flex-col items-start justify-start gap-1">
          <p class="flex-shrink-0 flex-grow-0 text-left text-base font-medium text-gray-900 opacity-50">When</p>
          <p class="h-7 w-[180px] flex-shrink-0 flex-grow-0 text-left text-lg font-bold text-gray-900">Select Move-in Date</p>
        </div>
        <svg
          width="1"
          height="44"
          viewBox="0 0 1 44"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
          class="flex-shrink-0 flex-grow-0"
          preserveAspectRatio="xMidYMid meet"
        >
          <line x1="0.5" y1="2.18557e-8" x2="0.499998" y2="44" stroke="#E0E7FF"></line>
        </svg>
        <div class="relative flex flex-grow flex-col items-start justify-start gap-1">
          <p class="flex-shrink-0 flex-grow-0 text-left text-base font-medium text-gray-900 opacity-50">Price</p>
          <p class="flex-shrink-0 flex-grow-0 text-left text-lg font-bold text-gray-900">$500-$2,500</p>
        </div>
        <svg
          width="1"
          height="44"
          viewBox="0 0 1 44"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
          class="flex-shrink-0 flex-grow-0"
          preserveAspectRatio="xMidYMid meet"
        >
          <line x1="0.5" y1="2.18557e-8" x2="0.499998" y2="44" stroke="#E0E7FF"></line>
        </svg>
        <div
          class="
            relative
            flex flex-shrink-0 flex-grow-0
            items-center
            justify-center
            gap-2.5
            overflow-hidden
            rounded-lg
            bg-indigo-500
            px-8
            py-4
          "
        >
          <p class="flex-shrink-0 flex-grow-0 text-center text-base font-bold text-white">Search</p>
        </div>
      </div>
    </div>
  </div>
</template>




<script>
import IconLogo from "./components/icons/IconLogo.vue";
import { FilmIcon } from "@heroicons/vue/outline";
export default {
  components: { IconLogo, FilmIcon },
};
</script>