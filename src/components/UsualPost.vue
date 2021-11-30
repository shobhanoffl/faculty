<template>
  <div class="post-wrap">
    <div class="post-header">
        <img src="https://www.finetoshine.com/wp-content/uploads/2020/04/Beautiful-Girl-Wallpapers-New-Photos-Images-Pictures.jpg" alt="" class="avator">
        <div class="post-header-info">
            <a class="location-link mintext"><v-icon small>mdi-map-marker</v-icon> BVB School, Thindal</a>
            <span style="float:right;margin-right: 10px;" class="mintext">Jun 21</span>
            <br>
            &nbsp;<div style="margin-top:6px;margin-left:1px;display:inline-block;font-size:16px;">Steve Jobs</div> 
            &nbsp;·<span class="mintext"> Attended a Seminar</span>
            <p>🔥 If you're tired of using outline styles for secondary buttons, a soft solid background based on the text color can be a great alternative.</p>
        </div>
    </div>
    <div class="align-straight">
      <img src="https://www.gizbot.com/images/2020-09/realme-7_159921061900.jpg" class="multi-img">
      <img src="https://www.gizbot.com/images/2020-09/realme-7_159921061900.jpg" class="multi-img">
    </div>
    <span class="attached-link"> + 2 images</span><br>
    <div class="align-straight">
      <div class="document-wrap" style="display: inline-block;">
        <v-icon dense>mdi-file-document</v-icon> document 
      </div>
      <div class="document-wrap" style="display: inline-block;">
        + 2 
      </div>
    </div>
    <div class="align-straight like-bar">
      <span><v-icon>mdi-thumb-up</v-icon></span>
      <span style="float:right;margin-right: 20px;"><v-icon>mdi-bookmark</v-icon></span>
      </div>
  </div>
</template>

<script>
export default {

}
</script>
<style scoped>
img {
  max-width:100%;
}
.avator {
  border-radius:50%;
  width:60px;
  height:60px;
  margin-right: 8px;
  margin-top: 28px;
  object-fit: cover;
}

.post-wrap {
  max-width:55%;
  background: #fff;
  margin: 0 auto;
  margin-top: 20px;
  border-radius:20px;
  padding: 20px;
  /* box-shadow: 1px 1px 8px 1px rgba(0,0,0,0.1); */
  border: 1px solid rgba(0,0,0,0.2);
}

.post-header {
  display: flex;
  align-items:flex-start;
  font-size:14px;
}
.post-header-info {
  font-weight:bold;
}
.post-header-info span.mintext {
  color:#606d77;
  font-weight:normal;
  margin-left: 5px;
}
.post-header-info p {
  font-weight:normal;
  margin-top: 5px;
}
img.multi-img{
  width: 168px;
  height: 160px;
  object-fit: cover;
  margin-left: 9px;
}
.attached-link{
  margin-left: 68px;
  color: #606d77;
  font-size: 14px;
}
.document-wrap{
  border: 1px solid #606d77;
  max-width: fit-content;
  border-radius: 25px;
  padding: 4px 10px 4px 8px;
  margin-left: 7px;
  margin-top: 10px;
}
.location-link{
  color:#606d77;
  font-weight:normal;
  font-size: 12px;
}
.align-straight{
  margin-left: 59px;
}
.like-bar{
  margin-left: 70px;
  margin-top: 20px;
}
/* .post-align-straight {
  padding-left: 60px;
}

.post-info-counts {
  display: flex;
  margin-left: 60px;
  margin-top: 10px;
}
.post-info-counts div {
  display: flex;
  margin-right: 20px;
}
.post-info-counts div svg {
  color:#657786;
  margin-right: 10px;
} */
@media screen and (max-width:320px){
  body {
    padding-left: 10px;
    padding-right: 10px;
  }
  .post-header {
    flex-direction:column;
  }
  .post-header img {
    margin-bottom: 20px;
  }
  .post-header-info p {
    margin-bottom: 30px;
  }
  .post-align-straight {
    padding-left: 0;
  }
  .post-info-counts {
  display: flex;
  margin-left: 0;
}
.post-info-counts div {
  margin-right: 10px;
}
}
@media (min-width:320px) and (max-width:481px){
  img.multi-img{
    width: 135px;
    height: 135px;
  }
}
@media (max-width:961px){
  .post-wrap{
    max-width: 100%;
  }
}
</style>