<template>
	<section class="container mt-5 tdu__card">
		<div class="d-flex gap-4 mb-3 align-items-center">
			<img
				src="/public/icons/global-icons/title-tag.png"
				alt="Icono del titulo"
			/>
			<h2 class="tdu__card--h2">Mi tarjeta TDU</h2>
		</div>
		<p class="tdu__card--p">
			Solo presenta tu Tarjeta antes de pedir la cuenta nota o factura y obtén
			desde 10% hasta 50% de descuento.
		</p>
		<div class="d-flex mb-3">
			<img src="/public/images/my-tdu-card.png" alt="Imagen del cupón" />
			<button>
				<img
					src="/public/icons/my-tdu-card/arrow-top.png"
					alt="Icono manito hacia arriba"
				/>
			</button>
		</div>
		<button class="d-flex tdu__card--button gap-3">
			<p>Ver Tutorial</p>
			<img
				src="/public/icons/my-tdu-card/arrow-right.svg"
				alt="Icono del botón para ver el tutorial"
			/>
		</button>
	</section>
</template>

<style lang="scss" scoped>
@import "@/scss/components/my-tdu-card.scss";
</style>
