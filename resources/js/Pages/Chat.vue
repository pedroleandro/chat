<template>
    <app-layout title="Chat">
        <template #header>
            <h2 class="font-semibold text-xl text-gray-800 leading-tight">
                Chat Realtime
            </h2>
        </template>

        <div class="py-12">
            <div class="max-w-7xl mx-auto sm:px-6 lg:px-8">
                <div class="bg-white overflow-hidden shadow-xl sm:rounded-lg flex" style="min-height: 400px; max-height: 400px;">
                    <!--                    Listagem de usuários-->
                    <div class="w-3/12 bg-gray-200 bg-opacity-25 border-r border-gray-200 overflow-y-scroll">
                        <ul>
                            <li class="p-6 text-lg text-gray-600 leading-7 font-semibold border-b border-gray-200 hover:bg-gray-200 hover:bg-opacity-50 hover:cursor-pointer">
                                <p class="flex items-center">
                                    Tiago Pereira
                                    <span class="ml-2 w-2 h-2 bg-blue-500 rounded-full"></span>
                                </p>
                            </li>
                            <li class="p-6 text-lg text-gray-600 leading-7 font-semibold border-b border-gray-200 hover:bg-gray-200 hover:bg-opacity-50 hover:cursor-pointer">
                                <p class="flex items-center">
                                    Thiago da Cruz
                                    <span class="ml-2 w-2 h-2 bg-blue-500 rounded-full"></span>
                                </p>
                            </li>
                            <li class="p-6 text-lg text-gray-600 leading-7 font-semibold border-b border-gray-200 hover:bg-gray-200 hover:bg-opacity-50 hover:cursor-pointer">
                                <p class="flex items-center">
                                    Gerson James
                                    <span class="ml-2 w-2 h-2 bg-blue-500 rounded-full"></span>
                                </p>
                            </li>
                            <li class="p-6 text-lg text-gray-600 leading-7 font-semibold border-b border-gray-200 hover:bg-gray-200 hover:bg-opacity-50 hover:cursor-pointer">
                                <p class="flex items-center">
                                    Juan Carlos
                                    <span class="ml-2 w-2 h-2 bg-blue-500 rounded-full"></span>
                                </p>
                            </li>
                            <li class="p-6 text-lg text-gray-600 leading-7 font-semibold border-b border-gray-200 hover:bg-gray-200 hover:bg-opacity-50 hover:cursor-pointer">
                                <p class="flex items-center">
                                    Airton Sousa
                                    <span class="ml-2 w-2 h-2 bg-blue-500 rounded-full"></span>
                                </p>
                            </li>
                            <li class="p-6 text-lg text-gray-600 leading-7 font-semibold border-b border-gray-200 hover:bg-gray-200 hover:bg-opacity-50 hover:cursor-pointer">
                                <p class="flex items-center">
                                    João Pedro
                                    <span class="ml-2 w-2 h-2 bg-blue-500 rounded-full"></span>
                                </p>
                            </li>
                            <li class="p-6 text-lg text-gray-600 leading-7 font-semibold border-b border-gray-200 hover:bg-gray-200 hover:bg-opacity-50 hover:cursor-pointer">
                                <p class="flex items-center">
                                    Helano Miguel
                                    <span class="ml-2 w-2 h-2 bg-blue-500 rounded-full"></span>
                                </p>
                            </li>
                            <li class="p-6 text-lg text-gray-600 leading-7 font-semibold border-b border-gray-200 hover:bg-gray-200 hover:bg-opacity-50 hover:cursor-pointer">
                                <p class="flex items-center">
                                    Luis Fernando Maia
                                    <span class="ml-2 w-2 h-2 bg-blue-500 rounded-full"></span>
                                </p>
                            </li>
                        </ul>
                    </div>
                    <!--                    Mensagens-->
                    <div class="w-9/12 flex flex-col justify-between">

                        <div class="w-full p-6 flex flex-col overflow-y-scroll">
                            <div class="w-full mb-3 text-right">
                                <p class="inline-block p-2 rounded-md messageSent" style="max-width: 75%;">
                                    Olá
                                </p>
                                <span class="block mt-1 text-xs text-gray-500">
                                    01/03/2022 13:42
                                </span>
                            </div>
                            <div class="w-full mb-3">
                                <p class="inline-block p-2 rounded-md messageReceive" style="max-width: 75%;">
                                    E ai
                                </p>
                                <span class="block mt-1 text-xs text-gray-500">
                                    01/03/2022 13:42
                                </span>
                            </div>
                            <div class="w-full mb-3 text-right">
                                <p class="inline-block p-2 rounded-md messageSent" style="max-width: 75%;">
                                    Olá
                                </p>
                                <span class="block mt-1 text-xs text-gray-500">
                                    01/03/2022 13:42
                                </span>
                            </div>
                            <div class="w-full mb-3">
                                <p class="inline-block p-2 rounded-md messageReceive" style="max-width: 75%;">
                                    E ai
                                </p>
                                <span class="block mt-1 text-xs text-gray-500">
                                    01/03/2022 13:42
                                </span>
                            </div>
                            <div class="w-full mb-3 text-right">
                                <p class="inline-block p-2 rounded-md messageSent" style="max-width: 75%;">
                                    Olá
                                </p>
                                <span class="block mt-1 text-xs text-gray-500">
                                    01/03/2022 13:42
                                </span>
                            </div>
                            <div class="w-full mb-3">
                                <p class="inline-block p-2 rounded-md messageReceive" style="max-width: 75%;">
                                    E ai
                                </p>
                                <span class="block mt-1 text-xs text-gray-500">
                                    01/03/2022 13:42
                                </span>
                            </div>
                            <div class="w-full mb-3 text-right">
                                <p class="inline-block p-2 rounded-md messageSent" style="max-width: 75%;">
                                    Olá
                                </p>
                                <span class="block mt-1 text-xs text-gray-500">
                                    01/03/2022 13:42
                                </span>
                            </div>
                            <div class="w-full mb-3">
                                <p class="inline-block p-2 rounded-md messageReceive" style="max-width: 75%;">
                                    E ai
                                </p>
                                <span class="block mt-1 text-xs text-gray-500">
                                    01/03/2022 13:42
                                </span>
                            </div>
                            <div class="w-full mb-3 text-right">
                                <p class="inline-block p-2 rounded-md messageSent" style="max-width: 75%;">
                                    Olá
                                </p>
                                <span class="block mt-1 text-xs text-gray-500">
                                    01/03/2022 13:42
                                </span>
                            </div>
                            <div class="w-full mb-3">
                                <p class="inline-block p-2 rounded-md messageReceive" style="max-width: 75%;">
                                    E ai
                                </p>
                                <span class="block mt-1 text-xs text-gray-500">
                                    01/03/2022 13:42
                                </span>
                            </div>
                            <div class="w-full mb-3 text-right">
                                <p class="inline-block p-2 rounded-md messageSent" style="max-width: 75%;">
                                    Olá
                                </p>
                                <span class="block mt-1 text-xs text-gray-500">
                                    01/03/2022 13:42
                                </span>
                            </div>
                            <div class="w-full mb-3">
                                <p class="inline-block p-2 rounded-md messageReceive" style="max-width: 75%;">
                                    E ai
                                </p>
                                <span class="block mt-1 text-xs text-gray-500">
                                    01/03/2022 13:42
                                </span>
                            </div>
                            <div class="w-full mb-3 text-right">
                                <p class="inline-block p-2 rounded-md messageSent" style="max-width: 75%;">
                                    Olá
                                </p>
                                <span class="block mt-1 text-xs text-gray-500">
                                    01/03/2022 13:42
                                </span>
                            </div>
                            <div class="w-full mb-3">
                                <p class="inline-block p-2 rounded-md messageReceive" style="max-width: 75%;">
                                    E ai
                                </p>
                                <span class="block mt-1 text-xs text-gray-500">
                                    01/03/2022 13:42
                                </span>
                            </div>
                        </div>

                        <div class="w-full bg-gray-200 bg-opacity-25 p-6 border-t border-gray-200">
                            <form action="">
                                <div class="flex rounded-md overflow-hidden border border-gray-300">
                                    <input type="text" class="flex-1 px-4 py-2 text-sm focus:outline-none">
                                    <button type="submit" class="ml-0.5 bg-indigo-500 hover:bg-indigo-600 text-white px-4 py-2">
                                        Enviar
                                    </button>
                                </div>
                            </form>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </app-layout>
</template>

<script>
import {defineComponent} from 'vue'
import AppLayout from '@/Layouts/AppLayout.vue'

export default defineComponent({
    components: {
        AppLayout,
    },
})
</script>
