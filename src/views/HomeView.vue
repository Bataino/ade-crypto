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
			<div class="sticky-top px-5 p-3 d-flex align-items-center justify-content-center px-2"
				style="background-color: lightgray;">
				<div class="text-center">
					<img alt="logo" class="rounded" width="100px" height="100px" src="/logo.jfif"><br>
				</div>
				<div class="text-end w-100 ">
					<div class="btn btn-primary bg-gradient float-right">
						CONNECT WALLET
					</div><br>
					<small class="text-dark">
						staking functionality goes live after public mint
					</small>
				</div>
			</div>
			<div class="row mx-auto bg-gradient py-4 _bg-secondary">
				<div class="col-12 col-lg-6">
					<div class="text-center py-5 mt-4 h-100">
						<img alt="logo" class="rounded-circle" width="300" height="300" src="/logo.jfif"><br>
						<div class="pt-5 pt-md-5 fs-5 fw-bold text-white">
							Join us for more ARB token reward
						</div>
					</div>
				</div>
				<div class="col-12 col-lg-6">
					<div class="p-3 px-3 px-md-5 fs-4 h-100 my-auto pt-3 pt-md-5 mt-md-5 text-start text-white">
						The First Optimised NFT staking on Arbitrum that reward NFT stakers in ARB token with a Juicy APY,
						where NFT and Staking meet to give a new use case to NFT
					</div>
				</div>
			</div>
		</div>


		<StakingBox :value='{
			nftType: "1NFT - 150NFT",
			nftStake: 0,
			apy: "1,500",
			myNft: 0,
			myRewards: 0
		}'>
		</StakingBox>

		<div class="py-5 mt-5"
			style="background-color: whitesmoke;margin-top: 100px !important;background-image: url('https://img.freepik.com/free-vector/realistic-white-monochrome-background_23-2149023989.jpg?w=740&t=st=1684620748~exp=1684621348~hmac=f5a4c15d96a60e479460ba61a673add900ab44706a459f7d5262d919496e0020');">
			<StakingBox :value='{
				nftType: "151NFT - 300NFT",
				nftStake: 0,
				apy: 3000,
				myNft: 0,
				myRewards: 0
			}'>
			</StakingBox>
			<StakingBox :value='{
				nftType: "301NFT - 500NFT",
				nftStake: 0,
				apy: "5000",
				myNft: 0,
				myRewards: 0
			}'>
			</StakingBox>
		</div>

		<div class="">
			<div style="" class="d-flex shadow-sm align-items-center bg-primary text-white p-3 p-md-4 py-3">
				<img alt="logo" class="rounded" width="70" height="70" src="/logo.jfif">
				<h4 class="ms-4 w-100 text-center">
					About Atom NFT
				</h4>
			</div>
			<div class="py-5 px-3 px-md-5" style="">
				<div _style="min-height: 1000px;" class="d-flex align-items-center p-md-3">
					<div class="rounded bg-primary bg-gradient text-white shadow p-5 my-md-5 p-md-5 mx-auto m-md-5 ">
						Atom NFT was born out of the idea that cryptocurrency profits and benefits should be for
						everyone
						That’s why we’re committed to create a welcoming NFT project welcoming all crypto
						traders/investors
						where
						everyone can participate to mint Atom NFT as cheap as 0.0006eth($1)/NFT in our public mint
						with a
						fair
						mint
						distribution and all NFT holders has the benefit to stake their NFT’s to earn ARB token
						after the
						public
						mint
						with a Juicy APY</div>
				</div>
			</div>
		</div>
		<div class="">
			<div class="d-flex align-items-center p-3 p-md-4 my-3 mb-5 justify-content-center">
				<img alt="logo" class="rounded" width="70" height="70" src="/logo.jfif">
				<h4 class="ms-4 text-white">
					Staking Reward Liquidity
				</h4>
			</div>
			<div class="shadow bg-white rounded p-2 mx-3 p-lg-5 mx-lg-5">
				<div class="row mx-auto w-100">
					<div class="col-12 col-lg-6">
						<BoxComponent :value='{
							title: "Public/Private Mint Funds",
							titlePercent: "100%",
							stakePool: "95%",
							marketingPool: "5%"
						}' class="w-100">
						</BoxComponent>
					</div>
					<div class="col-12 col-lg-6">
						<BoxComponent :value='{
							title: "Claim Reward Tax",
							titlePercent: "4%",
							stakePool: "3%",
							marketingPool: "1%"
						}' class="w-100">
						</BoxComponent>
					</div>
				</div>
			</div>
		</div>


		<div class="text-center p-4 pt-5 mt-4 bg-gradient bg-primary">
			<img alt="logo" class="rounded-circle" width="300" height="300" src="/logo.jfif" />
			<div class="mx-auto d-flex justify-content-center p-4">
				<a href="https://twitter.com/atom_earnARB" class="rounded-circle bg-success p-3">
					<icon icon="bi:twitter" class="fs-3 text-white">
					</icon>
				</a>
				<a href="https://discord.gg/rXWCPgr6ue" class="rounded-circle bg-success p-3 ms-5">
					<icon icon="ic:round-discord" class="fs-3 text-white">
					</icon>
				</a>
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