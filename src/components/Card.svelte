<div class="container">
	<div class="card-container">
		<div class="card">
			<div class="card-header">
				<h2>Başlık</h2>
				<div class="divider" />
			</div>
			<div class="card-body">
				<p>
					Lorem ipsum dolor sit amet consectetur, adipisicing elit. Ratione libero temporibus iusto
					ab doloremque! Quidem, at atque mollitia eveniet vel odit quia facilis doloremque quaerat
					quo impedit maiores asperiores quis.
				</p>
			</div>
			<div class="card-footer">
				<button class="btn">Detay</button>
			</div>
		</div>
	</div>
</div>

<style>
	.card-container {
		display: flex;
		flex-wrap: wrap;
		justify-content: center;
	}

	.card {
		width: 600px;
		margin: 10px;
		background-color: #fdfeff;
		border-radius: 8px;
		box-shadow: rgba(0, 0, 0, 0.1) 0px 1px 3px 0px, rgba(0, 0, 0, 0.06) 0px 1px 2px 0px;
	}
	.card-header .divider {
		border: 0.5px solid #e6e6e6;
		margin-top: 7px;
	}
	.card-header,
	.card-body,
	.card-footer {
		padding: 10px;
	}

	.card-footer button {
		margin-left: auto;
		background-color: #fdfeff;
		cursor: pointer;
		border: 1px solid rgba(0, 0, 0, 0.1);
		padding: 8px;
		border-radius: 5px;
		transition: 0.5s;
	}

	.card-footer button:hover {
		background-color: #e7eee9;
		transition: 0.5s;
		border: 1px solid #e7eee9;
	}
</style>
