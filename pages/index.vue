<template>
  <div class="min-h-screen bg-gray-200 antialiased">
    <Header />
    <SearchFilters />
    <main class="py-6">
      <div class="px-4">
        <h3 class="text-gray-900 text-x1">Los Angeles</h3>
        <p class="text-gray-600">
          Live like the stars in these luxurious Southern California estate
        </p>
      </div>
      <div class="px-4 mt-5 sm:flex sm:-mx-2 sm:overflow-x-auto sm:pb-8">
        <!-- eslint-disable vue/require-v-for-key, vue/no-unused-vars -->
        <div
          v-for="i in 4"
          :class="{ 'mt-10': i > 1 }"
          class="sm:mt-0 sm:max-w-xs sm:w-full sm:flex-shrink-0 sm:px-2"
        >
          <!-- eslint-enable vue/require-v-for-key, vue/no-unused-vars -->
          <div class="relative pb-5/6">
            <img
              class="absolute inset-0 rounded-lg shadow-md h-full object-cover"
              src="https://images.unsplash.com/photo-1512917774080-9991f1c4c750?ixlib=rb-1.2.1&auto=format&fit=crop&w=800&q=80"
            />
          </div>
          <div>
            <div class="relative px-4 -mt-16">
              <div class="bg-white rounded-lg px-4 py-4 shadow-lg">
                <div class="flex">
                  <span
                    class="inline-block px-2 py-1 leading-none bg-teal-200 text-teal-800 rounded-full font-semibold uppercase
                  tracking-wide text-xs"
                  >
                    Plus
                  </span>
                  <div
                    class="ml-2 text-xs text-gray-600 font-semibold uppercase tracking-wide"
                  >
                    3 beds &bull; 2 baths
                  </div>
                </div>
                <h4 class="mt-1 text-gray-900 font-semibold text-lg">
                  Modern home in city center
                </h4>
                <div class="mt-1">
                  <span class="text-gray-900">$1,400</span>
                  <span class="ml-1 text-sm text-gray-600">/wk</span>
                </div>
                <div class="mt-2 flex items-center text-sm text-gray-600">
                  <svg
                    class="h-4 w-4 fill-current text-teal-500"
                    viewBox="0 0 24 24"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      d="M8.128 19.825a1.586 1.586 0 0 1-1.643-.117 1.543 1.543 0 0 1-.53-.662 1.515 1.515 0 0 1-.096-.837l.736-4.247-3.13-3a1.514 1.514 0 0 1-.39-1.569c.09-.271.254-.513.475-.698.22-.185.49-.306.776-.35L8.66 7.73l1.925-3.862c.128-.26.328-.48.577-.633a1.584 1.584 0 0 1 1.662 0c.25.153.45.373.577.633l1.925 3.847 4.334.615c.29.042.562.162.785.348.224.186.39.43.48.704a1.514 1.514 0 0 1-.404 1.58l-3.13 3 .736 4.247c.047.282.014.572-.096.837-.111.265-.294.494-.53.662a1.582 1.582 0 0 1-1.643.117l-3.865-2-3.865 2z"
                    />
                  </svg>
                  <svg
                    class="h-4 w-4 fill-current text-teal-500"
                    viewBox="0 0 24 24"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      d="M8.128 19.825a1.586 1.586 0 0 1-1.643-.117 1.543 1.543 0 0 1-.53-.662 1.515 1.515 0 0 1-.096-.837l.736-4.247-3.13-3a1.514 1.514 0 0 1-.39-1.569c.09-.271.254-.513.475-.698.22-.185.49-.306.776-.35L8.66 7.73l1.925-3.862c.128-.26.328-.48.577-.633a1.584 1.584 0 0 1 1.662 0c.25.153.45.373.577.633l1.925 3.847 4.334.615c.29.042.562.162.785.348.224.186.39.43.48.704a1.514 1.514 0 0 1-.404 1.58l-3.13 3 .736 4.247c.047.282.014.572-.096.837-.111.265-.294.494-.53.662a1.582 1.582 0 0 1-1.643.117l-3.865-2-3.865 2z"
                    />
                  </svg>
                  <svg
                    class="h-4 w-4 fill-current text-teal-500"
                    viewBox="0 0 24 24"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      d="M8.128 19.825a1.586 1.586 0 0 1-1.643-.117 1.543 1.543 0 0 1-.53-.662 1.515 1.515 0 0 1-.096-.837l.736-4.247-3.13-3a1.514 1.514 0 0 1-.39-1.569c.09-.271.254-.513.475-.698.22-.185.49-.306.776-.35L8.66 7.73l1.925-3.862c.128-.26.328-.48.577-.633a1.584 1.584 0 0 1 1.662 0c.25.153.45.373.577.633l1.925 3.847 4.334.615c.29.042.562.162.785.348.224.186.39.43.48.704a1.514 1.514 0 0 1-.404 1.58l-3.13 3 .736 4.247c.047.282.014.572-.096.837-.111.265-.294.494-.53.662a1.582 1.582 0 0 1-1.643.117l-3.865-2-3.865 2z"
                    />
                  </svg>
                  <svg
                    class="h-4 w-4 fill-current text-teal-500"
                    viewBox="0 0 24 24"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      d="M8.128 19.825a1.586 1.586 0 0 1-1.643-.117 1.543 1.543 0 0 1-.53-.662 1.515 1.515 0 0 1-.096-.837l.736-4.247-3.13-3a1.514 1.514 0 0 1-.39-1.569c.09-.271.254-.513.475-.698.22-.185.49-.306.776-.35L8.66 7.73l1.925-3.862c.128-.26.328-.48.577-.633a1.584 1.584 0 0 1 1.662 0c.25.153.45.373.577.633l1.925 3.847 4.334.615c.29.042.562.162.785.348.224.186.39.43.48.704a1.514 1.514 0 0 1-.404 1.58l-3.13 3 .736 4.247c.047.282.014.572-.096.837-.111.265-.294.494-.53.662a1.582 1.582 0 0 1-1.643.117l-3.865-2-3.865 2z"
                    />
                  </svg>
                  <svg
                    class="h-4 w-4 fill-current text-teal-500"
                    viewBox="0 0 24 24"
                    xmlns="http://www.w3.org/2000/svg"
                  >
                    <path
                      d="M8.128 19.825a1.586 1.586 0 0 1-1.643-.117 1.543 1.543 0 0 1-.53-.662 1.515 1.515 0 0 1-.096-.837l.736-4.247-3.13-3a1.514 1.514 0 0 1-.39-1.569c.09-.271.254-.513.475-.698.22-.185.49-.306.776-.35L8.66 7.73l1.925-3.862c.128-.26.328-.48.577-.633a1.584 1.584 0 0 1 1.662 0c.25.153.45.373.577.633l1.925 3.847 4.334.615c.29.042.562.162.785.348.224.186.39.43.48.704a1.514 1.514 0 0 1-.404 1.58l-3.13 3 .736 4.247c.047.282.014.572-.096.837-.111.265-.294.494-.53.662a1.582 1.582 0 0 1-1.643.117l-3.865-2-3.865 2z"
                    />
                  </svg>
                  <span class="ml-2">
                    34 reviews
                  </span>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </main>
  </div>
</template>

<script>
import Header from '~/components/Header'
import SearchFilters from '~/components/SearchFilters'

export default {
  components: {
    Header,
    SearchFilters
  }
}
</script>
