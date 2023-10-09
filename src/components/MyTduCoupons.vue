<script setup></script>

<template>
	<section class="tdu__coupons pb-5">
		<div class="container">
			<div
				class="d-flex gap-4 justify-content-start align-items-center pt-5 ps-3 mb-4"
			>
				<img
					src="/public/icons/my-tdu-coupons/title-tag.png"
					alt="Icono decorativo para el texto"
				/>
				<p class="tdu__coupons--title">Mis cupones</p>
				<img
					src="/public/icons/my-tdu-coupons/tdu-logo.svg"
					alt="Logotipo TDU"
				/>
			</div>
			<p class="tdu__coupons--p ps-3 pb-3">
				Obtén beneficios adicionales para ti y tu familia en más de 10.000
				establecimientos a lo largo de la República Mexicana
			</p>
			<div class="container__coupons">
				<div class="coupon__card">
					<img
						class="coupon__card--img"
						src="/public/images/02.png"
						alt="Imagen del cupón"
					/>
					<div class="coupon__card--texts">
						<h3 class="coupon__card--h3">100 Montaditos</h3>
						<p class="coupon__card--p">En la cuenta local</p>
						<button class="coupon__card--btn">
							<img
								src="/public/icons/coupons-icons-page/button.png"
								alt="Icono del botón"
							/>
						</button>
					</div>
					<div class="coupon__card--span">
						<span>15% EFE.</span>
						<span>10% T.C.</span>
					</div>
				</div>
				<div class="coupon__card">
					<img
						class="coupon__card--img"
						src="/public/images/03.png"
						alt="Imagen del cupón"
					/>
					<div class="coupon__card--texts">
						<h3 class="coupon__card--h3">A Todo Mar</h3>
						<p class="coupon__card--p">En la cuenta local</p>
						<button class="coupon__card--btn">
							<img
								src="/public/icons/coupons-icons-page/button.png"
								alt="Icono del botón"
							/>
						</button>
					</div>
					<div class="coupon__card--span">
						<span>15% EFE.</span>
						<span>10% T.C.</span>
					</div>
				</div>
				<div class="coupon__card">
					<img
						class="coupon__card--img"
						src="/public/images/04.png"
						alt="Imagen del cupón"
					/>
					<div class="coupon__card--texts">
						<h3 class="coupon__card--h3">7 Pecaos</h3>
						<p class="coupon__card--p">En la cuenta local</p>
						<button class="coupon__card--btn">
							<img
								src="/public/icons/coupons-icons-page/button.png"
								alt="Icono del botón"
							/>
						</button>
					</div>
					<div class="coupon__card--span">
						<span>15% EFE.</span>
						<span>10% T.C.</span>
					</div>
				</div>
				<div class="coupon__card">
					<img
						class="coupon__card--img"
						src="/public/images/01.jpg"
						alt="Imagen del cupón"
					/>
					<div class="coupon__card--texts">
						<h3 class="coupon__card--h3">Acriton Fester</h3>
						<p class="coupon__card--p">En la cuenta local</p>
						<button class="coupon__card--btn">
							<img
								src="/public/icons/coupons-icons-page/button.png"
								alt="Icono del botón"
							/>
						</button>
					</div>
					<div class="coupon__card--span">
						<span>15% EFE.</span>
						<span>10% T.C.</span>
					</div>
				</div>
			</div>
			<img
				src="/public/icons/my-tdu-coupons/dots.png"
				alt="Icono desplazamiento de las tarjetas"
				class="text-center mx-auto pb-5"
			/>
			<button class="tdu__coupons--btn text-center">
				Ver más
				<img
					src="/public/icons/my-tdu-coupons/arrow-right.svg"
					alt="Icono del botón ver más"
				/>
			</button>
		</div>
	</section>
</template>

<style lang="scss" scoped>
@import "@/scss/components/my-tdu-coupons.scss";
</style>
