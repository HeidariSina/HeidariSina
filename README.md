<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Fira+Sans:ital,wght@1,300&display=swap" rel="stylesheet">
    <title>Sina Heidari</title>
    <style>
  body{
  margin: 0;
  padding: 0;
  text-align: center;
  width: 100vw;
  background-color: #e9c46a;
  overflow-x: hidden;
  color: white;
}
.main{
  padding:1rem 0 0rem 0;
}
nav{
  margin : 0 auto 2rem auto;
  padding: 0.5rem 0 0.5rem 0;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
  align-items: center;
  height: 3rem;
  background-color: #264653;
  width: 80%;
  border-radius: 50rem;
  border: 0.2rem solid #2a9d8f;
}
a{
  text-decoration: none;
  color: white;
  font-family: 'Fira Sans', sans-serif;
  letter-spacing: 0.1rem ;
  font-size: 1.2rem;
  min-width: 6rem;
}
h1{
  margin-bottom: 0;
}
.about_me{
  background-image: linear-gradient(#264653 , #2a8f83);
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
  width: 80%;
  height: 35rem;
  margin-left: auto;
  margin-right: auto;
  padding: 4rem 0 4rem 0;
  border-radius: 3rem;
}
.main_photo{
  min-width: 15rem;
  max-width: 22%;
  margin: auto 2rem auto 2rem;
  border-radius: 50rem;
  filter: grayscale(50%);
}
.content{
  margin: auto 2rem auto 2rem;
}
.about_me_title{
  margin-bottom: 1.5rem;
}
.main_text{
  width: 35vw;
  word-wrap: break-word;
  margin : 0.5rem auto 0.5rem auto;
  font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}
.career{
  padding:2rem 0 2rem 0 ;
}
.head1{
  margin: 0;
}
.section{
  margin: 1rem auto 0 auto;
  border-radius: 5rem;
  width: 70%;
  box-shadow: 0.3rem 0.5rem 0.5rem black;
  text-align: left;
  padding: 2rem 2rem 2rem 2rem;
  background-size: cover;
  background-repeat: no-repeat;
    
}
.st{
  font-family: Verdana, Geneva, Tahoma, sans-serif;
  font-size: 1.125rem;
  font-weight: lighter;
  margin-left: 1rem;
}
.sth{
  font-family: sans-serif;
  font-weight: normal;
  text-align: center;
}
li{
  font-family: Verdana, Geneva, Tahoma, sans-serif;
  font-size: 1.125rem;
  line-height: 2rem;
  font-weight: lighter;
  list-style-type :disc;
}
.PS{
  background-image: url(ps.jpg);
  background-position: center;
}
.pro_h3{
  margin-top: 2rem;
  margin-bottom: 0rem;
  font-style: oblique;
}
.pro_p{
  margin: 0;
  font-weight:lighter ;
}
.knowledge{
  font-family: Verdana, Geneva, Tahoma, sans-serif;
  text-align: center;
  padding-bottom: 4rem;
  padding-top: 2rem;
}
.cb{
    color:#264653;
}
.title{
  margin: 2rem 0rem 2rem 0; 
  font-style: italic;
}
.title_2{
  font-weight: 500;
  font-size: 1.5rem;
  font-style: italic;
}
.title_section{
  text-align: center;
  margin-left: 2rem;
  margin-bottom: 2rem;
  font-style: italic;
}
.cards{
  display: flex;
  justify-content: left;
  overflow-x: scroll;
  scroll-behavior: auto;
    
}
.card{
  cursor: grab;
  min-width: 10rem;
  min-height: 10rem;
  border: 0.25rem solid #2a9d8f;
  border-radius: 2.5rem;
  margin-right: 1rem;
  margin-left: 1rem;
  background-color: #264653;
  margin-bottom: 2rem;
  box-shadow: 0.4rem 0.9rem 0.9rem black;
}
.head3{
  font-size: 1rem;
  font-weight:500;
  font-family: 'Fira Sans', sans-serif;
  letter-spacing: 0.12rem;
  font-style: italic;
}
.title_logo{
  margin-top: 1rem;
  height: 5rem;
  width: 5rem;
}
.showdetail{
  border: 0.5rem solid #2a9d8f;
  border-radius: 7.5rem;
  display: flex;
  justify-content: space-around;
  width: 50%;
  height: 20%;
  margin-top: 5rem;
  padding: 2rem;
  margin-left: auto;
  margin-right: auto;
  background-color: #264653;
  flex-wrap: wrap;
}
.showdetail_img{
  width: 10rem;
  margin-right: 1rem;
  margin-left: 1rem;
}
.showdetail_text{
  word-wrap: break-word;
  width: 25vw;
  margin-left: auto;
  margin-right: auto;
}
.contact_me{
  padding:0.5rem 0 2rem 0;
  background-color: #264653;
}
.contact_me_class{
  padding-top: 1rem;
  display: flex;
  flex-wrap: wrap;
  justify-content: space-evenly;
}
.h4{
  font-size: 1.5rem;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  font-weight: lighter;
  font-style: italic;
}
.logo {
  width: 3rem;
  cursor: pointer;
}
::-webkit-scrollbar {
  width: 0rem;
  height: 0rem;
  }
::-webkit-scrollbar-track {
  box-shadow: inset 0 0 5px rgba(0,0,0,0); 
  border-radius: 50rem;
  }
::-webkit-scrollbar-thumb {
  background: white; 
  border-radius: 50rem;
  }
::-webkit-scrollbar-thumb:hover {
  background: whitesmoke; 
  }
    </style>
  </head>
  <body>
    <div class="main">
      <nav class="Nav">
        <a href="#about_me">About Me</a>
        <a href="#knowledge">Skills</a>
        <a href="#Projects">Projects</a>
        <a href="#Contact_Me">Contact Me</a>
      </nav>
      <div class="about_me" id="about_me">
        <div class="content">
          <h1 class="about_me_title">Hi There, I'm Sina</h1>
          <p class="main_text">I'm a Programmer in Fields of Web & Android and ios Applications and Many Other Things</p>
          <p class="main_text">and i Love to Work In Cyber Security Field</p>
          <p class="main_text">Also, I'm a little bit of Graphic Designer for Motion and Photos</p>
          <p class="main_text">I will Take My Bachelor Degree in Electrical Engineering at Amirkabir University of Technology (AUT) in Iran in July 2022</p>
        </div>
        <img src="Sina.webp" alt="Sina Heidari" class="main_photo" />
      </div>
    </div>
    <div id="knowledge" class="knowledge" >
      <h1 class="title cb">My Skills</h1>
      <div>
        <h2 class="title_section cb">Programming Language</h2>
        <div class="cards" id="PL"></div>
      </div>
      <div>
        <h2 class="title_section cb">Famous libraries</h2>
        <div class="cards" id="JL"></div>
      </div>
      <div>
        <h2 class="title_section cb">Adobe Products</h2>
        <div class="cards" id="AP"></div>
      </div>
    </div>
    <div id="Projects" class="career">
      <div>
        <h1 class="head1 cb">
          My Projects
        </h1>
        </div>
          <div class="section PS">
            <ul id="proj"></ul>
            <h3 class="st">And Also I Studied a lot of CE and CS Courses Like A.I , DataBaces , Algorithm , Data Structure , cyber security and ...</h3>
          </div>
      </div>
    </div>
    <div id="Contact_Me" class="contact_me">
      <h4 class="h4">You Can Easily Contact Me With Following Links</h4>
      <div class="contact_me_class">
        <a  href="https://github.com/HeidariSina" target="_blank">
          <img
            src="https://upload.wikimedia.org/wikipedia/commons/9/91/Octicons-mark-github.svg"
            alt="github logo"
            class="logo"
          />
        </a>
        <a href="https://t.me/SinaHeidari79" target="_blank">
          <img
            src="https://upload.wikimedia.org/wikipedia/commons/8/82/Telegram_logo.svg"
            alt="Telegram_Logo"
            class="logo"
          />
        </a>
        <a
          href="https://www.linkedin.com/in/sinaheidari2000/"
          target="_blank"
        >
          <img
            src="https://upload.wikimedia.org/wikipedia/commons/c/ce/Linkedin_circle.svg"
            alt="linkedin logo"
            class="logo"
          />
        </a>
        <a
          href="mailto: Sinaheidari2000@outlook.com?subject=WebSite"
          target="_blank"
        >
          <img src="https://upload.wikimedia.org/wikipedia/commons/e/ec/Circle-icons-mail.svg" alt="mail logo" class="logo" />
        </a>
      </div>
    </div>
  </body>
  <script>
      data = {
        pl: [
          {title: "HTML",url: "https://upload.wikimedia.org/wikipedia/commons/8/82/Devicon-html5-plain.svg",},
          {title: "CSS", url: "https://upload.wikimedia.org/wikipedia/commons/6/62/CSS3_logo.svg",},
          {title: "Java Script",url: "https://upload.wikimedia.org/wikipedia/commons/9/99/Unofficial_JavaScript_logo_2.svg",},
          {title: "PHP",url: "https://upload.wikimedia.org/wikipedia/commons/2/27/PHP-logo.svg",},
          {title: "C/C++",url: "https://upload.wikimedia.org/wikipedia/commons/1/18/ISO_C%2B%2B_Logo.svg",},
          {title: "C#",url: "https://upload.wikimedia.org/wikipedia/commons/0/0d/C_Sharp_wordmark.svg",},
          {title: "Python",url: "https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg",},
          {title: "ARM Assembly",url: "https://upload.wikimedia.org/wikipedia/commons/6/60/ARM_logo.svg",},
          {title: "Dart & Flutter",url: "https://raw.githubusercontent.com/dnfield/flutter_svg/7d374d7107561cbd906d7c0ca26fef02cc01e7c8/example/assets/flutter_logo.svg?sanitize=true",},
          {title: "SQL",url: "https://upload.wikimedia.org/wikipedia/commons/2/29/Postgresql_elephant.svg",},
          {title: "Java", url: "https://www.vectorlogo.zone/logos/java/java-icon.svg",},
          {title: "GO", url: "https://go.dev/blog/go-brand/Go-Logo/SVG/Go-Logo_Blue.svg",},
        ],
        jl: [
          {title: "React",url: "https://upload.wikimedia.org/wikipedia/commons/a/a7/React-icon.svg",},
          { title: "Redux",url: "https://raw.githubusercontent.com/reduxjs/redux/ca9463dd692ddcf85073bca921fd05f970bba6cf/logo/logo.svg",},
          {title: "NextJs",url: "https://upload.wikimedia.org/wikipedia/commons/8/8e/Nextjs-logo.svg",},
          {title: "jQuary",url: "https://upload.wikimedia.org/wikipedia/commons/8/81/JQuery_logo_text.svg",},
          {title: "Vue",url: "https://upload.wikimedia.org/wikipedia/commons/9/95/Vue.js_Logo_2.svg",},
          {title: "SASS",url: "https://upload.wikimedia.org/wikipedia/commons/9/96/Sass_Logo_Color.svg",},
          {title: "React Native",url: "https://upload.wikimedia.org/wikipedia/commons/a/a7/React-icon.svg",},
          {title: "Expo JS",url: "https://pagepro.co/static/img/expo-4f8e255836.svg",},
          {title: "NodeJs",url: "https://upload.wikimedia.org/wikipedia/commons/d/d9/Node.js_logo.svg",},
          {title: "Flask",url: "https://www.vectorlogo.zone/logos/pocoo_flask/pocoo_flask-icon.svg",},
        ],
        ap: [
          {title: "illustrator",url: "https://upload.wikimedia.org/wikipedia/commons/f/fb/Adobe_Illustrator_CC_icon.svg",},
          {title: "Premiere Pro",url: "https://upload.wikimedia.org/wikipedia/commons/4/40/Adobe_Premiere_Pro_CC_icon.svg",},
          {title: "After Effect",url: "https://upload.wikimedia.org/wikipedia/commons/c/cb/Adobe_After_Effects_CC_icon.svg",},
          {title: "Photoshop",url: "https://upload.wikimedia.org/wikipedia/commons/a/af/Adobe_Photoshop_CC_icon.svg",},
          {title: "XD", url: "https://upload.wikimedia.org/wikipedia/commons/c/c2/Adobe_XD_CC_icon.svg",},
          {title: "inDesign", url: "https://upload.wikimedia.org/wikipedia/commons/4/48/Adobe_InDesign_CC_icon.svg",},
          {title: "Audition",url: "https://upload.wikimedia.org/wikipedia/commons/0/0e/Adobe_Audition_CC_icon_%282020%29.svg",},
        ],
        pro:[
            {title:"Design Electrical Circuit", text:"Designing Electrical Circuit for Specific Gain, Swing of Voltage, Frequency Responce, Input Impedance and Output Impedance and Needs Hspice and ADS(Advance Design Manager) as Programs"},
            {title:"VLSI Projects", text:"Designing 4-Bit Fulladder with Propagate Path, Asynchronous Registers and RTL Circuit with 180nm Technology and Lowest Delay Time and Needs Micromind as Program"},
            {title:"VHDL Projects", text:"Projects Like Fulladder, Arithmetic Logic Unit(ALU), Counter, BCD Transformer, Traffic Lights and ... and for This Project Needs VHDL and Verilog as Language and ISE as Program"},
            {title:"Am & Fm Modulations", text:"Designing a Full Pack of Amplitude and Frequency modulation for Radio Signals and Filters of Modulations With Matlab"},
            {title:"Ai with STM" , text:"It's About Using Artificial Intelligence of STM and Give Data To Our Microprocessor With Usart Post and Need To Write an Algorithm for A.I and This Project Needs C and Python as Language and CubeMX and Keil UVisoin as UPrograms"},
            {title:"Smart Farming", text:"Design a Complete Pack for Have Smart Farm Sending and Receive Data From Website and Give it to Paspberry pi and to Our Microprocessor and we can see Data in Mathlab Have Reverse Path from Matlab to Website and i Program Frontend and Backend of Website and Help to Program Our Proccessor and for This Projects i Use HTML, Css, Js, jQuarry, Python, C"},
            {title:"Web Games", text:"Games Like Maze, Shootout, Breakout and Ping Pong, This Games Made with Java Scripts and Canvas of HTML "},
            {title:"Weather Site", text:"This Site Have Front-end and APIs and You can See and Search Cities and This Site Gives You The Weather Forcast Of 5 Days and In this Site Use 2 API one of them is Getting The Weather Forcast and the Other One is Searching The City and Used HTML, CSS, JS for Programming This Site"},
            {title:"Black Board Site", text:"a Site That is a online Black Board and You can change The Thickness and Color of the Pen and in The End You can Save What You Draw on the Board an Used HTML, CSS, JS for Programming This Site"},
            {title:"Supermarket Site", text:"in This Site Used React For Building The User Interface and Frontend of The Site and You Have Ability of Login Or Logout or Insert in Products or Edit Them"},
            {title:"Market DataBace", text:"Using PostgreSQL For Coding The Data Bace and Have 5 Tables and All ids Of the Tables Have a Relationship To Eechothers"},
            {title:"PC's Games", text:"Using Unity and Unreal Engine 4 for Gaming Engine and Build Terminal Hacker That Is the Guess The Word game and Rocket Games That is The Sending a Space Ship to The Specific Location Without Hitting any Objects"},
            {title:"Money Count App", text:"An App That Cont How Much Money You Spend in one Week and Show Them in The Bar Char and Designed with Dart & Flutter"}
          ],
      };
  function makecard(bace, prob) {
    var div = document.createElement("div");
    div.className = "card";
    bace.appendChild(div);
    var img = document.createElement("img");
    img.className = "title_logo";
    img.src = prob.url;
    img.alt = prob.title;
    div.appendChild(img);

    var h3 = document.createElement("h3");
    h3.innerText = prob.title;
    h3.className = "head3";
    div.appendChild(h3);
  }
  function Scrollbar(prob) {
    let isDown = false;
    let startX;
    let scrollLeft;

    prob.addEventListener("mousedown", (e) => {
      isDown = true;
      prob.classList.add("active");
      startX = e.pageX - prob.offsetLeft;
      scrollLeft = prob.scrollLeft;
    });
    prob.addEventListener("mouseleave", () => {
      isDown = false;
      prob.classList.remove("active");
    });
    prob.addEventListener("mouseup", () => {
      isDown = false;
      prob.classList.remove("active");
    });
    prob.addEventListener("mousemove", (e) => {
      if (!isDown) return;
      e.preventDefault();
      const x = e.pageX - prob.offsetLeft;
      const walk = (x - startX) * 3;
      prob.scrollLeft = scrollLeft - walk;
    });
  }
  function textReplace (prob , e){
    var li = document.createElement("li");
    var h3 = document.createElement("h3");
    h3.className ="pro_h3";
    h3.innerHTML = e.title;
    li.appendChild(h3);

    var p = document.createElement("p");
    p.innerHTML = e.text;
    p.className = "pro_p";
    li.appendChild(p);
    prob.appendChild(li);
  }
    data.pro.map((e) => textReplace(document.querySelector("#proj"), e));
    pl = document.querySelector("#PL");
    data.pl.map((e) => makecard(pl, e));
    Scrollbar(pl);
    jl = document.querySelector("#JL");
    data.jl.map((e) => makecard(jl, e));
    Scrollbar(jl);
    ap = document.querySelector("#AP");
    data.ap.map((e) => makecard(ap, e));
    Scrollbar(ap);
  </script>
</html>
