<template>
  <Head>
    <Title>Home</Title>
  </Head>

  <div class="flex flex-col items-center px-10">
    <h1 class="text-2xl font-semibold text-slate-50">Hello, World! 🥳</h1>
    <h2 class="font-medium text-slate-200">
      Este é um template de
      <strong class="font-semibold text-green-400">Nuxt 3</strong> para iniciar
      projetos simples, porém escalonável.
    </h2>
    <div class="w-full flex-col pt-5">
      <h3 class="text-left text-sm font-semibold text-green-400">
        O template conta com
      </h3>
      <ul class="flex justify-around pt-3">
        <li>
          <a
            class="flex h-24 w-24 flex-col items-center justify-center gap-2 rounded text-slate-50 hover:bg-slate-800 lg:h-28 lg:w-28"
            href="https://nuxt.com"
            target="_blank"
          >
            <IconNuxt class="w-12 lg:w-16" />
            <span>Nuxt 3</span>
          </a>
        </li>
        <li>
          <a
            class="flex h-24 w-24 flex-col items-center justify-center gap-2 rounded text-slate-50 hover:bg-slate-800 lg:h-28 lg:w-28"
            href="https://tailwindcss.com"
            target="_blank"
          >
            <IconTailwindCSS class="w-12 lg:w-16" />
            <span>Nuxt 3</span>
          </a>
        </li>
        <li>
          <a
            class="flex h-24 w-24 flex-col items-center justify-center gap-2 rounded text-slate-50 hover:bg-slate-800 lg:h-28 lg:w-28"
            href="https://www.typescriptlang.org"
            target="_blank"
          >
            <IconTypeScript class="w-12 lg:w-16" />
            <span>TypeScript</span>
          </a>
        </li>
      </ul>
      <p class="mt-3 text-center text-sm font-medium text-slate-400">
        Além de: Heroicons, Husky, Commitizen e Prettier.
      </p>
    </div>
  </div>
</template>
