# ios-mapdiary-app

#### NaverCloudPlatForm의  지도API 사용 
    - 지도 불러오기: Mobile Dynamic Map (ios SDK)  3.x 버전 (git-lfs)
    - 장소 검색기능: Search Places API  -> 2020.06 서비스 종료됨

- initial: 
  - 네이버 MobileMap 불러오기 ( 현재위치 추가 ) + SearchPlaces API 호출
  
- master: 8/23 금
    - 협업을 위한 xcode다운그레이드: xcode 9.4.1로 변경 
    - 장소검색결과 newDiaryVC에 전달
    - Firebase 연동하여 newDiary 데이터저장
    - 지도에 marker 추가
    
    *ToDo*
    - ~~*UIImage Firebase*~~
    - ~~*지도 커스텀알아보기 (레이어, 모드변경 등): 지도 버전3으로 높혀야 할듯*~~
    - ~~*지도 마커커스텀 (이미지)*~~
    - ~~*ShowDiaryVC, DiaryLogVC*~~
    - *논의해야할 내용: 첫화면 등록버튼 (첫화면 지도 or 목록, 전체적인 흐름 다시) + datePicker 달력으로 변경 + '갈 곳' 기능*
    - *비동기검색*

- newVersion:
    - Mobile map sdk 버전 업그레이드 3.x (대용량 파일업로드 git-lfs 이용)

- final: 8/25 일 ~ 8/26 월   
   - 글작성 및 보기기능 완성 
   - Firebase Storage 이용하여 이미지 업로드 
   - Alamofire 이용하여 장소 검색 api와 글쓰기기능 사이 정보전달 연동 
   - UI/UX 연결
 
 

    

