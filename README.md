 <head>
       <style>
       *{
    
    font-family: 'Indie Flower', cursive;
    margin: 0;
    padding: 0%;
    box-sizing: border-box;  
    scroll-behavior: smooth;
    
 }

 header {
width: 100%;
background-color:rgba(226, 200,197);
padding: 10px 200px;
display: flex;
justify-content:space-between;
z-index: 999;
position: fixed;
align-items: center;
 }

.logo{
    text-decoration: none;
    color:black;
    font-size: 1.8em;
    font-weight: 500;
    text-transform:uppercase;
}

.navBar a{
    text-decoration: none;
    font-size: 1.1em;
    font-weight: 500;
    color:black;
    padding-left: 30px;
}

.navBar a:hover{
    color:#ca8093;
}

section{
    padding: 100px 100px;
}

.main{
    width: 100%;
    min-height: 100vh;
    display: flex;
    align-items: center ;
    background: url(Images/Eman.jfif) no-repeat ;
    background-size:cover;
    background-position:0cm -9.5cm;
    background-attachment: fixed;
    padding: 3% 3% ;
}

.main h2{
   padding: 2% 10%;
    font-size: 1.4em;
    font-weight: 400;
    color: black;
}

.main h2 .myName
{
    
    display: inline-block;
    color: black;
    font-size: 2em;
    font-weight: 600;
}

.animation_des::after{
    content: '|';
    text-align:start;
    position:absolute;
    right: 30%;
    margin: 0% 20% 10%;
    background-color:rgba(226, 200,197) ;
    width: 42%;
    animation: typing 8s steps(50) alternate infinite;
}


.background{
    border-radius: 20%;
    width: 55%;
    background-color:rgba(226, 200,197);
}

.contact_btn{
    text-decoration: none;
    font-size: 1.1em;
    font-weight: 700;
    color: black;
    background:linear-gradient(#fdd9d9,rgb(230, 159, 151));
    display: inline-block;
    padding: .9375em 2.1875em;
    border-radius: 15px;
    letter-spacing: 1px;
    margin-left: 70px;
    transition: .7s ease;
    box-shadow: #ca8093;
}

.contact_btn:hover{
   background-color: #ca8093;
   transform: scale(1.1); 
}

.social-media {
    padding: 2% 12% 2%;
}
.social-media a{
    font-size: 1.7em;
    color:black;
    padding-right: 15px;
}

.social-media a:hover{
    color:black;
}

.title{
    display: flex;
    justify-content: center;
    font-size: 2em;
    font-weight: 800;
    margin-bottom: 30px;
}

.content{
    display: flex;
    justify-content: center;
    flex-direction: row;
    flex-wrap: wrap;
}



.programming .content{
    justify-content:space-between;
    background: linear-gradient(#fdd9d9 , rgb(193, 157, 154) );
    backdrop-filter: blur(.7rem);
    border-radius: 15%;
    padding: 10%;

}

.programming .skills{
    font-size: 2em;
}

.programming h2{
font-size: 2em;
font-weight: 600;
}


.card{
    background-color: #ca8093;
    width: 21.30em;
    box-shadow: 0px 5px 25px rgba(1 1 1 / 15%);
    border-radius: 15px;
    padding: 25px;
    margin: 15px;
    transition: .7s ease;
}

.card:hover{
    transform: scale(1.1);
}

.icon{
    font-size: 8em;
    color: antiquewhite;
    text-align: center;
   
}

.info{
    text-align: center;
}

.info h3{
    color: black;
    font-size: 1.1em;
    font-weight: 800;
    margin: 10px;
}

.info p {
    color: black;
    font-size: 1.2em;

}
table{
    display: flex;
    justify-content: center;   
}

th, td {
    padding: 20px;
    text-align: left;
    border-bottom: 5px solid rgb(4, 4, 4);
    font-size: 1.5em;
} 

tr:nth-child(odd) 
{
    background-color: #fdd9d9;
}


.des{
    list-style-type: circle;
}
.contact .icons{
font-size: 4.4em;
text-align: center;
color: antiquewhite;
}

.info_to_contact{
    font-size: 1em;
    font-weight: 800;
    text-align: center;
}

footer{
    background-color:rgba(226, 200,197);
    color: black;
    display: flex;
    justify-content: space-between;
    padding: 2em;
}

.footer_Title{
    font-size: 1.3em;
    font-weight: 500;
}

.footer_Title span{
    color:blueviolet
}

footer .social-media{
    padding: 2px 2px 2px;
}

.project_link{
text-decoration: none;
color: black;
font-weight: 600;


}


.animation{
    animation-name:changStyleFont;
    animation-duration: 1.5s;
    animation-iteration-count: infinite; 
    font-size: 1.7em;
}

.animation_title{
 text-align: center;
 font-size: 2em;
 position: relative;


}

.animation_title::after{
    content: '|';
    text-align:start;
    position:absolute;
    color: #000;
    right: 17%;
    margin: 0% 20% 10%;
    background-color:#f2cecd;
    width: 24%;
    animation: typing 3s steps(17) alternate infinite;
}

@keyframes  typing{
 to{width: 0%;}
}

@keyframes changStyleFont
{
    from{font-style: normal;
        color:black;}
    to{font-style: italic;
    color:brown;}

}



.senior{
    background: linear-gradient(#fdd9d9 , rgb(193, 157, 154) );
    box-shadow: 0 1rem 2rem rgba(0,0,0,.3);
    backdrop-filter: blur(.4rem);
    border-radius: 5%;
}

.senior .content{
    justify-content:space-between;
    justify-items: center;
}

.senior_des h2{
  text-shadow: 2px 1px 2px #752f41;
}

.senior_des{
    background: rgba(255, 255, 255, .2);
    backdrop-filter: blur(.4rem);
    padding: 10% 5% 0%;
    border-radius: 40%;
}

.senior_des p{
  padding: 5px;
  width: 500px;
  height: 300px;
  text-align: justify;
  font-weight: 600;
}

.senior_image img{
    padding-top: 3em;
    width: 500px;
    height: 400px;
    border-radius: 40%;
    box-shadow: 0px 7px 4px .2rem #ca8093;

}

figcaption{
    text-align: center;
    font-weight: 600;
}

.internshipCard{
    background-color: #ca8093;
    width: 21.30em;
    border-radius: 50px;
    padding: 25px ;
    margin: 15px;
    font-size: 1.2em;
    text-align: center;
    font-weight: 500;
}
</style>
    </head>



<body>
        <header>
            <a href="#" class="logo">Eman's portfolio </a>
            <nav class="navBar">
                <a href="#WorkExperince">Work Experience</a>
                <a href="#Senior_project">Senior Project</a>
                <a href="#projects">Other Projects</a>
                <a href="#skills">Skills</a>
                <a href="#contactMe">Contact Me</a>
            </nav>
        </header>

        <section class="main">
            <div class="background">
                <h2>Hi ,I'm <br> <span class="myName">Eman Yahya  </span><br> <span class="animation_des">Fresh graduate majoring in Computer Systems Engineering.</span></h2>
                <a href="#internship" class="contact_btn">Why I am interested to join this training?</a>
                <div class="social-media">
                    <a href="https://www.linkedin.com/in/eman-yahya-0429aa231/" target="_blank"><i class="fa-brands fa-linkedin"></i></a>
                    <a href="https://github.com/EmanYahya210" target="_blank"><i class="fa-brands fa-github" ></i></a>
                    <a href="https://instagram.com/eng.eman_3?igshid=YmMyMTA2M2Y=" target="_blank"><i class="fa-brands fa-instagram"></i></a>
                </div>
            </div>
        </section>


        <section class="cards" id="WorkExperince">
            <h2 class="title">WORK EXPERIENCE</h2>
            <div class="content">
                <div class="card">
                    <div class="icon">
                        <i class="fa-solid fa-computer"></i>
                    </div>
                    <div class="info">
                        <h3>Internship</h3>
                        <p>React.js training at Asal technologies.</p>
                    </div>
                </div>
                <div class="card">
                    <div class="icon">
                        <i class="fa-solid fa-virus-covid"></i>
                    </div>
                    <div class="info">
                        <h3>Palestinian Ministry of Health</h3>
                        <p>Voluntary data entry of<br>COVID-19.</p>
                    </div>
                </div>
                <div class="card">
                    <div class="icon">
                        <i class="fa-solid fa-building-columns"></i>
                    </div>
                    <div class="info">
                        <h3>Arab American University</h3>
                        <p>Volunteer with the Public Relations Department.</p>
                    </div>
                </div>
            </div>
        </section>

        <section class="senior" id="Senior_project">
            <h2 class="animation_title">My Senior Project</h2>
            <div class="content">
            
            <div class="senior_des">
            <h2>Eye-controlled Game for the Disabled People</h2>
            <p><br>We created a game with features and specifications that ease up the process of playing for disabled people who are unable to play games or control a computer with their hands without needing any help and it uses a simple Webcam to transform eye motions into a code that the computer can understand which allows individuals to play a game with their eyes.</p>
            </div>

            <div class="senior_image">
                <figure>
                <img src="Images/senior.png">
                <figcaption><br>System Overview.</figcaption>
                </figure>
                
            </div>

        </div>
        </section>

        <section class="project" id="projects">
            <h2 class="title">Projects</h2>
            <table>
                <tr>
                    <th>Project name</th>
                    <th>Project link</th>
                </tr>
        
                <tr>
                    <td>React.js project</td>
                    <td><a href="https://www.linkedin.com/posts/eman-yahya-0429aa231_react-project-github-activity-6965296232785166336-M9Om?utm_source=linkedin_share&utm_medium=member_desktop_web" class="project_link" target="_blank"><span class="animation">Click here</span>  to show the project in  <span class="animation">LinkedIn</span></a></td>
                </tr>

                <tr>
                    <td>Unity (C# language) project </td>
                    <td><a href="https://www.linkedin.com/feed/update/urn:li:activity:6960586398143787009/" class="project_link" target="_blank"><span class="animation">Click here</span> to show the project in <span class="animation">LinkedIn</span></a></td>
                </tr>
            
            </table> 
            
            
        </section>

        <section class="programming" id="skills">
        
        <div class="content">
            <div>
                <h2>Programming skill</h2>
                <ul class="skills">
                    <li>Web Development.</li>
                    <li>React.js.</li>
                    <li>Git and GitHub.</li>
                    <li>Unity.</li>
                </ul>
            </div>
            <div>
                <h2>Expertise skill</h2>
                <ul class="skills">
                    <li>Planning and Coordination.</li>
                    <li>Excellent Communication.</li>
                    <li>Flexible and Adaptable.</li>
                    <li>Analytical & Critical Thinking.</li>
                </ul>
            </div>
            <div>
                <h2>Languages</h2>
                <ul class="skills">
                    <li>Arabic.</li>
                    <li>English.</li>
                
                </ul>
            </div>
        </div>
        
        </section>

        <section class="internship" id="internship">
            <h2 class="title">Why I am interested to join this training ?</h2>
            <div class="content">
                <div class="internshipCard">
                    <div>
                        <p>Expand my knowledge in web development.</p>
                    </div>
                </div>
                <div class="internshipCard">
                    <div>
                        <p>To gain skills that allow me to enter the field of work and find job opportunities.</p>
                    </div>
                </div>
                <div class="internshipCard">
                    <div>
                        <p>Participation in courses with people who have competence and experience.</p>
                    </div>
                </div>
                <div class="internshipCard">
                    <div>
                        <p>Design websites using react.js professionally.</p>
                    </div>
                </div>
                <div class="internshipCard">
                    <div>
                        <p>Learn about new technologies.</p>
                    </div>
                </div>

        
        </section>


        <section class="contact" id="contactMe">
            <h2 class="title">Let's work together</h2>
            <div class="content">
                <div class="card">
                    <div class="icons">
                        <i class="fa-solid fa-phone"></i>
                    </div>
                    <div class="info_to_contact">
                        <h3>Phone</h3>
                        <p>00972598621040</p>
                    </div>

                </div>

                <div class="card">
                        <div class="icons">
                            <i class="fa-solid fa-envelope"></i>
                        </div>
                        <div class="info_to_contact">
                            <h3>Email</h3>
                            <p>emanalsayed210@gmail.com</p>
                        </div>
                </div>
            </div>
        </section>

        
        <footer>
            <p class="footer_Title">Copyright@<span>Eman Yahya</span></p>
            <div class="social-media">
                <a href="https://www.linkedin.com/in/eman-yahya-0429aa231/" target="_blank"><i class="fa-brands fa-linkedin"></i></a>
                <a href="https://github.com/EmanYahya210" target="_blank"><i class="fa-brands fa-github" ></i></a>
                <a href="https://instagram.com/eng.eman_3?igshid=YmMyMTA2M2Y=" target="_blank"><i class="fa-brands fa-instagram"></i></a>
            </div>
        </footer>
