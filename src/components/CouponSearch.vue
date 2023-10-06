<script setup>
import { ref } from "vue";
let isSearchingCoupons = ref(false);

function handleClickBtnSearch() {
	isSearchingCoupons.value = !isSearchingCoupons.value;
}
</script>

<template>
	<section class="container mt-3">
		<div class="d-flex justify-content-between coupon__search">
			<div class="d-flex align-items-center gap-3">
				<div class="coupon__search--span"></div>
				<h1 v-show="isSearchingCoupons === false" class="coupon__search--title">
					Cupones
				</h1>
				<input
					v-show="isSearchingCoupons === true"
					type="text"
					placeholder="Nombre del establecimiento..."
				/>
			</div>
			<div class="d-flex gap-2">
				<button
					v-show="isSearchingCoupons === false"
					class="coupon__search--button-edit"
				>
					<img
						src="/public/icons/coupons-icons-page/card-edit.png"
						alt="Icono editar"
					/>
				</button>
				<button
					@click="handleClickBtnSearch"
					class="coupon__search--button-search"
				>
					<img
						src="/public/icons/coupons-icons-page/search-normal.svg"
						alt="Icono buscar"
					/>
				</button>
			</div>
		</div>
		<h3 class="coupon__search--h3 mt-3">Explora tus cupones</h3>
	</section>
</template>

<style lang="scss" scoped>
@import "@/scss/components/coupon-search.scss";
</style>
