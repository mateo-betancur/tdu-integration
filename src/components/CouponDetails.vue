<template>
	<section class="container">
		<div class="coupon__details">
			<img
				src="/public/icons/coupon-details/coupon-img.png"
				alt="Imagen el cupón"
				class="mx-auto"
			/>
			<div
				class="d-flex gap-3 justify-content-start coupon__details--prices mb-3"
			>
				<p>15% EFE.</p>
				<p>10% T.C.</p>
			</div>
			<div class="d-flex align-items-center coupon__personal--info mb-5">
				<div class="d-flex px-5 py-4 justify-content-between">
					<div class="coupon__personal--info">
						<p>Pepito Pérez Marriaga</p>
						<h3>Obtén tu beneficio TDU</h3>
						<p class="fw-bold">
							Valida hasta <span class="fw-light">09/24</span>
						</p>
					</div>
					<img
						src="/public/icons/coupon-details/tdu-logo.svg"
						alt="Icono TDU"
					/>
				</div>
				<img
					src="/public/icons/global-icons/arrow-top.png"
					alt="Mano hacia arriba"
					class="top__hand--icon mx-auto"
				/>
			</div>
			<div class="d-flex gap-3 mb-4 align-items-center">
				<img
					src="/public/icons/coupon-details/title-tag.png"
					alt="Etiqueta del titulo"
				/>
				<h2>[100 Montaditos]</h2>
			</div>
			<div class="coupons__details--p">
				<a
					href="https://www.tdu.com.mx/home"
					class="text-decoration-none coupon__detail--link d-block mb-4"
					>https://www.tdu.com.mx/home</a
				>
				<p>
					No es acumulable con otras promociones y/o descuentos. Válido en todas
					sus sucursales.
				</p>
				<h3 class="fw-bold mt-5 mb-4">Términos y condiciones</h3>
				<p>
					Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam
					nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat
					volutpat.
				</p>
			</div>
			<button class="d-flex mb-4 gap-3 align-items-center">
				<img
					src="/public/icons/coupon-details/location.svg"
					alt="Icono ubicación"
					class="location__icon"
				/>
				Ver sucursales
			</button>
		</div>
	</section>
</template>

<style lang="scss" scoped>
@import "@/scss/components/coupon-details.scss";
</style>
