<template>
<div class="profile-section">
  <div max-width="550" class="profile-box">
      <img class="profile-photo" src="https://1.bp.blogspot.com/-8QVDPKqg6kI/X_Wri1r8ynI/AAAAAAAAESc/UkAndga8U5Ett_8qslotRkaAJr27iT_-QCNcBGAsYHQ/s500/no-pain-no-gain-wgatsapp-dp-min.jpg" />

      <v-card-title class="profile-name">Name</v-card-title>
      <span class="profile-designation">Asst. Professor - IT Dept.asdkbaisdbuabsdo<br>askdhbasidbusadiabsdibb</span>
      <div class="profile-stats-section">
      <v-divider></v-divider>    
      <div class="profile-stats-1">
          <ul>
              <li><span class="stat-count">200</span></li>
              <li><span class="stat-count">1</span></li>
              <li><span class="stat-count">1</span></li>
              <li><span class="stat-count">1</span></li>
          </ul>
      </div>
      <div class="profile-stats-2">
          <ul>
              <li><span class="stat-count">Posts</span></li>
              <li><span class="stat-count">Courses</span></li>
              <li><span class="stat-count">Seminars</span></li>
              <li><span class="stat-count">Projects</span></li>
          </ul>
      </div>
      <v-divider></v-divider> 
      </div>
  </div>
</div>
</template>

<script>
export default {

}
</script>

<style scoped>
.profile-section{
    display:flex;
    justify-content: center;
}
.profile-box{
    border: 2px solid black;
    width: 65%;
}
.profile-photo{
    display: inline-block;
    left: 0.8rem;
    top: 0.8rem;
    position: relative;
    margin-right: 1rem;
    border-radius: 50%;
    border-collapse: separate; 
    max-height:9rem;
    max-width:9rem;
}
.profile-name{
    display: inline-block;
    position: relative;
    bottom: 6rem;
    margin-left: 1.9rem;
}
.profile-designation{
    display: inline-block;
    position: relative;
    top: -2rem;
    left: -4.4rem;
}
.proj-count{
    font-size: 2.8rem;
}
ul{
    list-style-type: none;
}
.profile-stats-1 ul{
    display: grid;
    grid-gap: 1rem;
    grid-template-columns:  repeat(4, 16.25%);
    justify-content: center;
    position: relative;
    text-align: center;
    padding: 0.8rem 0.2rem 0.3rem 0.2rem;
}
.profile-stats-2 ul{
    display: grid;
    grid-gap: 1rem;
    grid-template-columns:  repeat(4, 16.25%);
    justify-content: center;
    text-align: center;
    padding: 0.2rem;
}
.profile-stats-1{
    display: grid;
    font-weight: bold;
}
.profile-stats-2{
    display: grid;
}
.profile-stats-section{
    background: whitesmoke;
}
</style>