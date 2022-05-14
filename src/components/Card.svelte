<script>
    export let posts
    console.log(posts)
</script>
<div class="container">
    {#each posts as post (post.id)}

        <div class="card-container">
            <div class="card">
                <div class="card-header">
                    <h2>{post.title}</h2>
                    <div class="divider"></div>
                </div>
                <div class="card-body">
                    <p>
                        {post.body}
                    </p>
                </div>
                <div class="card-footer">
                    <button class="btn">Detay</button>
                </div>
            </div>
        </div>

    {/each}
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

<<<<<<< HEAD
	.card-footer button:hover,
	.card-footer button:focus {
		background-color: #e7eee9;
		transition: 0.5s;
		border: 1px solid #e7eee9;
		box-shadow: 0 0.5em 0.5em -0.4em #e7eee9;
		transform: translateY(-0.25em);
	}
=======
    .card-footer button:hover {
        background-color: #e7eee9;
        transition: 0.5s;
        border: 1px solid #e7eee9;
    }
>>>>>>> 69f6927734df7c7d8de97d9180944f558aab06ee
</style>
