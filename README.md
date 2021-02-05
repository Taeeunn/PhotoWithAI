# PWA_APP

# 2/5 am 01:00

### 1. 작업방향(기능 구체화)

    기능 1) 사진 구도 가이드
    기능 2) 비슷한 여러 사진들 중 가장 잘 찍은 사진을 선택해줌 
            2.1) 배경 사진 (인물 없는 풍경사진)
            2.2) 인물 사진


### 2. 작업 진행상황

    2.1 AI 
      * google opensource NIMA 활용, 학습된 모델 front와 연결중 
      * 인물 사진은 데이터셋을 찾아 직접 학습시켜 구현할 계획

    2.2 FrontEnd
     * 완료된 디자인작업물로 화면 그리기 작업
     * 디바이스 갤러리 접근 등 모바일 핵심기능 구현중

    2.3 Backend
    * heroku로 서버구축완료
    * 앱에서 서버로 이미지 다중파일 처리 작업중 
    
    2.4 1차 프로토 타입( 기능2 흐름 )
    
![image](https://user-images.githubusercontent.com/50574738/106924960-f88e8100-6752-11eb-9420-3394bea86d45.png)


### 3. ~10:00 am
* 멘토링 
* Good/Bad case 인물 사진 데이터 셋 모으기
* 각 파트 작업 이어서 진행



# 2/5 pm 01:00

### 1. 기능 상세화
    * 기능 1) AI 카메라 (take a photo with AI)
        - 비율, face detection, foot detection 활용 예정
    * 기능 2) 사진 셀렉 기능(pick better one with AI)
        - 풍경/인물 사진 중 선택
        - 선택한 5장(예)의 사진 중에서 가장 잘 찍은 사진 하나를 추천(like-갤러리 내 기능, 인스타 연동)
        
### 2. 작업 진행상황

    * 이미지 연동- get, post 요청하여 body로 내용 넣어서 서버로 이미지 전송 확인
    * AI: opencv - key point detection in video sequences
    * 확정된 기능 디자인 수정

    
    
    
