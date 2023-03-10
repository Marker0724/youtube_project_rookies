# SK Shieldus Rookies 미니 프로젝트


## 주제 
* 특정 음악장르 유튜버를 여려명 지정하고, 영상에서 볼 수 있는 속성들를 사용해, 결산 레포트 만들기
* 최종적으로 본인 유튜브(까까들)와 상관관계 분석

## 속성값

### 국가
- 국내

### 음악 장르
- 발라드

### YouTube 자료
- 제목, 구독자, 조회수, 좋아요, 싫어요 등등

## 분석 유튜버

### 연예인 음악 유튜버
 - 기준
   - 커버곡이 아닌 본인의 곡이 일반인도 알법한 노래인 가수
 - 성시경 (https://www.youtube.com/@sungsikyung)
 - 임한별 (https://www.youtube.com/@onestarl)
 - 탑현 (https://www.youtube.com/@Tophyun)

### 비연예인 음악 유튜버
 - 기준
   - 커버곡으로 유튜브에서 어느정도 유명세를 가진 가수
 - 마라는대로 (https://www.youtube.com/@MaRa_Music)
 - 버블디아 (https://www.youtube.com/@Bubble-dia)
 - 셀프노트 스튜디오 (https://www.youtube.com/@user-pw3lj1vv9j)

### 까까들
- https://www.youtube.com/channel/UCiSsEIQ_O4Z5ykHXCj4pcuw
 
## 참고 자료
- 유튜브(Youtube) API - 6. Data API (Channels) (https://joypinkgom.tistory.com/32)
- API를 활용한 유튜브 크롤링 (https://ssongblog.tistory.com/125) 
- [Youtube크롤링] 1. Youtube API 호출하기 (https://blog.naver.com/doublet7411/221511344483) 
- (API+python)Youtube API를 이용하여 좋아요 수 가져오기 (https://anfrhrl5555.tistory.com/93)
- 네고왕 조회,좋아요,댓글 수 가져오기 (https://yobro.tistory.com/190)
- API를 활용한 유튜브 크롤링 (https://ssongblog.tistory.com/125)
- 유튜브 댓글을 이용한 text mining(https://shinminyong.tistory.com/4)

### 공식문서
- Data API (https://developers.google.com/youtube/v3/getting-started?hl=ko)
- API 속성부분 (https://developers.google.com/youtube/v3/docs?hl=ko#Videos)
- API Python 코드 예시 자료 (https://developers.google.com/youtube/v3/code_samples/python?hl=ko)

## 프로젝트 참고 
 - [미니프로젝트] 데이터 수집 (https://velog.io/@moonstar/미니프로젝트-데이터-수집)
 - 유튜브 썸네일 속 글자로 조회수 예측하기 (https://velog.io/@recoder/hitshike-thumbnail-text-01)

## 필요 패키지 설치
- 유튜브 API 라이브러리
  - !pip install --upgrade google-api-python-client
  - !pip install oauth2client
