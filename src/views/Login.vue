<template>
    <div class="login container">
        <div class="row">
            <div>
                <h1>LOGIN</h1>
            </div>
        </div>
        <div class="row my-5">
            <form class="border border-3 p-3 border-primary">
                <div class="mb-3 form-floating">
                    <input type="text" id="accNumber" class="form-control" placeholder="account number">
                    <label for="accNumber" class="form-label">Account number</label>
                </div>
                <div class="mb-3 form-floating">
                    <input type="password" id="password" class="form-control" placeholder="password">
                    <label for="password" class="form-label">Password</label>
                </div>
                <button id="btn" class="btn btn-lg btn-info">Login</button>
            </form>
            <h3 id="err"></h3>
        </div>
    </div>
</template>