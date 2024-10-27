# 👩‍💻 Project: Silver Lining
### 키오스크를 사용하기 어려운 고령층 소비자에게도 접근이 용이한 키오스크 AI 서비스.

<br>

## 👨‍🏫 Project Introduction (Team 실버라이닝)
#### 나이듦에 따른 신체의 노화가 단점으로 받아들여질 수 있는 상황에서 긍정적으로 생각해보자는 취지를 담은 프로젝트. 
- 키오스크 서비스에 접근하기 어려운 고령의 고객이 키오스크를 쉽게 이용할 수 있도록 구성한 서비스
- 얼굴 인식을 통해 키오스크를 이용하려는 사용자의 나이를 자동으로 파악하여 대상 연령대에 맞춘 UI/UX로 긍정적인 이용 경험 유도

<br>

## 💡Function
- Django admin customization: 유저, 메뉴, 해시태그 CRUD 
- 얼굴 인식 기능: Opencv 얼굴 인식 후 이미지를 통한 나이 추정
- 음성 인식 기능: STT로 입력 받은 데이터를 AI답변 및 메뉴 추천
- 연령별 맞춤 템플릿: 고령층과 비고령층의 UI/UX와 기능의 차별화를 통해 연령 맞춤 서비스 제공
- AWS를 이용 웹 서비스 제공 
- javascript를 이용한 새로고침없이 프론트엔드 데이터 변경


<br>


## ⏲️ Development time 
- 2024.05.13(월) ~ 2023.06.12(수)


<br>

## 💻 Development Environment
- **Programming Language** : Python 3.10
- **Web Framework** : DJANGO 4.2
- **Database** : SQLite (for development and testing), PostgreSQL (for Release)
- **IDE** : Visual Studio Code, Pycharm
- **Version Control** : Git, GitHub, Docker
- **Communication** : Zep, Slack, Figma, Zoom
- **Server** : AWS(EC2)
  
<br>

## 🖥️Preview


<p align="center">
  <strong>⭐로그인</strong>
</p>
  
<p align="center">
  <img src="https://github.com/user-attachments/assets/7bd48f2d-fecd-49b3-8003-315307faf77f" alt="로그인">
</p>

<p align="center">
  <strong>⭐메뉴 등록</strong>
</p>
  
<p align="center">
  <img src="https://github.com/user-attachments/assets/50464aae-d43d-4921-a855-8e394a8425b7" alt="메뉴추가">
</p>

<p align="center">
  <strong>⭐얼굴인식(일반)</strong>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/0229a614-8ca4-4c42-81ee-d1cab77b2324" alt="얼굴인식(일반인)">
</p>

<p align="center">
  <strong>⭐얼굴인식(고연령)</strong>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/4b958a0f-c660-45fe-9a85-dd853cd460ea" alt="얼굴인식(고연령)">
</p>

<p align="center">
  ⭐ 태그별 메뉴 분류 ⭐ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  ⭐ AI 메뉴 추천 ⭐ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  ⭐ 나라별 언어변경 ⭐
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/9d139424-a754-4ad1-99f8-0ef202081a64" alt="태그별 메뉴 분류" width="30%">
  &nbsp;&nbsp;&nbsp;
  <img src="https://github.com/user-attachments/assets/c03249fc-a46b-4589-9f1c-b3a4386d9493" alt="AI 메뉴 추천" width="30%">
  &nbsp;&nbsp;&nbsp;
  <img src="https://github.com/user-attachments/assets/cf5efe55-b1f0-40bf-b578-f3e333b02d2f" alt="언어별 메뉴" width="30%">
</p>

<p align="center">
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  ⭐ 결제 ⭐ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  ⭐ 고연령 음성인식 ⭐ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
  ⭐ 각 키오스크 화면 전환 ⭐
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/f476b6d6-0877-4669-bfe2-0571030fb5d1" alt="결제" width="30%">
  &nbsp;&nbsp;&nbsp;
  <img src="https://github.com/user-attachments/assets/30b94cb9-89a5-4738-8025-e48b31b1b31f" alt="고연령 음성인식" width="30%">
  &nbsp;&nbsp;&nbsp;
  <img src="https://github.com/user-attachments/assets/1e1f576b-bb08-4acf-99bb-2f1d3c0a3266" alt="키오스크화면전환" width="30%">
</p>


<br>

## 📝 Project

  - 시연 영상 : [유튜브 시연영상](https://www.youtube.com/watch?v=Q7jmeQ_tOPE&t=42s)을 통하여 확인

  - 아이디어 회의 : 개발 기획 단계 및 아이디를 논의하기 위해 [피그마](https://www.figma.com/board/CUporczK2kYaCbjQQIDoVO/final-project?node-id=0-1&t=99pB1pcpflZp4QJg-0)를 활용하여 작성

  - 트러블 슈팅 : 문제점 보완 및 개선을 위해 [노션](https://teamsparta.notion.site/8-silver-lining-f9ee581e81e8456c8d78729434c5ca06)을 활용하여 기록

![image](https://github.com/user-attachments/assets/2ded4c7c-f96a-43a2-a67f-cfaa198e72af)

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


## 💻Technical Description

### 1. 언어 변경기능


<p align="center">
  <img src="https://github.com/user-attachments/assets/cf5efe55-b1f0-40bf-b578-f3e333b02d2f" alt="언어별 메뉴" width="30%">
</p>


```python
# 언어를 변경하는 함수입니다.
def switch_language(request):
    lang = request.GET.get('lang', settings.LANGUAGE_CODE)
    if lang:
        # 언어 변경
        translation.activate(lang)
        # 언어 쿠키 설정
        response = redirect(request.META.get('HTTP_REFERER', '/'))
        response.set_cookie(settings.LANGUAGE_COOKIE_NAME, lang)
        return response
    return redirect(request.META.get('HTTP_REFERER', '/'))
```

💡 Django의 기본 번역기능을 이용하여 각 언어에 맞추어 변경 가능

### 2. AI 추천기능

```python
class AIbot(APIView):
    def post(request):
        # POST 요청을 처리하는 메소드입니다.
        # AI 봇에게 입력된 텍스트를 전달하고 응답을 받습니다.
        input_text = request.data.get('inputText')
        current_user = request.user
        message, recommended_menu = bot(input_text, current_user)
        return Response({'responseText': message, 'recommended_menu': recommended_menu})
```

💡 POST 입력시 bot.py 내부 bot 함수를 통하여 추천 메뉴 및 메세지 생성 후 return

<br>

<details>
<summary> 📗 AI 프롬프트 </summary>

<br>

## 프롬프트
```python
def get_recommended_menus(client, input_text, current_user):
    system_data = f"""
        You are considered a staff member related to {category_text}.
        Our store offers the following menu items: {menu}.
        Additionally, we use the following hashtags in our store: {hashtags}.
        """

    system_output = f"""
        The format of the data I desire as a result is:
        "Recommended Menu: [menu_name]"
        For the "Recommended Menu" section, select three options that are most closely related to the customer's request and rank them accordingly.
        The main format of recommended menu should be "Recommended Menu: menu_name, menu_name, menu_name".
        The output of recommended menus must include three items. If fulfilling three items is difficult to achieve, go through the menu table to find the closest menu possible.
        It would be easier for you to consider hashtags when finding related menu.
        When there are more than one keyword that you take into account, you should prioritize the keyword that is related to the menu.
        For example, when the customer asks for 'iced coffee', you should consider the menu that is 'coffee', rather than 'iced' beverages.
        """
    completion = client.chat.completions.create(
        model="gpt-4o",
        messages=[
            {"role": "system", "content": system_data},
            {"role": "system", "content": system_output},
            {"role": "user", "content": input_text},
        ],
    )

    ai_response = completion.choices[0].message.content
    recommended_menu = []

    try:
        for line in ai_response.split('\n'):
            line = line.strip()  
            if line.startswith('Recommended Menu:'):
                recommended_menu = line.split('Recommended Menu: ')[1].strip().split(', ')
                break  

    except IndexError:
        recommended_menu = []

    return recommended_menu
```

</details>

### 3. 얼굴 인식 기능

```javascript
    function submitForm(imageData) {
        // FormData 객체 생성
        var formData = new FormData();

        // 이미지 데이터를 FormData 객체에 추가
        var blob = dataURItoBlob(imageData);
        formData.append('faceImageData', blob, 'face_image.jpeg');

        // CSRF 토큰 가져오기
        const csrftoken = getCookie('csrftoken');

        // 이미지 데이터가 있는 경우 AJAX 요청 보냄
        $.ajax({
            url: '/orders/face_recognition/',
            method: 'POST',
            headers: {'X-CSRFToken': csrftoken},
            data: formData,
            processData: false,  // jQuery가 데이터를 쿼리 문자열로 변환하는 것을 방지
            contentType: false,   // jQuery가 contentType을 설정하는 것을 방지
            success: function (response) {
                // 서버 응답을 성공적으로 받은 후에 수행할 작업
                console.log('Success:', response);
                // 얼굴 나이 확인
                var ageNumber = response.age_number;
                // 나이에 따라 페이지 리디렉션
                if (ageNumber >= 60) {
                    window.location.href = "{% url 'orders:elder_start' %}";
                } else {
                    window.location.href = "{% url 'orders:menu' %}";
                }
            },
            error: function (xhr, status, error) {
                console.error('Error:', error);
                // 오류 처리
            }
        });
    }
```

💡AJAX를 사용하여 이미지 데이터 전송

```python
@csrf_exempt
def face_recognition(request):
    if request.method == 'POST' and 'faceImageData' in request.FILES:
        # Get uploaded image
        uploaded_image = request.FILES['faceImageData']
        age_number = face(uploaded_image)

        return JsonResponse({'age_number': age_number})
    return HttpResponse("Please upload an image.")
```

💡 bot.py 내부의 face 함수를 이용 나이값 계산

<br>

<details>
<summary> 📗 얼굴인식 AI </summary>

<br>

```python
def face(uploaded_image):
    # Read the image using OpenCV
    image_data = uploaded_image.read()
    nparr = np.frombuffer(image_data, np.uint8)
    frame = cv2.imdecode(nparr, cv2.IMREAD_COLOR)

    # 얼굴 인식을 위한 분류기를 로드합니다.
    face_cascade = cv2.CascadeClassifier(cv2.data.haarcascades + 'haarcascade_frontalface_default.xml')

    # 흑백 이미지로 변환합니다.
    gray = cv2.cvtColor(frame, cv2.COLOR_BGR2GRAY)

    # 얼굴을 감지합니다.
    faces = face_cascade.detectMultiScale(gray, scaleFactor=1.1, minNeighbors=5, minSize=(30, 30))

    if len(faces) > 0:
        # 이미지를 저장하고 base64로 변환합니다.
        image_path = "face.jpg"
        cv2.imwrite(image_path, frame)

        with open(image_path, "rb") as image_file:
            encoded_image = base64.b64encode(image_file.read()).decode('utf-8')

        base64_image = f"data:image/jpeg;base64,{encoded_image}"

        # OpenAI API에 요청합니다.
        headers = {
            "Content-Type": "application/json",
            "Authorization": f"Bearer {settings.OPEN_API_KEY}"
        }

        instruction = """
                                    Although age can be difficult to predict, please provide an approximate number for how old the person in the photo appears to be. 
                                    Please consider that Asians tend to look younger than you might think.
                                    And Please provide an approximate age in 10-year intervals such as teens, 20s, 30s, 40s, 50s, 60s, 70s, or 80s.
                                    When you return the value, remove the 's' in the end of the age interval.
                                    For example, when you find the person to be in their 20s, just return the value as 20.
                                    Please return the inferred age in the format 'Estimated Age: [inferred age]'.
                                    """

        payload = {
            "model": "gpt-4o",
            "messages": [
                {
                    "role": "user",
                    "content": [
                        {
                            "type": "text",
                            "text": instruction,
                        },
                        {
                            "type": "image_url",
                            "image_url": {
                                "url": base64_image
                            }
                        }
                    ]
                }
            ],
            "max_tokens": 300
        }
        # OpenAI API로 요청을 보냅니다.
        response = requests.post("https://api.openai.com/v1/chat/completions", headers=headers, json=payload)

        try:
            os.remove(image_path)
            print(f"{image_path} 이미지가 삭제되었습니다.")

        except FileNotFoundError:
            print(f"{image_path} 이미지를 찾을 수 없습니다.")

        # OpenAI API에서 반환된 응답을 파싱합니다.
        ai_answer = response.json()
        print("ai_answer", ai_answer)
        # 추정된 나이를 가져옵니다.
        age_message = ai_answer["choices"][0]['message']['content']
        age = age_message.split("Estimated Age: ")[1].strip()
        age_number = int(age)
        print("당신의 얼굴나이 : ", age_number)
        return age_number
    return 20
```

</details>


<br>

## 📌 Key Features

### 1. 키오스크 사용자 
#### (1) 얼굴인식을 통한 연령층 식별과 키오스크 UI 맞춤화 
   - 브라우저의 카메라 호환기능을 통해 키오스크 사용자의 얼굴 사진을 찍고 사용자의 나이 값를 도출
   - 결과값이 고령층인 경우와 비고령층인 경우를 구분해서 키오스크 주문 UI를 맞춤화해서 제공

<br>

#### (2) 고령층과 비고령층 주문단계 차별화
#### (2-1) 고령층
1. 고령층에 맞추어 버튼 및 글자의 크기를 기존 대비 확대 및 단순화하여 편의성 확대
2. 터치를 최소화 하기 위하여 음성데이터 기반으로 AI가 추천메뉴를 화면에 출력
3. 메뉴 이용에 불필요한 부분을 제외, 고객의 니즈에 필요한 부분만 출력하여 오입력 방지
4. 재추천, 장바구니(추가, 수정, 삭제), 결제하기 기능을 모두 음성인식으로 동작하도록 구현

#### (2-2) 비고령층 (일반적인 키오스크 터치 주문 + 음성인식 메뉴 추천)
1. 기본적으로는 일반적인 키오스크와 동일하게 사용 가능
2. 필요의 따라 음성입력으로 AI 기능을 사용 가능
3. 언어에 맞추어 메뉴와 버튼이 변경 가능

<br>

#### (2-3) 결제 이후 주문번호 배정
   - 2-1 ~ 2-2 과정 후 주문메뉴가 데이터 베이스의 저장이 되며 주문번호 발급
   - 매일마다 주문번호가 초기화되어 1번 부터 주문번호가 생성된다

<br>

### 2. 점주 (staff)
#### (1) 메뉴 CRUD
- 메뉴 생성 전에 필요한 해시태그들을 미리 설정하여 각 메뉴 분류기능 구현
- 메뉴 생성시에는 메뉴 이름, 가격, 해시태그, 이미지를 함께 작성
  
#### (2) 주문 현황
- 키오스크를 통한 결제된 내역을 확인할 수 있으며 주문의 상태를 통하여 "주문/진행중/완료"를 확인 가능

<br>

### 3. 관리자 (superuser)
#### (1) staff CRUD 및 메뉴 CRUD
- 새로운 staff계정을 생성, 조회, 수정, 삭제 및 관리자 권한으로 각 계정의 메뉴를 수정 할 수 있다
#### (2) staff에 permission 부여
- admin page내의 group을 새로 생성하여 staff가 메뉴 CRUD에만 접근가능하도록 제한한다

<br>

## 📄 ERD:
![SivlerLining (2)](https://github.com/billyhyunjun/Silver-Lining/assets/159408752/7ef6181b-7b38-4a7c-ae2f-6d6d880f0197)

<br><br>
