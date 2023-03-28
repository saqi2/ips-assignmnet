<template>
  <div class="page">
    <div class="ipslogo">
      <img src="../assets/ips-logo.png" />
    </div>

    <div class="title-block">
      <p class="pill new-course">NEW COURSE</p>
      <p class="title">iPhone Photo Academy</p>
    </div>

    <div class="iphone-frame-block">   
      <div class="iphone-frame parent">
 
        <img class="image1" src="../assets/iPhone-frame.png" />   
        <img class="iphone-frame-camera-ui image2" src="../assets/camera-ui.png">
        <!-- <img class= "progress-length1" src ="../assets/progress-lenght.png"> -->
      </div> 
        
    </div>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.page {
  /* MacBook Pro 14" */

  position: relative;
  width: 1512px;
  height: 982px;
  left: 106px;
  top: 144px;

  /* black */
  background: #0f0f0f;
}

.ipslogo {
  /* ips-logo */
  position: absolute;
  width: 180px;
  height: 45px;
  left: 156px;
  top: 62px;
}

.title-block {
  position: absolute;
  width: 449px;
  height: 406px;
  left: 156px;
  top: 288px;
}

.iphone-frame-block {
  position: absolute;
  width: 560px;
  height: 880px;
  left: 820px;
  top: 32px;
}

.iphone-frame {
position: absolute;
/* width: 390px;
height: 740px;
left: 57px;
top: 55px; */

width: 306.17px;
height: 669.22px;
left: 123.28px;
top: 113.26px;

/* filter: blur(70px); */
}

.cameraImage {
position: absolute;
width: 306px;
height: 414px;
left: 123px;
top: 217.5px;
}


.iphone-frame-camera-ui {
  /* camera-ui */
position: absolute;
width: 306.17px;
height: 669.22px;
left: 123.28px;
top: 113.26px;
background: url("../assets/portrait.jpg"); 
/* background: url(IMG_103ABC1F1E57-1.jpg); */
border-radius: 31.5987px;
}

.pill {
  display: flex;
  flex-direction: row;
  align-items: flex-start;
  padding: 16px 16px;
  gap: 8px;
  width: 150px;
  height: 20px;
  background: #2b5341;
  border-radius: 30px;
  font-family: "Open Sans";
  font-style: normal;
  font-weight: 600;
  font-size: 12px;
  line-height: 12px;
  letter-spacing: 2px;
  text-transform: uppercase;
  color: #eeecec;
  flex: none;
  order: 0;
  flex-grow: 0;
}

.title {
  width: 449px;
  height: 126px;
  font-family: "Montserrat";
  font-style: normal;
  font-weight: 400;
  font-size: 63px;
  line-height: 63px;
  color: #eeecec;
  flex: none;
  order: 1;
  flex-grow: 0;
}

.progress-length1 {
  position: absolute;
width: 55px;
height: 1px;
left: 0px;
top: 0px;

/* light-gray */

background: #3A3A3A;
border-radius: 1px;
}

.parent {
  position: relative;
  /* top: 0;
  left: 0; */
}
.image1 {
  position: relative;
  top: 0;
  left: 0;
  /* border: 1px red solid; */
}
.image2 {
  position: absolute;
  top: 10px;
  left: 15px;
  /* border: 1px green solid; */
}
</style>
