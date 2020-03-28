<template>
	<form name="contact" method="POST" data-netlify="true">
        <h3>Say something nice about aggsu</h3>
		<p>
			<label>Your Name: <input type="text" name="name"/></label>
		</p>
		<p>
		</p>
		<p>
		</p>
		<p>
			<label>Message: <textarea name="message"></textarea></label>
		</p>
		<p>
			<button type="submit">Send</button>
		</p>
	</form>
</template>

<script>
export default {
  name: "Form"
};
</script>
