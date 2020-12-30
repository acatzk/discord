<template>
  <!-- main flex -->
  <div id="app" class="flex">
    <!-- first col -->
    <div class="bg-gray-900 w-20 flex-none flex flex-col min-h-screen h-screen px-2 py-2">
      <div class="overflow-y-auto">
        <ul class="text-center space-y-3 mt-2">
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
    <div class="flex flex-col min-h-screen h-screen">
      <!-- first col -->
      <div class="flex text-white h-12 border-b border-gray-900">
        <div class="bg-gray-800 w-56 flex-none flex items-center justify-between px-3 p-2">
          <div class="font-semibold tracking-wide">Tailwind CSS</div>
          <button>
            <svg  class="w-8 h-8" 
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
        <div class="bg-gray-750 flex-1 flex items-center justify-between px-4 border-b border-gray-900">
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
                <div class="relative flex">
                  <input  class="rounded bg-gray-900 text-gray-200 text-xs px-2 py-1 focus:outline-none" placeholder="Search" type="text" />
                  <span class="absolute right-0 top-0 mt-1 mr-1">
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
          <div class="overflow-y-auto">
            hastag sidebar Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quasi at a laboriosam voluptates cupiditate quis quia autem debitis inventore, accusantium minus. Autem, expedita vitae modi saepe, eaque ipsum a error quaerat accusantium hic cumque eius. Necessitatibus soluta repellendus dolorum laudantium quod exercitationem reprehenderit, ipsa voluptatem ab cum, amet, recusandae vero dignissimos dolores ratione illo natus! Minus unde quidem commodi odit quibusdam voluptates sunt quaerat fuga ad repellendus obcaecati perspiciatis tempore maxime voluptas, nihil amet sint. Quas, delectus. Saepe magnam quo repellendus aut perspiciatis minima fugiat quidem laudantium similique numquam optio impedit, velit nam omnis qui nemo ex ducimus. Praesentium dicta temporibus tempore eius molestiae repellat, corporis, facilis omnis tempora minima quibusdam? Culpa consequatur, veniam aperiam ab tempore reiciendis iusto, deleniti asperiores quam tenetur minus? Ullam repellendus temporibus eum in ipsum debitis harum placeat maxime ad exercitationem accusamus esse totam tempora cupiditate est adipisci delectus, corrupti facere autem deserunt eveniet quis illo. Quo sed facere animi labore possimus blanditiis deserunt fugiat ipsa unde, repellat aliquam consectetur accusantium nulla tenetur, odit, sint officia. Repudiandae delectus dolorum vel quis fuga est nemo incidunt magnam. Iusto similique maiores veniam mollitia libero dolorum hic soluta itaque ducimus exercitationem eos natus officiis deserunt quo necessitatibus, laborum reiciendis quae cumque, voluptate recusandae nisi id debitis. Repudiandae dicta debitis aliquam atque explicabo praesentium distinctio deleniti reiciendis voluptate, velit obcaecati at voluptatem ratione tempora voluptatum eligendi nisi quae saepe. Distinctio voluptate tempore corporis cupiditate optio minima suscipit, voluptas doloribus. Voluptatem, ipsam aperiam asperiores quo mollitia ipsum nulla. Eius, tempore.
          </div>
          <div class="bg-gray-750">buttom</div>
        </div>

        <div class="flex-1 flex justify-between overflow-y-hidden">
          <div class="bg-gray-800 flex-1 flex flex-col justify-between">
            <div class="overflow-y-auto">
              main content Lorem ipsum dolor sit amet, consectetur adipisicing elit. Cum amet, magnam eos eveniet ex provident! Reiciendis vel corporis libero laudantium quasi voluptates facilis, rem vitae illo nihil hic veritatis debitis reprehenderit. Voluptatum sunt assumenda provident aperiam officia harum. Eos beatae corporis perferendis magni expedita! Quasi quod reprehenderit expedita nesciunt omnis nobis cumque cum velit qui, tenetur, autem, quo vitae deserunt incidunt. Debitis vero corrupti in optio placeat maxime explicabo, possimus accusantium at nesciunt incidunt temporibus ratione impedit, totam quo laboriosam enim aperiam, eius voluptate commodi cum sint? Reiciendis quae dolores autem tenetur ratione asperiores culpa velit delectus voluptates saepe repudiandae similique, cumque repellat. Nihil nobis ut velit, exercitationem quod, porro est, minima veritatis omnis veniam rerum soluta? Sequi ab, omnis fuga praesentium voluptate quasi amet molestiae vero libero aliquid laborum deleniti in magnam architecto. Sit autem aliquid debitis eius dolorum facilis. Repellat et suscipit vero voluptatem neque? Qui impedit autem omnis, cum exercitationem corrupti, nihil consequatur adipisci dolor necessitatibus quam sequi sint et vel dolorum, perspiciatis natus laborum aliquam voluptatum neque nisi cumque distinctio ea. Odio iste eum aliquam sunt rem impedit, totam ipsa quia laboriosam explicabo incidunt accusamus aspernatur itaque, reprehenderit libero modi. Et eum blanditiis eligendi facilis fugit consequatur accusantium nam minima commodi eaque sapiente cupiditate iste, ad laboriosam velit, vero officia rerum explicabo modi? Quam error quia minus cum et possimus repudiandae consequuntur voluptas sunt veniam molestiae, voluptatibus magni quidem praesentium dolorum minima dicta distinctio nam nulla aliquid? Vero cum quasi dolorem eveniet, qui neque consectetur harum velit debitis maiores ratione mollitia ut numquam quod dolorum amet minus corporis perferendis? Molestiae dolorem laborum provident distinctio, nostrum et sit doloremque quam nulla, repellat eaque ullam libero odit, vitae fuga voluptatem perspiciatis quia blanditiis doloribus consequuntur. Esse, consequatur quaerat. Facilis maiores enim dolore numquam earum tempora fugiat cupiditate est, aut eaque veritatis aspernatur velit sit nesciunt ducimus quaerat ab saepe blanditiis voluptates vero nam pariatur odio! Aut a, non, possimus sed repudiandae ipsam doloribus deserunt dolor perferendis ea blanditiis amet dolores odit cumque quo. Possimus voluptate id veritatis enim fugiat magnam iusto exercitationem aliquam iste reiciendis maiores explicabo eligendi, eaque inventore? Quam iure at voluptate, voluptatum saepe perferendis. Animi earum quos repellendus blanditiis obcaecati id architecto, labore quo at voluptatem, vero excepturi, est consequatur ratione sequi. Asperiores, ducimus. Veritatis voluptas ea quod, tempore dolorem cum libero similique unde culpa ullam totam exercitationem tenetur fugiat perferendis eius vitae blanditiis reiciendis facere in voluptates architecto impedit magni. Enim aut, a nostrum inventore libero dolore autem quisquam voluptas dolorum eius alias commodi accusamus rem molestias vero eaque consectetur officiis. Hic dolorum alias eligendi laborum adipisci, velit porro corporis ullam non ut quae, repellat blanditiis reiciendis debitis provident iusto sequi fugit corrupti asperiores voluptatem dolor expedita iste? Vel tempora, sint distinctio eius aperiam facere quibusdam veniam asperiores veritatis odit voluptatum maiores ut quia delectus nobis inventore sed perspiciatis expedita beatae. Consectetur consequatur aliquam magni veritatis labore, possimus earum eveniet optio explicabo libero, laborum cumque dolor sequi reiciendis provident pariatur. Blanditiis voluptas, earum asperiores numquam officiis repellendus cumque velit exercitationem amet in at saepe facilis ipsum, praesentium distinctio molestias incidunt deserunt reprehenderit placeat voluptatibus fugiat? Labore commodi fuga dolore sint eligendi nobis error laboriosam quis, molestias aliquid numquam illum explicabo magnam, temporibus hic officiis impedit iusto! Odio, iusto facere cupiditate quis consectetur saepe dignissimos accusantium deserunt voluptate a enim neque aliquid unde dolores, facilis non eaque quisquam nam autem deleniti repellendus necessitatibus atque dolore. Soluta illum quod doloribus, fugit debitis dolor, corrupti, ex explicabo repellendus recusandae delectus. Cum quasi ipsa facilis sit maiores ducimus rem blanditiis, quibusdam consequuntur sunt debitis fuga, magni id repudiandae! Ipsam commodi praesentium temporibus possimus nostrum porro, autem odio, earum quos alias corporis consequuntur corrupti molestiae. Corrupti magnam, quaerat iusto rerum nostrum, asperiores alias iste et eaque est cumque sunt ex perferendis! Numquam perspiciatis aliquid earum distinctio excepturi doloribus ipsam sapiente, corporis, maxime consectetur, esse nostrum illum! Rerum ullam dolore iusto, illum saepe expedita! Sunt ullam modi incidunt aliquam tempora iste eos perspiciatis natus quam, quod odit velit fugit enim consequuntur nisi. Corporis maiores quibusdam, molestias nemo excepturi dignissimos et odio laborum suscipit consequuntur quisquam repudiandae deleniti voluptas amet blanditiis iusto? Maiores, fugit. Ad ipsa, adipisci sit similique voluptate obcaecati hic nesciunt, assumenda labore voluptates ducimus repellendus ex, at ipsum reiciendis explicabo nostrum in maiores accusamus omnis. Unde vero vitae perspiciatis nobis tempora, voluptates dolorem cumque non, enim reiciendis eaque, sapiente quas accusamus deleniti itaque aliquam? Praesentium, fugiat? Assumenda cupiditate quam aspernatur ratione ut quasi aperiam unde dignissimos exercitationem rem ea vel nisi, quas eius nulla voluptatum! Placeat, tenetur a! Tempora placeat dolorem illum sit assumenda, quaerat magni! Rerum minus illum obcaecati consequatur similique itaque possimus sit mollitia eius earum sint, quasi nam aspernatur fugit reprehenderit ducimus blanditiis laudantium. Dolores quibusdam necessitatibus est maxime corrupti sit, id placeat libero ut quidem beatae iure! Laborum esse, cum voluptas molestias autem earum assumenda velit modi quibusdam aliquam quia illum quae sint asperiores dolorum labore impedit nemo qui expedita suscipit? Omnis explicabo fuga, cumque unde, velit animi iusto sint sit esse quibusdam dolores magni ut et odit perspiciatis nihil dolore! Reprehenderit consectetur ut distinctio minus fuga minima officiis ea totam. In iure magni voluptatibus saepe repudiandae quos consequuntur ipsa excepturi corrupti incidunt autem, doloremque dicta voluptas atque laborum reiciendis, aliquid cum ad quasi expedita quia. Sequi voluptate tenetur consequatur repellendus, modi deserunt molestiae, aliquam doloremque a, provident corporis quas exercitationem ipsam reprehenderit soluta laboriosam placeat officia delectus ducimus officiis illum ab ipsum dolorum? Deleniti, laborum sapiente temporibus voluptates, quod laudantium, expedita veniam suscipit tenetur eveniet corporis voluptatibus et obcaecati doloremque dicta. Expedita perspiciatis quaerat neque corrupti fugiat architecto dolorum nam provident similique vel facere error molestias ipsam voluptatum quasi totam explicabo, debitis est maiores laborum placeat dolore quam fuga dicta! Ut maiores rerum, sint fugiat repellendus nesciunt doloribus doloremque quasi quisquam! Consequatur obcaecati illo quisquam praesentium accusantium odit perferendis ad rerum, harum ratione deserunt enim ea quos id architecto inventore nisi, ipsum nam maxime necessitatibus fugit distinctio sit? Reiciendis asperiores eius cum recusandae.
            </div>
            <div class="bg-gray-700">bottom</div>
          </div>
          <div class="flex-none w-56 bg-gray-800 overflow-y-auto">sidebar Lorem ipsum dolor sit amet consectetur adipisicing elit. Laudantium deleniti unde eveniet saepe at sed nihil accusantium nam? Fuga minus necessitatibus omnis labore voluptas non adipisci ipsam sint iusto harum nobis aspernatur nemo doloremque ipsa eos qui perspiciatis repellat quia commodi, numquam hic sit et officia. Quae fuga voluptas quaerat nemo. Ducimus, praesentium, saepe voluptas officia officiis dolorem aperiam at exercitationem excepturi quasi delectus veritatis alias sit ullam fuga vero. Animi laborum cupiditate magni. Illum neque velit cumque numquam eius. Enim numquam minus autem quaerat consequatur expedita nihil dolore voluptates? Facilis tempore quasi cum? Explicabo recusandae maxime perspiciatis pariatur, dolor qui. Quaerat maiores pariatur sed corporis inventore excepturi. Sunt neque dignissimos doloremque ipsa officia rerum deserunt velit quisquam a explicabo consequatur consequuntur iure dolores veritatis, libero iusto assumenda mollitia possimus dolor labore voluptatibus! Nam quos veritatis atque corrupti incidunt nisi, neque est officiis. Officia distinctio facilis dignissimos! Nostrum deserunt saepe vitae eaque dolorem vel adipisci, eum hic. Ex, quas. Aliquid aliquam commodi voluptates. Perferendis facilis voluptate quo fugit. Id exercitationem ab laudantium, ipsam alias doloremque sunt sequi quas reprehenderit temporibus nostrum voluptate porro, quia ratione laborum voluptatum iure modi culpa. Vitae, saepe perferendis tempore, incidunt quibusdam iusto reiciendis, aliquam nostrum neque unde vero earum consequatur fugit numquam suscipit! Incidunt aliquam maxime beatae? A, deserunt. Quidem distinctio impedit laudantium. Sapiente possimus modi molestiae exercitationem, rem quis quae esse temporibus mollitia omnis eveniet dolorum eaque suscipit! Sunt consequuntur quidem commodi, velit quia, esse rem repellendus saepe incidunt obcaecati quod, amet excepturi. Quas?</div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    name: 'app',
    props: {},
    components: {},
    data () {
      return {}
    }
  }
</script>
