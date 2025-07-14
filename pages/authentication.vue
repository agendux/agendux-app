<template>
    <section class="bg-white dark:bg-olive">
        <div class="flex flex-row items-center justify-between px-16 py-8 mx-auto md:h-screen lg:py-0">
            <div class="w-full rounded-lg border border-emerald-700 dark:border dark:border-emerald-500 md:mt-0 sm:max-w-md xl:p-0">
                <div class="p-6 space-y-4 md:space-y-6 sm:p-8">
                    <form class="space-y-4 md:space-y-6" action="#">
                        <div>
                            <label for="email" class="block mb-2 text-sm font-medium text-emerald-700 dark:text-emerald-500">Login</label>
                            <input type="email" name="email" id="email" placeholder="exemplo@email.com" class="indent-2 w-full py-2.5 rounded-lg border border-emerald-700 text-emerald-700 block dark:border-emerald-500 dark:placeholder-gray-500 dark:text-emerald-500">
                        </div>
                        <div>
                            <label for="password" class="block mb-2 text-sm font-medium text-emerald-700 dark:text-emerald-500">Senha</label>
                            <input type="password" name="password" id="password" placeholder="••••••••" class="indent-2 w-full py-2.5 rounded-lg border border-emerald-700 text-emerald-700 block dark:border-emerald-500 dark:placeholder-gray-500 dark:text-emerald-500">
                        </div>
                        <div class="flex items-center justify-between">
                            <div class="flex items-start">
                                <div class="flex items-center h-5">
                                    <input id="remember" aria-describedby="remember" type="checkbox" class="w-4 h-4 border rounded border-emerald-700 bg-white dark:border-emerald-500 dark:bg-olive">
                                </div>
                                <div class="ml-3 text-sm">
                                    <label for="remember" class="text-emerald-700 dark:text-emerald-500">Lembrar de mim</label>
                                </div>
                            </div>
                            <a href="#" class="text-sm hover:underline text-emerald-700 dark:text-emerald-500">Esqueceu sua senha?</a>
                        </div>
                        <button type="submit" class="w-full text-emerald-700 dark:text-emerald-500 bg-olive hover:bg-primary-700 focus:ring-4 focus:outline-none focus:ring-primary-300 font-medium rounded-lg text-sm px-5 py-2.5 text-center dark:bg-primary-600 dark:hover:bg-primary-700 dark:focus:ring-primary-800">Entrar</button>
                    </form>
                </div>
            </div>
            <div class="w-full rounded-lg border border-emerald-700 dark:border dark:border-emerald-500 md:mt-0 sm:max-w-md xl:p-0">
                <div class="p-6 space-y-4 md:space-y-6 sm:p-8">
                </div>
            </div>
        </div>
    </section>
</template>

<script setup lang="ts">
import '~/assets/css/config.css'
definePageMeta({
    layout: 'no-header'
})
</script>