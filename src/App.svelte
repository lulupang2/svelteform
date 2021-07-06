<script>
	export let name;
	let isRed = false
</script>


<main>
	<h1>회원가입</h1>
	<div class =box>
		<form action="login.jsp" method="post" >
		<input type="text" name="" id="" placeholder="아이디를 입력하세요">
		<input type="password" name="" id="" placeholder="비밀번호를 입력하세요">
		</form>

	</div>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	.box{
		margin : 0 auto;
		background-color: #ff3333;
		width: 640px;
		height: 480px;
		border-radius: 40px;

	}
	.box input { display: flex;}
	.box input[type=text] {
		border:0px;
	}
	.box input[type=password] {
		border:0px;
	}


	h1 {
		color: #686;
		text-transform: uppercase;
		font-size: 2em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>