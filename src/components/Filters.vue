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
				<div class="filters__valor">
					<p>Valor</p>
					<div
						class="accordion accordion-flush mt-2 mb-4"
						id="accordionFlushExample"
					>
						<div class="accordion-item">
							<h2 class="accordion-header" id="flush-headingOne">
								<button
									class="accordion-button collapsed"
									type="button"
									data-bs-toggle="collapse"
									data-bs-target="#flush-collapseOne"
									aria-expanded="false"
									aria-controls="flush-collapseOne"
								>
									<img
										src="/public/icons/filters/arrow-down.svg"
										alt="Flecha hacia abajo"
									/>
									Características
								</button>
							</h2>
							<div
								id="flush-collapseOne"
								class="accordion-collapse collapse"
								aria-labelledby="flush-headingOne"
								data-bs-parent="#accordionFlushExample"
							>
								<div class="d-flex gap-3 mt-3">
									<input type="checkbox" name="con-capsula" id="con-capsula" />
									<label for="con-capsula">Con capsula</label>
								</div>
								<div class="d-flex gap-3">
									<input type="checkbox" name="con-capsula" id="sin-capsula" />
									<label for="sin-capsula">Sin capsula</label>
								</div>
							</div>
						</div>
						<div class="accordion-item">
							<h2 class="accordion-header" id="flush-headingTwo">
								<button
									class="accordion-button collapsed"
									type="button"
									data-bs-toggle="collapse"
									data-bs-target="#flush-collapseTwo"
									aria-expanded="false"
									aria-controls="flush-collapseTwo"
								>
									<img
										src="/public/icons/filters/arrow-down.svg"
										alt="Flecha hacia abajo"
									/>
									Cantidad
								</button>
							</h2>
							<div
								id="flush-collapseTwo"
								class="accordion-collapse collapse"
								aria-labelledby="flush-headingTwo"
								data-bs-parent="#accordionFlushExample"
							>
								<div class="d-flex gap-3 mt-3">
									<input type="checkbox" name="14s" id="14s" />
									<label for="14s">14s</label>
								</div>
								<div class="d-flex gap-3">
									<input type="checkbox" name="15s" id="15s" />
									<label for="15s">15s</label>
								</div>
								<div class="d-flex gap-3">
									<input type="checkbox" name="20s" id="20s" />
									<label for="20s">20s</label>
								</div>
								<div class="d-flex gap-3">
									<input type="checkbox" name="25s" id="25s" />
									<label for="25s">25s</label>
								</div>
							</div>
						</div>
					</div>
				</div>
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
