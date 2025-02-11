<div align="center">
  
![image](assets/image1.gif)


# Oak's Kindergarden

<details>
  <summary><strong>&nbsp;Table of Contents</strong></summary>

&nbsp;  
[About The Project](#about-the-project)<br/>
[Team Members](#team-members)<br/>
[Built With](#built-with)<br/>
[Architecture](#aws-architecture)<br/>
[model](#model)<br/>

</details>

</div>

&nbsp;

<!-- ABOUT THE PROJECT -->
## About The Project

Project Duration: Dec 17, 2023 - Dec 24, 2023

Oak's Kindergarden은 Inha Univ. 와 Chiangmai Univ. 가 함께 주관한 CAMT 해커톤에서 제작한 Automation Smart Farm 입니다. 내장된 센서를 통해 배양 중인 잎채소의 상태를 실시간으로 앱을 통해 모니터링하고, 재배 완료 시까지 수분량을 자동으로 조절합니다. 

&nbsp;

### Key Feature
- **Sensing data:** Sensing the temperture, humidity, soil moisture.

- **Monitoring:** Check the growth status of crops using OLED and Webcam with Blynk Application.

- **Touch-less Farming:** Supply all Farming Process Automatically.

- **Watering:** Auto water supplying System.


&nbsp;

<!-- Team -->
## Team Members
* **Team Member:** Ha Sung-min, BA, Inha Univ.
* **Team Member:** Yun Seo Young, BA, Inha Univ.* 
* **Team Member:** Ja, Computer Engineering, Chiangmai Univ.* 
* **Team Member:** Tao, Computer Engineering, Chiangmai Univ.* 

&nbsp;

<!-- Built with -->
## Built With
![Python](https://img.shields.io/badge/Python-3.11.4-3776AB?style=for-the-badge&logo=python&logoColor=yellow)   
![Node.js](https://img.shields.io/badge/NodeJS-18.17.0-339933?style=for-the-badge&logo=nodedotjs&logoColor=yellow)  


&nbsp;

## Architecture
![image](assets/image2.png)

## Model
AI hub의 상추 데이터를 사용하여 잎채소의 생육상태를 판별하고  
성장 상태를 확인하는 CNN 모델을 학습했습니다.

팀에서 만든 Automation SamrtFarm 기기에서는 연결된 미니캠으로   
잎상추 채소의 수확 가능 여부를 파악하고, 디스플레이에 결과를 송출합니다.  

학습과정과 사용 방법을 아래에 작성하였습니다.

<a href='model/CNN_Model.ipynb'>CNN 모델 학습과정</a>