<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
    name: "StakingBox"
})
</script>
<template>
    <div class="p-4 p-md-5 py-md-4 row w-100">
        <div class="col-12 col-lg-6">
            <div class="shadow-sm bg-gradient bg-warning text-white _border rounded mt-5 mt-md-0"
                style="min-height: 200px;">
                <div class="border-bottom p-3 fw-bold text-center">
                    STATS FOR 25!NFT-600NFT HOLDERS
                </div>
                <div class="d-flex justify-content-between align-items-center h-100 p-3 px-4 fs-5">
                    <div class="text-center pt-4 my-auto">
                        STAKED NFT<br>
                        <span class="fw-bold">
                            0
                        </span>
                    </div>
                    <span class="text-center pt-4">
                        APY<br>
                        <span class="fw-bold">
                            6000%
                        </span>
                    </span>
                </div>
            </div>
        </div>
        <div class="col-12 col-sm-6 col-lg-3">
            <div class="shadow mt-4 mt-lg-0 rounded bg-primary bg-gradient text-white">
                <div class="border-bottom p-3 fw-bold text-center">
                    MY NFT STAKE
                </div>
                <div class="text-center py-4 fs-4">
                    0 NFT
                </div>
                <div class="d-flex justify-content-between px-3 pb-3">
                    <span class=" btn btn-warning bg-gradient">
                        STAKE NFT
                    </span>
                    <span class=" btn bg-gradient btn-warning ms-3">
                        UNSTAKE NFT
                    </span>
                </div>
            </div>
        </div>
        <div class="col-12 col-sm-6 col-lg-3">
            <div class="mt-4 mt-lg-0 shadow bg-gradient bg-primary text-white rounded">
                <div class="border-bottom p-3 px-5 fw-bold text-center">
                    MY REWARDS
                </div>
                <div class="text-center py-4 fs-4">
                    0 ARB
                </div>
                <div class="px-3 pb-3 text-center d-flex justify-content-center">
                    <div class=" btn btn-warning bg-gradient">
                        CLAIM REWARDS
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>