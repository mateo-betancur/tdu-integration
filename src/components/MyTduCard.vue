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
			Sólo presenta tu tarjeta antes de pedir la cuenta nota o factura y obtén
			desde 10% hasta 50% de descuento.
		</p>
		<div class="mb-3">
			<div class="top__card p-4">
				<div class="d-flex mb-4 justify-content-between">
					<img
						src="/public/icons/my-tdu-card/principal-logo.svg"
						alt="Logo de conectados"
					/>
					<img
						src="/public/icons/my-tdu-card/white-logo.svg"
						alt="Logo de TDU"
					/>
				</div>
				<h3 class="top__card--h3">6037 9975 9598 3090</h3>
			</div>
			<div class="bottom__card p-4 d-flex flex-column justify-content-end">
				<p class="mb-0">Pepito Pérez Marriaga</p>
				<div
					class="d-flex justify-content-between align-items-end bottom__card--texts"
				>
					<p class="bottom__card--date">
						Valida hasta <br />
						<span>09/24</span>
					</p>
					<p class="bottom__card--cvv">
						CVV <br />
						<span>341</span>
					</p>
				</div>
			</div>
		</div>
		<div class="mb-3">
			<div class="card__reverse--top p-4">
				<div class="d-flex justify-content-between card__reverse--header mb-2">
					<h2>100 Montaditos</h2>
					<p>15% EFE. y 10% T.C.</p>
				</div>
				<div>
					<div
						class="card__reverse--middle d-flex align-items-center justify-content-between mb-2"
					>
						<div class="card__middle--p">
							<p class="fw-bold mb-1">Términos</p>
							<p>
								En artículos con precio de línea para compras <br />
								online usa el código
								<br />
								Y para compras en tiendas físicas el código
							</p>
						</div>
						<div class="card__reverse--codes mt-4">
							<p>mdsw646237%</p>
							<p>mdsw646237%</p>
						</div>
					</div>
					<p class="card__reverse--promotion mb-4">
						No aplica con ofertas en promociones y/o descuentos
					</p>
					<p class="card__reverse--footer mx-auto">
						Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean
						commodo ligula eget dolor. Aenean massa. Cum sociis natoque
						penatibus et magnis dis parturient montes, nascetur ridiculus mus.
						Donec quam felis, ultricies nec, pellentesque eu, pretium
					</p>
				</div>
			</div>
			<div
				class="d-flex px-5 py-2 justify-content-between card__reverse--bottom"
			>
				<img src="/public/icons/my-tdu-card/coupon-icon.png" alt="" />
				<img src="/public/icons/my-tdu-card/blue-reverse-logo.svg" alt="" />
			</div>
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
