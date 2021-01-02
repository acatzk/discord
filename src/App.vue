<template>
  <!-- main flex -->
  <div id="app" class="flex">
    <!-- first col -->
    <div class="bg-gray-900 w-20 flex-none flex flex-col min-h-screen h-screen px-2 py-2">
      <div class="overflow-y-auto">
        <ul class="text-center space-y-3">
          <li>
            <a href="#">
              <img class="w-12 h-12 bg-gray-800 hover:bg-gray-700 mx-auto rounded-full p-2 transition" src="@/assets/imgs/discord.png" alt="discord-img" />
            </a>
          </li>
          <li class="border-b border-gray-700 mx-4"></li>
          <li>
            <a href="#">
              <img class="w-12 h-12 bg-orange-700 hover:bg-orange-600 mx-auto rounded-full p-2 transition" src="@/assets/imgs/laravel.png" alt="discord-img" />
            </a>
          </li>
          <li>
            <a href="#">
              <img class="w-12 h-12 bg-green-100 hover:bg-green-50 mx-auto rounded-full p-2 transition" src="@/assets/imgs/vue.png" alt="discord-img" />
            </a>
          </li>
          <li>
            <a href="#">
              <svg  class="w-12 h-12 bg-gray-800 hover:bg-teal-500 text-teal-500 hover:text-white mx-auto rounded-full p-2 transition" 
                    fill="currentColor" 
                    xmlns:xlink="http://www.w3.org/1999/xlink" 
                    xmlns="http://www.w3.org/2000/svg" 
                    viewBox="0 0 20 20" 
                    preserveAspectRatio="xMidYMid meet">
                <path xmlns="http://www.w3.org/2000/svg" 
                      fill-rule="evenodd" 
                      d="M10 5a1 1 0 011 1v3h3a1 1 0 110 2h-3v3a1 1 0 11-2 0v-3H6a1 1 0 110-2h3V6a1 1 0 011-1z" 
                      clip-rule="evenodd">
                </path>
              </svg>
            </a>
          </li>
          <li>
            <a href="#">
              <svg  class="w-12 h-12 bg-gray-800 hover:bg-teal-500 text-teal-500 hover:text-white mx-auto rounded-full p-3 transition" 
                    fill="currentColor" 
                    xmlns:xlink="http://www.w3.org/1999/xlink" 
                    xmlns="http://www.w3.org/2000/svg" 
                    viewBox="0 0 20 20" 
                    preserveAspectRatio="xMidYMid meet">
                <path xmlns="http://www.w3.org/2000/svg" 
                      fill-rule="evenodd" 
                      d="M8 4a4 4 0 100 8 4 4 0 000-8zM2 8a6 6 0 1110.89 3.476l4.817 4.817a1 1 0 01-1.414 1.414l-4.816-4.816A6 6 0 012 8z" 
                      clip-rule="evenodd">
                </path>
              </svg>
            </a>
          </li>
          <li class="border-b border-gray-700 mx-4"></li>
          <li>
            <a href="#">
              <svg  class="w-12 h-12 bg-gray-800 hover:bg-teal-500 text-teal-500 hover:text-white mx-auto rounded-full p-3 transition" 
                    fill="currentColor" 
                    xmlns:xlink="http://www.w3.org/1999/xlink" 
                    xmlns="http://www.w3.org/2000/svg" 
                    viewBox="0 0 20 20" 
                    preserveAspectRatio="xMidYMid meet">
                <path xmlns="http://www.w3.org/2000/svg" 
                      fill-rule="evenodd"
                      d="M3 17a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zm3.293-7.707a1 1 0 011.414 0L9 10.586V3a1 1 0 112 0v7.586l1.293-1.293a1 1 0 111.414 1.414l-3 3a1 1 0 01-1.414 0l-3-3a1 1 0 010-1.414z" 
                      clip-rule="evenodd">
                </path>
              </svg>
            </a>
          </li>
        </ul>
      </div>
    </div>
    <!-- second col -->
    <div class="flex-1 flex flex-col min-h-screen h-screen">
      <!-- first col -->
      <div class="flex text-white h-12 border-b border-gray-900">
        <div class="bg-gray-800 w-56 flex-none flex items-center justify-between px-3 p-2">
          <div class="font-semibold tracking-wide">Tailwind CSS</div>
          <button>
            <svg  class="w-6 h-6" 
                  fill="currentColor" 
                  xmlns:xlink="http://www.w3.org/1999/xlink" 
                  xmlns="http://www.w3.org/2000/svg" 
                  viewBox="0 0 20 20" 
                  preserveAspectRatio="xMidYMid meet">
              <path xmlns="http://www.w3.org/2000/svg" 
                    fill-rule="evenodd" 
                    d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z" 
                    clip-rule="evenodd">
              </path>
            </svg>
          </button>
        </div>
        <div class="bg-gray-750 flex-1 flex items-center justify-between px-4 border-b border-gray-900 h-12">
          <div class="flex items-center">
            <div class="text-gray-500 text-2xl">#</div>
            <div class="ml-2 text-sm text-white">general</div>
            <div class="border-l pl-3 ml-3 border-gray-600 text-xs text-gray-400">general discussin of Tailwind CSS</div>
          </div>
          <div class="flex items-center">
            <a class="ml-4" href="#">
              <svg  class="w-6 h-6 text-gray-500 hover:text-gray-200 rounded-full"  
                    fill="currentColor" 
                    xmlns:xlink="http://www.w3.org/1999/xlink"
                    xmlns="http://www.w3.org/2000/svg" 
                    viewBox="0 0 20 20" 
                    preserveAspectRatio="xMidYMid meet">
                <path xmlns="http://www.w3.org/2000/svg" d="M10 2a6 6 0 00-6 6v3.586l-.707.707A1 1 0 004 14h12a1 1 0 00.707-1.707L16 11.586V8a6 6 0 00-6-6zm0 16a3 3 0 01-3-3h6a3 3 0 01-3 3z"></path>
              </svg>
            </a>
            <a class="ml-4" href="#">
              <svg  class="w-6 h-6 text-gray-500 hover:text-gray-200 rounded-full"  
                    fill="currentColor" 
                    xmlns:xlink="http://www.w3.org/1999/xlink"
                    xmlns="http://www.w3.org/2000/svg" 
                    viewBox="0 0 20 20" 
                    preserveAspectRatio="xMidYMid meet">
                <path xmlns="http://www.w3.org/2000/svg" d="M13.586 3.586a2 2 0 112.828 2.828l-.793.793-2.828-2.828.793-.793zm-2.207 2.207L3 14.172V17h2.828l8.38-8.379-2.83-2.828z"></path>
              </svg>
            </a>
            <a class="ml-4" href="#">
              <svg  class="w-6 h-6 text-gray-500 hover:text-gray-200 rounded-full"  
                    fill="currentColor" 
                    xmlns:xlink="http://www.w3.org/1999/xlink"
                    xmlns="http://www.w3.org/2000/svg" 
                    viewBox="0 0 20 20" 
                    preserveAspectRatio="xMidYMid meet">
                <path xmlns="http://www.w3.org/2000/svg" 
                      d="M9 6a3 3 0 11-6 0 3 3 0 016 0zm8 0a3 3 0 11-6 0 3 3 0 016 0zm-4.07 11c.046-.327.07-.66.07-1a6.97 6.97 0 00-1.5-4.33A5 5 0 0119 16v1h-6.07zM6 11a5 5 0 015 5v1H1v-1a5 5 0 015-5z">
                </path>
              </svg>
            </a>
            <a class="ml-4" href="#">
              <form>
                <div class="relative">
                  <input  class="rounded bg-gray-900 text-gray-200 text-xs px-2 py-1 focus:outline-none border-none" placeholder="Search" type="text" />
                  <span class="absolute right-0 top-0 mr-1 mt-1">
                    <svg  class="w-4 h-4 text-gray-400 hover:text-gray-200"
                          fill="currentColor" 
                          xmlns:xlink="http://www.w3.org/1999/xlink" 
                          xmlns="http://www.w3.org/2000/svg" 
                          viewBox="0 0 20 20"
                          preserveAspectRatio="xMidYMid meet">
                      <path xmlns="http://www.w3.org/2000/svg" 
                            fill-rule="evenodd" 
                            d="M8 4a4 4 0 100 8 4 4 0 000-8zM2 8a6 6 0 1110.89 3.476l4.817 4.817a1 1 0 01-1.414 1.414l-4.816-4.816A6 6 0 012 8z" 
                            clip-rule="evenodd">
                      </path>
                    </svg>
                  </span>
                </div>
              </form>
            </a>
            <a class="ml-4" href="#">
              <svg  class="w-6 h-6 text-gray-500 hover:text-gray-200 rounded-full"  
                    fill="currentColor" 
                    xmlns:xlink="http://www.w3.org/1999/xlink"
                    xmlns="http://www.w3.org/2000/svg" 
                    viewBox="0 0 20 20" 
                    preserveAspectRatio="xMidYMid meet">
                <path xmlns="http://www.w3.org/2000/svg" 
                      fill-rule="evenodd" 
                      d="M14.243 5.757a6 6 0 10-.986 9.284 1 1 0 111.087 1.678A8 8 0 1118 10a3 3 0 01-4.8 2.401A4 4 0 1114 10a1 1 0 102 0c0-1.537-.586-3.07-1.757-4.243zM12 10a2 2 0 10-4 0 2 2 0 004 0z" 
                      clip-rule="evenodd">
                </path>
              </svg>
            </a>
            <a class="ml-4" href="#">
              <svg  class="w-6 h-6 text-gray-500 hover:text-gray-200 rounded-full" 
                    fill="currentColor" 
                    xmlns:xlink="http://www.w3.org/1999/xlink" 
                    xmlns="http://www.w3.org/2000/svg" 
                    viewBox="0 0 20 20" 
                    preserveAspectRatio="xMidYMid meet">
                <path xmlns="http://www.w3.org/2000/svg" 
                      fill-rule="evenodd" 
                      d="M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-8-3a1 1 0 00-.867.5 1 1 0 11-1.731-1A3 3 0 0113 8a3.001 3.001 0 01-2 2.83V11a1 1 0 11-2 0v-1a1 1 0 011-1 1 1 0 100-2zm0 8a1 1 0 100-2 1 1 0 000 2z" 
                      clip-rule="evenodd">
                </path>
              </svg>
            </a>
          </div>
        </div>
      </div>
      <!-- second col -->
      <div class="text-white flex-1 flex overflow-y-hidden">
        <div class="bg-gray-800 w-56 flex-none flex flex-col justify-between">
          <div class="overflow-y-auto text-sm">
            <ul class="px-2 py-3">
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-900 rounded transition">
                <a href="#" class="flex items-center">
                  <span class="text-xl">#</span>
                  <span class="ml-2">Welcome</span>
                </a>
              </li>
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-900 rounded transition">
                <a href="#" class="flex items-center">
                  <span class="text-xl">#</span>
                  <span class="ml-2">faq</span>
                </a>
              </li>
            </ul>
            <!-- Tailwind CSS List -->
            <button class="flex items-center text-gray-500 hover:text-gray-200 focus:outline-none" @click="tailwindToggle = !tailwindToggle">
              <svg  class="w-5 h-5" 
                    fill="currentColor" 
                    xmlns:xlink="http://www.w3.org/1999/xlink" 
                    xmlns="http://www.w3.org/2000/svg" 
                    viewBox="0 0 20 20" 
                    preserveAspectRatio="xMidYMid meet">
                <path v-if="tailwindToggle" xmlns="http://www.w3.org/2000/svg" 
                      fill-rule="evenodd" 
                      d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z" 
                      clip-rule="evenodd"></path>
                <path v-else xmlns="http://www.w3.org/2000/svg" fill-rule="evenodd" d="M7.293 14.707a1 1 0 010-1.414L10.586 10 7.293 6.707a1 1 0 011.414-1.414l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414 0z" clip-rule="evenodd"></path>
              </svg>
              <h3 class="uppercase tracking-wide font-semibold text-xs">Tailwind CSS</h3>
            </button>
            <div v-show="tailwindToggle">
              <ul class="px-2 py-1">
                <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-900 rounded transition bg-gray-750">
                  <a href="#" class="flex items-center justify-between">
                    <div class="flex items-center">
                      <span class="text-xl">#</span>
                      <span class="ml-2 font-semibold text-gray-300">general</span>
                    </div>
                    <button class="focus:outline-none focus:ring-1 focus:ring-gray-500 rounded  text-gray-300">
                      <svg  class="w-5 h-5" 
                            fill="currentColor" 
                            xmlns:xlink="http://www.w3.org/1999/xlink" 
                            xmlns="http://www.w3.org/2000/svg" 
                            viewBox="0 0 20 20" 
                            preserveAspectRatio="xMidYMid meet">
                        <path xmlns="http://www.w3.org/2000/svg" 
                              d="M8 9a3 3 0 100-6 3 3 0 000 6zm0 2a6 6 0 016 6H2a6 6 0 016-6zm8-4a1 1 0 10-2 0v1h-1a1 1 0 100 2h1v1a1 1 0 102 0v-1h1a1 1 0 100-2h-1V7z"></path>
                      </svg>
                    </button>
                  </a>
                </li>
                <li v-for="(list, i) in tailwindList" :key="i" 
                    class="text-gray-500 px-2 hover:bg-gray-900 rounded transition" 
                    @mouseover="list.isHover = true" 
                    @mouseleave="list.isHover = false">
                  <a href="#" class="flex items-center justify-between">
                    <div class="flex items-center">
                      <span class="text-xl">#</span>
                      <span class="ml-2" :class="list.title === 'course' || list.title === 'showcase' ? 'font-semibold text-gray-300' : ''">{{ list.title }}</span>
                    </div>
                    <button class="focus:outline-none focus:ring-1 focus:ring-gray-500 rounded" :class="list.isHover ? 'block' : 'hidden'">
                      <svg  class="w-5 h-5" 
                            fill="currentColor" 
                            xmlns:xlink="http://www.w3.org/1999/xlink" 
                            xmlns="http://www.w3.org/2000/svg" 
                            viewBox="0 0 20 20" 
                            preserveAspectRatio="xMidYMid meet">
                        <path xmlns="http://www.w3.org/2000/svg" 
                              d="M8 9a3 3 0 100-6 3 3 0 000 6zm0 2a6 6 0 016 6H2a6 6 0 016-6zm8-4a1 1 0 10-2 0v1h-1a1 1 0 100 2h1v1a1 1 0 102 0v-1h1a1 1 0 100-2h-1V7z"></path>
                      </svg>
                    </button>
                  </a>
                </li>
              </ul>
            </div>
            <!-- Community List -->
            <button class="flex items-center text-gray-500 hover:text-gray-200 focus:outline-none" @click="communityToggle = !communityToggle">
              <svg  class="w-5 h-5" 
                    fill="currentColor" 
                    xmlns:xlink="http://www.w3.org/1999/xlink" 
                    xmlns="http://www.w3.org/2000/svg" 
                    viewBox="0 0 20 20" 
                    preserveAspectRatio="xMidYMid meet">
                <path v-if="communityToggle" xmlns="http://www.w3.org/2000/svg" 
                      fill-rule="evenodd" 
                      d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z" 
                      clip-rule="evenodd"></path>
                <path v-else xmlns="http://www.w3.org/2000/svg" fill-rule="evenodd" d="M7.293 14.707a1 1 0 010-1.414L10.586 10 7.293 6.707a1 1 0 011.414-1.414l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414 0z" clip-rule="evenodd"></path>
              </svg>
              <h3 class="uppercase tracking-wide font-semibold text-xs">Community</h3>
            </button>
            <div v-show="communityToggle">
              <ul class="px-2 py-1">
                <li v-for="(list, i) in communityList" :key="i" 
                    class="text-gray-500 px-2 hover:bg-gray-900 rounded transition" 
                    @mouseover="list.isHover = true" 
                    @mouseleave="list.isHover = false">
                  <a href="#" class="flex items-center justify-between">
                    <div class="flex items-center">
                      <span class="text-xl">#</span>
                      <span class="ml-2" :class="list.title === 'feedback' ? 'font-semibold text-gray-300' : ''">{{ list.title }}</span>
                    </div>
                    <button class="focus:outline-none focus:ring-1 focus:ring-gray-500 rounded" :class="list.isHover ? 'block' : 'hidden'">
                      <svg  class="w-5 h-5" 
                            fill="currentColor" 
                            xmlns:xlink="http://www.w3.org/1999/xlink" 
                            xmlns="http://www.w3.org/2000/svg" 
                            viewBox="0 0 20 20" 
                            preserveAspectRatio="xMidYMid meet">
                        <path xmlns="http://www.w3.org/2000/svg" 
                              d="M8 9a3 3 0 100-6 3 3 0 000 6zm0 2a6 6 0 016 6H2a6 6 0 016-6zm8-4a1 1 0 10-2 0v1h-1a1 1 0 100 2h1v1a1 1 0 102 0v-1h1a1 1 0 100-2h-1V7z"></path>
                      </svg>
                    </button>
                  </a>
                </li>
              </ul>
            </div>
            <!-- Off Topic -->
            <button class="flex items-center text-gray-500 hover:text-gray-200 focus:outline-none" @click="offTopicToggle = !offTopicToggle">
              <svg  class="w-5 h-5" 
                    fill="currentColor" 
                    xmlns:xlink="http://www.w3.org/1999/xlink" 
                    xmlns="http://www.w3.org/2000/svg" 
                    viewBox="0 0 20 20" 
                    preserveAspectRatio="xMidYMid meet">
                <path v-if="offTopicToggle" xmlns="http://www.w3.org/2000/svg" 
                      fill-rule="evenodd" 
                      d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z" 
                      clip-rule="evenodd"></path>
                <path v-else xmlns="http://www.w3.org/2000/svg" fill-rule="evenodd" d="M7.293 14.707a1 1 0 010-1.414L10.586 10 7.293 6.707a1 1 0 011.414-1.414l4 4a1 1 0 010 1.414l-4 4a1 1 0 01-1.414 0z" clip-rule="evenodd"></path>
              </svg>
              <h3 class="uppercase tracking-wide font-semibold text-xs">Off Topic</h3>
            </button>
            <div v-show="offTopicToggle">
              <ul class="px-2 py-1">
                <li v-for="(list, i) in offTopicList" :key="i" 
                    class="text-gray-500 px-2 hover:bg-gray-900 rounded transition" 
                    @mouseover="list.isHover = true" 
                    @mouseleave="list.isHover = false">
                  <a href="#" class="flex items-center justify-between">
                    <div class="flex items-center">
                      <span class="text-xl">#</span>
                      <span class="ml-2" :class="list.title === 'random' ? 'font-semibold text-gray-300' : ''">{{ list.title }}</span>
                    </div>
                    <button class="focus:outline-none focus:ring-1 focus:ring-gray-500 rounded" :class="list.isHover ? 'block' : 'hidden'">
                      <svg  class="w-5 h-5" 
                            fill="currentColor" 
                            xmlns:xlink="http://www.w3.org/1999/xlink" 
                            xmlns="http://www.w3.org/2000/svg" 
                            viewBox="0 0 20 20" 
                            preserveAspectRatio="xMidYMid meet">
                        <path xmlns="http://www.w3.org/2000/svg" 
                              d="M8 9a3 3 0 100-6 3 3 0 000 6zm0 2a6 6 0 016 6H2a6 6 0 016-6zm8-4a1 1 0 10-2 0v1h-1a1 1 0 100 2h1v1a1 1 0 102 0v-1h1a1 1 0 100-2h-1V7z"></path>
                      </svg>
                    </button>
                  </a>
                </li>
              </ul>
            </div>
          </div>
          <div class="bg-gray-850 flex items-center justify-between px-2 py-2">
            <a href="#" class="flex items-center">
              <div class="flex-shrink-0">
                <img class="w-8 h-8 object-cover rounded-full" src="@/assets/imgs/avatar.jpg" alt="avatar">
              </div>
              <div class="ml-2 text-xs">
                <div class="text-white">angryboy19</div>
                <div class="text-gray-500 text-xxs">#56489</div>
              </div>
            </a>
            <div class="flex items-center text-gray-500">
              <a href="#" class="hover:text-gray-300">
                <svg  class="w-5 h-5" 
                      fill="currentColor" 
                      xmlns:xlink="http://www.w3.org/1999/xlink" 
                      xmlns="http://www.w3.org/2000/svg" 
                      viewBox="0 0 20 20" 
                      preserveAspectRatio="xMidYMid meet">
                  <path xmlns="http://www.w3.org/2000/svg" 
                        fill-rule="evenodd" 
                        d="M7 4a3 3 0 016 0v4a3 3 0 11-6 0V4zm4 10.93A7.001 7.001 0 0017 8a1 1 0 10-2 0A5 5 0 015 8a1 1 0 00-2 0 7.001 7.001 0 006 6.93V17H6a1 1 0 100 2h8a1 1 0 100-2h-3v-2.07z" clip-rule="evenodd">
                  </path>
                </svg>
              </a>
              <a href="#" class="hover:text-gray-300 ml-3">
                <svg  class="w-5 h-5" 
                      fill="currentColor" 
                      xmlns:xlink="http://www.w3.org/1999/xlink" 
                      xmlns="http://www.w3.org/2000/svg" 
                      viewBox="0 0 20 20" 
                      preserveAspectRatio="xMidYMid meet">
                  <path xmlns="http://www.w3.org/2000/svg" 
                        d="M18 3a1 1 0 00-1.196-.98l-10 2A1 1 0 006 5v9.114A4.369 4.369 0 005 14c-1.657 0-3 .895-3 2s1.343 2 3 2 3-.895 3-2V7.82l8-1.6v5.894A4.37 4.37 0 0015 12c-1.657 0-3 .895-3 2s1.343 2 3 2 3-.895 3-2V3z">
                  </path>
                </svg>
              </a>
              <a href="#" class="hover:text-gray-300 ml-3">
                <svg  class="w-5 h-5" 
                      fill="currentColor" 
                      xmlns:xlink="http://www.w3.org/1999/xlink" 
                      xmlns="http://www.w3.org/2000/svg" 
                      viewBox="0 0 20 20" 
                      preserveAspectRatio="xMidYMid meet">
                  <path xmlns="http://www.w3.org/2000/svg" 
                        fill-rule="evenodd" 
                        d="M11.49 3.17c-.38-1.56-2.6-1.56-2.98 0a1.532 1.532 0 01-2.286.948c-1.372-.836-2.942.734-2.106 2.106.54.886.061 2.042-.947 2.287-1.561.379-1.561 2.6 0 2.978a1.532 1.532 0 01.947 2.287c-.836 1.372.734 2.942 2.106 2.106a1.532 1.532 0 012.287.947c.379 1.561 2.6 1.561 2.978 0a1.533 1.533 0 012.287-.947c1.372.836 2.942-.734 2.106-2.106a1.533 1.533 0 01.947-2.287c1.561-.379 1.561-2.6 0-2.978a1.532 1.532 0 01-.947-2.287c.836-1.372-.734-2.942-2.106-2.106a1.532 1.532 0 01-2.287-.947zM10 13a3 3 0 100-6 3 3 0 000 6z" 
                        clip-rule="evenodd">
                  </path>
                </svg>
              </a>
            </div>
          </div>
        </div>

        <div class="flex-1 flex justify-between overflow-y-hidden">
          <div class="bg-gray-750 flex-1 flex flex-col justify-between">
            <div class="overflow-y-auto text-sm text-gray-400">
              <div class="flex mx-6 my-3 py-4 border-t border-gray-700" v-for="(post, i) in posts" :key="i">
                <div class="flex-shrink-0">
                  <a href="#">
                    <img class="w-10 h-10 rounded-full bg-gray-850  object-cover" :src="post.avatar" alt="post.avatar">
                  </a>
                </div>
                <div class="px-2 py-1 ml-2 bg-gray-700 rounded-lg">
                  <div class="flex items-end">
                    <a class="text-white hover:underline" href="#">{{ post.username }}</a>
                    <span class="ml-2 text-gray-500 text-xs">{{ post.created_at }}</span>
                  </div>
                  <div class="mt-1 mb-1">
                    <div>{{ post.caption }}</div>
                  </div>
                </div>
              </div>
            </div>
            <div class="bg-gray-750 h-24 mx-4 py-3 flex items-center border-t border-gray-500">
              <button class="focus:outline-none bg-gray-700 h-10 px-2 py-2 rounded-l border-r border-gray-750">
                <svg  class="h-6 w-6 text-gray-300 hover:text-white" 
                      stroke="none" 
                      fill="currentColor" 
                      xmlns:xlink="http://www.w3.org/1999/xlink" 
                      xmlns="http://www.w3.org/2000/svg" 
                      viewBox="0 0 20 20" 
                      preserveAspectRatio="xMidYMid meet" 
                      data-attributes-set=",xmlns:xlink,xmlns,viewBox,preserveAspectRatio">
                  <path xmlns="http://www.w3.org/2000/svg" 
                        fill-rule="evenodd" 
                        d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-11a1 1 0 10-2 0v2H7a1 1 0 100 2h2v2a1 1 0 102 0v-2h2a1 1 0 100-2h-2V7z" 
                        clip-rule="evenodd">
                  </path>
                </svg>
              </button>
              <div class="flex-1">
                <input type="text" class="w-full focus:outline-none text-sm h-10 px-2 py-2 bg-gray-700 text-gray-200 border-none border-gray-700" v-model="input" @keyup.enter="onSubmitChat">
              </div>
              <div class="bg-gray-700 h-10 px-2 py-2 rounded-r flex items-center">
                <button class="bg-gray-700 h-10 px-2 py-2 border-l border-gray-750">
                  <svg  class="h-6 w-6 text-gray-300 hover:text-white" 
                        stroke="none" 
                        fill="currentColor" 
                        xmlns:xlink="http://www.w3.org/1999/xlink" 
                        xmlns="http://www.w3.org/2000/svg" 
                        viewBox="0 0 20 20" 
                        preserveAspectRatio="xMidYMid meet" 
                        data-attributes-set=",xmlns:xlink,xmlns,viewBox,preserveAspectRatio">
                    <path xmlns="http://www.w3.org/2000/svg" fill-rule="evenodd" d="M5 5a3 3 0 015-2.236A3 3 0 0114.83 6H16a2 2 0 110 4h-5V9a1 1 0 10-2 0v1H4a2 2 0 110-4h1.17C5.06 5.687 5 5.35 5 5zm4 1V5a1 1 0 10-1 1h1zm3 0a1 1 0 10-1-1v1h1z" clip-rule="evenodd">
                    </path>
                    <path xmlns="http://www.w3.org/2000/svg" d="M9 11H3v5a2 2 0 002 2h4v-7zm2 7h4a2 2 0 002-2v-5h-6v7z">
                    </path>
                  </svg>
                </button>
                <button class="bg-gray-700 h-10 px-2 py-2">
                  <svg  class="h-6 w-6 text-gray-300 hover:text-white" 
                        stroke="none" 
                        fill="currentColor" 
                        xmlns:xlink="http://www.w3.org/1999/xlink" 
                        xmlns="http://www.w3.org/2000/svg" 
                        viewBox="0 0 20 20" 
                        preserveAspectRatio="xMidYMid meet" 
                        data-attributes-set=",xmlns:xlink,xmlns,viewBox,preserveAspectRatio">
                    <path xmlns="http://www.w3.org/2000/svg" 
                          fill-rule="evenodd" 
                          d="M12.586 4.586a2 2 0 112.828 2.828l-3 3a2 2 0 01-2.828 0 1 1 0 00-1.414 1.414 4 4 0 005.656 0l3-3a4 4 0 00-5.656-5.656l-1.5 1.5a1 1 0 101.414 1.414l1.5-1.5zm-5 5a2 2 0 012.828 0 1 1 0 101.414-1.414 4 4 0 00-5.656 0l-3 3a4 4 0 105.656 5.656l1.5-1.5a1 1 0 10-1.414-1.414l-1.5 1.5a2 2 0 11-2.828-2.828l3-3z" clip-rule="evenodd">
                    </path>
                  </svg>
                </button>
                <button class="bg-gray-700 h-10 px-2 py-2">
                  <svg  class="h-6 w-6 text-gray-300 hover:text-white" 
                        stroke="none" 
                        fill="currentColor" 
                        xmlns:xlink="http://www.w3.org/1999/xlink" 
                        xmlns="http://www.w3.org/2000/svg" 
                        viewBox="0 0 20 20" 
                        preserveAspectRatio="xMidYMid meet" 
                        data-attributes-set=",xmlns:xlink,xmlns,viewBox,preserveAspectRatio">
                    <path xmlns="http://www.w3.org/2000/svg" 
                          fill-rule="evenodd" 
                          d="M10 18a8 8 0 100-16 8 8 0 000 16zM7 9a1 1 0 100-2 1 1 0 000 2zm7-1a1 1 0 11-2 0 1 1 0 012 0zm-.464 5.535a1 1 0 10-1.415-1.414 3 3 0 01-4.242 0 1 1 0 00-1.415 1.414 5 5 0 007.072 0z" 
                          clip-rule="evenodd">
                    </path>
                  </svg>
                </button>
              </div>
            </div>
          </div>
          <div class="flex-none w-56 bg-gray-800 overflow-y-auto px-3 py-3">
            <h3 class="text-xs font-semibold uppercase tracking-wide text-gray-500">Core Team - 1</h3>
            <ul class="mt-2">
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-750 py-1 my-2 rounded transition">
                <a href="#" class="flex items-center">
                  <span>
                    <a href="#">
                      <img class="w-8 h-8 rounded-full object-cover" src="@/assets/imgs/avatar.jpg" alt="avatar">
                    </a>
                  </span>
                  <span class="ml-2">angryboy19</span>
                </a>
              </li>
            </ul>
            <h3 class="mt-6 text-xs font-semibold uppercase tracking-wide text-gray-500">Online - 254</h3>
            <ul class="mt-2">
              <li class="text-gray-500 px-2 hover:text-gray-200 hover:bg-gray-750 py-1 my-2 rounded transition" v-for="(post, i) in posts" :key="i">
                <a href="#" class="flex items-center">
                  <span>
                    <a href="#">
                      <img class="w-8 h-8 rounded-full object-cover" :src="post.avatar" alt="avatar">
                    </a>
                  </span>
                  <span class="ml-2">{{ post.username }}</span>
                </a>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'app',
    data () {
      return {
        input: '',
        tailwindToggle: true,
        communityToggle: true,
        offTopicToggle: true,
        tailwindList: [
          {
            title: 'core-dev',
            isHover: false
          },
          {
            title: 'course',
            isHover: false
          },
          {
            title: 'plugins',
            isHover: false
          },
          {
            title: 'docs',
            isHover: false
          },
          {
            title: 'showcase',
            isHover: false
          },
          {
            title: 'help',
            isHover: false
          },
        ],
        communityList: [
          {
            title: 'feedback',
            isHover: false
          },
          {
            title: 'jobs',
            isHover: false
          }
        ],
        offTopicList: [
          {
            title: 'design',
            isHover: false
          },
          {
            title: 'development',
            isHover: false
          },
          {
            title: 'random',
            isHover: false
          }
        ],
        posts: [
          {
            username: 'angryboy19',
            avatar: require('@/assets/imgs/avatar.jpg'),
            caption: 'Greetings of the Season and Best Wishes for a New Year.',
            created_at: '01/02/2021'
          },
          {
            username: 'onenight231',
            avatar: 'https://external-content.duckduckgo.com/iu/?u=http%3A%2F%2Fwww.newsshare.in%2Fwp-content%2Fuploads%2F2017%2F04%2FMiniclip-8-Ball-Pool-Avatar-11.png&f=1&nofb=1',
            caption: 'Happy Holidays. Best wishes for a season of love, peace and joy!',
            created_at: '01/01/2021'
          },
          {
            username: 'sadboy13',
            avatar: 'https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse3.mm.bing.net%2Fth%3Fid%3DOIP.ULYowpbnr0VtDEqJ6P7tfQHaHa%26pid%3DApi&f=1',
            caption: 'Happy Holidays. Best wishes for a season of love, peace and joy!',
            created_at: '01/01/2021'
          },
          {
            username: 'whitehacker21',
            avatar: 'https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse4.mm.bing.net%2Fth%3Fid%3DOIP.UcUOvyrg9xpEQuW_BkkllQHaHa%26pid%3DApi&f=1',
            caption: 'Here’s to a season filled with warmth, comfort and good cheer!',
            created_at: '12/31/2020'
          },
          {
            username: 'girlybitch',
            avatar: 'https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fcms-assets.tutsplus.com%2Fuploads%2Fusers%2F107%2Fprofiles%2F2394%2FprofileImage%2Favatar-new400.jpg&f=1&nofb=1',
            caption: 'Holiday Greetings and Best Wishes for a New Year of happiness in a world of peace',
            created_at: '01/02/2021'
          },
          {
            username: 'bosscat',
            avatar: 'https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse3.mm.bing.net%2Fth%3Fid%3DOIP.dLKDCF7xkgEebmdzmeo6xQHaHa%26pid%3DApi&f=1',
            caption: 'May you and your family enjoy all the warmth this season has to offer. Have a wonderful holiday and a new year filled with love.',
            created_at: '01/02/2021'
          },
          {
            username: 'angryboy19',
            avatar: require('@/assets/imgs/avatar.jpg'),
            caption: 'Greetings of the Season and Best Wishes for a New Year.',
            created_at: '01/02/2021'
          },
          {
            username: 'onenight231',
            avatar: 'https://external-content.duckduckgo.com/iu/?u=http%3A%2F%2Fwww.newsshare.in%2Fwp-content%2Fuploads%2F2017%2F04%2FMiniclip-8-Ball-Pool-Avatar-11.png&f=1&nofb=1',
            caption: 'Happy Holidays. Best wishes for a season of love, peace and joy!',
            created_at: '01/01/2021'
          },
          {
            username: 'sadboy13',
            avatar: 'https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse3.mm.bing.net%2Fth%3Fid%3DOIP.ULYowpbnr0VtDEqJ6P7tfQHaHa%26pid%3DApi&f=1',
            caption: 'Happy Holidays. Best wishes for a season of love, peace and joy!',
            created_at: '01/01/2021'
          },
          {
            username: 'whitehacker21',
            avatar: 'https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse4.mm.bing.net%2Fth%3Fid%3DOIP.UcUOvyrg9xpEQuW_BkkllQHaHa%26pid%3DApi&f=1',
            caption: 'Here’s to a season filled with warmth, comfort and good cheer!',
            created_at: '12/31/2020'
          },
          {
            username: 'girlybitch',
            avatar: 'https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fcms-assets.tutsplus.com%2Fuploads%2Fusers%2F107%2Fprofiles%2F2394%2FprofileImage%2Favatar-new400.jpg&f=1&nofb=1',
            caption: 'Holiday Greetings and Best Wishes for a New Year of happiness in a world of peace',
            created_at: '01/02/2021'
          },
          {
            username: 'bosscat',
            avatar: 'https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse3.mm.bing.net%2Fth%3Fid%3DOIP.dLKDCF7xkgEebmdzmeo6xQHaHa%26pid%3DApi&f=1',
            caption: 'May you and your family enjoy all the warmth this season has to offer. Have a wonderful holiday and a new year filled with love.',
            created_at: '01/02/2021'
          },
          {
            username: 'angryboy19',
            avatar: require('@/assets/imgs/avatar.jpg'),
            caption: 'Greetings of the Season and Best Wishes for a New Year.',
            created_at: '01/02/2021'
          },
          {
            username: 'onenight231',
            avatar: 'https://external-content.duckduckgo.com/iu/?u=http%3A%2F%2Fwww.newsshare.in%2Fwp-content%2Fuploads%2F2017%2F04%2FMiniclip-8-Ball-Pool-Avatar-11.png&f=1&nofb=1',
            caption: 'Happy Holidays. Best wishes for a season of love, peace and joy!',
            created_at: '01/01/2021'
          },
          {
            username: 'sadboy13',
            avatar: 'https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse3.mm.bing.net%2Fth%3Fid%3DOIP.ULYowpbnr0VtDEqJ6P7tfQHaHa%26pid%3DApi&f=1',
            caption: 'Happy Holidays. Best wishes for a season of love, peace and joy!',
            created_at: '01/01/2021'
          },
          {
            username: 'whitehacker21',
            avatar: 'https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse4.mm.bing.net%2Fth%3Fid%3DOIP.UcUOvyrg9xpEQuW_BkkllQHaHa%26pid%3DApi&f=1',
            caption: 'Here’s to a season filled with warmth, comfort and good cheer!',
            created_at: '12/31/2020'
          },
          {
            username: 'girlybitch',
            avatar: 'https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fcms-assets.tutsplus.com%2Fuploads%2Fusers%2F107%2Fprofiles%2F2394%2FprofileImage%2Favatar-new400.jpg&f=1&nofb=1',
            caption: 'Holiday Greetings and Best Wishes for a New Year of happiness in a world of peace',
            created_at: '01/02/2021'
          },
          {
            username: 'bosscat',
            avatar: 'https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Ftse3.mm.bing.net%2Fth%3Fid%3DOIP.dLKDCF7xkgEebmdzmeo6xQHaHa%26pid%3DApi&f=1',
            caption: 'May you and your family enjoy all the warmth this season has to offer. Have a wonderful holiday and a new year filled with love.',
            created_at: '01/02/2021'
          },
        ]
      }
    },
    methods: {
      onSubmitChat () {
        this.posts.push({
          username: 'angryboy19',
          avatar: require('@/assets/imgs/avatar.jpg'),
          caption: this.input,
          created_at: '01/02/2021'
        })
        this.input = ''
      }
    }
  }
</script>
