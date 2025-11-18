<script setup>

</script>

<template>
    
        <div class="main">
            <div id="mainmenu">
                
                <p class="mainmenutext">
                    Das ist ein Projeckt füt Ihre Arbeit zu planieren 
                </p>
                <div class="mainmenubuttonadd">
                    <span class="menubuttonname"> Add </span>
                </div>    
            </div> 
            <div id="mainmenu">
                <p class="mainmenutext">
                    Das ist ein Projeckt füt Ihre Arbeit zu planieren 
                </p>
                <div class="mainmenubuttonadd">
                    <span class="menubuttonname"> Add </span>
                </div>    
            </div> 
            <div id="mainmenu">
                <p class="mainmenutext">
                    Das ist ein Projeckt füt Ihre Arbeit zu planieren 
                </p>
                <div class="mainmenubuttonadd">
                    <span class="menubuttonname"> Add </span>
                </div>    
            </div> 
        </div>
    
</template>

<style scoped>
.furall {
    margin: 5px;
    padding: 5px;
    border-style: solid;
    border-color: rgb(131, 10, 50);
    border-width: 1px;
    border-radius: 2px; 

    display:grid;
    grid-template-columns: 250px 250px;
}
.main {
    align-self: center;
    justify-self: center;
    margin: 0px;
    padding: 0px;


    border-style: solid;
    border-color: rgb(29, 37, 29);
    border-width: 1px;
    border-radius: 2px;

    display:flex;
    
}
#mainmenu {
    margin: 5px;
    padding: 0px;
    box-shadow: 5px 5px 5px gray;
    width: 200px;
    height: 120px;
    border-style: solid;
    border-color: black;
    border-width: 1px;
    border-radius: 2px;
    position: relative;
    display: block;
}

.mainmenutext {
    font-size: 12px;
    font-family: 'Times New Roman', Times, serif;
    text-align: center;
    margin: 5px auto auto auto;
    user-select: none;
}
.menubuttonname {
    margin: auto auto auto auto;
    user-select: none;
    position: absolute;
    left: 11px;
    top: 14px;
}
.mainmenubuttonadd {
    border-style: solid;
    border-color: rgb(29, 37, 29);
    border-width: 1px;
    border-radius: 2px;
    width: 50px;
    height: 50px;
    text-align: center;
    background-color: rgb(134, 180, 134);
    margin: auto 8px 8px auto;
    display: block;
    position: absolute;
    left: 140px;
    top: 60px;

}
.mainmenubuttonadd:hover {
    border-style: solid;
    border-color: green;
    border-width: 1px;
    border-radius: 2px;
    width: 50px;
    height: 50px;
    box-shadow: 5px 5px 5px green;
}
.mainmenubuttonadd:active {
    border-style: solid;
    border-color: green;
    border-width: 1px;
    border-radius: 2px;
    width: 47px;
    height: 47px;
    box-shadow: 3px 3px 3px red;
    margin: auto 12px 12px auto;
    left: 143px;
    top: 63px;
}

</style>