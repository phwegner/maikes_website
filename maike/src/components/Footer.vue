<template>
<div class="fixed-bottom">
  
      <nav
    class="navbar navbar-expand-lg navbar-dark justify-content-between mb-3">
    <ul class="navbar-nav navbar-nav-hover flex-row align-items-center">
        <li class="nav-item">
            <a href="#" class="nav-link" role="button">
                <span class="nav-link-inner-text">📺 Start</span>
            </a>
        </li>
        <li class="nav-item">
            <a href="#" class="nav-link"
                role="button">
                <span
                    class="nav-link-inner-text">😃 	&Uuml;ber mich</span>
            </a>
        </li>
    </ul>
    <div class="time text-center">
        <span class="time text-uppercase">{{currentTime}}</span>
    </div>
</nav>
  
</div>
</template>

<script>
var currentDate = new Date();
export default {
    data(){
        return {
            currentTime: currentDate.getHours() + ":" + currentDate.getMinutes()
        }
    }
}
</script>

<style>

</style>