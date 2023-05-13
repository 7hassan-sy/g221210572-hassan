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
}

section{
    padding: 100px 200px;

}

.main{
    width: 100%;
    min-height: 100vh;
    display: flex;
    align-items: center;
    background: url(pngtree-electronic-technology-website-texture-background-banner-image_156039.jpg)  no-repeat;
    background-size: cover;
    background-position: center bottom;
    background-attachment: fixed;
}

.main h2{
    font-size:23px ;
    font-weight: 500;
}

.main h2 span{
    display: inline-block;
    color: #c8d9ea;
    font-size: 48px;
    font-weight: 600;
    margin-top: 10px;
}

.main h3{
    font-size:31px ;
    font-weight: 700;
    letter-spacing: 1px;
    margin-top: 10px;
    margin-bottom: 30px;
}

.btn{
    color: #c8d9ea;
    background-color:#1b92d1 ;
    text-decoration: none;
    font-size: 18px;
    font-weight: 600;
    display: inline-block;
    padding: 15px 35px ;
    letter-spacing: 1px;
    border-radius: 15px;
    margin-bottom: 40px;
    transition: 0.7s ease;
}

.btn:hover{
    background-color: #37afe2;
    transform: scale(1.1);
}

.soc a{
    color: black;
    font-size: 28px;
    padding-right: 30px;
}
section .first-section{
    margin: 15px;
}
.first-section .col-lg-3.col-12 img{
    height: 320px;
    width: 319px;
    border: 5px solid #1b92d1;
    border-radius: 240px;
    padding: 5px;
    background-color: white;
    margin: 1%;
    position: relative;
    left: -85px;
    transition: 0.7s ease;

}

img {
    vertical-align: middle;
}

.first-section h1{
    font-size: 32px;
    width:55%;
    z-index: 5;
    position: relative;
    top:-312px;
    left: 200px;
    text-align: center;
    color:black;
}
h1{
    margin-bottom: 8px;
    font-weight: 800;
    line-height: 1.2;
    margin-top: 0;
    margin-bottom: 8px;
    display: block;
    margin-inline-end: 0px;
    margin-block-start: 0px;
}

.first-section p{
    border: 5px solid #1b92d1;
    padding: 15px;
    font-size: 34px;
    border-radius: 50px;
    position: relative;
    top: -330px;
    left: 230px;
}


p{
    margin-top: 0;
    margin-bottom: 20px;
    margin: 0;
    font-weight: 800px;
    text-align: left;
    text-align: justify;
    display: block;
    margin-block-start: 1em;
    margin-block-end: 1em;
    margin-inline-start: 1em;
    margin-inline-end: 1em;
}

.first-section .col-lg-3.col-12 img:hover{
    width: 22%;
    height: 350px;
}

.title{
    display: flex;
    justify-content: center;
    color:#1b92d1;
    font-size: 36px;
    font-weight: 800;
    margin-bottom: 50px;
    position: relative;
    top: -415px;
}

.ct{
    display: flex;
    justify-content: center;
    flex-direction: row;
    flex-wrap: wrap;
    position: relative;
    top: -395px;
}

.card{
    background-color: #37afe2;
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
    font-size: 20px;
    font-weight: 10px;
    margin: 10px;
}

.lik{
    text-decoration: none;
    color: black;
}

.foo{
    background-color: #1b92d1;
    padding: 32px;
    display: flex;
    justify-content: space-between;
}

.foo-title{
    font-size: 25px;
    font-weight: 700;
}

.foo-title span{
    color: #ecf5fb;
    font-size: 15px;
    font-weight: 300;
}

.fa-solid.fa-arrow-up{
    color: black;
    padding: 30px;
}

@media(max-width:991px){
    html{
        font-size: 55%;
    }
    .header{
        padding: 2rem;
    }
    .main h2{
        position: relative;
        top: 32px;
        left: -73px;
        font-weight: 600;
    }
    .main h2 span{
        font-size: 27px;
    }
    .main h3{
        font-size: 29px;
        position: relative;
        top: 34px;
        left: -73px;
        font-weight: 600;
    }
    .btn{
        position: relative;
        top: 25px;
        left: -73px;
        font-weight: 900;
        font-size: 15px;
    }
    .soc a{
        position: relative;
        left: -60px;
        top: 5px;
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
    .main h2{
        position: relative;
        top: 88px;
        left: -149px;
        font-weight: 600;
    }
    .main h2 span{
        font-size: 15px;
    }
    .main h3{
        font-size: 25px;
        position: relative;
        top: 87px;
        left: -149px;
        font-weight: 600;
    }
    .btn{
        position: relative;
        top: 70px;
        left: -149px;
        font-weight: 900;
        font-size: 11px;
    }
    .soc a{
        position: relative;
        left: -133px;
        top: 50px;
    }
}
@media(min-width:0px) and (max-width:705){
    html{
        font-size: 55%;
    }
}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link rel="stylesheet" href="cv.css">
    <title>cv</title>
</head>
<body>
    <header class="header" >
        <div id="menubar" class="fa-solid fa-bars"></div>
        <a href="index.html"class="logo">Hassan
            <span>syr</span>
        </a>
        <nav class=navc>
            <a href="index.html" >Home</a>
            <a href="#" >CV</a>
            <a href="#" >MyCity</a>
            <a href="#" >Interests</a>
            <a href="#" >Communication</a>
        </nav>
        <div id="login-btn">
                <button type="button" class="bz">login</button>
                <i class="fa-solid fa-user"></i>
            </div>
    </header>
    <section class="main">
        <div>
            <h3>if you don't succeed try ,<br> try and try again.</h3>
            <a href="#sa" class="btn">educational</a> 
            <a href="#sp" class="btn">projects</a> 
        </div>
    </section>
    <section class="cd" id="sa">
        <h2 class="title">Educational Stages </h2>
        <div class="ct">
            <div class="card">
                <div class="imgf">
                    <img src="1-80.jpg" alt="footbal" >
                </div>
                <div class="in">
                    <h3>Elementary and <br>preparatory</h3>
                    <p>
                        I started studying the primary stage in 2009 in Aleppo at Al-Rasheed Private School and completed it in 2013. I stopped studying for a year because of the conditions in Syria.
                        I completed the middle school journey in Turkey and completed it in 2018 in one of the schools in Turkey.
                    </p>
                </div>
            </div>
            <div class="card">
                <div class="imgf">
                    <img src="k_02104744_IMG_20201106_092346.jpg" alt="">
                </div>
                <div class="in">
                    <h3>High school</h3>
                    <p>
                        I started high school studies in the winter of 2018 in Turkey in the city of Hatay at the Girikhan Anatolian High School and finished it in 2022 and it was one of the most beautiful period of my life
                    </p>
                </div>
            </div>
            <div class="card">
                <div class="imgf">
                    <img src="timthumb (1).jpeg" alt="">
                </div>
                <div class="in">
                    <h3>university</h3>
                    <p>
                        I started my undergraduate studies in Turkey at the University of Sakarya, in the Faculty of Computer Engineering, in the winter of 2023. The university is one of the best universities in Turkey, and I am now completing my studies there.
                    </p>
                </div>
            </div>
        </div>
        
    </section>
    <section class="projects" id="sp" class="content">
        <h2 class="title">projects</h2>
        <div class="content">
            <div class="pcard">
                <div class="pimg">
                    <img src="A6487-Is-online-learning-here-to-stay-Image.jpg" alt="">
                </div>
                <div class="pn">
                    <p class="pca">System programming project for a school</p>
                    <strong class="pt">
                        <span>Click to see the project</span>
                        <a href="#" class="m">Click</a>
                    </strong>
                </div>
            </div>

            <div class="pcard">
                <div class="pimg">
                    <img src="5dc6c05ec03c0e20f8424160.jpeg" class="matm" alt="">
                </div>
                <div class="pn">
                    <p class="pca">System programming project for a restaurant</p>
                    <strong class="pt">
                        <span>Click to see the project</span>
                        <a href="#" class="m">Click</a>
                    </strong>
                </div>
            </div>

            <div class="pcard">
                <div class="pimg">
                    <img src="كيفية-تصميم-موقع-الكتروني.jpg" alt="">
                </div>
                <div class="pn">
                    <p class="pca">A personal website programming project</p>
                    <strong class="pt">
                        <span>Click to see the project</span>
                        <a href="#" class="m">Click</a>
                    </strong>
                </div>
            </div>
        </div>
    </section>
    <section class="Skl">
        <h1 class="title">MY SKILLS</h1>
        <div class="content">
        <div class="dlip" >
            <h3 class="h3a">Technical skills:</h3>
            <small class="nsp">c++</small>
            <div class="mu">
                <div class="bar" style="    width: 70%;
                background-color: #37afe2;">70%</div>
            </div>
            <small class="nsp">c#</small>
            <div class="mu">
                <div class="bar" style="    width: 50%;
                background-color: #37afe2;">50%</div>
            </div>
            <small class="nsp">js</small>
            <div class="mu">
                <div class="bar" style="    width: 60%;
                background-color: #37afe2;">60%</div>
            </div>
            <small class="nsp">php</small>
            <div class="mu">
                <div class="bar" style="    width: 30%;
                background-color: #37afe2;">30%</div>
            </div>
            <small class="nsp">css</small>
            <div class="mu">
                <div class="bar" style="    width: 90%;
                background-color: #37afe2;">90%</div>
            </div>
            <small class="nsp">html</small>
            <div class="mu">
                <div class="bar" style="    width: 90%;
                background-color: #37afe2;">90%</div>
            </div>

            <h3 class="h3a">The languages ​​I know:</h3>
            <small class="nsp">English</small>
            <div class="mu">
                <div class="bar" style="    width: 50%;
                background-color: #37afe2;">50%</div>
            </div>
            <small class="nsp">Turkish</small>
            <div class="mu">
                <div class="bar" style="    width: 80%;
                background-color: #37afe2;">80%</div>
            </div>
            <small class="nsp">Arabic</small>
            <div class="mu">
                <div class="bar" style="    width: 100%;
                background-color: #37afe2;">0%</div>
            </div>
        </div>
    </div>
    </section>
    <footer class="foo">
        <div class="soc">
            <a href="https://instagram.com/hassan__sy3?igshid=ZGUzMzM3NWJiOQ=="><i class="fa-brands fa-instagram"></i></a>
            <a href="https://github.com/7hassan-sy"><i class="fa-brands fa-github"></i></a>
            <a href="https://www.tiktok.com/@hassan_syr3?_t=8c7rLAVwTf4&_r=1"><i class="fa-brands fa-tiktok"></i></a>
            <a href="https://youtube.com/@hassansyr5060"><i class="fa-brands fa-youtube"></i></a>
        </div>
        <a href="indexcv.html">
        <i class="fa-solid fa-arrow-up" ></i>
        </a>
        </footer>
    <script src="main.js"></script>
</body>
</html>
