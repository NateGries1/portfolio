<section class="container">
	<div class="contact-form-container">
		<h2 class="title">Contact Me</h2>
		<form
			action="https://formspree.io/f/mkgnlddz"
			method="POST"
			class="email-form"
			id="contactForm"
		>
			<div class="form-group">
				<label for="name">Your email:</label>
				<input type="email" id="name" name="email" placeholder="example123@gmail.com" required />

				<span class="error-message" id="nameError"></span>
			</div>
			<div class="form-group">
				<label for="message">Your Message:</label>
				<textarea id="message" name="message" placeholder="Write message here" rows="5" required
				></textarea>
				<span class="error-message" id="messageError"></span>
			</div>
			<button type="submit" class="submit-button"> Send Message </button>
		</form>
	</div>
</section>

<style>
	.container {
		display: flex;
		justify-content: center;
		align-items: center;
		height: 100vh;
	}
	.contact-form-container {
		padding: 20px;
		background-color: transparent;
		border: 1px solid white;
		border-radius: 8px;
		max-width: 600px;
		width: 80%;
	}

	h2 {
		margin-top: 0;
		color: white;
		text-align: center;
	}

	.form-group {
		margin-bottom: 1rem;
	}

	label {
		display: block;
		margin-bottom: 0.5rem;
		font-weight: bold;
		color: white;
	}

	input,
	textarea {
		width: 100%;
		padding: 0.8rem;
		background-color: transparent;
		border: 1px solid white;
		border-radius: 8px;
		box-sizing: border-box;
		font-size: 1rem;
		color: white;
	}

	textarea {
		resize: vertical;
	}

	.error-message {
		color: red;
		font-size: 0.875rem;
		display: none; /* Hidden by default */
	}

	.submit-button {
		background-color: #28a745;
		color: white;
		border: none;
		padding: 0.75rem;
		border-radius: 4px;
		font-size: 1rem;
		cursor: pointer;
		width: 100%;
		transition: background-color 0.3s;
	}

	.submit-button:hover {
		background-color: #218838;
	}
</style>
