<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
    name: 'BoxComponent'
})
</script>

<style></style>

<template>
    <div class="p-4 px-md-5 mx-auto d-flex flex-wrap ">
        <div class="d-flex w-100 fw-bold justify-content-between p-3 shadow bg-gradient bg-warning rounded">
            <span>
                Public Mint Funds
            </span>
            <span>
                100%
            </span>
        </div>
        <div style="line-height: 40px;" class="d-flex w-100 text-white justify-content-between p-3 my-2 shadow-sm bg-gradient bg-primary fw-bold rounded">
            <div class="text-start">
                Staking Reward Pool<br>
                Marketing Pool
            </div>
            <div class="text-start fw-bold" >
                100%<br>
                100%
            </div>
        </div>
    </div>
</template>
