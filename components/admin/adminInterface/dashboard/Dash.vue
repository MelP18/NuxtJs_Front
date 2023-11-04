<template>
    <div class="dashboard__component  ">
        <div class="dashboard">
            <div class="dashboard__content flex flex-col gap-12">
                <div class="dashboard__top w-full flex flex-wrap gap-8">
                    <Project/>
                    <Customer/>
                    <File/>
                </div>
                <div class="dashboard__midlle w-full">
                    <Report/>
                </div>
                <div class="dashboard__bottom w-full mt-8 flex flex-wrap gap-8">
                  <Message/>
                    <Document/>
                    <NewCustomer/>
                </div>
            </div>
        </div>
    </div>
</template>


<script lang="ts" setup>
import Customer from './Customer.vue'
import Project from './Project.vue'
import File from './File.vue'
import Report from './Report.vue'
import Message from './Message.vue'
import Document from './Document.vue'
import NewCustomer from './NewCustomer.vue'
</script>
