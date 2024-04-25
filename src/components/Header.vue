<template>
    <div class="container">
        <div class="navbar">
            <a href="#" class="logo"><img src="../assets/img/logo.svg" alt=""></a>
            <li class="navbar_list">
                <ul ><a class="navbar_list-text id1" href="">Home</a></ul>
                <ul ><a class="navbar_list-text" href="">Episodes</a></ul>
                <ul ><a class="navbar_list-text" href="">About</a></ul>
                <ul ><a class="navbar_list-text" href="">Contact</a></ul>
            </li>
        </div>
        <div class="header_logo">
            <div class="header_logo_1">
                <img src="../assets/img/main-1.png" alt="">
                <div class="header_logo-">
                     <div class="">
                        <p class="header_logo-text1">Take your podcast to the</p>
                        <p class="header_logo-text1">next level</p>
                    </div>
                     <div class="header_logo_2">
                        <p class="header_logo-text2">Listen on</p>
                        <li class="header_logo_icon">
                           <ul><a  href=""><img  src="../assets/img/spotify.svg" alt=""></a></ul> 
                           <ul><a  href=""><img  src="../assets/img/img-2.svg" alt=""></a></ul> 
                           <ul><a  href=""><img  src="../assets/img/img-3.svg" alt=""></a></ul> 
                           <ul><a  href=""><img  src="../assets/img/img-4.svg" alt=""></a></ul> 
                           <ul><a  href=""><img  src="../assets/img/img-5.svg" alt=""></a></ul> 
                        </li>
                     </div>
                </div>
            </div>
           
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.container{
    display: flex;
    flex-direction: column;
    background:#191919;
    padding-top:43px
}
.navbar{
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    padding: 0 50px;
}
.navbar_list{
    display: flex;
    justify-content: center;
    flex-direction: row;
    align-items: center;
    gap:40px;
    margin-right: 20px;
}
.navbar_list-text{
color: #FFF;
font-size: 17px;
line-height: 27px;
}
.id1{
    color: #118DA8;
}
.header_logo{
    margin: 0 70px;
    margin-top:66px
}
.header_logo_1{
    display: flex;
    align-items: center;
}
.header_logo-{
display: flex;
flex-direction: column;
padding: 0 60px;
}
.header_logo-text1{
color: #FFF;
font-size: 70px;
line-height: 88px;
letter-spacing: 3.2px;
}
.header_logo_2{
    margin: 90px 0 0 22px;
}
.header_logo-text2{
color: #FFF;
font-size: 15px;
line-height: 24px;
margin-bottom: 12px;
}
.header_logo_icon{
 gap: 17px;
 display: flex;
 flex-direction: row;
}

</style>