<template>
  <div class="d-flex justify-content-center signin">
    <div class="logo">
      <div class="d-flex justify-content-center">
        <img src="https://i.postimg.cc/LsddLPp9/Logo.png" alt="" />
      </div>
      <div class="bold Alphitter">登入 Alphitter</div>
    </div>
    <div class="form1">
      <form>
        <div class="mb-3 label-parents">
          <input
            type="email"
            class="form-control input1 input-space rounded-0"
            id="exampleInputEmail1"
            aria-describedby="emailHelp"
            placeholder="帳號"
            style="width: 540px; height: 50px"
          />

          <label for="exampleInputEmail1" class="form-label">帳號</label>
          <div id="emailHelp" class="form-text"></div>
        </div>

        <div class="mb-3 label-parents">
          <input
            type="password"
            class="form-control input1 rounded-0"
            id="exampleInputPassword1"
            placeholder="密碼"
            style="width: 540px; height: 50px"
          />

          <label for="exampleInputPassword1" class="form-label">密碼</label>
        </div>

        <button
          style="width: 540px; height: 50px"
          type="submit"
          class="btn bold mt-3"
        >
          登入
        </button>
      </form>

      <div class="signup-alphitter d-flex justify-content-end">
        <a class="bold mr-1 a1" href="#" style="color: #0099ff; font-size: 18px"
          >註冊 Alphitter</a
        ><span class="bold mr-1" style="color: #0099ff; font-size: 18px"
          >·</span
        >

        <a class="bold" href="#" style="color: #0099ff; font-size: 18px"
          >後台登入</a
        >
      </div>
    </div>
  </div>
</template>

<style scoped>
.signin {
  margin-top: 100px;
  position: relative;
}
.logo {
  margin-top: -60px;
  position: absolute;
}
.form1 {
  margin-top: 65px;
}
button {
  background-color: #ff6600;
  color: white;
  border-radius: 35px;
  font-size: 18px;
}
button:hover {
  color: white;
}
button:focus {
  /* outline: 0; */
  border-color: #ccc;
  outline: none;
  box-shadow: none;
}
.bold {
  font-weight: bold;
}
.Alphitter {
  font-size: 25px;
  margin-top: 30px;
}
.form-control {
  margin-top: -20px;
}

input {
  /* position: relative; */
  background-color: #f5f8fa;
  border-top: none;
  border-right: none;
  border-left: none;
  border-color: #657786;
  border-width: 2px;
}
input.form-control:focus {
  border-color: #ccc;
  outline: none;
  box-shadow: none;
  background-color: #f5f8fa;
  border-color: #657786;
}
.input1:placeholder-shown::placeholder {
  color: transparent;
}
.label-parents {
  position: relative;
  margin-top: 30px;
}
.input1:placeholder-shown ~ label {
  display: block;
}
.input1:not(:placeholder-shown) ~ label {
  display: none;
}

label {
  position: absolute;
  top: 2px;
  left: 12px;
  font-size: 15px;
  font-weight: bold;
  color: #657786;
}
.input-space {
  margin-bottom: 39px;
}

.signup-alphitter {
  margin-top: 40px;
  /* border-bottom: 1px solid #0099ff;
  width: 70px; */
  text-decoration: none;
}
a {
  text-decoration: none;
  position: relative;
}
a::after {
  content: "";
  position: absolute;
  background-color: #0099ff;
  width: 72px;
  height: 1px;
  bottom: 4px;
  left: 0px;
}
.a1 {
  text-decoration: none;
  position: relative;
}
.a1::after {
  content: "";
  position: absolute;
  background-color: #0099ff;
  width: 118px;
  height: 1px;
  bottom: 4px;
  left: 0px;
}
</style>


