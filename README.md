# 팀프로젝트
## 🕹️Flashback Arcade
명지대 팀프로젝트 강의에서 진행한 간단 웹 프로젝트  
웹사이트: <a href="https://zealous-forest-0f6f05700.3.azurestaticapps.net">링크 클릭</a>
<br/>
<br/>

## 🛠개발기간
2023-09 ~ 2023-11
<br/>
<br/>

## 😎프로젝트 간략 설명
- 웹사이트
- 웹 고전 게임 플랫폼
- 유저 로그인
- 게임 스코어 랭킹 보드
- 전체 유저 랭킹 보드
- 전체 채팅
- 채팅 번역
<br/>
<br/>

## 👍기술 스택
### 🎨프론트
- react
- bootstrap
- etc... 외부 게임 npm 모듈
- 배포:  static wep app on free plan

### 🖥️백엔드
- C# - ASP.NET Core API
- Blazor Server (채팅)
- DB: Sqlite
- 구글 OAuth
- Naver Papago API

### 🕸️배포
- 프론트: azure static wep app
- 백엔드: azure wep app
- db: 배포x, Sqlite 사용 중
<br/>
<br/>

## 👥👥팀구성
팀 인원 5명 / 개발 인원 4명  

*팀장 천제희*:  
- 기여도 90%  
- 개발 총괄 (프론트, 백엔드, 배포)
<br/>

최지원:
- 기여도 6%
- CSS 변경
<br/>

장우재:
- 기여도 2%
- 도배 방지 알고리즘 작성
<br/>

장용찬:
- 기여도 2%
- 욕설 필터 알고리즘(Trie) 작성
<br/>
<br/>

## 📹완성본 결과 동영상
유튜브 영상: <a href="https://www.youtube.com/watch?v=1BRQhjjtLGE&t=53s&ab_channel=JeheeCheon">링크 클릭</a>
<br/>
<br/>

## 🌏웹사이트 링크
웹사이트: <a href="https://zealous-forest-0f6f05700.3.azurestaticapps.net/">링크 클릭</a>
<br/>
<br/>

## 부록
인증 토큰을 쿠키에 저장하도록 구현해둔 상태인데 프론트와 백엔드 배포된 곳의 도메인이 각각 다른 상태입니다.  
따라서 IOS와 Safari 환경에서 Cross site tracking 이슈로 인해 로그인이 정상 작동 되지 않습니다.  
