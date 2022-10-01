# website-grid
this project ,its project that entails website for marketing only, where lots of product can be set for sell and buying
home page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>portfolio</title>
    <link rel="stylesheet" href="portofolio.css">
    
    <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.5.0/css/all.css" integrity="sha384-B4dIYHKNBt8Bc12p+WXckhzcICo0wtJAoU8YZTY5qE0Id1GSseTk6S+L3BlXeVIU" 

</head>
<body>
    <section class="fay">
        <div class="logo"><img src="th.png" alt=""></div>
        <nav class="sain">
            <ul class="sona">
                <li class="zani">projects</li>
                <li class="zani">about me</li>
                <li class="zani">contacts</li>
            </ul>

        </nav>
    </section>
    <h1>Bramwel Amugada</h1>
    <h3>web developer</h3>
    <p>Am young, inspired hardwork guy <br> 
Using Javascript,HTML and CSS for my projects <br> Learned on my own in bootcamp and used  <br> several tutarials and help from community.
    </p>
    <button class="button" id="OnClick">about me</button>
    
</body>
</html>
contact page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>contacts</title>
    <link rel="stylesheet" href="contacts.css">
    

</head>
<body>
    <section class="stan">
    <div class="logo"><img src="th.png" alt=""></div>
   <div>
        <ul class="dan">
            <li class="san" >
               <button class="das" id="sav"> about me</button>
            </li>
            <li class="san" ><button class="das">projects</button></li>
            <li class="san"><button class="das" >Home</button> </li>
        </ul>
    </div>
    </section> 
    <section class="baya">
<h1>contacts</h1>
<ul>
   
             
    </ul>
 </section>
 <section class="can">

 </section>
 <script src="contact.js"></script>
</body>
</html>
contact style.css
body{
    background-color: rgb(47, 40, 40);
}
.stan{
    display: flex;
    justify-content: space-between;
    background-color: black;
}
.dan{
    display: flex;
    
    
}
.san{
    padding: 30px;
 font-weight: 600;
 font-size: larger;
 color: azure;
 list-style: none;
 
}
.das{
    padding: 20px 10px;
    transition: 3sec all  ease;
    border-radius: 5px;
    background-color: brown;
    cursor:unset;
    font-weight: 600;
}
.baya{
    background-color: rgb(56, 54, 54);
    height: 500px;
    width: 500px;
    margin-top: 10px;
    border-radius: 5px;
}
.baya h1{
    color: bisque;
    text-align: center;
    padding: 0px px;
}
.icon{
    width: 10px;
    height: 10px;;
}
.can{
    width: 1330px;
    height: 200px;
    background-color: black;
    margin-top: 17px;
    border-radius: 5px;
    margin-left: 3px;

}



