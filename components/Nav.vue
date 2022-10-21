<template>
    <div class="dark:bg-gray-900">
          <div>
              <div class="relative">
                <div class="absolute top-3 right-10">📞 <a class="text-red-600 font-bold" href="tel:0913996633">0913996633</a> - <a class="text-red-600 font-bold" href="tel:0912996633">0912996633</a></div>
                  <!-- For md screen size -->
                  <div v-if="search" id="md-searchbar" class="bg-white w-full dark:bg-gray-900 lg:hidden py-5 px-6 items-center justify-between">
                      <div class="flex items-center space-x-3 text-gray-800 dark:text-white">
                          <div>
                              <svg class="fill-stroke" width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                                  <path d="M9 17C13.4183 17 17 13.4183 17 9C17 4.58172 13.4183 1 9 1C4.58172 1 1 4.58172 1 9C1 13.4183 4.58172 17 9 17Z" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" />
                                  <path d="M18.9984 18.9999L14.6484 14.6499" stroke="currentColor" stroke-width="1.25" stroke-linecap="round" stroke-linejoin="round" />
                              </svg>
                          </div>
                          <input type="text" placeholder="Tìm sản phẩm" class="text-sm leading-none dark:text-gray-300 dark:bg-gray-900 text-gray-600 focus:outline-none" />
                      </div>
                      <div class="space-x-6">
                          <button aria-label="view favourites" class="text-gray-800 dark:text-white focus:outline-none focus:ring-2 focus:ring-gray-800">
                              <svg class="fill-stroke" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
                                  <path
                                      d="M13.8921 3.07357C13.5516 2.73291 13.1473 2.46267 12.7023 2.2783C12.2574 2.09392 11.7804 1.99902 11.2988 1.99902C10.8171 1.99902 10.3402 2.09392 9.89521 2.2783C9.45023 2.46267 9.04595 2.73291 8.70544 3.07357L7.99878 3.78024L7.29211 3.07357C6.60432 2.38578 5.67147 1.99938 4.69878 1.99938C3.72609 1.99938 2.79324 2.38578 2.10544 3.07357C1.41765 3.76137 1.03125 4.69422 1.03125 5.66691C1.03125 6.6396 1.41765 7.57245 2.10544 8.26024L2.81211 8.96691L7.99878 14.1536L13.1854 8.96691L13.8921 8.26024C14.2328 7.91974 14.503 7.51545 14.6874 7.07048C14.8718 6.6255 14.9667 6.14857 14.9667 5.66691C14.9667 5.18525 14.8718 4.70831 14.6874 4.26334C14.503 3.81836 14.2328 3.41408 13.8921 3.07357V3.07357Z"
                                      stroke="currentColor"
                                      stroke-width="1.5"
                                      stroke-linecap="round"
                                      stroke-linejoin="round"
                                  />
                              </svg>
                          </button>
                          <button aria-label="go to cart" class="text-gray-800 dark:text-white focus:outline-none focus:ring-2 focus:ring-gray-800">
                              <svg class="fill-stroke" width="18" height="18" viewBox="0 0 18 18" fill="none" xmlns="http://www.w3.org/2000/svg">
                                  <path d="M3.66667 1L1 4.2V15.4C1 15.8243 1.1873 16.2313 1.5207 16.5314C1.8541 16.8314 2.30628 17 2.77778 17H15.2222C15.6937 17 16.1459 16.8314 16.4793 16.5314C16.8127 16.2313 17 15.8243 17 15.4V4.2L14.3333 1H3.66667Z" stroke="currentColor" stroke-width="1.25" stroke-linecap="round" stroke-linejoin="round" />
                                  <path d="M1 4.2002H17" stroke="currentColor" stroke-width="1.25" stroke-linecap="round" stroke-linejoin="round" />
                                  <path d="M12.5564 7.3999C12.5564 8.2486 12.1818 9.06253 11.515 9.66264C10.8482 10.2628 9.94386 10.5999 9.00087 10.5999C8.05788 10.5999 7.15351 10.2628 6.48671 9.66264C5.81991 9.06253 5.44531 8.2486 5.44531 7.3999" stroke="currentColor" stroke-width="1.25" stroke-linecap="round" stroke-linejoin="round" />
                              </svg>
                          </button>
                      </div>
                  </div>
                  <!-- For md screen size -->

                  <!-- For large screens -->
                  <div class="dark:bg-gray-900 bg-gray-50 px-6 py-9">
                      <div class="container mx-auto flex items-center justify-between">
                          <h1 class="md:w-2/12 cursor-pointer text-gray-800 dark:text-white" aria-label="the Crib.">
                              <svg class="w-auto h-11"  version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" width="400" height="400" viewBox="0, 0, 400,400"><g id="svgg"><path id="path0" d="M0.000 200.000 L 0.000 400.000 200.000 400.000 L 400.000 400.000 400.000 200.000 L 400.000 0.000 200.000 0.000 L 0.000 0.000 0.000 200.000 M378.548 3.822 C 388.295 7.160,395.248 14.612,397.752 24.404 C 398.779 28.422,398.968 372.016,397.945 376.877 C 395.738 387.369,388.030 395.428,377.136 398.634 L 374.440 399.427 202.052 399.540 C 89.949 399.614,28.686 399.525,26.866 399.285 C 15.092 397.733,6.171 390.051,2.540 378.338 L 1.679 375.560 1.583 202.313 C 1.488 29.797,1.491 29.051,2.241 25.447 C 4.605 14.088,14.038 4.897,25.285 2.996 C 26.257 2.832,105.466 2.720,201.306 2.748 L 375.560 2.799 378.548 3.822 M67.259 104.539 C 54.828 107.323,53.182 125.680,64.848 131.425 L 67.334 132.649 96.447 132.836 C 129.028 133.045,126.773 132.842,128.159 135.691 C 129.341 138.119,130.626 135.569,113.051 165.672 C 110.115 170.700,106.593 176.744,105.223 179.104 C 99.785 188.478,83.744 216.066,81.793 219.403 C 79.714 222.959,77.424 226.878,71.548 236.940 C 69.810 239.916,66.248 246.045,63.632 250.560 C 61.015 255.075,57.738 260.700,56.349 263.060 C 51.998 270.449,51.344 272.303,51.344 277.239 C 51.344 286.586,57.747 294.855,66.978 297.428 C 70.214 298.330,169.275 298.188,171.884 297.277 C 185.259 292.610,184.888 273.952,171.338 269.767 C 169.031 269.055,167.752 269.030,133.132 269.030 L 97.313 269.030 96.067 267.783 C 93.408 265.124,93.372 265.238,100.964 252.239 C 106.551 242.672,110.569 235.769,113.994 229.851 C 114.647 228.722,116.015 226.371,117.035 224.627 C 118.054 222.882,121.962 216.166,125.720 209.701 C 129.478 203.237,133.595 196.185,134.868 194.030 C 138.074 188.603,141.135 183.351,154.116 161.007 C 160.315 150.336,166.240 140.177,167.282 138.433 C 168.324 136.688,169.494 134.609,169.882 133.812 C 175.614 122.044,168.711 107.691,155.863 104.662 C 153.104 104.012,70.129 103.897,67.259 104.539 M204.961 104.891 C 201.374 106.129,198.630 108.559,196.828 112.093 L 195.336 115.020 195.336 200.887 L 195.336 286.754 196.207 288.912 C 201.576 302.214,221.260 300.163,223.848 286.032 C 224.407 282.984,224.415 119.877,223.857 116.418 C 222.409 107.440,213.437 101.967,204.961 104.891 M284.888 104.324 C 260.273 107.839,242.476 124.637,238.422 148.182 C 237.376 154.259,237.264 284.798,238.302 287.900 C 242.438 300.251,259.352 301.532,265.042 289.925 L 266.231 287.500 266.434 220.336 C 266.589 168.807,266.744 152.781,267.096 151.493 C 272.169 132.965,294.266 126.813,307.654 140.201 C 316.763 149.309,316.867 165.742,307.868 173.813 C 302.256 178.846,298.766 180.385,291.604 180.985 C 270.769 182.730,270.945 209.971,291.791 209.864 C 335.473 209.642,359.633 156.937,331.464 123.321 C 320.138 109.805,301.045 102.017,284.888 104.324 " stroke="none" fill="#fbfbfb" fill-rule="evenodd"></path><path id="path1" d="M25.285 2.996 C 14.038 4.897,4.605 14.088,2.241 25.447 C 1.491 29.051,1.488 29.797,1.583 202.313 L 1.679 375.560 2.540 378.338 C 6.171 390.051,15.092 397.733,26.866 399.285 C 28.686 399.525,89.949 399.614,202.052 399.540 L 374.440 399.427 377.136 398.634 C 388.030 395.428,395.738 387.369,397.945 376.877 C 398.968 372.016,398.779 28.422,397.752 24.404 C 395.248 14.612,388.295 7.160,378.548 3.822 L 375.560 2.799 201.306 2.748 C 105.466 2.720,26.257 2.832,25.285 2.996 M155.863 104.662 C 168.711 107.691,175.614 122.044,169.882 133.812 C 169.494 134.609,168.324 136.688,167.282 138.433 C 166.240 140.177,160.315 150.336,154.116 161.007 C 141.135 183.351,138.074 188.603,134.868 194.030 C 133.595 196.185,129.478 203.237,125.720 209.701 C 121.962 216.166,118.054 222.882,117.035 224.627 C 116.015 226.371,114.647 228.722,113.994 229.851 C 110.569 235.769,106.551 242.672,100.964 252.239 C 93.372 265.238,93.408 265.124,96.067 267.783 L 97.313 269.030 133.132 269.030 C 167.752 269.030,169.031 269.055,171.338 269.767 C 184.888 273.952,185.259 292.610,171.884 297.277 C 169.275 298.188,70.214 298.330,66.978 297.428 C 57.747 294.855,51.344 286.586,51.344 277.239 C 51.344 272.303,51.998 270.449,56.349 263.060 C 57.738 260.700,61.015 255.075,63.632 250.560 C 66.248 246.045,69.810 239.916,71.548 236.940 C 77.424 226.878,79.714 222.959,81.793 219.403 C 83.744 216.066,99.785 188.478,105.223 179.104 C 106.593 176.744,110.115 170.700,113.051 165.672 C 130.626 135.569,129.341 138.119,128.159 135.691 C 126.773 132.842,129.028 133.045,96.447 132.836 L 67.334 132.649 64.848 131.425 C 53.182 125.680,54.828 107.323,67.259 104.539 C 70.129 103.897,153.104 104.012,155.863 104.662 M215.690 105.463 C 220.129 107.541,223.059 111.470,223.857 116.418 C 224.415 119.877,224.407 282.984,223.848 286.032 C 221.260 300.163,201.576 302.214,196.207 288.912 L 195.336 286.754 195.336 200.887 L 195.336 115.020 196.828 112.093 C 200.419 105.049,208.635 102.162,215.690 105.463 M301.679 105.178 C 331.181 111.631,349.421 141.181,341.900 170.336 C 335.986 193.261,315.090 209.745,291.791 209.864 C 270.945 209.971,270.769 182.730,291.604 180.985 C 298.766 180.385,302.256 178.846,307.868 173.813 C 316.867 165.742,316.763 149.309,307.654 140.201 C 294.266 126.813,272.169 132.965,267.096 151.493 C 266.744 152.781,266.589 168.807,266.434 220.336 L 266.231 287.500 265.042 289.925 C 259.352 301.532,242.438 300.251,238.302 287.900 C 237.264 284.798,237.376 154.259,238.422 148.182 C 242.476 124.637,260.273 107.839,284.888 104.324 C 287.704 103.922,298.430 104.468,301.679 105.178 " stroke="none" fill="#8b8b8b" fill-rule="evenodd"></path></g></svg>
                          </h1>
                          <ul class="hidden w-8/12 md:flex items-center justify-center space-x-8">
                              <li>
                                  <a href="javascript:void(0)" class="dark:text-white text-base text-gray-800 focus:outline-none focus:ring-2 focus:ring-gray-800 hover:underline">Sản phẩm</a>
                              </li>
                              <li>
                                  <a href="javascript:void(0)" class="dark:text-white text-base text-gray-800 focus:outline-none focus:ring-2 focus:ring-gray-800 hover:underline">Phòng ngủ</a>
                              </li>
                              <li>
                                  <a href="javascript:void(0)" class="dark:text-white text-base text-gray-800 focus:outline-none focus:ring-2 focus:ring-gray-800 hover:underline">Smart Bedroom</a>
                              </li>
                              <li>
                                  <a href="javascript:void(0)" class="dark:text-white text-base text-gray-800 focus:outline-none focus:ring-2 focus:ring-gray-800 hover:underline">Hệ thống Showroom</a>
                              </li>
                              <li>
                                  <a href="javascript:void(0)" class="dark:text-white text-base text-gray-800 focus:outline-none focus:ring-2 focus:ring-gray-800 hover:underline">Blog</a>
                              </li>
                          </ul>

                          <div class="md:w-2/12 justify-end flex items-center space-x-4 xl:space-x-8">
                              <div class="hidden lg:flex items-center">
                                  <button aria-label="search items" class="text-gray-800 dark:hover:text-gray-300 dark:text-white focus:outline-none focus:ring-2 focus:ring-gray-800" @click="search=!search">
                                      <svg class="fill-stroke" width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                                          <path d="M5 11C5 15.4183 8.58172 19 13 19C17.4183 19 21 15.4183 21 11C21 6.58172 17.4183 3 13 3C8.58172 3 5 6.58172 5 11Z" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" />
                                          <path d="M2.99961 20.9999L7.34961 16.6499" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" />
                                      </svg>
                                  </button>
                                  <input v-if="search" id="searchInput" type="text" placeholder="search" class="text-sm dark:bg-gray-900 dark:placeholder-gray-300 text-gray-600 rounded ml-1 border border-transparent focus:outline-none focus:border-gray-400 px-1" />
                              </div>
                              <div class="hidden lg:flex items-center space-x-4 xl:space-x-8">
                                  <button aria-label="view favourites" class="text-gray-800 dark:hover:text-gray-300 dark:text-white focus:outline-none focus:ring-2 focus:ring-gray-800">
                                      <svg class="fill-stroke" width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                                          <path
                                              d="M20.8401 4.60987C20.3294 4.09888 19.7229 3.69352 19.0555 3.41696C18.388 3.14039 17.6726 2.99805 16.9501 2.99805C16.2276 2.99805 15.5122 3.14039 14.8448 3.41696C14.1773 3.69352 13.5709 4.09888 13.0601 4.60987L12.0001 5.66987L10.9401 4.60987C9.90843 3.57818 8.50915 2.99858 7.05012 2.99858C5.59109 2.99858 4.19181 3.57818 3.16012 4.60987C2.12843 5.64156 1.54883 7.04084 1.54883 8.49987C1.54883 9.95891 2.12843 11.3582 3.16012 12.3899L4.22012 13.4499L12.0001 21.2299L19.7801 13.4499L20.8401 12.3899C21.3511 11.8791 21.7565 11.2727 22.033 10.6052C22.3096 9.93777 22.4519 9.22236 22.4519 8.49987C22.4519 7.77738 22.3096 7.06198 22.033 6.39452C21.7565 5.72706 21.3511 5.12063 20.8401 4.60987V4.60987Z"
                                              stroke="currentColor"
                                              stroke-width="1.5"
                                              stroke-linecap="round"
                                              stroke-linejoin="round"
                                          />
                                      </svg>
                                  </button>
                                  <button aria-label="go to cart" class="text-gray-800 dark:hover:text-gray-300 dark:text-white focus:outline-none focus:ring-2 focus:ring-gray-800">
                                      <svg class="fill-stroke" width="26" height="26" viewBox="0 0 26 26" fill="none" xmlns="http://www.w3.org/2000/svg">
                                          <path d="M5 1L1 5.8V22.6C1 23.2365 1.28095 23.847 1.78105 24.2971C2.28115 24.7471 2.95942 25 3.66667 25H22.3333C23.0406 25 23.7189 24.7471 24.219 24.2971C24.719 23.847 25 23.2365 25 22.6V5.8L21 1H5Z" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" />
                                          <path d="M1 5.7998H25" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" />
                                          <path d="M18.3346 10.6001C18.3346 11.8731 17.7727 13.094 16.7725 13.9942C15.7723 14.8944 14.4158 15.4001 13.0013 15.4001C11.5868 15.4001 10.2303 14.8944 9.23007 13.9942C8.22987 13.094 7.66797 11.8731 7.66797 10.6001" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" />
                                      </svg>
                                  </button>
                              </div>

                              <!-- <div class="md:hidden ">📞 <a class="text-red-600 font-bold" href="tel:0913996633">0913996633</a> - <a class="text-red-600 font-bold" href="tel:0912996633">0912996633</a></div> -->

                              <div class="flex lg:hidden">
                                  <button aria-label="show options" class="text-white bg-green-800 dark:text-white dark:hover:text-gray-300 hidden md:flex focus:outline-none focus:ring-2 rounded focus:ring-gray-600" @click="search=!search">
                                      <svg class="fill-stroke" width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                                          <path d="M4 6H20" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" />
                                          <path d="M10 12H20" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" />
                                          <path d="M6 18H20" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" />
                                      </svg>
                                  </button>

                                  <button aria-label="open menu" class="text-white bg-green-700 dark:text-white dark:hover:text-gray-300 md:hidden focus:outline-none focus:ring-2 rounded focus:ring-gray-600" @click="menu=true">
                                      <svg class="fill-stroke" width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                                          <path d="M4 6H20" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" />
                                          <path d="M10 12H20" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" />
                                          <path d="M6 18H20" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round" />
                                      </svg>
                                  </button>
                              </div>
                          </div>
                      </div>
                  </div>
                  <!-- For small screen -->
                  <div v-if="menu" id="mobile-menu" class="absolute dark:bg-gray-900 z-10 inset-0 md:hidden bg-white flex flex-col h-screen w-full">
                      <div class="flex items-center justify-between border-b border-gray-200 dark:border-gray-700 pb-4 p-4">
                          <div class="flex items-center space-x-3">
                              <div>
                                  <svg class="fill-stroke text-gray-800 dark:text-white" width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                                      <path d="M9 17C13.4183 17 17 13.4183 17 9C17 4.58172 13.4183 1 9 1C4.58172 1 1 4.58172 1 9C1 13.4183 4.58172 17 9 17Z" stroke="currentColor" stroke-width="1.25" stroke-linecap="round" stroke-linejoin="round" />
                                      <path d="M18.9984 18.9999L14.6484 14.6499" stroke="currentColor" stroke-width="1.25" stroke-linecap="round" stroke-linejoin="round" />
                                  </svg>
                              </div>
                              <input type="text" placeholder="Tìm sản phẩm" class="text-sm dark:bg-gray-900 text-gray-600 placeholder-gray-600 dark:placeholder-gray-300 focus:outline-none" />
                          </div>

                          <button aria-label="close menu" class="focus:outline-none focus:ring-2 rounded focus:ring-gray-600" @click="menu=false">
                              <svg class="fill-stroke text-gray-800 dark:text-white" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
                                  <path d="M12 4L4 12" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" />
                                  <path d="M4 4L12 12" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" />
                              </svg>
                          </button>
                      </div>
                      <div class="mt-6 p-4">
                          <ul class="flex flex-col space-y-6">
                              <li>
                                  <a href="javascript:void(0)" class="dark:text-white flex items-center justify-between hover:underline text-base text-gray-800 focus:outline-none focus:ring-2 focus:ring-gray-800">
                                      Sản phẩm
                                      <div>
                                          <svg class="fill-stroke text-black dark:text-white" width="12" height="12" viewBox="0 0 12 12" fill="none" xmlns="http://www.w3.org/2000/svg">
                                              <path d="M4.5 3L7.5 6L4.5 9" stroke="currentColor" stroke-width="0.75" stroke-linecap="round" stroke-linejoin="round" />
                                          </svg>
                                      </div>
                                  </a>
                              </li>
                              <li>
                                  <a href="javascript:void(0)" class="dark:text-white flex items-center justify-between hover:underline text-base text-gray-800 focus:outline-none focus:ring-2 focus:ring-gray-800">
                                      Phòng ngủ
                                      <div>
                                          <svg class="fill-stroke text-black dark:text-white" width="12" height="12" viewBox="0 0 12 12" fill="none" xmlns="http://www.w3.org/2000/svg">
                                              <path d="M4.5 3L7.5 6L4.5 9" stroke="currentColor" stroke-width="0.75" stroke-linecap="round" stroke-linejoin="round" />
                                          </svg>
                                      </div>
                                  </a>
                              </li>
                              <li>
                                  <a href="javascript:void(0)" class="dark:text-white flex items-center justify-between hover:underline text-base text-gray-800 focus:outline-none focus:ring-2 focus:ring-gray-800">
                                      Smart Bedroom
                                      <div>
                                          <svg class="fill-stroke text-black dark:text-white" width="12" height="12" viewBox="0 0 12 12" fill="none" xmlns="http://www.w3.org/2000/svg">
                                              <path d="M4.5 3L7.5 6L4.5 9" stroke="currentColor" stroke-width="0.75" stroke-linecap="round" stroke-linejoin="round" />
                                          </svg>
                                      </div>
                                  </a>
                              </li>
                              <li>
                                  <a href="javascript:void(0)" class="dark:text-white flex items-center justify-between hover:underline text-base text-gray-800 focus:outline-none focus:ring-2 focus:ring-gray-800">
                                      Hệ thống Showroom
                                      <div>
                                          <svg class="fill-stroke text-black dark:text-white" width="12" height="12" viewBox="0 0 12 12" fill="none" xmlns="http://www.w3.org/2000/svg">
                                              <path d="M4.5 3L7.5 6L4.5 9" stroke="currentColor" stroke-width="0.75" stroke-linecap="round" stroke-linejoin="round" />
                                          </svg>
                                      </div>
                                  </a>
                              </li>
                              <li>
                                  <a href="javascript:void(0)" class="dark:text-white flex items-center justify-between hover:underline text-base text-gray-800 focus:outline-none focus:ring-2 focus:ring-gray-800">
                                      Blog
                                      <div>
                                          <svg class="fill-stroke text-black dark:text-white" width="12" height="12" viewBox="0 0 12 12" fill="none" xmlns="http://www.w3.org/2000/svg">
                                              <path d="M4.5 3L7.5 6L4.5 9" stroke="currentColor" stroke-width="0.75" stroke-linecap="round" stroke-linejoin="round" />
                                          </svg>
                                      </div>
                                  </a>
                              </li>
                          </ul>
                      </div>
                      <div class="h-full flex items-end">
                          <ul class="flex flex-col space-y-8 bg-gray-50 w-full py-10 p-4 dark:bg-gray-800">
                              <li>
                                  <a href="javascript:void(0)" class="dark:text-white text-gray-800 flex items-center space-x-2 focus:outline-none focus:ring-2 focus:ring-gray-800 hover:underline">
                                      <div>
                                          <svg class="fill-stroke" width="22" height="22" viewBox="0 0 22 22" fill="none" xmlns="http://www.w3.org/2000/svg">
                                              <path d="M4.33333 1L1 5V19C1 19.5304 1.23413 20.0391 1.65087 20.4142C2.06762 20.7893 2.63285 21 3.22222 21H18.7778C19.3671 21 19.9324 20.7893 20.3491 20.4142C20.7659 20.0391 21 19.5304 21 19V5L17.6667 1H4.33333Z" stroke="currentColor" stroke-width="1.25" stroke-linecap="round" stroke-linejoin="round" />
                                              <path d="M1 5H21" stroke="currentColor" stroke-width="1.25" stroke-linecap="round" stroke-linejoin="round" />
                                              <path d="M15.4436 9C15.4436 10.0609 14.9753 11.0783 14.1418 11.8284C13.3083 12.5786 12.1779 13 10.9991 13C9.82039 13 8.68993 12.5786 7.85643 11.8284C7.02294 11.0783 6.55469 10.0609 6.55469 9" stroke="currentColor" stroke-width="1.25" stroke-linecap="round" stroke-linejoin="round" />
                                          </svg>
                                      </div>
                                      <p class="text-base">Giỏ hàng</p>
                                  </a>
                              </li>
                              <li>
                                  <a href="javascript:void(0)" class="dark:text-white text-gray-800 flex items-center space-x-2 focus:outline-none focus:ring-2 focus:ring-gray-800 hover:underline">
                                      <div>
                                          <svg class="fill-stroke" width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                                              <path
                                                  d="M17.3651 3.84172C16.9395 3.41589 16.4342 3.0781 15.8779 2.84763C15.3217 2.61716 14.7255 2.49854 14.1235 2.49854C13.5214 2.49854 12.9252 2.61716 12.369 2.84763C11.8128 3.0781 11.3074 3.41589 10.8818 3.84172L9.99847 4.72506L9.11514 3.84172C8.25539 2.98198 7.08933 2.49898 5.87347 2.49898C4.65761 2.49898 3.49155 2.98198 2.6318 3.84172C1.77206 4.70147 1.28906 5.86753 1.28906 7.08339C1.28906 8.29925 1.77206 9.46531 2.6318 10.3251L3.51514 11.2084L9.99847 17.6917L16.4818 11.2084L17.3651 10.3251C17.791 9.89943 18.1288 9.39407 18.3592 8.83785C18.5897 8.28164 18.7083 7.68546 18.7083 7.08339C18.7083 6.48132 18.5897 5.88514 18.3592 5.32893C18.1288 4.77271 17.791 4.26735 17.3651 3.84172V3.84172Z"
                                                  stroke="currentColor"
                                                  stroke-width="1.5"
                                                  stroke-linecap="round"
                                                  stroke-linejoin="round"
                                              />
                                          </svg>
                                      </div>
                                      <p class="text-base">Danh sách yêu thích</p>
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
    name: "NabarComponet",
    data() {
        return {
            menu: false,
            search: false,
            options: false
        };
    }
};
</script>