.tabs-v {
float: left;
display: inline-block;
width: 4rem;
height: 100%;
}

.tabs-v,
.tabs-v * {
box-sizing: border-box;
-webkit-tap-highlight-color: transparent;
}

.tabs-v > input[type="radio"] {
-webkit-appearance: none;
-moz-appearance: none;
-ms-appearance: none;
-o-appearance: none;
appearance: none;
display: none;
}

.tabs-v > input[type="radio"]:checked + label {
background: white;
background-image: -moz-linear-gradient(left, #ffffff 0%, #ffffff 50%, #333333 50%, #333333 100%, #333333 100%);
background-image: -webkit-linear-gradient(left, #ffffff 0%, #ffffff 50%, #333333 50%, #333333 100%, #333333 100%);
background-image: linear-gradient(to right, #ffffff 0%, #ffffff 50%, #333333 50%, #333333 100%, #333333 100%);
background-size: 200% 200%;
background-position: 0;
}

.tabs-v > input[type="radio"]:checked + label:before {
-moz-transform: translate(0, -50%);
-ms-transform: translate(0, -50%);
-webkit-transform: translate(0, -50%);
transform: translate(0, -50%);
-moz-transform: translate3d(0, -50%, 0);
-ms-transform: translate3d(0, -50%, 0);
-webkit-transform: translate3d(0, -50%, 0);
transform: translate3d(0, -50%, 0);
-moz-transition: -moz-transform 0.35s;
-o-transition: -o-transform 0.35s;
-webkit-transition: -webkit-transform 0.35s;
transition: transform 0.35s;
}

.tabs-v > input[type="radio"]:checked + label:after { color: #333333; }

.tabs-v > label {
border: none;
padding: 0;
background: none;
outline: none;
border-radius: 0;
-moz-transition: background-position 0.25s, box-shadow 0.25s;
-o-transition: background-position 0.25s, box-shadow 0.25s;
-webkit-transition: background-position 0.25s, box-shadow 0.25s;
transition: background-position 0.25s, box-shadow 0.25s;
position: relative;
float: left;
display: inline-block;
width: 100%;
height: 25%;
text-align: center;
line-height: 25vh;
margin: 0;
background: #333333;
background-image: -moz-linear-gradient(left, #ffffff 0%, #ffffff 50%, #333333 50%, #333333 100%, #333333 100%);
background-image: -webkit-linear-gradient(left, #ffffff 0%, #ffffff 50%, #333333 50%, #333333 100%, #333333 100%);
background-image: linear-gradient(to right, #ffffff 0%, #ffffff 50%, #333333 50%, #333333 100%, #333333 100%);
background-size: 200% 200%;
background-position: 100%;
box-shadow: inset 0px 1px 0 white, inset -1px 0 0px 0px white;
}

.tabs-v > label:first-of-type { box-shadow: inset -1px 0 0px 0px white; }

.tabs-v > label:after {
content: attr(data-text);
position: absolute;
top: 50%;
left: 50%;
display: inline-block;
width: 100%;
color: white;
text-align: center;
-moz-transform: translate(-50%, -50%);
-ms-transform: translate(-50%, -50%);
-webkit-transform: translate(-50%, -50%);
transform: translate(-50%, -50%);
-moz-transform: translate3d(-50%, -50%, 0);
-ms-transform: translate3d(-50%, -50%, 0);
-webkit-transform: translate3d(-50%, -50%, 0);
transform: translate3d(-50%, -50%, 0);
-moz-transition: color 0.25s;
-o-transition: color 0.25s;
-webkit-transition: color 0.25s;
transition: color 0.25s;
}

.tabs-v > label:before {
content: '';
position: absolute;
left: 100%;
top: 50%;
display: inline-block;
width: 0;
height: 0;
border-top: solid 1rem transparent;
border-bottom: solid 1rem transparent;
border-right: solid 1.5rem transparent;
border-left: solid 1.5rem;
border-left-color: white;
-moz-transform: translate(-5.5rem, -50%);
-ms-transform: translate(-5.5rem, -50%);
-webkit-transform: translate(-5.5rem, -50%);
transform: translate(-5.5rem, -50%);
-moz-transform: translate3d(-5.5rem, -50%, 0);
-ms-transform: translate3d(-5.5rem, -50%, 0);
-webkit-transform: translate3d(-5.5rem, -50%, 0);
transform: translate3d(-5.5rem, -50%, 0);
-moz-transition: -moz-transform 0.2s;
-o-transition: -o-transform 0.2s;
-webkit-transition: -webkit-transform 0.2s;
transition: transform 0.2s;
}

.tabs-v > .tab-c {
position: fixed;
display: inline-block;
width: 100%;
height: 100%;
left: 4rem;
text-align: center;
-moz-transition: -moz-transform 0.5s;
-o-transition: -o-transform 0.5s;
-webkit-transition: -webkit-transform 0.5s;
transition: transform 0.5s;
}

.tabs-v > .tab-c > .card {
position: absolute;
left: 50%;
top: 50%;
display: inline-block;
width: 70%;
max-height: 80%;
overflow-x: hidden;
overflow-y: auto;
padding: 2rem;
box-shadow: 0 0 0 1px white;
color: white;
-webkit-overflow-scrolling: touch;
-moz-transform: translate(-50%, -50%) translate(-1.5rem, 0);
-ms-transform: translate(-50%, -50%) translate(-1.5rem, 0);
-webkit-transform: translate(-50%, -50%) translate(-1.5rem, 0);
transform: translate(-50%, -50%) translate(-1.5rem, 0);
-moz-transform: translate3d(-50%, -50%, 0) translate3d(-1.5rem, 0, 0);
-ms-transform: translate3d(-50%, -50%, 0) translate3d(-1.5rem, 0, 0);
-webkit-transform: translate3d(-50%, -50%, 0) translate3d(-1.5rem, 0, 0);
transform: translate3d(-50%, -50%, 0) translate3d(-1.5rem, 0, 0);
}

.tabs-v > .tab-c > .card > h1 { margin-top: 0; }

.tabs-v > input[type="radio"]:nth-of-type(1):checked ~ .tab-c:nth-of-type(1) {
-moz-transform: translate(0, 0%);
-ms-transform: translate(0, 0%);
-webkit-transform: translate(0, 0%);
transform: translate(0, 0%);
-moz-transform: translate3d(0, 0%, 0);
-ms-transform: translate3d(0, 0%, 0);
-webkit-transform: translate3d(0, 0%, 0);
transform: translate3d(0, 0%, 0);
}

.tabs-v > input[type="radio"]:nth-of-type(1):checked ~ .tab-c:nth-of-type(2) {
-moz-transform: translate(0, 100%);
-ms-transform: translate(0, 100%);
-webkit-transform: translate(0, 100%);
transform: translate(0, 100%);
-moz-transform: translate3d(0, 100%, 0);
-ms-transform: translate3d(0, 100%, 0);
-webkit-transform: translate3d(0, 100%, 0);
transform: translate3d(0, 100%, 0);
}

.tabs-v > input[type="radio"]:nth-of-type(1):checked ~ .tab-c:nth-of-type(3) {
-moz-transform: translate(0, 200%);
-ms-transform: translate(0, 200%);
-webkit-transform: translate(0, 200%);
transform: translate(0, 200%);
-moz-transform: translate3d(0, 200%, 0);
-ms-transform: translate3d(0, 200%, 0);
-webkit-transform: translate3d(0, 200%, 0);
transform: translate3d(0, 200%, 0);
}

.tabs-v > input[type="radio"]:nth-of-type(1):checked ~ .tab-c:nth-of-type(4) {
-moz-transform: translate(0, 300%);
-ms-transform: translate(0, 300%);
-webkit-transform: translate(0, 300%);
transform: translate(0, 300%);
-moz-transform: translate3d(0, 300%, 0);
-ms-transform: translate3d(0, 300%, 0);
-webkit-transform: translate3d(0, 300%, 0);
transform: translate3d(0, 300%, 0);
}

.tabs-v > input[type="radio"]:nth-of-type(2):checked ~ .tab-c:nth-of-type(1) {
-moz-transform: translate(0, -100%);
-ms-transform: translate(0, -100%);
-webkit-transform: translate(0, -100%);
transform: translate(0, -100%);
-moz-transform: translate3d(0, -100%, 0);
-ms-transform: translate3d(0, -100%, 0);
-webkit-transform: translate3d(0, -100%, 0);
transform: translate3d(0, -100%, 0);
}

.tabs-v > input[type="radio"]:nth-of-type(2):checked ~ .tab-c:nth-of-type(2) {
-moz-transform: translate(0, 0%);
-ms-transform: translate(0, 0%);
-webkit-transform: translate(0, 0%);
transform: translate(0, 0%);
-moz-transform: translate3d(0, 0%, 0);
-ms-transform: translate3d(0, 0%, 0);
-webkit-transform: translate3d(0, 0%, 0);
transform: translate3d(0, 0%, 0);
}

.tabs-v > input[type="radio"]:nth-of-type(2):checked ~ .tab-c:nth-of-type(3) {
-moz-transform: translate(0, 100%);
-ms-transform: translate(0, 100%);
-webkit-transform: translate(0, 100%);
transform: translate(0, 100%);
-moz-transform: translate3d(0, 100%, 0);
-ms-transform: translate3d(0, 100%, 0);
-webkit-transform: translate3d(0, 100%, 0);
transform: translate3d(0, 100%, 0);
}

.tabs-v > input[type="radio"]:nth-of-type(2):checked ~ .tab-c:nth-of-type(4) {
-moz-transform: translate(0, 200%);
-ms-transform: translate(0, 200%);
-webkit-transform: translate(0, 200%);
transform: translate(0, 200%);
-moz-transform: translate3d(0, 200%, 0);
-ms-transform: translate3d(0, 200%, 0);
-webkit-transform: translate3d(0, 200%, 0);
transform: translate3d(0, 200%, 0);
}

.tabs-v > input[type="radio"]:nth-of-type(3):checked ~ .tab-c:nth-of-type(1) {
-moz-transform: translate(0, -200%);
-ms-transform: translate(0, -200%);
-webkit-transform: translate(0, -200%);
transform: translate(0, -200%);
-moz-transform: translate3d(0, -200%, 0);
-ms-transform: translate3d(0, -200%, 0);
-webkit-transform: translate3d(0, -200%, 0);
transform: translate3d(0, -200%, 0);
}

.tabs-v > input[type="radio"]:nth-of-type(3):checked ~ .tab-c:nth-of-type(2) {
-moz-transform: translate(0, -100%);
-ms-transform: translate(0, -100%);
-webkit-transform: translate(0, -100%);
transform: translate(0, -100%);
-moz-transform: translate3d(0, -100%, 0);
-ms-transform: translate3d(0, -100%, 0);
-webkit-transform: translate3d(0, -100%, 0);
transform: translate3d(0, -100%, 0);
}

.tabs-v > input[type="radio"]:nth-of-type(3):checked ~ .tab-c:nth-of-type(3) {
-moz-transform: translate(0, 0%);
-ms-transform: translate(0, 0%);
-webkit-transform: translate(0, 0%);
transform: translate(0, 0%);
-moz-transform: translate3d(0, 0%, 0);
-ms-transform: translate3d(0, 0%, 0);
-webkit-transform: translate3d(0, 0%, 0);
transform: translate3d(0, 0%, 0);
}

.tabs-v > input[type="radio"]:nth-of-type(3):checked ~ .tab-c:nth-of-type(4) {
-moz-transform: translate(0, 100%);
-ms-transform: translate(0, 100%);
-webkit-transform: translate(0, 100%);
transform: translate(0, 100%);
-moz-transform: translate3d(0, 100%, 0);
-ms-transform: translate3d(0, 100%, 0);
-webkit-transform: translate3d(0, 100%, 0);
transform: translate3d(0, 100%, 0);
}

.tabs-v > input[type="radio"]:nth-of-type(4):checked ~ .tab-c:nth-of-type(1) {
-moz-transform: translate(0, -300%);
-ms-transform: translate(0, -300%);
-webkit-transform: translate(0, -300%);
transform: translate(0, -300%);
-moz-transform: translate3d(0, -300%, 0);
-ms-transform: translate3d(0, -300%, 0);
-webkit-transform: translate3d(0, -300%, 0);
transform: translate3d(0, -300%, 0);
}

.tabs-v > input[type="radio"]:nth-of-type(4):checked ~ .tab-c:nth-of-type(2) {
-moz-transform: translate(0, -200%);
-ms-transform: translate(0, -200%);
-webkit-transform: translate(0, -200%);
transform: translate(0, -200%);
-moz-transform: translate3d(0, -200%, 0);
-ms-transform: translate3d(0, -200%, 0);
-webkit-transform: translate3d(0, -200%, 0);
transform: translate3d(0, -200%, 0);
}

.tabs-v > input[type="radio"]:nth-of-type(4):checked ~ .tab-c:nth-of-type(3) {
-moz-transform: translate(0, -100%);
-ms-transform: translate(0, -100%);
-webkit-transform: translate(0, -100%);
transform: translate(0, -100%);
-moz-transform: translate3d(0, -100%, 0);
-ms-transform: translate3d(0, -100%, 0);
-webkit-transform: translate3d(0, -100%, 0);
transform: translate3d(0, -100%, 0);
}

.tabs-v > input[type="radio"]:nth-of-type(4):checked ~ .tab-c:nth-of-type(4) {
-moz-transform: translate(0, 0%);
-ms-transform: translate(0, 0%);
-webkit-transform: translate(0, 0%);
transform: translate(0, 0%);
-moz-transform: translate3d(0, 0%, 0);
-ms-transform: translate3d(0, 0%, 0);
-webkit-transform: translate3d(0, 0%, 0);
transform: translate3d(0, 0%, 0);
}

::-webkit-scrollbar {
width: 14px;
}

::-webkit-scrollbar-thumb {
background: rgba(255, 255, 255, 0.5);
box-shadow: inset 0 0 0 4px #333333;
}

.content {
position: relative;
float: left;
display: inline-block;
width: 100%;
height: 100%;
}

html,
body {
width: 100%;
height: 100%;
margin: 0;
padding: 0;
background: #333333;
overflow: hidden;
scrollbar-face-color: white;
scrollbar-base-color: #FFF;
scrollbar-track-color: #333333;
scrollbar-arrow-color: #333333;
scrollbar-shadow-color: #333333;
}
