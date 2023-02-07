<h1>Hi</h1>

<style global>
	h1 {
		/* 
			To reproduce:
			- change to blue
			- observe it updates to be blue
			- change back to red
			- observe it stays blue
			- observe that if `global` is removed from the `style` tag, it works as expected
		*/
		color: red;
	}
</style>
