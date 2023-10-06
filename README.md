# responsive-design
playstation design

![image](https://github.com/jitender72/responsive-design/assets/147124830/e22cfeab-2c9a-4fa9-981c-f69d5a02731d)

* {
    margin: 0;
    padding: 0;
}

.container {
    height: 150vh;
    width: 100%;
    padding-left: 8px;
    padding-right: 8px;
    overflow: hidden;
    box-sizing: border-box;

}

.container img {
    height: 60px;
}

.container .nav-bar {
    display: flex;
    /* position: fixed; */
    width: 100%;

}

.nav-bar ul {
    display: flex;
    justify-content: flex-end;
    align-items: center;
    width: 100%;
    flex-wrap: wrap;
    /* display: none; */



}

.nav-bar ul li {
    list-style: none;
    margin: 0px 15px;
    text-align: right;
    font-size: 20px;
}

.nav-bar ul li:hover {
    border-bottom: 2px solid #fb5283;
}

.container .logo {
    width: 50px;
    margin: 30px 20px;
    cursor: pointer;
}

.container .menu-icon {
    width: 50px;
    margin: 30px 0px;
    cursor: pointer;
    display: none;
}
#menu-icon{
    
}
.row {
    /* border: 1px solid red; */
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin: 100px 0px;

}

.row .col-1 {
    flex-basis: 40%;
    position: relative;
    margin-left: 50px;
    /* border: 1px solid red; */
    
}

.col-1 h2 {
    font-size: 54px;
    padding-left: 6px;
}

.col-1 h3 {
    font-size: 30px;
    color: #707070;
    font-weight: 100;
    margin: 20px 0;
    padding-left: 6px;
}

.col-1 p {
    font-size: 20px;
    font-weight: 100;
    color: #b7b7b7;
    margin: 20px;
    padding-left: 6px;
}

.col-1 h4 {
    margin: 5px 0;
    font-size: 20px;
    padding-left: 6px;
}

button {
    width: 140px;
    height: 35px;
    display: flex;
    justify-content: center;
    align-items: center;
    border: 0;
    /* padding: 12px 10px; */
    outline: none;
    color: #fff;
    background: linear-gradient(to right, #fb5283, #ff3527);
    border-radius: 6px;
    cursor: pointer;
    transition: width 0.5s;
    margin-left: 6px;
}

button img {
    width: 30px;
    margin-left: 10px;
    position: relative;
    top: 2px;
    object-fit: contain;
    display: none;

}

button:hover img {
    display: 
    inline-block;
}

button:hover {
    display: flex;
    /* justify-content: space-between; */
    align-items: center;
}

.col-1::after {
    content: "";
    border-left: 5px solid #fb5283;
    height: 57%;
    position: absolute;
    top: 8px;

}
.col-2{
 
    display: flex;
    /* justify-content: center; */
    align-items: center;
    position: relative;
    flex-basis: 60%;
}
.col-2 .controller{
   width: 90%;
   height: fit-content;
    /* object-fit: contain; */
    /* object-fit:fill; */


}
.color-box{
    position: absolute;
    top:0px;
    right:0px;
    background-color: #fb5283;
    height: 100%;
    width: 80%;
    border-radius: 20px 0 0 20px;
    z-index: -1;
    transform: translateX(150px);
   
    
}
.add-btn{
    text-align: center;
    color: white;
    cursor: pointer;
}
.add-btn img{
width:25px;
height: 22px;

border-radius: 50%;
margin-bottom: 5px;

}
.add-btn p small{
    /* text-align: center; */
    color: white;
}
.social-links img{
    height: 15px;
    margin: 20px;
    cursor: pointer;
}
.social-links{
    text-align: center;
}
.menu-icon:checked ~ ul{
    display: inline-block; 
}


@media screen and (max-width: 980px){
    .color-box{
        transform: translateX(120px);
    }
}
@media screen and (max-width: 950px){
    .color-box{
        transform: translateX(100px);
    }

    }
    @media screen and (max-width: 844px){
        .color-box{
            transform: translateX(90px);
        }
    }
    @media screen and (max-width: 772px){
        .color-box{
            transform: translateX(80px);
        }
    }
    @media screen and (max-width: 704px){
        .color-box{
            transform: translateX(70px);
        }
    }
    @media screen and (max-width: 644px){
        .color-box{
            transform: translateX(60px);
        }
    }
    @media screen and (max-width: 734px){
        .color-box{
            transform: translateX(50px);
        }
    }
    @media screen and (max-width: 556px){
        .color-box{
            transform: translateX(40px);
        }
    }
    @media screen and (max-width: 588px){
        .nav-bar ul{
            display: none;
        }
        .nav-bar .menu-icon{
            display: block;
            /* position: relative;
            right: -420px; */
        }
        
    }
    
    @media screen and (max-width: 530px){
        .row{
            display: flex;
            flex-direction: column;
            justify-content: center;

        }
        .row .col-2{
         margin-top: 50px;
        }
    }
    @media screen and (max-width: 400px){
        .nav-bar {
            display: flex;
            justify-content: space-between;
        }
    }
    @media screen and (max-width: 588px){
        .nav-bar {
            display: flex;
            justify-content: space-between;
        }
    }
    @media screen and (max-width: 588px){
        ul{
            display: flex;
            flex-direction: column;
            /* margin-top: 100px; */
            /* border: 1px solid red; */
            /* background-color: #fb5283; */
            position: relative;
            top: 100px;
            /* border-radius: 8px; */
            

            
        }
        ul li{
            padding: 10px 15px;
            color: black;
        }
        ul li:hover{
            border-bottom: 2px solid #fb5283;
        }
        
    }

    


   

  


