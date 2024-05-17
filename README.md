
<!-- 제목 -->
<!-- <h1 align="center">Hi 👋, I'm Grokeen from Korea 🇰🇷</h1> -->
<!-- <h3 align="center">Surviving as a developer 🧗‍♀️</h3>   -->



<!-- 깃허브 상태 -->
<!-- ![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=Grokeen&show_icons=true&theme=radical) -->

<!--
📌 [포트폴리오](/portfolio.md)
📌 [PDF 다운로드](https://drive.google.com/file/d/1kXj9weLHKVow_333rESxEHxEiERa0n4B/view?usp=sharing)
📌 [메일 보내기](mailto:ygreen0516@gmail.com)
-->

<!-- 백준 알고리즘 레벨 -->
<!-- [![Solved.ac프로필](http://mazassumnida.wtf/api/v2/generate_badge?boj=ygreen0516)](https://solved.ac/ygreen0516) -->

<head>
    <style>
body {
    background-color: #e0f7fa;
    margin: 0;
    padding: 0;
}
.container {
    /** 배경 색깔 지정  */
    background-color: #b4d1da;
    /** 모서리 둥글게 */
    border-radius: 9px;
    /** 윤곽선 */
    border: 1px solid #738186;
    /** 기본 너비, 높이 지정 */
    width: 640px;
    height: 440px;
    /** 좌우 마진을 auto(중앙에 배치), 상하 마진을 100px로 지정 */
    margin: 66px auto;
    /** .bookdot 요소에서 absolute 속성값을 이용하기 위해 position: relative 로 설정 */
    position: relative;
}
.containerdetted {
    border: 2px dashed white;
    border-radius: 9px;
    left: 15px;
    top: 15px;
    right: 15px;
    bottom: 15px;
    position: absolute;
}
.containermain {
    width: 585px;
    height: 385px;
    background-color: white;
    margin: 10px;
    border-radius: 9px;
    position: absolute;
}
/* 이미지 부분 */
.content {
    width: 90%;
    padding: 10px;
    box-sizing: border-box;
    position: relative;
    /* 좌측정렬 */
    /* float:left; */
}
/* 이미지 파일 */
.main {
    display: flex;
    justify-content: space-between;
}
.mini-room img {
    width: 90%;
    border: 2px solid #ddd;
}
/* 사이드바 */
.sidebar {
    width: 15%;
    left: 480px;
    top: 15px;
    right: 15px;
    bottom: 15px;
    /* 간격 */
    padding: 0px;
    box-sizing: border-box;
    position: absolute;
}
.menu ul {
    list-style: none;
    padding: 0;
    background-color: hsla(193, 36%, 52%, 0.891);
    /* 경계 둥글 */
    border-radius: 10px / 40px;
}
.menu ul:hover {
    transform: scale(1.1);
    color: #fff;
    background-color: #27E09D;
    box-shadow: 0px 26px 56px 0px rgba(0, 0, 0, 0.10), 
                0px 102px 102px 0px rgba(0, 0, 0, 0.09), 
                0px 230px 138px 0px rgba(0, 0, 0, 0.05), 
                0px 410px 164px 0px rgba(0, 0, 0, 0.01), 
                0px 640px 179px 0px rgba(0, 0, 0, 0.00);
}
.menu li {
    margin: 10px;
    /* 글씨 가운데 정렬 */
    text-align: center;
}
.menu a {
    text-decoration: none;
    color: #ffffff;
    font-weight: bold;
}
/* 추가 자기소개 */
.plus {
    padding: 10px;
}
.plusimg{
    position: absolute;
    width: 120%;
    left: 10px;
    top: 255px;
}
.plustext {
    position: absolute;
    left: 230px;
    top: 270px;
    right: 15px;
    bottom: 15px;
    color: #000000;
    text-decoration: none;
    font-size:10px;
}
.plusinfo{
    position: absolute;
    left: 230px;
    top: 350px;
}
    </style>
</head>
<body>
    <div class="container">
        <div class="containerdetted">
            <div class="containermain">
                <!--  -->
                <div class="content">
                    <div class="main">
                        <div class="mini-room">
                            <img src="cyworld.jpeg" alt="Mini Room">
                        </div>
                    </div>
                </div>
                <!--  -->
                <div class="sidebar">
                    <div class="menu">
                        <ul class="mainmenu">
                            <li><a href="https://github.com/Grokeen">홈</a></li>
                        </ul>
                        <ul>
                            <li><a href="https://Grokeen.github.io">미니룸</a></li>
                        </ul>
                        <ul>
                            <li><a href="#">일촌평</a></li>
                        </ul>
                        <ul>
                            <li><a href="mailto:ygreen0516@gmail.com">편지함</a></li>
                        </ul>
                    </div>
                </div>
                <!--  -->
                <div class="plus">
                    <div class="plusimg">
                        <img src="https://github-readme-stats.vercel.app/api/top-langs?username=Grokeen&show_icons=true&locale=en&layout=compact" alt="Grokeen" style="width:30%"/>
                    </div>
                    <div class="plustext">
                        🖥️ Frontend : React<br/>
                        🔌 Backend : Spring, Django
                    </div>
                    <div class="plusinfo">
                        <img src="https://img.shields.io/github/followers/Grokeen?style=social" style="background-color: white"/>
                        <img src="https://img.shields.io/twitter/follow/groke_en"/>
                        <img src="https://komarev.com/ghpvc/?username=Grokeen&style=flat-square"/>
                    </div>
                </div>
                <!--  -->
            </div>
        </div>
    </div>
</body>


