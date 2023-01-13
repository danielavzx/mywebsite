<template>
    <div>
        <img id = "cam" src = "camera-png.webp" >
        <img id = "cam2" src = "camera-png.webp" >
        <img id = "cam3" src = "camera-png.webp" >
        <img id = "cs1" src = "csicon.png" >
        <img id = "cs2" src = "csicon.png" >
        <img id = "cont1" src = "1266221-200.png">
        <img id = "cont2" src = "1266221-200.png">
        <img id = "code1" src = "png-coding-1.png">
        <img id = "code2" src = "png-coding-1.png">
        
        

        <center>
        <h1 id = "myname">Hi, I'm Daniela Velazquez!</h1>
        <p id = "pronouns">She/Her/Hers</p>
        <p id = "line">First-Gen Computer Science & Film</p>
        <br>
        <p id = "uni">Columbia University</p>
     

        <img id = "pic" src = "IMG-8754.jpg" >

        </center>

    </div>
        
</template>

<style>
    
    @import 'https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600&display=swap';
   
    body{
        background-color: #000;
    }

    #myname{
        font-size: 60px;
        font-family: 'Playfair Display', serif;
        color: white;
        text-decoration: underline wavy cyan 10px; 
    }

    #pic{
        width: 295px;
        height: 360px;
        border: 1px solid #ddd;
        border-radius: 50%;
        padding: 5px;
        position: relative;
        top: -270px;
        
    }

    #pronouns{
        line-height: 20px;
        font-size: 20px;
        position: relative;
        top: 440px;
        color: white;
    }

    #line{
        line-height: 40px;
        font-size: 28px;
        position: relative;
        top: 410px;
        color: white;
    }

    #uni{
        line-height: 90px;
        font-size: 28px;
        position: relative;
        top: 305px;
        color: white;
    }

    #cam{
        position: absolute;
        top: 250px;
        width: 75px;
        height: 60px;
        transform: rotate(310deg);
        left: 400px;
    }

    #cam2{
        position: absolute;
        top: 340px;
        width: 75px;
        height: 60px;
        transform: rotate(40deg);
        right: 300px;
    }

    #cam3{
        position: absolute;
        top: 220px;
        width: 40px;
        height: 30px;
        transform: rotate(310deg);
        right: 470px;
    }

    #cs1{
        position: absolute;
        top: 390px;
        width: 70px;
        height: 70px;
        transform: rotate(30deg);
        left: 200px;
    }

    #cs2{
        position: absolute;
        top: 190px;
        width: 70px;
        height: 70px;
        transform: rotate(30deg);
        right: 200px;
    }

    #cont1{
        position: absolute;
        top: 190px;
        width: 70px;
        height: 70px;
        transform: rotate(340deg);
        left: 100px;
    }

    #cont2{
        position: absolute;
        top: 450px;
        width: 70px;
        height: 70px;
        transform: rotate(340deg);
        right: 200px;
    }

    #code1{
        position: absolute;
        top: 430px;
        width: 160px;
        height: 100px;
        transform: rotate(340deg);
        right: 470px;
    }

     #code2{
        position: absolute;
        top: 430px;
        width: 160px;
        height: 100px;
        transform: rotate(10deg);
        left: 470px;
    }

    




</style>