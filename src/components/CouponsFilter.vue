<template>
	<section class="container coupons__filter mt-3">
		<div class="d-flex align-items-center gap-4">
			<img
				src="/public/icons/coupons-filter/title-tag.png"
				alt="Icono del titulo"
			/>
			<h2>
				Agrega o escoge <br />
				una dirección
			</h2>
		</div>
		<div class="d-flex gap-2 mt-4">
			<div class="coupons__card--location p-4">
				<img
					src="/public/icons/coupons-filter/blue-arrow.svg"
					alt="Icono establecimientos cerca"
				/>
			</div>
			<button class="coupons__filter--button">
				Ver establecimientos cerca de mí
			</button>
		</div>
		<hr class="my-5" />
		<div class="coupons__filter--select mb-4">
			<select name="estado" id="">
				<option value="">Estado</option>
			</select>
			<select name="ciudad" id="">
				<option value="">Ciudad</option>
			</select>
		</div>
		<button class="d-flex button__search--direction">
			<img
				src="/public/icons/coupons-filter/location.svg"
				alt="Icono ubicación"
			/>
			Ingrese una nueva dirección
		</button>
		<button class="button__search--coupons">
			Ver cupones
			<img
				src="/public/icons/coupons-filter/search.svg"
				alt="Icono buscar cupones"
			/>
		</button>
	</section>
</template>

<style lang="scss" scoped>
@import "@/scss/components/coupons-filter.scss";
</style>
