<template>
    <div class="report__table__component h-full">
        <div class="flex flex-col gap-14">
            <div class="">
                <h2 class="text-xl font-bold">Suivi Notaire</h2>
            </div>
            <div class="flex flex-col gap-14">
                <div class="flex gap-2.5 items-center border border-black p-1 max-w-xl">
                    <NuxtLink to=""
                        class="py-1 px-4 bg-slate-700 rounded rounded-[4px] text-white font-bold whitespace-nowrap">Dossier
                        Réservation</NuxtLink>
                    <NuxtLink to=""
                        class="py-1 px-4 bg-gray-400 rounded rounded-[4px] text-white font-bold whitespace-nowrap">
                        Financement
                    </NuxtLink>
                    <NuxtLink to=""
                        class="py-1 px-4 bg-gray-400 rounded rounded-[4px] text-white font-bold whitespace-nowrap">
                        Préparation
                        Rendez-vous</NuxtLink>
                </div>
                <div>
                    <div v-for="item in customerReservation" class="flex gap-5">
                        <div class="flex flex-col items-center">
                            <div class="w-12 h-12 bg-gray-200 rounded-full flex items-center justify-center">
                                <i>{{ item.icon }}</i>
                            </div>
                            <hr :class="item.line">
                        </div>
                        <div class="mt-3">
                            <h5>{{ item.name }}</h5>
                        </div>
                    </div>
                </div>

            </div>

        </div>
    </div>
</template>

<script lang="ts" setup>
import { ref } from 'vue'
import { customerReservation } from '../../../database/customerReservation'
</script>

  

