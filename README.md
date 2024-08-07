# 👩‍💻Project: Silver Lining
### "Every cloud has a silver lining."
#### 키오스크를 사용하기 어려운 고령층 소비자에게도 접근이 용이한 키오스크 AI 서비스.

<br>

## 👨‍🏫 Project Introduction (Team 실버라이닝)
#### 나이듦에 따른 신체의 노화가 단점으로 받아들여질 수 있는 상황에서 긍정적으로 생각해보자는 취지를 담은 프로젝트. 
- 키오스크 서비스에 접근하기 어려운 고령의 고객이 키오스크를 쉽게 이용할 수 있도록 구성한 서비스
- 얼굴 인식을 통해 키오스크를 이용하려는 사용자의 나이를 자동으로 파악하여 대상 연령대에 맞춘 UI/UX로 긍정적인 이용 경험 유도
- 음성 인식을 통한 AI 추천으로 고객에게 음성을 입력 받아 맞춤 메뉴 제안



<br>

- Django admin customization: 유저, 메뉴, 해시태그 CRUD 
- 이용자 input 처리: opencv, gTTS, gSTT를 js에서 이용
- 얼굴 인식 기능: opencv로 얼굴 인식 후 gpt로 나이를 추정
- 음성 인식 기능: STT로 입력받은 음성을 gpt로 처리하고 받은 응답을 TTS로 출력
- AI 메뉴 추천 모델: 받은 음성을 기반으로 gpt-4o 로 메뉴 추천
- 연령별 맞춤 템플릿: 고령층과 비고령층의 UI/UX와 기능의 차별화를 통해 연령 맞춤 서비스 제공

<br>


## ⏲️ Development time 
- 2024.05.13(월) ~ 2023.06.12(수)


<br>

## 💻 Development Environment
- **Programming Language** : Python 3.10
- **Web Framework** : DJANGO 4.2
- **Database** : SQLite (for development and testing), PostgreSQL (for Release)
- **IDE** : Visual Studio Code, Pycharm
- **Version Control** : Git, GitHub
- **Communication** : Zep, Slack, Figma, Zoom
  
<br>

## 📝 Project

  - Notion : https://www.notion.so/teamsparta/8-silver-lining-f9ee581e81e8456c8d78729434c5ca06

  - Figma : https://www.figma.com/board/CUporczK2kYaCbjQQIDoVO/final-project?node-id=0-1&t=99pB1pcpflZp4QJg-0


<br>

## 💭 기술적 의사결정

- OpenAI GPT-4o 적용
    
    초기: OpenAI GPT 3.5-turbo 모델을 사용하여 대화형 인터페이스에서 고객과의 대화를 처리하고자 시도
    변경: 테스트 결과 GPT 4o를 사용했을 때 responseText의 정확도가 개선된다고 판단
    구현 결과: 고객과의 대화에서 상대적으로 자연스러운 대화를 유도하고, 적절한 답변을 제공하는 데 성공
    
- 얼굴인식 모델 변경

    초기: deepface libraray를 사용하여 얼굴인식 기능을 구현함
    변경: deepface의 나이 추정값의 정확도 이슈가 발생 -> GPT 4o의 프롬프트 수정으로 더 정확도 높은 나이 추정값을 얻음
    구현 결과: GPT-4o 모델을 사용하여 얼굴인식 기능을 구현. 사용자의 얼굴을 정확하게 인식하고, 해당 사용자에게 맞춤형 서비스를 제공하는 데 성공
    
- STT, TTS 브라우저 기능 활용
    
    브라우저의 기본 STT 및 TTS 기능을 JavaScript를 통해 활용하여 음성인식 및 음성출력 기능을 구현
    구현 결과: 브라우저 상에서 음성인식과 음성출력이 가능하도록 변경하여 사용자에게 더욱 편리한 환경을 제공하는 데 성공
    
- JSON 데이터 전송 및 부트스트랩 활용
    
    JavaScript를 통해 JSON 형식으로 데이터를 주고 받으며, 부트스트랩을 활용하여 프론트엔드를 빠르게 개발
    구현 결과: 페이지를 새로 고치지 않고도 메뉴 변경 및 장바구니 기능을 구현하여 사용자가 원활하게 주문을 진행
    
- Admin 페이지 활용
    
    Django의 Admin 페이지 기능을 활용하여 User 및 Menu 관련 데이터를 관리
    핵심 기능: Admin 페이지를 통해 데이터를 쉽게 추가 및 수정할 수 있도록 하여 프로젝트 개발 단계를 진행

- Redis 적용

    음성인식으로 장바구니 기능을 구현하는 와중에 GPT 답변의 정확도 향상을 위해 현재 장바구니 현황을 전달할 필요성 대두
    여러 선택지 가운데 수정이 잦고, 굳이 DB에 장바구니의 모든 변경사항이 반영될 필요가 없으므로 Redis 채택
    구현 결과: Redis를 사용하여 elder_menu.html의 장바구니 기능을 구현
<br>


## 📌 Key Features

### 1. 키오스크 사용자 
#### (1) 얼굴인식을 통한 연령층 식별과 키오스크 UI 맞춤화 
   - 브라우저에서 제공하는 카메라 기능을 통해 키오스크 사용자의 얼굴 사진을 찍고, 사진에서 해당 사용자의 나이를 도출한다.
   - 도출해낸 나이가 고령층인 경우와 비고령층인 경우를 구분해서 키오스크 주문 UI를 맞춤화해서 제공한다.

<br>

#### (2) 고령층과 비고령층 주문단계 차별화
#### (2-1) 고령층
1. 고령층 주문 페이지 로딩과 동시에 출력되는 안내멘트 이후에 음성인식이 시작된다
2. 입력받은 음성데이터를 토대로 메뉴추천 AI가 추천메뉴를 띄워서 알려준다
3. 가장 추천되는 메뉴가 팝업창에 나타나고, 사용자는 이 메뉴를 장바구니에 넣거나 다른 추천 메뉴를 볼 수 있다
4. 메뉴 재추천, 장바구니 기능(추가, 수정, 삭제), 결제하기 기능을 모두 음성인식으로 사용할 수 있다다


#### (2-2) 비고령층 (일반적인 키오스크 터치 주문 + 음성인식 메뉴 추천)
1. 기본적으로는 일반적인 터치 주문 방식과 동일하게 사용할 수 있다
2. 안내멘트에 따라 음성인식 버튼을 누르면 메뉴추천 AI 기능을 음성인식으로 사용할 수 있다
3. 고령층 주문단계와는 달리 음성인식 버튼을 눌러 메뉴 재추천 기능만을 사용할 수 있다

<br>

#### (2-3) 결제 이후 주문번호 배정
   - 앞선 2-1 ~ 2-2까지의 과정에서 공통적으로 제공되는 기능이다
   - 하루마다 주문번호가 초기화된다

<br>

### 2. 점주 (staff)
#### (1) 메뉴 CRUD
- 메뉴 생성 전에 필요한 해시태그들을 미리 설정해줘야 한다
- 메뉴 생성시에는 메뉴 이름, 가격, 해시태그, 이미지를 업로드해야 한다
- 해당 해시태그는 비고령층 키오스크 템플릿에서 카테고리로 기능하며, 이에 따라 분류된 메뉴를 볼 수 있다
  
#### (2) 주문 현황 관련 (구현 예정)

<br><br>

### 3. 관리자 (superuser)
#### (1) staff CRUD 및 메뉴 CRUD
- 새로운 staff계정을 생성, 조회, 수정, 삭제할 수 있고, staff가 작성한 메뉴에 대해서도 관리자 차원에서 생성, 조회, 수정, 삭제를 할 수 있다
#### (2) staff에 permission 부여
- admin page내의 group을 새로 생성하여 staff가 메뉴 CRUD에만 접근가능하도록 제한한다

<br><br>
     

## 📄 ERD:
![SivlerLining (2)](https://github.com/billyhyunjun/Silver-Lining/assets/159408752/7ef6181b-7b38-4a7c-ae2f-6d6d880f0197)

