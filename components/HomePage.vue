<template>
    <div>
         <h1 id = "myname">Daniela Velazquez</h1>
        <img id = "cam" src = "camera-png.webp" >

        <center>
        <p id = "pronouns">She/Her/Hers</p>
        <p id = "line">First-Gen Computer Science & Film</p>
        <br>
        <p id = "uni">Columbia University</p>
        </br>

        <img id = "pic" src = "IMG-8754.jpg" >

        </center>

    </div>
        
</template>

<style>
    
    @import 'https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600&display=swap';
   
    #myname{
        font-size: 30px;
        font-family: 'Playfair Display', serif;
    }

    #pic{
        width: 295px;
        height: 360px;
        border: 1px solid #ddd;
        border-radius: 50%;
        padding: 5px;
        position: relative;
        top: -250px;
        
    }

    #pronouns{
        line-height: 20px;
        font-size: 20px;
        position: relative;
        top: 440px;
    }

    #line{
        line-height: 40px;
        font-size: 28px;
        position: relative;
        top: 410px;
    }

    #uni{
        line-height: 90px;
        font-size: 28px;
        position: relative;
        top: 305px;
    }

    #cam{
        position: relative;
        top: 250px;
        width: 75px;
        height: 60px;
        transform: rotate(310deg);
    
    }




    
   
</style>