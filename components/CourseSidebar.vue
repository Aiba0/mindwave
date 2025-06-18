<template>
  <div class="w-96 ml-6 bg-white border border-gray-200 h-screen overflow-y-auto">
    <div class="px-6 border-b border-gray-200">
      <div class="flex items-center justify-between items-center p-4">
        <h3 class="text-lg font-semibold text-gray-900">Course Contents</h3>
        <span class="text-sm text-green-600 font-medium">15% Completed</span>
      </div>
    </div>

    <div>
      <div>
        <div class="border-b border-gray-200">
          <button class="w-full flex items-center justify-between p-4 text-left bg-gray-100">
            <div class="flex items-center">
              <svg class="w-4 h-4 text-blue-600 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"/>
              </svg>
              <span class="font-medium text-blue-500">Getting Started</span>
            </div>
            <div class="flex items-center text-[12px] text-gray-500">
              <svg class="w-4 h-4 mr-1" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"/>
              </svg>
              <span>4 lectures</span>
              <span class="mx-2">•</span>
              <span>51m</span>
              <span class="mx-2">•</span>
              <span>25% finish (1/4)</span>
            </div>
          </button>

          <div class="px-4 pb-4">
            <div class="space-y-2">
              <div class="flex items-center p-3">
                <div class="w-6 h-6 bg-blue-600 flex items-center justify-center mr-3">
                  <svg class="w-4 h-4 text-white" fill="currentColor" viewBox="0 0 24 24">
                    <path d="M9 16.17L4.83 12l-1.42 1.41L9 19 21 7l-1.41-1.41z"/>
                  </svg>
                </div>
                <div class="flex-1">
                  <div class="text-sm font-medium text-gray-900">1. What is Webflow?</div>
                </div>
                <span class="text-sm text-gray-500">07:31</span>
              </div>

              <div class="flex items-center p-3 hover:bg-gray-50 -lg">
                <div class="w-6 h-6 border-2 border-gray-300  mr-3"></div>
                <div class="flex-1">
                  <div class="text-sm text-gray-700">What is Webflow?</div>
                </div>
                <span class="text-sm text-gray-500">07:31</span>
              </div>

              <div class="flex items-center p-3 hover:bg-gray-50 -lg">
                <div class="w-6 h-6 border-2 border-gray-300  mr-3"></div>
                <div class="flex-1">
                  <div class="text-sm text-gray-700">What is Webflow?</div>
                </div>
                <span class="text-sm text-gray-500">07:31</span>
              </div>
            </div>
          </div>
        </div>

<!--        <div class="border-b border-gray-200">-->
<!--          <button class="w-full flex items-center justify-between p-4 text-left hover:bg-gray-50">-->
<!--            <div class="flex items-center">-->
<!--              <div class="w-6 h-6 border-2 border-gray-300  mr-3"></div>-->
<!--              <span class="text-gray-700">2. Sign up in Webflow</span>-->
<!--            </div>-->
<!--            <span class="text-sm text-gray-500">07:31</span>-->
<!--          </button>-->
<!--        </div>-->

<!--        <div class="border-b border-gray-200">-->
<!--          <button class="w-full flex items-center justify-between p-4 text-left hover:bg-gray-50">-->
<!--            <div class="flex items-center">-->
<!--              <div class="w-6 h-6 border-2 border-gray-300  mr-3"></div>-->
<!--              <span class="text-gray-700">3. Teaser of Webflow</span>-->
<!--            </div>-->
<!--          </button>-->
<!--        </div>-->

<!--        <div class="border-b border-gray-200">-->
<!--          <button class="w-full flex items-center justify-between p-4 text-left hover:bg-gray-50">-->
<!--            <div class="flex items-center">-->
<!--              <div class="w-6 h-6 border-2 border-gray-300  mr-3"></div>-->
<!--              <span class="text-gray-700">4. Figma Introduction</span>-->
<!--            </div>-->
<!--          </button>-->
<!--        </div>-->

        <div class="border-b border-gray-200">
          <button class="w-full flex items-center justify-between p-4 text-left hover:bg-gray-50">
            <div class="flex items-center">
              <svg class="w-4 h-4 text-gray-400 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"/>
              </svg>
              <span class="text-gray-700">Secret of Good Design</span>
            </div>
            <div class="flex items-center text-[12px] text-gray-500">
              <svg class="w-4 h-4 mr-1" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"/>
              </svg>
              <span>52 lectures</span>
              <span class="mx-2">•</span>
              <span>5h 49m</span>
            </div>
          </button>
        </div>

        <div class="border-b border-gray-200">
          <button class="w-full flex items-center justify-between p-4 text-left hover:bg-gray-50">
            <div class="flex items-center">
              <svg class="w-4 h-4 text-gray-400 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"/>
              </svg>
              <span class="text-gray-700">Practice Design Like an Artist</span>
            </div>
            <div class="flex items-center text-[12px] text-gray-500">
              <svg class="w-4 h-4 mr-1" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"/>
              </svg>
              <span>43 lectures</span>
              <span class="mx-2">•</span>
              <span>51m</span>
            </div>
          </button>
        </div>

        <div class="border-b border-gray-200">
          <button class="w-full flex items-center justify-between p-4 text-left hover:bg-gray-50">
            <div class="flex items-center">
              <svg class="w-4 h-4 text-gray-400 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"/>
              </svg>
              <span class="text-gray-700">Web Development (webflow)</span>
            </div>
            <div class="flex items-center text-[12px] text-gray-500">
              <svg class="w-4 h-4 mr-1" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"/>
              </svg>
              <span>137 lectures</span>
              <span class="mx-2">•</span>
              <span>10h 6m</span>
            </div>
          </button>
        </div>

        <div class="border-b border-gray-200">
          <button class="w-full flex items-center justify-between p-4 text-left hover:bg-gray-50">
            <div class="flex items-center">
              <svg class="w-4 h-4 text-gray-400 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"/>
              </svg>
              <span class="text-gray-700">Secrets of Making Money Freelancing</span>
            </div>
            <div class="flex items-center text-[12px] text-gray-500">
              <svg class="w-4 h-4 mr-1" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"/>
              </svg>
              <span>21 lectures</span>
              <span class="mx-2">•</span>
              <span>38m</span>
            </div>
          </button>
        </div>

        <div class="border-b border-gray-200">
          <button class="w-full flex items-center justify-between p-4 text-left hover:bg-gray-50">
            <div class="flex items-center">
              <svg class="w-4 h-4 text-gray-400 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"/>
              </svg>
              <span class="text-gray-700">Advanced</span>
            </div>
            <div class="flex items-center text-[12px] text-gray-500">
              <svg class="w-4 h-4 mr-1" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"/>
              </svg>
              <span>34 lectures</span>
              <span class="mx-2">•</span>
              <span>1h 33m</span>
            </div>
          </button>
        </div>

        <div class="border-b border-gray-200">
          <button class="w-full flex items-center justify-between p-4 text-left hover:bg-gray-50">
            <div class="flex items-center">
              <svg class="w-4 h-4 text-gray-400 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"/>
              </svg>
              <span class="text-gray-700">What's Next</span>
            </div>
            <div class="flex items-center text-[12px] text-gray-500">
              <svg class="w-4 h-4 mr-1" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"/>
              </svg>
              <span>7 lectures</span>
              <span class="mx-2">•</span>
              <span>1h 17m</span>
            </div>
          </button>
        </div>
      </div>
    </div>
  </div>
</template>