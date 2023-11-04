<template>
    <div class="document__component flex flex-col gap-5">
        <div class="text-xl font-bold">
            <h2>Documents</h2>
        </div>
        <div class="flex gap-5">
            <TableDocument/>
            <NewDocument/>
        </div>
        
    </div>

   
</template>

<script lang="ts" setup>
    import TableDocument from './TableDocument.vue';
    import NewDocument from './NewDocument.vue';
</script>