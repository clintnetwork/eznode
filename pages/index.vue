<template>
	<div>
		<pre>
                                        888             d8b
                                        888             Y8P
                                        888
 .d88b. 88888888 88888b.   .d88b.   .d88888  .d88b.     888  .d88b.
d8P  Y8b   d88P  888 "88b d88""88b d88" 888 d8P  Y8b    888 d88""88b
88888888  d88P   888  888 888  888 888  888 88888888    888 888  888
Y8b.     d88P    888  888 Y88..88P Y88b 888 Y8b.    d8b 888 Y88..88P
 "Y8888 88888888 888  888  "Y88P"   "Y88888  "Y8888 Y8P 888  "Y88P"
</pre>
<!--		<p>Bitcoin & Lightning Network Full Nodes.</p>-->
		<pre>
<!--Bitcoin & Lightning Network Full Nodes.-->
$ bitcoin-cli -rpcconnect=eznode.io sendrawtransaction "signedhex"</pre>
<!--		<h1>eznode.io</h1>-->
	</div>

</template>

<script>
export default {}
</script>

<style>
pre:first-child
{
	background: -webkit-linear-gradient(
		45deg, orangered, orange);
	-webkit-background-clip: text;
	-webkit-text-fill-color: transparent;
	//color: orangered;
	line-height: 1em;
	margin-bottom: 21px;
}

p
{
	color: orangered;
	border-bottom: 1px solid;
	display: inline-block;
	font-weight: 300;
	font-size: 15pt;
}

</style>
