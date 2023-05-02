# DekodePortfolio
----------------------index.html file-------------------
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Divyansh Portfolio Website</title>
    <link rel="stylesheet" href="style.css">
    <script src="https://kit.fontawesome.com/34f23c8a22.js" crossorigin="anonymous"></script>
</head>
<body>
<div id="header">
    <div class="container">
        <nav>
            <img src="images/dekod.png" class="logo">
            <ul id="sidemenu">
                <li><a href="#header">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#portfolio">Portfolio</a></li>
                <li><a href="#contact">Contact</a></li>
                <i class="fa-solid fa-xmark" onclick="closemenu()"></i>
            </ul>
            <i class="fa-solid fa-bars" onclick="openmenu()"></i>
        </nav>
        <div class="header-text">
            <p>UI.UX Designer</p>
            <h1>Hi,I'm <span>Divyansh</span> <br> Pratap Singh <br> From India</h1>
        </div>
    </div>
</div>

<!-- ---------about--------------- -->
<div id="about">
    <div class="container">
        <div class="row">
            <div class="about-col-1">
                <img src="images/user2 (1).jpg" alt="">
            </div>
            <div class="about-col-2">
                <h1 class="sub-title">About Me</h1>
                <p>I am Divyansh Pratap Singh. I have experience of video editing for 1 year and have basic knowledge about sql and python.Currently i am learning front End Development.I am from CSE Department living in India.I have been a 5 star rating holder at TypeDozo with Certification.
                
                
                </p>
                <div class="tab-titles">
                    <p class="tab-links active-link " onclick="opentab('skills')">Skills</p>
                    <p class="tab-links"onclick="opentab('experience')">Experience</p>
                    <p class="tab-links" onclick="opentab('education')">Education</p>
                </div>
                <div class="tab-contents active-tab" id="skills">
                    <ul>
                        <li><span>UI/UX</span><br>Designing Web/App Interfaces</li>
                        <li><span>Web Development</span><br>Designing Web/App Interfaces</li>
                        <li><span>App Development</span><br>Building Android/Ios apps</li>
                    </ul>
                </div>
                <div class="tab-contents" id="experience">
                    <ul>
                        <li><span>2021 - Current</span><br>UI/UX Design Training at ET Institute</li>
                        <li><span>2019 - 2021</span><br>Team lead at StarApp Lic.</li>
                        <li><span>2017-2029</span><br>UI/ux Design Executive at Coin Digital  Ltd.</li>
                        <li><span>2016-2017</span><br>Internship at eart eCommerce.</li>

                    </ul>
                </div>
                <div class="tab-contents" id="education">
                    <ul>
                        <li><span>2016</span><br>UI/UX Design Training at ET Institute</li>
                        <li><span>2016</span><br>MBA from MIT Bangalore.</li>
                        <li><span>2014</span><br>BBA from ISM Bangalore.</li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</div>
<!-- -------------services------------- -->
<div class="services">
    <div class="container">
        <h1 class="sub-title">My Services</h1>
        <div class="services-list">
            <div>
                <i class="fa-solid fa-code"></i>
                <h2>Web Design</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quibusdam dolor aliquam maxime, sed quaerat omnis totam cupiditate, magni exercitationem obcaecati voluptates doloribus iure.</p>
                <a href="#">learn more</a>
            </div>
            <div>
                <i class="fa-solid fa-crop"></i>
                <h2>UI/UX Design</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quibusdam dolor aliquam maxime, sed quaerat omnis totam cupiditate, magni exercitationem obcaecati voluptates doloribus iure.</p>
                <a href="#">learn more</a>
            </div>
            <div>
                <i class="fa-brands fa-app-store-ios"></i>
                <h2>App Design</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quibusdam dolor aliquam maxime, sed quaerat omnis totam cupiditate, magni exercitationem obcaecati voluptates doloribus iure.</p>
                <a href="#">learn more</a>
            </div>
        </div>

    </div>
</div>
<!-- -----------portifolio---------- -->
<div id="portfolio">
    <div class="container">
        <h1 class="sub-title">My Work</h1>
        <div class="worklist">
            <div class="work">
                <img src="images/work-2.png" alt="">
                <div class="layer">
                    <h3>Social Media App</h3>
                    <p>The app connects you to the talented people around the world.Download it from Play Store</p>
                    <a href="#"><i class="fa-solid fa-up-right-from-square"></i></a>
                </div>
                
            </div>
            <div class="work">
                <img src="images/my image.jpg" alt="">
                <div class="layer">
                    <h3>Doing Projects</h3>
                    <p>Project Making</p>
                    <a href="#"><i class="fa-solid fa-up-right-from-square"></i></i></a>
                </div>
            </div>
            <div class="work">
                <img src="images/work-3.png" alt="">
                <div class="layer">
                    <h3>Online Shopping Apps</h3>
                    <p>The app connect you to talented people</p>
                    <a href="#"><i class="fa-solid fa-up-right-from-square"></i></a>
                </div>
            </div>
        </div>
        <a href="#" class="btn">See More</a>
    </div>
</div>
<!-- ------------contact--------- -->
<div id="contact">
    <div class="container">
        <div class="row">
            <div class="contact-left">
                <h1 class="sub-title">Contact Me</h1>
                <p ><i class="fa-solid fa-paper-plane"></i>contact@example.com</p>
                <p><i class="fa-solid fa-phone"></i> 09373907387</p>
                <div class="social-icons">
                    <a href="https://www.instagram.com/dps_047/" ><i class="fa-brands fa-instagram"></i></a>
                  
                    <a href=""><i class="fa-brands fa-youtube"></i></a>
                  
                    <a href="https://in.linkedin.com/in/divyansh-pratap-singh-5338a5272"><i class="fa-brands fa-linkedin"></i></a>
                
                </div>
                <a href="images/my cv 2.pdf" download class="btn btn2">Download CV</a>
            </div>
            <div class="contact-right">
                <form name="submit-to-google-sheet">
                    <input type="text" name="Name" placeholder="Your Name" required>
                    <input type="text" name="email" placeholder="Your Email" required>
                    <textarea name="Message"  rows="6" placeholder="Your Message"></textarea>
                    <button type="submit" class="btn btn2">Submit </button>
                </form>  
            </div>
        </div>
    </div>
    <div class="copyright">
        <p>Copyright <i class="fa-regular fa-copyright"></i> Dekod . Made with <i class="fa-solid fa-heart"></i> by Divyansh pratap Singh </p>
    </div>
</div>

<script>
    var tablinks = document.getElementsByClassName("tab-links");
    var tabcontents = document.getElementsByClassName("tab-contents");
    
    function opentab(tabname){
        for(tablink of tablinks){
            tablink.classList.remove("active-link");


        }
        for(tabcontent of tabcontents){
            tabcontent.classList.remove("active-tab");
        }
        event.currentTarget.classList.add("active-link");
        document.getElementById(tabname).classList.add("active-tab")
    }
</script>   
<script>
    const scriptURL = '<https://script.google.com/macros/s/AKfycbwDMpVQYy1XQ_mO63t5ZzqMBaAmwiPIQ7rw4BJnB-8KJIDUl7zRd-FgHQm8d7LB79E/exec>'
    const form = document.forms['submit-to-google-sheet']
  
    form.addEventListener('submit', e => {
      e.preventDefault()
      fetch(scriptURL, { method: 'POST', body: new FormData(form)})
        .then(response => console.log('Success!', response))
        .catch(error => console.error('Error!', error.message))
    })
  </script>
  <script>
    var sidemenu = document.getElementById("sidemenu");

    function openmenu(){
        sidemenu.style.right="0";
        
    }
    function closemenu(){
        sidemenu.style.right="-200px";

    }
  </script>
</body>
</html>


--------------------------cssfile ----------------------


*{
    margin: 0;
    padding: 0;
    font-family:'Times New Roman', Times, serif;
    box-sizing: border-box;
}
html{
    scroll-behavior: smooth;
}
body{
    background: #080808;
    color:#fff;
}
#header{
    width: 100%;
    height: 100vh;
    background-image: url(images/main\ bg\ 51.jpg);
    background-size: cover;
    background-position: center;

}
.container{
    padding: 10px 10%;
}
nav{
    display: flex;
    align-items: center;
    justify-content: space-between;
    flex-wrap: wrap;
}
.logo{
    width: 140px;
} 
nav ul li{
    display: inline-block;
    list-style: none;
    margin: 10px 20px;
}
nav ul li a{
    color: #fff;
    text-decoration: none;
    font-size: 18px;
    position: relative;

     
} 
nav ul li a::after{
    content: '';
    width: 0;
    height: 3px;
    background: #fab005;
    position: absolute;
    left: 0;
    bottom: -6px;
    transition: 0.5s;

}
nav ul li a:hover::after{
    width: 100%;
}
.header-text{
    margin-top: 20%;
    font-size: 30px;

}
.header-texth1{
    font-size: 60px;
    margin-top: 20px;

}
.header-text h1 span{
    color: #ff004f;

}
/* ---------about-------- */
#about{
    padding: 80px 0;
    color:#ababab;
}
.row{
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
}
.about-col-1{
    flex-basis: 35%;
}
.about-col-1 img{
    width: 100%;
    border-radius: 15px;


} 
.about-col-2{
    flex-basis: 60%;
}
.sub-title{
    font-size: 60px;
    font-weight: 600;
    color: white;



}
.tab-titles{
    display: flex;
    margin: 20px 0 40px;

}
.tab-links{
    margin-right: 50px;
    font-size: 18px;
    font-weight: 900;
    cursor: pointer;
    position: relative;

}
.tab-links::after{
    content: '';
    width: 0;
    height: 3px;
    background:#ff004f;
    position: absolute;
    left: 0;
    bottom: -8px;
    transition: 0.5s;

}
.tab-links.active-link::after{
    width: 50%;
}
.tab-contents ul li{
    list-style: none;
    margin: 10px 0;

}
.tab-contents ul li span{
    color: #b54769;
    font-size: 14px;
}
.tab-contents{
    display: none;

}
.tab-contents.active-tab{
    display: block;
}

/* --------services------- */
.services-list{
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(250px,1fr));
    grid-gap: 40px;
    margin-top: 50px;
}
.services-list div{
        background: #263636;
        padding: 40px;
        font-size: 13px;
        font-weight: 300;
        border-right: 10px;
        transition: background 0.5s,transform 0.5s;

}
.services-list div i{
    font-size: 50px;
    margin-bottom: 30px;


}
.services-list div h2{
    font-size: 30px;
    font-weight: 500;
    margin-bottom: 15px;
}
.services-list div a{
    text-decoration: none;
    color: #fff;
    font-size: 12px;
    margin-top: 20px;
    display: inline-block;
}
.services-list div:hover{
    background-color: #ff004f;
    transform: translateY();
}
.work{
    border-radius: 10px;
    position: relative;
    overflow: hidden;
}
.work img{
    margin: 10px;
    display: flex;
    display: inline;
    width: 20%;
    border-radius: 10px;
    transition:transform 0.5s ;

    
    

}
.layer{
    width: 100%;
    height: 100%;
    background: linear-gradient(rgba(0,0,0,0.6),#ff004f);
    border-radius: 10px;
    position: absolute;
    left: 0;
    bottom: 0;
    overflow: hidden;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction:column ;
    padding: 0 40px;
    text-align: center;
}
.layer h3{
    font-weight: 500;
    margin-bottom: 20px;
}
.layer a{
    margin-top: 20px;
    color: #ff004f;
    text-decoration: none;
    font-size: 18px;
    line-height: 60px;
    background: black;
    width: 60px;
    height: 60px;
    border-radius: 50%;
    text-align: center;
}
work:hover img{
    transform: scale(1.1);

}
.btn{
    display: block;
    margin: 50px auto;
    width: fit fit-content;
    border: 1px solid #ff004f;
    padding: 14px 50px;
    border-radius: 6px;
    text-decoration: none;
    color: #fff;
}
.btn:hover{
    background-color: #ff004f;
}
/* --------contact------------ */
.contact-left{
    flex-basis:60%;
}
.contact-right{
    flex-basis: 60%;

}
.contact-left p{
    margin-top: 30px;

}
.contact-left p i{
    color: #ff004f;
    margin: 15px;
    font-size: 25px;
}
.social-icons a{
    text-decoration: none;
    font-size: 30px;
    margin-right: 15px;
    color: #ababab;
    display: inline-block;
    transition: transform 0.5s;
}
.social-icons a:hover{
    color: #ff004f;
    transform: translate(-5px);
}
.btn.btn2{
    display: inline-block;
    background: #ff004f;
}
.contact-right{
    width: 100%;
    
}
form input,form textarea{
    width: 100;
    border: 0;
    outline: 0;
    background: #263636;
    padding: 15px;
    margin: 15px 0;
    color: #fff;
    font-size: 18px;
    border-radius: 6px;
}
form btn2{
    padding: 14px 60px;
    font-size: 18px;
    margin-top: 20px;
    cursor:pointer ;
}
.copyright{
        width: 100%;
        text-align: center;
        padding: 25px 0;
        background: #262626;
        font-weight: 300;
        margin-top: 20px;
}
.copyright i{
    color: red;
}



/* ------------vss for small screen------ */
nav .fas{
    display: none;
}
@media only screen and (max-width:600px){
    #header{
        background-image: url(images/main\ bg52.jpg);
    }
    .header-text{
        margin-top: 100%;
        font-size: 16px; 
    }
    .header-text h1{
        font-size: 30px;
    }
    nav .fas{
        display: block;
        font-size: 25px;
    }
    nav ul{
        background:#ff004f;
        position: fixed;
        top: 0;
        right: -200px;
        width: 200px;
        height: 100vh;
        padding-top: 50px;
        z-index: 2;
        transition: right 0.5s;
    }
    nav ul li{
        display: block;
        margin: 25px;

    }
    nav ul .fas{
        position: absolute;
        top: 25px;
        left: 25px;
        cursor: pointer;
    }
    .sub-title{
        font-size: 40px;
    }
    .about-col-1, .about-col-2{
        flex-basis: 100%;
    }
    .about-col-1{
        margin-bottom: 30px;

    }
    .about-col-2{
        font-size: 14px;
    }
    .tab-links{
        font-size: 16px;
        margin-right: 20px;
    }
    .contact-left, .contact-right{
        flex-basis: 100%;
    }
    .copyright{
        font-size: 14px;
    }
    
} 

-------------------resources used---------------------
[my-cv.pdf](https://github.com/divyansh2375/DekodePortfolio/files/11371230/my-cv.pdf)
![phone-background](https://user-images.githubusercontent.com/130889408/235618003-124e1366-9d03-4122-b788-19dfbd55656c.png)
![user2 (1)](https://user-images.githubusercontent.com/130889408/235618028-be044a65-08db-4d37-809e-95fc27f5a5e4.jpg)
![user2 (1)](https://user-images.githubusercontent.com/130889408/235618033-d71e8737-ea2a-45f8-a4a1-03b9a0a76977.png)
![user2 (2)](https://user-images.githubusercontent.com/130889408/235618042-3fb2777e-f2e5-414d-b448-dcb1a08b43e8.png)
![work-2](https://user-images.githubusercontent.com/130889408/235618055-45939240-0738-42f4-9207-c1ecece45e4e.png)
![work-3](https://user-images.githubusercontent.com/130889408/235618071-25a55e22-bb88-4832-bd88-cef1ca4f07e0.png)
![dekod](https://user-images.githubusercontent.com/130889408/235618084-989b52d3-c119-49b7-803a-b33c88f2810d.png)
![main bg 3](https://user-images.githubusercontent.com/130889408/235618089-3df362c8-dbc3-46ae-b24a-b4def7cea9de.jpg)
![main bg 51](https://user-images.githubusercontent.com/130889408/235618090-697e7356-83da-45fa-ae01-3f523086f3e5.jpg)
![main bg4](https://user-images.githubusercontent.com/130889408/235618098-5f05e581-fb87-439c-8f51-3b7d9ac06b7a.jpg)
![main bg5](https://user-images.githubusercontent.com/130889408/235618102-8b395ad9-188a-4c5e-bb7a-9b572ccb73ff.jpg)
![main bg52](https://user-images.githubusercontent.com/130889408/235618121-3eee40d3-8961-4fa3-9f70-12bda13c26fb.jpg)
[my cv 2.pdf](https://github.com/divyansh2375/DekodePortfolio/files/11371235/my.cv.2.pdf)
![my image](https://user-images.githubusercontent.com/130889408/235618133-8684b6a3-d860-4166-9f7b-4e37528e6c0b.jpg)



