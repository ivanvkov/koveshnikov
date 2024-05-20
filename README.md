html,body,div,span,applet,object,iframe,h1,h2,h3,h4,h5,h6,p,blockquote,pre,a,abbr,acronym,address,big,cite,code,del,dfn,em,img,ins,kbd,q,s,samp,small,strike,strong,sub,sup,tt,var,b,u,i,center,dl,dt,dd,ol,ul,li,fieldset,form,label,legend,table,caption,tbody,tfoot,thead,tr,th,td,article,aside,canvas,details,embed,figure,figcaption,footer,header,hgroup,menu,nav,output,ruby,section,summary,time,mark,audio,video{margin:0;padding:0;border:0;font-size:100%;font:inherit;vertical-align:baseline}article,aside,details,figcaption,figure,footer,header,hgroup,menu,nav,section{display:block}body{line-height:1}ol,ul{list-style:none}blockquote,q{quotes:none}blockquote:before,blockquote:after,q:before,q:after{content:'';content:none}table{border-collapse:collapse;border-spacing:0}
@import url("https://fonts.googleapis.com/css?family=Roboto:400,500,600,700");
header #headline, header #circular-bg {

  position: absolute;

  top: 600px;

  left: 800px;

  transform: translate(-50%, -50%);

}
* {

  box-sizing: border-box;

  text-align: center;

  text-decoration: none;

  color: #fff;

}
body {

  background-image: url("https://raw.githack.com/ivanvkov/koveshnikov/main/volvo1.jpg");

  font-family: "Roboto", sans-serif;

  overflow: auto;

}
header .info p {

  position: relative;

  margin: 0;

  line-height: 1.6;

  font-size: 15px;

  color: white;

  text-align: justify;

  top: -500px;

  left: -10px;

}
header #circular-bg {

  width: 85vw;

  height: 85vw;

  background: CadetBlue;

  border-radius: 50%;

  z-index: -10;

}
header nav {

  width: 1000px;

  margin: 30px auto 0 auto;

}
header nav a {

  font-size: 18px;

  margin-left: 20px;

  position: relative;

  color: white;

}
header #brand {

  font-size: 100px;

  font-weight: 700;

  position: absolute;

  left: 20vw;

  top: 15%;

}
header #brand:before {

  content: "";

  position: absolute;

  width: 110%;

  height: 60px;

  background-image: url("https://raw.githack.com/ivanvkov/koveshnikov/main/volvo%202.jpeg");

  bottom: -10px;

  left: -5%;

  border-radius: 60px;

  z-index: -1;

}
header img {

  position: absolute;

  width: 600px;

  top: 200px;

  left: 300px;

}
header #headline {

  font-size: 30px;

  line-height: 35px;

  text-align: left;

  left: 20%;

  top: 45%;

}

  

header #headline:before {

  content: "";

  position: absolute;

  width: 60px;

  height: 4px;

  background: #fff;

  top: 22%;

  left: -85%;

}

  

header #headline:after {

  content: "with the best guitar diller ever";

  position: absolute;

  top: 120%;

  left: -10%;

  font-size: 20px;

  letter-spacing: 1px;

}
header button {

  margin-top: 120vh;

  width: 140px;

  height: 50px;

  background: #00cc99;

  border: none;

  font-weight: 600;

  border-radius: 5px;

  font-size: 15px;

}
.container {

  width: 100%;

}
.packages {

  margin: 20px;

  top: -300px;

  position: relative;

  width: 300px;

  padding-bottom: 1.5em;

  height: 100%;

  background-color: CadetBlue;

  display: flex;

  flex-direction: column;

  align-items: center;

  text-align: center;

  border-radius: 20px;

  box-shadow: 0 19px 38px rgba(30, 35, 33, 1), 0 15px 12px rgba(30, 35, 33, 0.2);

  flex-wrap: wrap;

  color: #f4f4f4;

}
h1,

h2 {

  font-size: 2.2em;

}
.list li {

  font-size: 20px;

  list-style: none;

  border-bottom: 1px solid #f4f4f4;

  padding-inline-start: 0;

  border-width: 1px;

  padding: 10px;

}

.first {

  margin-top: 40px;

  border-top: 1px solid #f4f4f4;

}

.list {

  width: 80%;

}



ol, ul {

  padding: 0;

}



.top {

  display: flex;

  flex-direction: column;

  align-items: center;

  position: relative;

  top: -300px;

}



input,

label {

  display: inline-block;

  vertical-align: middle;

  margin: 10px 0;

}
.button {

  padding: 10px 30px;

  text-decoration: none;

  font-size: 1.4em;

  margin: 15px 15px;

  border-radius: 50px;

  color: #f4f4f4;

  transition: all 0.3s ease 0s;

}



.button:hover {

  transform: scale(1.2);

}
.button1 {

  background-color: #00cc99;

  box-shadow: 0 0 10px 0 #00cc99 inset, 0 0 20px 2px #00cc99;

}



.button2 {

  background-color: #00cc99;

  box-shadow: 0 0 10px 0 #00cc99 inset, 0 0 20px 2px #00cc99;

}
.switch {

  position: relative;

  top: -5px;

  display: inline-block;

  width: 60px;

  height: 34px;

}



.switch input {

  opacity: 0;

  width: 0;

  height: 0;

}
.slider {

  position: absolute;

  cursor: pointer;

  top: 0;

  left: 0;

  right: 0;

  bottom: 0;

  background-color: #1e2321;

  -webkit-transition: 0.4s;

  box-shadow: 2px 6px 25px #1e2321;

  transform: translate(0px, 0px);

  transition: 0.6s ease transform, 0.6s box-shadow;



}



.slider:before {

  position: absolute;

  content: "";

  height: 26px;

  width: 26px;

  left: 4px;

  bottom: 4px;

  background-color: white;

  -webkit-transition: 0.4s;

  transition: 0.4s;

}



input:checked + .slider {

  background-color: #50bfe6;

}



input:focus + .slider {

  box-shadow: 0 0 1px #50bfe6;

}



input:checked + .slider:before {

  -webkit-transform: translateX(26px);

  -ms-transform: translateX(26px);

  transform: translateX(26px);

}



.slider.round {

  border-radius: 34px;

}



.slider.round:before {

  border-radius: 50%;

}
.package-container {

  display: flex;

  align-items: center;

  justify-content: center;

  flex-wrap: wrap;

}

![image](https://github.com/ivanvkov/koveshnikov/assets/158248787/14db281c-a735-4066-9fc3-dc959707c6ac)
