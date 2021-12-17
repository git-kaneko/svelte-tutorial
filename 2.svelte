<script>
	let src = 'tutorial/image.gif';
</script>

<!-- src={src}のように、属性の名前と値の変数が一致することは珍しくありません。このような場合、Svelteでは省略して書くことができます。 -->
<img {src} alt="A man dances.">