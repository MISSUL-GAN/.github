<p>
  <img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FMISSUL-GAN&count_bg=%2380A68F&title_bg=%233C6B50&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false"/> &nbsp
  <a href="https://missulgan.art/"><img src="https://img.shields.io/badge/Missul;GAN-4C8765.svg?style=for-the-social&logo=Mega&logoColor=white&link=https://missulgan.art/"/></a> &nbsp
  <a href="https://api.missulgan.art/swagger-ui/index.html"><img src="https://img.shields.io/badge/-API Spec-%23Clojure?style=for-the-social&logo=Swagger&logoColor=white&link=https://api.missulgan.art/swagger-ui/index.html"/></a> &nbsp
  <a href="https://youtu.be/JZaOMU84G38"><img src="https://img.shields.io/badge/Demo Video-%23FF0000.svg?style=for-the-social&logo=YouTube&logoColor=white&link=https://youtu.be/JZaOMU84G38"/></a>
</p>

# Missul;GAN
**숭실대학교 소프트웨어학부 소프트웨어공모전 총장상🥇**
### GAN을 활용한 작품 공유 커뮤니티 및 NFT 연동 서비스
<img width="1500" alt="미슐간 대표 이미지" src="https://user-images.githubusercontent.com/87802191/189531752-368286e0-993b-41fa-9bb2-8b8c3f52ad7f.png">

## 🖥️ View
### 로그인
- 카카오톡, 구글 등 소셜 로그인 지원

![missulgan-login](https://user-images.githubusercontent.com/87802191/211185021-97aac88e-1640-4908-9171-337887455ce5.gif)


### 작품 생성
- GAN, CNN 알고리즘을 사용하여 사용자가 업로드한 사진을 특정 화풍으로 변환
  - GAN: 특정 데이터 집합으로부터 판별자 모델과 생성자 모델이 서로 적대적으로 학습하면서 실제와 가까운 이미지, 동영상, 음성 등을 자동 생성하는 알고리즘 중 하나
  - CNN: 필터링 기법을 인공신경망에 적용하여 행렬로 표현된 필터의 각 요소가 데이터 처리에 적합하도록 자동으로 학습되는 과정을 통해 이미지를 분류하는 기법
- 작품 명과 작품 설명을 입력하여 하나의 작품을 생성함
- 작품 이미지 다운로드, 카카오톡 공유하기 가능

![missulgan-gan사진변환](https://user-images.githubusercontent.com/87802191/211185027-45506c6e-16e7-437b-923f-10f42a275c5f.gif)


### 작품 감상
- 다른 사람들이 만든 작품을 감상하는 커뮤니티 기능
- 원하는 태그 선택 시 작품 필터 기능
- 좋아요순, 최신순, 랜덤순 정렬 
- 좋아요 및 스크랩 기능으로 소통

![메인화면(태그)](https://user-images.githubusercontent.com/87802191/212468673-084169d0-a51f-43a8-906d-60bac2225c00.gif)
![메인화면(조회)](https://user-images.githubusercontent.com/87802191/212469020-90eb1eb3-e541-49e8-aae3-f3d992cfe7eb.gif)


###  NFT 등록
- NFT를 제공받을 수 있는 이더리움 지갑 주소 입력
- 작품의 NFT 가격 및 통계 정보 제공
- 미슐간 OpenSea 마켓 플레이스 : https://opensea.io/collection/missulgan-art

![nft민팅](https://user-images.githubusercontent.com/87802191/212467832-936cad98-6f8c-454e-883d-4ca032c019e7.gif)

![오픈씨](https://user-images.githubusercontent.com/87802191/212468216-7fd1e2ea-fa12-4302-9971-ade6dd8adcd3.png)


---

## 📚 Repository
| [GAN_Front](https://github.com/MISSUL-GAN/GAN_Front) | [GAN_Back](https://github.com/MISSUL-GAN/GAN_Back) | [GAN_DeepLearning](https://github.com/MISSUL-GAN/GAN_DeepLearning) |
|:--------:|:--------:|:--------:|


## 👨‍💻Team member👩‍💻
 | ![손시연](https://user-images.githubusercontent.com/87802191/189529793-ca61e452-347e-4a07-84fc-7cc7443a6fed.png) | ![박성철](https://user-images.githubusercontent.com/87802191/189529737-330c6c70-c1c3-4a44-a777-fefd33056869.png) | ![이유진](https://user-images.githubusercontent.com/87802191/189529771-c5dd1fce-bab6-4d5a-8534-4a9ca7207202.png) | ![장환곤](https://user-images.githubusercontent.com/87802191/189529785-32d61d43-103f-422b-a8d4-a7b07babc640.png) | ![임세현](https://user-images.githubusercontent.com/87802191/189529778-ac9f73cc-75ac-460c-a542-29e15ad8704c.png) |
|:--------:|:-------:| :-------:| :-------:| :-------:| 
| [손시연](https://github.com/siyeonSon) | [박성철](https://github.com/0chil) | [이유진](https://github.com/nijuy) | [장환곤](https://github.com/HwanGonJang) |  [임세현](https://github.com/seddong) |
| Back-end | Back-end / Front-end | Front-end | AI | Design | 

<br>

### 🖥️ Architecture
<img alt="서버 시스템 아키텍쳐" src="https://user-images.githubusercontent.com/87802191/189530029-df2c0f0c-35bb-4f98-82bd-0f94a941b6d7.png">

<br>

### 🖥️ Server Deployment Environment
🖼️ **Image Server**

<img alt="이미지 서버 배포" src="https://user-images.githubusercontent.com/87802191/189529874-439bc429-b967-4b7b-a2ae-0514f041acdc.png">

📟 **Front-end Server**

<img alt="프론트 배포" src="https://user-images.githubusercontent.com/87802191/189529917-3b5afae3-a02b-4d50-8649-d76f6ce8e92b.png">

🗄️ **Back-end Server**

<img alt="백 배포" src="https://user-images.githubusercontent.com/87802191/189529928-3a55421b-9a94-4a5f-9b96-db63d1b423af.png">

<br> 

### 🖥️ Tech Stack
<img alt="기술 스택" src="https://user-images.githubusercontent.com/87802191/189531203-364a7563-0f8d-41b2-8bf8-4423f2a6b78a.png">

<br>

### 📈 ERD
<img alt="ERD" src="https://user-images.githubusercontent.com/87802191/189530721-05133139-ef18-4d90-9786-c3830d891d0d.png">

<br>

### 🎞️ Flow Chart
<img alt="플로우차트" src="https://user-images.githubusercontent.com/87802191/189530771-0648cd21-7127-443c-8ce6-8d945da453c4.png">
