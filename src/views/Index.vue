<template>
    <section id="main_contents">
        <div class="wrapper">
            <div class="title">
                <h3 class="main_title">나의 MBIT</h3>
                <h3 class="sub_title">My Best IT personalities</h3>
            </div>
            <div class="intro">
                <div class="intro_title">
                    <h1>나의 개발 유형은?!</h1>
                    <div class="type">
                        <ul class="type_list">
                            <li>개발자</li>
                            <li>데이터 분석과 인공지능</li>
                            <li>정보보안</li>
                            <li>게임 개발</li>
                            <li>개발자</li>
                        </ul>
                    </div>
                </div>
            </div>
            <div class="buttons">
                <a href="/form.html">
                    <button class="start" type="button">시작하기</button>
                </a>
            </div>

            <div class="result_data">
                <div class="data_wrap">
                    <h3>참여자 수</h3>
                    <ul>

                        <li>백엔드 개발자 : 81명</li>

                        <li>프론트엔드 개발자 : 70명</li>

                        <li>데이터 분석과 인공지능 : 127명</li>

                        <li>정보보안 : 48명</li>

                        <li>게임 개발 : 30명</li>

                    </ul>
                </div>
            </div>

            <div class="weniv">
                <a href="http://www.paullab.co.kr">
                    <img v-bind:src="require('../assets/img/weniv_logo_black.png')" alt="weniv">
                </a>
            </div>

        </div>
    </section>
</template>

<script>
export default {
    
}
</script>

<style scoped>
@keyframes rotate {
    0% {
        transform: translateY(0);
    }
    25% {
        transform: translateY(-20%);
    }
    50% {
        transform: translateY(-40%);
    }
    75% {
        transform: translateY(-60%);
    }
    100% {
        transform: translateY(-80%);
    }
}



#main_contents {
    display: flex;
    justify-content: center;
    width: 100%;
    height: 100%;
    margin-top: 100px;
}

#main_contents .wrapper {
    display: flex;
    flex-direction: column;
    width: 100%;
    height: 100%;
    max-width: 500px;
}

.title {
    text-align: center;
    padding-bottom: 50px;
}

.main_title {
    font-family: "GmarketSansBold";
    font-size: 50px;
    padding-bottom: 15px;
}

.sub_title {
    font-size: 20px;
    font-weight: bold;
    color: #7F47DD;
}

.intro {
    text-align: center;
    padding-bottom: 40px;
}

.intro_title h1 {
    font-size: 30px;
    padding-bottom: 15px;
}

.type {
    font-size: 25px;
    line-height: 3em;
    height: 3em;
    overflow: hidden;
}

.type_list {
    animation: rotate 7s infinite;
}

.buttons {
    text-align: center;
    padding-bottom: 50px;
}

.buttons button {
    width: 300px;
    height: 50px;
    padding: 5px;
    border-style: none;
    border-radius: 10px;
    font-family: "NEXON Lv1 Gothic OTF";
    font-size: 20px;
    font-weight: bold;
    cursor: pointer;
    background-color: #fff;
    color: #7F47DD;
    margin-bottom: 20px;
}

.buttons button:hover {
    text-decoration: underline;
}

.result_data {
    display: flex;
    justify-content: center;
}

.result_data .data_wrap {
    width: 270px;
    padding: 15px;
    border-top: 3px solid #000;
    border-bottom: 3px solid #000;
    line-height: 1.5;
    margin-bottom: 50px;
}

.result_data h3 {
    text-align: center;
    font-size: 20px;
    font-weight: bold;
    padding: 20px 0 30px; 
}

.result_data li {
    padding-bottom: 20px;
    font-size: 15px;
}

.weniv {
    display: flex;
    justify-content: center;
    padding-bottom: 50px;
}

.weniv a {
    width: 100px;
}

.weniv img{
    width: 100%;
    height: auto;
}

@media all and (min-width: 279px) and (max-width: 359px) {
    #main_contents{
        margin-top: 50px;
    }
    
    #main_contents .wrapper {
        max-width: 300px;
    }
    
    .title {
        padding-bottom: 40px;
    }

    .main_title {
        font-size: 35px;
    }
    
    .sub_title {
        font-size: 15px;
    }

    .intro {
        padding-bottom: 20px;
    }
    
    .intro_title h1 {
        font-size: 20px;
    }
    
    .type {
        font-size: 17px;
    }
    
    .buttons {
        padding-bottom: 20px;
    }
    
    .buttons button {
        font-size: 17px;
        width: 200px;
        height: 40px;
    }

    .result_data .data_wrap {
        margin-bottom: 30px;
        width: 170px;
    }

    .result_data h3 {
        font-size: 17px;
    }
    
    .result_data li {
        font-size: 15px;
    }

    .weniv a {
        width: 70px;
    }
}

@media all and (min-width: 360px) and (max-width: 600px) {
    #main_contents{
        margin-top: 50px;
    }
    
    #main_contents .wrapper {
        max-width: 350px;
    }
    
    .title {
        padding-bottom: 40px;
    }

    .main_title {
        font-size: 40px;
    }
    
    .sub_title {
        font-size: 17px;
    }

    .intro {
        padding-bottom: 20px;
    }
    
    .intro_title h1 {
        font-size: 20px;
    }
    
    .type {
        font-size: 17px;
    }
    
    .buttons {
        padding-bottom: 20px;
    }
    
    .buttons button{
        font-size: 20px;
        width: 250px;
        height: 50px;
    }

    .result_data .data_wrap {
        margin-bottom: 30px;
        width: 220px;
    }

    .result_data h3 {
        font-size: 20px;
    }
    
    .result_data li {
        font-size: 17px;
    }

    .weniv a {
        width: 90px;
    }
}

@media all and (min-width: 1920px) and (max-width: 2560px) {
    #main_contents .wrapper {
        max-width: 700px;
    }
    
    .main_title {
        font-size: 70px;
        padding-bottom: 20px;
    }
    
    .sub_title {
        font-size: 30px;
    }

    .buttons button{
        font-size: 30px;
        width: 350px;
        height: 60px;
    }
    
    .result_data .data_wrap {
        width: 320px;
    }
    
    .result_data h3 {
        font-size: 30px;
    }
    
    .result_data li {
        font-size: 20px;
    }
    
    .weniv a {
        width: 150px;
    }
}
</style>