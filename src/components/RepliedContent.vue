<template>
  <div class="replied-content d-flex justify-content-center">
    <div
      class="card border-dark mb-3"
      id="card2"
      style="width: 470px; height: 400px"
    >
      <div class="card-header">
        <img src="https://i.postimg.cc/pdc5H7Qh/Vector.png" alt="X" />
      </div>
      <div class="card-body d-flex flex-row">
        <div>
          <div class="Photo">
            <img src="https://i.postimg.cc/cHxqRxr2/Post-Photo.png" alt="" />
          </div>

          <div class="divider">
            <img src="https://i.postimg.cc/L6HStVZh/divider.png" alt="" />
          </div>
        </div>

        <div class="replied-relative">
          <div class="d-flex flex-row">
            <h5 class="card-title mr-2">Apple</h5>
            <p style="color: #657786">@apple・3 小時</p>
          </div>
          <p class="card-text">
            Nulla Lorem mollit cupidatat irure. Laborum magna nulla duis ullamco
            cillum dolor. Voluptate exercitation incididunt aliquip deserunt
            reprehenderit elit laborum.
          </p>
          <small class="replied"
            ><span style="color: #657786; font-weight: bold">回覆給</span
            ><span style="color: #ff6600"> @apple</span></small
          >

          <div id="thumbnail">
            <img src="https://i.postimg.cc/jjGcTZrX/Photo.png" alt="" />
            <span style="color: #9197a3; font-weight: bold" class="push"
              >推你的回覆</span
            >
            <div>
              <input
                style="width: 380px; height: 140px; border: none; outline: none"
                type="text"
              />
            </div>
          </div>
        </div>
      </div>

      <div class="d-flex flex-row justify-content-end">
        <button
          style="width: 60px; height: 40px"
          type="submit"
          class="btn btn-warning"
        >
          回覆
        </button>
      </div>
    </div>
  </div>
</template>

<style scoped>
.replied-content {
  margin-top: 50px;
  background-color: white;
}
#card2 {
  border-radius: 12px;
  /* padding: 20px 20px; */
}
.card-header {
  border-radius: 14px 14px 0px 0px;
  background-color: white;
}
.replied-relative {
  position: relative;
}
.card-title {
  margin-left: 10px;
}

.card-text {
  margin-top: -14px;
  margin-left: 10px;
  position: relative;
}
.Photo {
  margin-left: -10px;
  margin-top: 3px;
}
.divider {
  margin-top: 8px;
  margin-left: 10px;
}
.replied {
  margin-left: 9px;
  position: absolute;
  top: 108px;
}
#thumbnail {
  margin-top: 40px;
  margin-left: -35px;
  position: relative;
}
.push {
  position: absolute;
  top: 6px;
  left: 43px;
}
button {
  border-radius: 35px;
  margin-bottom: 10px;
  margin-right: 10px;
  background-color: #ff6600;
  color: white;
}
</style>