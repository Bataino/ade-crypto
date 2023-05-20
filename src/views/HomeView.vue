<script lang="ts">
import BoxComponent from "@/components/BoxComponent.vue"
import StakingBox from "@/components/StakingBox.vue"
import { Icon } from "@iconify/vue"
import { defineComponent } from 'vue';

export default defineComponent({
	components: { BoxComponent, StakingBox, icon: Icon }
})
</script>

<template>
	<div class="w-100">
		<div class="">
			<div style="background: whitesmoke;" class="d-flex shadow-sm align-items-center _bg-white p-3 p-md-4 pt-5">
				<img alt="logo" class="rounded" width="70px" height="70px" src="/logo.jfif">
				<h4 class="ms-4 w-100 text-center">
					About Atom NTF
				</h4>
			</div>
			<div class="p-5" style="background-image: url('https://img.freepik.com/free-vector/modern-technology-background-with-orange-dots_1035-7714.jpg?w=740&t=st=1684618714~exp=1684619314~hmac=e914e787bedf3ae3276cf71739a5cede05b1282f6011bdf9b6f1e03a877a87a6');">
				<div _style="min-height: 1000px;" class="d-flex align-items-center p-3">
					<div class="rounded bg-primary  bg-gradient text-white shadow p-5 py-5 my-5 p-md-5 mx-auto m-md-5 ">
						Atom NFT was born out of the idea that cryptocurrency profits and benefits should be for
						everyone
						That’s why we’re committed to create a welcoming NFT project welcoming all crypto
						traders/investors
						where
						everyone can participate to mint Atom NFT as cheap as 0.0008eth($1.5)/NFT in our public mint
						with a
						fair
						mint
						distribution and all NFT holders has the benefit to stake their NFT’s to earn ARB token
						after the
						public
						mint
						with a Juice APY</div>
				</div>
			</div>
		</div>
		<div class=" bg-white">
			<div class="d-flex align-items-center p-3 p-md-4 pt-5 mt-3 justify-content-center">
				<img alt="logo" class="rounded" width="100px" height="100px" src="/logo.jfif">
				<h3 class="ms-4">
					Staking Reward Liquidity
				</h3>
			</div>
			<div class="shadow bg-white rounded p-2 mx-5 p-lg-5 mx-lg-5">
				<div class="row mx-auto w-100">
					<div class="col-12 col-lg-6" v-for="x in [1, 2]">
						<BoxComponent class="w-100"></BoxComponent>
					</div>
				</div>
			</div>
		</div>
		<div class="py-5 my-5" style="background-color: whitesmoke;margin-top: 100px !important;background-image: url('https://img.freepik.com/free-vector/realistic-white-monochrome-background_23-2149023989.jpg?w=740&t=st=1684620748~exp=1684621348~hmac=f5a4c15d96a60e479460ba61a673add900ab44706a459f7d5262d919496e0020');">
			<StakingBox v-for="x in [1, 2]"></StakingBox>
		</div>
		<div class="_">
			<div class=" px-5 p-3 d-flex align-items-center justify-content-center px-2">
				<div class="text-center">
					<img alt="logo" class="rounded" width="100px" height="100px" src="/logo.jfif"><br>
				</div>
				<div class="text-end w-100 ">
					<div class="btn btn-primary bg-gradient float-right">
						CONNECT WALLET
					</div><br>
					<small>
						sharing functionality goes live after public mint
					</small>
				</div>
			</div>
			<div class="text-center py-5">
				<img alt="logo" class="rounded" width="100px" height="100px" src="/logo.jfif"><br>
				<div class="mt-3">
					Join us for more ARB token reward
				</div>
			</div>
			<div class="p-3 px-5">
				The First Optimised NFT staking on Arbitrum that reward NFT stakers in ARB token with a Juicy APY, where NFT
				and Staking meet to give a new use case to NFT
			</div>
		</div>
		<StakingBox></StakingBox>
		<div class="text-center p-4 bg-gradient bg-primary">
			<img alt="logo" class="rounded-circle" style="min-width: 200px;" width="200px" height="200px" src="/logo.jfif" />
			<div class="mx-auto d-flex justify-content-center p-4">
				<span class="rounded-circle bg-secondary p-3">
					<icon icon="bi:twitter" class="fs-3 text-white">
					</icon>
				</span>
				<span class="rounded-circle bg-secondary p-3 ms-3">
					<icon icon="icon-park-outline:telegram" class="fs-3 text-white">
					</icon>
				</span>
			</div>
		</div>
	</div>
</template>

<style>
.min-100vh {
	min-height: 100vh;
}

.min-60vh {
	min-height: 60vh;
}
</style>