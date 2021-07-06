<script>
    export let name;
    let isRed = false
</script>


<main>
    <h1>회원가입</h1>
    <div class=box>

        <form action="login.jsp" method="post">
            <input type="text" name="" id="" placeholder="아이디를 입력하세요">
            <input type="password" name="" id="" placeholder="비밀번호를 입력하세요">
            <br><input type="button" value="로그인">
            <input type="button" value="회원가입">
        </form>

    </div>
</main>

<style>
    main {
        display: grid;
        place-items: center;
        text-align: center;
        padding: 1em;
        min-width: 100vw;
        max-width: 640px;

    }

    .box {

        display: grid;
        place-items: center;
        background-color: #ff6655;
        width: 30vmax;
        padding-top: 4em;
        padding-bottom: 4em;
        border-radius: 40px;

    }

    .box input::placeholder {
        color: #fff;

    }
    input:focus{
        outline: none;
        caret-color: #FFF;
    }

    .box input[type=text] {
        border: 1px solid #fff;
        background-color: #ff6655;
        padding-left: 10px;
        border-radius: 70px;
        width: 40vmin;
        height: 50px;
        color: #fff;
    }

    .box input[type=password] {
        border: 1px solid #fff;
        background-color: #ff6655;
        padding-left: 10px;
        border-radius: 70px;
        width: 40vmin;
        height: 50px;
        top: 50%;
        color: #fff;

    }

    .box input[type=button] {
        margin-top: 1vh;
        border-radius: 10px;
        color: #ff6655;
        font-weight: bolder;
        width: 17.5vw;
        height: 35px;
        border: 0;
        background-color: #fff;

    }
    .box input[type=button]:hover{
        cursor: pointer;
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