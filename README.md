[Bike Sharing Demand](https://www.kaggle.com/competitions/bike-sharing-demand/overview)


---

프로젝트 설정 방법

폴더 새로 만든 뒤, 해당 폴더에서 아래 명령어 실행해서 git 연결합니다.
```
git init

git branch -m main

git remote add origin https://github.com/gptjddldi/kg-bike-sharing-demand.git

git pull origin main

```

작업하실 땐 branch 새로 만들어서 작업합니다.

```
git checkout -b {브랜치 이름(아무거나)}

git add {파일 이름}

git commit -m "{커밋 메세지}"

git push origin {브랜치 이름}
```

푸쉬하시면 https://github.com/gptjddldi/kg-bike-sharing-demand/pulls 탭에서 PR 생성할 수 있습니다.


환경설정이 잘 안되면 그냥 평소에 하던대로 개발하고 같이 봐요! ㅎㅎ


---


Data Fields

- datetime - 시간별 날짜 + 타임스탬프  
- season 
    - 1: 봄
    - 2: 여름
    - 3: 가을
    - 4: 겨울 
- holiday - 휴일
- workingday - 주말도 휴일도 아닌 날
- weather
    - 1: 맑음, 구름 조금, 구름 조금, 흐림
    - 2: 안개 + 흐림, 안개 + 산발적 구름, 안개 + 구름조금, 안개
    - 3: 약한 눈, 약한 비 + 천둥번개 + 흩날리는 구름, 약한 비 + 흩날리는 구름
    - 4: 폭우 + 얼음판 + 뇌우 + 안개, 눈 + 안개 
- temp - 실제 온도 (섭씨)
- atemp - 체감 온도 (섭씨)
- humidity - 상대 습도
- windspeed - 풍속
- casual - 비회원의 대여 수
- registered - 회원의 대여 수
- count - 총 대여 횟수 (casual + registered)