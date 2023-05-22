<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
    name: 'BoxComponent',
    props:['value']
})
</script>

<style></style>

<template>
    <div class="p-4 px-md-5 mx-auto d-flex flex-wrap ">
        <div class="d-flex w-100 fw-bold justify-content-between p-3 shadow bg-gradient bg-warning rounded">
            <span>
                {{ value.title }}
            </span>
            <span>
                100%
            </span>
        </div>
        <div style="line-height: 40px;" class="d-flex w-100 text-white justify-content-between mt-2">
            <div class="text-start shadow-sm bg-gradient bg-primary fw-bold rounded p-3 my-2 w-100 me-2">
                Staking Reward Pool<br>
                Marketing Pool
            </div>
            <div class="text-start px-4 fw-bold text-start shadow-sm bg-gradient bg-primary fw-bold rounded p-3 my-2" >
                {{ value.stakePool}}<br>
                {{ value.marketingPool }}
            </div>
        </div>
    </div>
</template>
