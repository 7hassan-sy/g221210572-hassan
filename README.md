@import url('https://fonts.googleapis.com/css2?family=Cairo&family=Poppins:ital,wght@0,400;0,500;0,600;1,500&display=swap');

*{
    font-family: 'Poppins', sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    outline: none;
    text-decoration: none;
    text-transform: capitalize;
    transition: all .2s linear;
}
:root{
    --border: .1rem solid rgba(18, 75, 180, 0.568);
}
.bz{
    display:inline-block;
    margin-top: 1rem;
    border-radius: .5rem;
    background-color:#1b92d1 ;
    padding: .8rem 3rem;
    font-size: 1.7rem;
    font-weight: 500;
    cursor: pointer;
    border-color: #1b92d1;
    transition: 0.7s ease;
}

.bz:hover{
    color: #c8d9ea;
    transform: scale(1.1);
    font-weight: 700;
}
html{
    font-size: 62.5%;
    overflow-x: hidden;
    scroll-behavior: smooth;
    scroll-padding-top: 140px;
}
.header{
    background-color: #1b92d1;
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    z-index: 999;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 2rem 9%;
}

.header .logo{
    color: black;
    font-weight: bolder;
    font-size: 28px;
}

.header .logo span{
    color: #ecf5fb;
    font-size: 20px;
    
}

.header .navc a{
    color: black;
    font-size: 18px;
    font-weight: 600;
    margin: 0 1rem;
}

.header .navc a:hover{
    color: #c8d9ea;
    transform: scale(1.1);

}

.header #login-btn i{
    display: none;
    cursor: pointer;
    font-size: 2.5rem;
    color: #c8d9ea;
}
.header.active{
    box-shadow: 0 0.5rem 1rem rgba(18, 75, 180, 0.568);
    padding: 2rem 9%;
}
#menubar{
    display: none;  
    font-size: 2.5rem;
    cursor: pointer;
}

body{
    background-color: #c8d9ea;
    background: url(img/maxresdefault.jpg) no-repeat;
    background-size: cover;
    background-position: center bottom;
    background-attachment: fixed;
}
.loginfrm{
    position: fixed;
    top: -150%;
    left: 0;
    z-index: 1000;
    height: 100%;
    width: 100%;
    background: #c8d9ea;
    display: flex;
    justify-content: center;
    align-items: center;
    opacity: 0;
}
.loginfrm.active{
    top:0;
    opacity: 1;
}
.loginfrm form{
    padding: 2rem;
    margin: 2rem;
    border-radius: 0.5rem;
    box-shadow: 0 5px 25px rgba(18, 75, 180, 0.568);
    background: #c8d9ea;
    border: var(--border);
    text-align: center;
    width: 40rem;
}

.loginfrm form .btns{
    display: flex;
    align-items: center;
    gap: 1rem;
}

.loginfrm form .btn{
    display: block;
    width: 100%;
    margin: .5rem 0;
}

.loginfrm form h3{
    color: #37afe2;
    font-size: 2.5rem;
    padding-bottom: 1rem;
    text-transform: uppercase;
}

.loginfrm form .box{
    margin: .7rem 0;
    width: 100%;
    text-transform: none;
    color:black;
    font-size: 1.5rem;
    padding: 1rem 1.2rem;
    border: var(--border);
    border-radius: 0.5rem;
}

.loginfrm form p{
    padding: 1rem 0;
    font-size: 1.5rem;
    color: black;
}

.loginfrm form p a{
    color: #37afe2;
    text-decoration: underline;
}

.loginfrm #close-login-btn{
    position: absolute;
    top: 1.5rem;
    right: 2.5rem;
    font-size: 5rem;
    color: black;
    cursor: pointer;
}
.btns{
    display: flex;
    justify-content: center;
    align-items: center;
}
.btns .bz{
    color: black;
}

/*  */
.centact{
    overflow: hidden;
    padding-block: 5rem 2rem;
    position: relative;
    top: 141px;
    left: 100px;
    height: 130vh;
}
input,
textarea,
button 
{
    outline: none;
    border: none;
}

.section__title,
.section__subtitle{
    text-align: center;
    color: black;
    font-weight: 700;
}
.section__title{
    font-size: 20px;
    margin-bottom: 1.5rem;
    display: flex;
    justify-content: center;
    align-items: center;
    position: relative;
    left: -40px;

}
.section__subtitle{
    display: flex;
    justify-content: center;
    color:#1b92d1;
    font-size: 36px;
    font-weight: 800;
    margin-bottom: 50px;
    position: relative;
    top: 35px;
    left: -40px;
}
.spanm{
    color:black;
}


.button{
    display: inline-block;
    background-color: #1b92d1;
    padding: 1rem 1.75rem;
    border-radius: .5rem;
    color: black;
    font-weight: 600;
    justify-self: center;
    cursor: pointer;
}
.contact__container{
    padding-top: 1rem;  
    display: grid;
    gap: 1.5rem;
    max-width: 1120px;
    margin-inline: 1.5rem;
    position: relative;
    top:50px;
}


.contact__form{
    display: grid;
    row-gap: 1rem;
    position: relative;

}
.contact__group{
    display: grid;
    row-gap: 1rem;

}

.contact__input{
    padding: 1rem 1.25rem;
    border-radius: .5rem;
    background-color: #37afe2;
    color: black;
}

#msg{
    height: 20rem;
    resize: none;
    margin-bottom: 2rem;
    color: black;
}

.contact__message{
    position: absolute;
    left: 0;
    font-size: 15px;
    bottom: 4.15rem;
}
/*  */
.ct{
    display: flex;
    justify-content: center;
    flex-direction: row;
    flex-wrap: wrap;
    position: relative;
    top: -30px;
}

.card{
    background-color: #c8d9ea;
    width: 440px;
    box-shadow: 0 5px 25px rgba(18, 75, 180, 0.568);
    border-radius: 10px;
    padding: 25px;
    margin: 20px ;
    transition: 0.7s ease;
}

.card:hover{
    transform: scale(1.1);
}

.imgf img{
    display:inline-block;
    width: 400px;
    height: 180px;
}

.in{
    text-align: center;
}

.in h3{
    color: black;
    font-size: 25px;
    font-weight: 10px;
    margin: 10px;
}

.cd p{
    font-size: 20px;
}
.lik{
    text-decoration: none;
    color: black;
}
.foo{
    background-color:#1b92d1;
    padding: 32px;
    display: flex;
    justify-content: space-between;
    position: relative;
    top: +50px;
}

.foo .soc a{
    color: black;
    font-size: 28px;
    padding-right: 30px;
}
.fa-solid.fa-arrow-up{
    color: black;
}
@media(max-width:991px){
    html{
        font-size: 55%;
    }
    .header{
        padding: 2rem;
    }
}

@media(max-width:768px){
    .header #login-btn i{
        display: block;
    }
    .header #login-btn .bz{
        display: none;
    }
    .header .navc{
        position: absolute;
        top: 99%;
        left: 0;
        right: 0;
        background:#1b92d1;
        border-top: var(--border);
        clip-path: polygon( 0 0 , 100% 0, 100% 0 , 0 0);
        }
    .header .navc.active{
        clip-path: polygon(0 0 , 100% 0 , 100% 100% , 0 100%);
    }    
    .header .navc a{
        display: block;
        margin: 2rem;
        font-size: 2rem;
    }  
    #menubar{
        display: block;
    }  
    #menubar .fa-bars{
        transform: rotate(180deg);
    }
    .header.active{
        padding: 2rem;  
    }
}
@media(min-width:0px) and (max-width:705){
    html{
        font-size: 55%;
    }
}
