<template>
    <div class="w-full h-screen flex overflow-hidden">

        <div class="flex flex-col justify-around items-center w-3/6 h-full">
            <div>
                <h2 class="font-bold">Bienvenue Administrateur</h2>
            </div>
            <slot />
            <div class="flex gap-2">
                <p>Mot de passe oublié? Créer un </p>
                <NuxtLink to="" class="text-[#01A4AE] font-bold"> nouveau</NuxtLink>
            </div>
        </div>
        <div class="w-3/6 bg-[#EDDBC8] w-full h-full flex justify-center items-center">
            <masterAdminAuthMasterRight/>
        </div>
    </div>
</template>