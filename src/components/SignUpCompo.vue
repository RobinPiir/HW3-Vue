<template>
    <div class="center">
        <div>
        <p><strong>WELCOME TO POST IT</strong></p>
        <p id="sign-up">Create an account</p>
        <p><strong>or</strong></p>
        </div>
        <form action="index.html">
        <input type="email" name="email" placeholder="Email" required>
        <input type="password" name="password" placeholder="Password" required>
        <button type="submit">Sign Up</button>
        </form>
        <p>Forgot password</p>
    </div>
</template>

<style scoped>
.center{
    display: flex;
    flex-direction: column;
    position: absolute;
    text-align: center;
    top: 50%;
    left: 50%;
    margin-right: -50%;
    transform: translate(-50%, -50%);
    padding-top: 10px;
    padding-bottom: 10px;
    padding-left: 10px;
    padding-right: 10px;
    border: 1px solid #646174;
    background-color: #B1CDA4;
    border-radius: 5px;
}

#SignUp{
    color:blue;
    text-align: center;
    cursor: pointer;
    padding: 5px 5px;
    line-height: 2;
}

#SignUp: hover{
    background-color: #7ebeb6;
    color: #092747;

}

input[type=email],input[type=password] {
    padding: 5px;
    display: grid;
    border: 5px solid #ccc;
    box-sizing: border-box;

}

button[type=submit]{

    background-color: #04AA6D;
    border: none;
    color: white;
    padding: 15px 15px;
    margin: 15px 4px;
    border-radius: 15px;
    cursor: pointer;
}
</style>