<script setup></script>

<template>
	<button
		type="button"
		class="btn btn-primary"
		data-bs-toggle="modal"
		data-bs-target="#exampleModal"
	>
		Filtros por marca
	</button>
	<div
		class="modal fade"
		id="exampleModal"
		tabindex="-1"
		aria-labelledby="exampleModalLabel"
		aria-hidden="true"
	>
		<div class="modal-dialog">
			<div class="modal-content container">
				<div class="d-flex justify-content-end">
					<button
						type="button"
						class="btn-close"
						data-bs-dismiss="modal"
						aria-label="Close"
					></button>
				</div>
				<div class="input__container mb-5">
					<input type="text" placeholder="Buscar..." />
					<img
						src="/public/icons/filters/search.svg"
						alt="Icono de buscar"
						class="search__icon"
					/>
				</div>
				<p>Valor</p>

				<button type="button" class="btn w-100 mb-5 btn__apply--filters">
					Aplicar
				</button>
			</div>
		</div>
	</div>
</template>

<style lang="scss" scoped>
@import "@/scss/components/filters.scss";
</style>
