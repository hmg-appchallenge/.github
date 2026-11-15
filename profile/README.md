<p align="center">
  <img src="https://raw.githubusercontent.com/hmg-appchallenge/hyundai-appchallenge-frontend/main/app/src/main/res/mipmap-xxxhdpi/ic_launcher.png" width="96" alt="차곡차곡 아이콘">
</p>

<h1 align="center">팀 스포티카이 · 차곡차곡</h1>

<p align="center">
  출발부터 도착까지 차가 달리는 리듬 위에 가족의 목소리와 악기가 하나씩 더해져,<br>
  드라이브마다 우리 가족만의 노래가 완성되는 차량용 가족 음악 앱<br>
  현대자동차그룹 차량용 앱 개발 공모전 참가팀
</p>

## 왜 만들었나요

가족의 이동은 대부분 차 안에서 이뤄져요. 그런데 차 안의 아이는 운전자의 주의를 흩뜨리고, 그렇다고 화면을 쥐여 주면 아이의 건강과 차멀미가 걱정이에요. 차곡차곡은 아이가 화면 대신 **소리로 참여**하고, 운전자는 운전에 집중하고, 가족은 함께 노래를 만드는 시간을 만들어요.

## 차곡차곡

| 기능 | 내용 |
|---|---|
| 주행 리듬이 비트로 | 정차 80 BPM 2비트 → 시속 1~30 km 95 BPM 4비트 → 31~70 km 110 BPM 8비트 → 71 km 이상 125 BPM 16비트. 그날 달린 길마다 다른 비트가 만들어져요 |
| 가족 목소리별 악기 | 가족 이름과 목소리를 한 번 등록하고 12종 악기 중 하나씩 골라요. 녹음 중 누가 소리를 냈는지 구분해 그 사람의 악기가 더해져요 |
| 아이의 말이 가사로 | 녹음에서 들린 단어와 의성어로 AI가 동요 가사와 노래를 만들고, 가장 많이 들린 단어로 제목을 붙여요 |
| 캐릭터와 보관함 | 완성되면 고른 캐릭터가 노래 비트에 맞춰 춤을 추고, 완성곡은 차 안 보관함에 쌓여요 |
| 운전을 방해하지 않게 | 주행 중에는 캐릭터를 숨기고 소리로만 반응해요. 캐릭터 크게 보기와 이름 입력은 정차 중에만 돼요 |
| 아이 정보 보호 | 처음 켤 때 보호자 동의를 받고, 서버는 녹음과 완성곡을 남기지 않아요. 완성곡과 가족 정보는 차 안에만 저장해요 |

## 저장소

| 저장소 | 내용 |
|---|---|
| [hyundai-appchallenge-frontend](https://github.com/hmg-appchallenge/hyundai-appchallenge-frontend) | Pleos Connect(Android Automotive) 앱. Kotlin + Jetpack Compose |
| hyundai-appchallenge-backend | 노래 생성 서버. 음성 인식, 목소리 구분, 가사·제목(Claude), 반주·노래(ElevenLabs Music) |

제출용 APK는 프론트엔드 저장소의 [`apk/`](https://github.com/hmg-appchallenge/hyundai-appchallenge-frontend/tree/main/apk) 폴더에 있어요. 설치와 실행 방법은 [README](https://github.com/hmg-appchallenge/hyundai-appchallenge-frontend#실행-방법)를 봐 주세요.

## 팀원

| 역할 | 이름 | 소속 | 이메일 |
|---|---|---|---|
| 기획 · PM | 정다영 | 홍익대학교 | wjdekdud8268@naver.com |
| 디자인 | 김정현 | 서경대학교 | jczhy11@naver.com |
| 프론트엔드 | 김현중 | 구름 | rugbysh99@gmail.com |
| 백엔드 · AI | 박세준 | 경북대학교 | mnunu1234@naver.com |
