<template>
  <div class="relative w-full flex min-h-screen flex-col justify-center overflow-hidden bg-gray-50 py-6 sm:py-12">
    <div class="relative bg-white px-6 pt-10 pb-8 shadow-xl ring-1 ring-gray-900/5 sm:mx-auto sm:max-w-lg sm:rounded-lg sm:px-10">
      <div class="mx-auto max-w-md">
        <p class="pt-12 font-bold text-xl text-gray-600">Emacs Applications Framework</p>
        <div class="divide-y divide-gray-300/50">
          <div class="space-y-6 py-8 text-base leading-7 text-gray-600">
            <p class="pt-8 text-base">It will be the key to ultimately Live in Emacs</p>
            <ul class="space-y-4">
              <li class="flex items-center">
                <svg class="h-6 w-6 flex-none fill-sky-100 stroke-sky-500 stroke-2" stroke-linecap="round" stroke-linejoin="round">
                  <circle cx="12" cy="12" r="11" />
                  <path d="m8 13 2.165 2.165a1 1 0 0 0 1.521-.126L16 9" fill="none" />
                </svg>
                <p class="ml-4">
                  Writing Multimedia Applications for Emacs with Qt and Web technology.
                </p>
              </li>
              <li class="flex items-center">
                <svg class="h-6 w-6 flex-none fill-sky-100 stroke-sky-500 stroke-2" stroke-linecap="round" stroke-linejoin="round">
                  <circle cx="12" cy="12" r="11" />
                  <path d="m8 13 2.165 2.165a1 1 0 0 0 1.521-.126L16 9" fill="none" />
                </svg>
                <p class="ml-4">
                  Support multithreading, never get stuck in Emacs
                </p>
              </li>
              <li class="flex items-center">
                <svg class="h-6 w-6 flex-none fill-sky-100 stroke-sky-500 stroke-2" stroke-linecap="round" stroke-linejoin="round">
                  <circle cx="12" cy="12" r="11" />
                  <path d="m8 13 2.165 2.165a1 1 0 0 0 1.521-.126L16 9" fill="none" />
                </svg>
                <p class="ml-4">
                  Multilingual Collaborative Programming, including Elisp, Python, C++, NodeJS, WASM etc.
                </p>
              </li>
            </ul>
            <p>This is Tailwindcss demo for EAF, all config is out of box, you can write tailwindcss applications directly!</p>
          </div>
          <div class="pt-8 text-base font-semibold leading-7">
            <p class="text-gray-900">Support more than 20 high-quality applications</p>
            <p>
              <a href="https://github.com/orgs/emacs-eaf/repositories" class="text-sky-500 hover:text-sky-600">And more &rarr;</a>
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
 export default {
   name: 'HelloWorld',
 }
</script>
