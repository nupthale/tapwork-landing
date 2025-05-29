<script setup>
</script>

<template>
  <div class="relative w-full flex min-h-screen flex-col bg-background">
    <div class="flex min-h-screen flex-col">
      <header class="fixed top-0 z-50 w-full border-border/40 bg-background/95 backdrop-blur supports-[backdrop-filter]:bg-background/60">
        <div class="container flex h-14 max-w-screen-2xl items-center">
          <div class="flex gap-6 md:gap-10">
            <a class="hidden items-center space-x-2 md:flex mt-8" href="/">
              <span class="hidden font-bold sm:inline-block">
                <img src="./assets/logo4.png" alt="Logo" width="140px">
              </span>
            </a>
            <nav class="hidden gap-6 md:flex">
              <!-- <a class="flex items-center text-lg font-medium transition-colors hover:text-foreground/80 sm:text-sm text-foreground/60" href="/#features">Features</a>
              <a class="flex items-center text-lg font-medium transition-colors hover:text-foreground/80 sm:text-sm text-foreground/60" href="/pricing">Pricing</a>
              <a class="flex items-center text-lg font-medium transition-colors hover:text-foreground/80 sm:text-sm text-foreground/60" href="/contact">Contact</a> -->
            </nav>
          </div>
        </div>
      </header>
      <main class="flex-1">
        <section class="relative py-20 overflow-hidden">
          <div class="absolute inset-0 overflow-hidden pointer-events-none">
            <div class="absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 w-[800px] h-[800px] opacity-30">
              <div class="absolute inset-0 rounded-full bg-gradient-to-r from-blue-400 to-purple-400 blur-3xl animate-blob"></div>
              <div class="absolute inset-0 rounded-full bg-gradient-to-r from-purple-400 to-pink-400 blur-3xl animate-blob animation-delay-2000"></div>
              <div class="absolute inset-0 rounded-full bg-gradient-to-r from-pink-400 to-blue-400 blur-3xl animate-blob animation-delay-4000"></div>
            </div>
          </div>
          <div class="relative container mx-auto px-4 text-center">
            <span class="inline-block px-4 py-2 rounded-full bg-white dark:bg-gray-800 text-gray-800 dark:text-gray-200 text-sm font-medium mb-8" style="opacity: 1; will-change: auto; transform: none; background: rgba(35,40,77,.05); backdrop-filter: blur(30px); box-shadow: rgba(0, 0, 0, 0.06) 0px 2px 4px 0px inset;">Help you complete document editing in minutes</span>
            <h1 class="text-4xl md:text-5xl lg:text-6xl font-bold text-gray-900 dark:text-white mb-8" style="opacity: 1; will-change: auto; transform: none; line-height: 80px;">
              Launch Document Editing<br>
              <span class="bg-clip-text text-transparent bg-gradient-to-r from-blue-600 to-purple-600 dark:from-blue-400 dark:to-purple-400" style="background: radial-gradient(95% 55.37% at 95% 28.12%,#8d55ed 0,#4752e6 100%); background-clip: text; color: transparent">Only Minutes</span>
            </h1>
            <div class="flex flex-col sm:flex-row items-center justify-center gap-4 mb-8" style="opacity: 1; will-change: auto; transform: none;">
              <a class="cursor-pointer">
                <img src="./assets/macappstore.svg" alt="macappstore" width="200px">
              </a>
            </div>
          <div class="max-w-5xl mx-auto">
            <div class="relative rounded-2xl overflow-hidden" style="opacity: 1; will-change: auto; transform: none; box-shadow: rgba(100, 100, 111, 0.2) 0px 7px 29px 0px;">
        
              <div class="relative bg-white dark:bg-gray-900 aspect-video">
                <div class="absolute left-3 top-2">
                  <div class="flex gap-2">
                    <div class="w-3 h-3 rounded-full bg-red-500"></div>
                    <div class="w-3 h-3 rounded-full bg-yellow-500"></div>
                    <div class="w-3 h-3 rounded-full bg-green-500"></div></div>
                </div>
                <img src="./assets/index2.png" class="w-full " />
                  
                </div>
              </div>
            </div>
          </div>
        </section>
      </main>
    </div>
  </div>
</template>

<style scoped>
.container {
    width: 100%;
    margin-right: auto;
    margin-left: auto;
    padding-right: 2rem;
    padding-left: 2rem;
}

@media (min-width: 1400px) {
    .container {
        max-width: 1400px;
    }
}

.bg-background\/95 {
  background: hsl(var(--background)/.6);
}
</style>
