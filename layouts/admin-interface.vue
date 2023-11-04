<template>
    <div class="wrapper overflow-x-hidden">
        <div class="wrapper__content">
            <div class="layouts">
                <masterAdminInterfaceHeader/>
            </div>
            <div class="flex">
                <masterAdminInterfaceSidebar/>
                <main>
                    <div class="main__content w-[calc(100vw_-_108px)] h-[calc(100vh_-_58.5px)] bg-[#F8F7F5] py-[35px] overflow-y-scroll overflow-x-hidden">
                        <div class="xl:container xl:mx-auto px-12">
                            <slot />
                        </div>   
                    </div>
                </main>  
            </div>
        </div>
    </div>
</template>

<script lang="ts" setup>

</script>