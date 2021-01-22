# 웹사이트 이용 가이드



### 공통

- 텍스트

  | 종류      | 사용법             | 결과             |
  | --------- | ------------------ | ---------------- |
  | 줄바꿈    | `안녕<br>하세요`   | 안녕<br />하세요 |
  | 굵은 글씨 | `<b>굵은 글씨</b>` | **굵은 글씨**    |
  | 이탤릭    | `<i>이탤릭</i>`    | *이탤릭*         |

  

- 링크

  - 상대경로
    
    - 예시: `/events/2`
      - `https://현재도메인/events/2`로 가게됨
    - 용도: 내부 페이지 입력할 때
    
  - 절대경로
    
    - 예시: `https://naver.com`
      
    - 유의: `https://` 를 반드시 포함해주셔야 합니다.
    
    - 용도: 외부 사이트 입력할 때
    
      

- 이미지

  - jpg, jpeg, gif, png, svg 포맷 지원



### 이벤트들

통합페이지에 보이는 것들

| 명칭              | 설명                                               | 비고                   |
| ----------------- | -------------------------------------------------- | ---------------------- |
| 이벤트명          | 이벤트 제목                                        |                        |
| 이벤트 설명       | 이벤트 제목 위에 들어갈 이벤트 설명                |                        |
| 배경 색상         | 배경 이미지에 겹쳐질 배경 색상                     |                        |
| image             | 배경 이미지                                        |                        |
| 시작일자          | 이벤트 시작 일자                                   | 24시간제로 입력        |
| 종료일자          | 이벤트 종료 일자                                   | 24시간제로 입력        |
| 링크              | 이벤트 클릭하면 넘어가는 개별 페이지 주소          | 상대경로 또는 절대경로 |
| 공개여부          | 통합페이지에 공개할지 여부. 체크를 해제하면 미공개 |                        |
| 수집하는 개인정보 | 개인정보 약관에 들어감                             |                        |



### 통합페이지 설정

| 명칭            | 설명                                                   | 비고          |
| --------------- | ------------------------------------------------------ | ------------- |
| 첫째줄 헤드라인 | 통합페이지 첫째줄 텍스트                               |               |
| 둘째줄 헤드라인 | 통합페이지 둘째줄 텍스트                               |               |
| 셋째줄 설명글   | 통합페이지 셋째줄 텍스트                               |               |
| 블로그 링크     | 하단의 블로그 버튼을 클릭하면 열릴 블로그 링크         | https:// 포함 |
| 인스타그램 링크 | 하단의 인스타그램 버튼을 클릭하면 열릴 인스타그램 링크 | https:// 포함 |
| 매장찾기 링크   | 하단의 매장찾기 버튼을 클릭하면 열릴 인스타그램 링크   | https:// 포함 |



### 이벤트1 설정

| 명칭        | 설명      | 비고                                                         |
| ----------- | --------- | ------------------------------------------------------------ |
| color       | 배경색상  | - HEX 혹은 RGB 형태 사용 (예: `#ffffff` == `rgb(255, 255, 255)`)<br />- 투명도를 원하는 경우 `rgba(255, 255, 255, 0.1)` 형태로 입력<br />- 그라디언트를 원하는 경우 https://cssgradient.io/ 에서 생성. 단 "background:"와 ";"는 제외하고 입력 |
| image1      | 아래 참고 | 권장 사이즈 535 x 229                                        |
| image2      | 아래 참고 | 권장 사이즈 455 x 79                                         |
| image3      | 아래 참고 | 권장 사이즈 500 x 146                                        |
| image4      | 아래 참고 | 권장 사이즈 457 x 385                                        |
| image_apps  | 아래 참고 | 권장 사이즈 675 x 824                                        |
| image_steps | 아래 참고 | 권장 사이즈 584 x 175                                        |

그외는 아래 사진 참고

![](https://user-images.githubusercontent.com/17509651/105249133-f527c100-5bba-11eb-90ea-6a3a87623e4e.png)

- 이때 이미지 파일은 png 형식이어야 배경이 투명하게 유지됩니다.
- 권장 사이즈는 현재 적용된 이미지의 사이즈일 뿐, 필수가 아닙니다.



### 이벤트1 응모자들

| 명칭            | 엑셀파일에서의 영어 명칭 | 설명                                                |
| --------------- | ------------------------ | --------------------------------------------------- |
| ID              | ID                       | 시스템상 ID (시간순)                                |
| 이름            | name                     | 응모자 이름                                         |
| 휴대폰번호      | phone                    | 응모자 휴대폰 번호                                  |
| app1            | app1                     | FLO                                                 |
| app2            | app2                     | wavve                                               |
| app3            | app3                     | 원스토어북스                                        |
| app4            | app4                     | V컬러링                                             |
| app5            | app5                     | XBOX 게임 패스                                      |
| 네이버 아이디   | naverid                  | 응모자가 제출한 네이버 ID                           |
| 네이버 리뷰 URL | url                      | 응모자가 제출한 URL                                 |
| 제출완료여부    | submitted                | true면 제출 완료                                    |
| created_at      | created_at               | 제출 시각                                           |
| updated_at      | updated_at               | 수정 일자 (수정이 불가하므로 항상 제출 시각과 일치) |
|                 | event_id                 | 항상 1                                              |



### 이벤트2 응모자들

| 명칭         | 엑셀파일에서의 영어 명칭 | 설명                                                         |
| ------------ | ------------------------ | ------------------------------------------------------------ |
| ID           | ID                       | 시스템상 ID (시간순)                                         |
| 이름         | name                     | 응모자 이름                                                  |
| 휴대폰번호   | phone                    | 응모자 휴대폰 번호                                           |
| 선택한 경품  | prize                    | 1: 원스토어북스<br />2: V컬러링<br />3: XBOX 게임 패스<br />4: FLO<br />5: wavve |
| 매장 코드    | shop                     | 응모자가 입력한 매장 코드                                    |
| 제출완료여부 | submitted                | true면 제출 완료                                             |
| created_at   | created_at               | 제출 시각                                                    |
| updated_at   | updated_at               | 수정 일자 (수정이 불가하므로 항상 제출 시각과 일치)          |
|              | event_id                 | 항상 2                                                       |



### 주의사항

- "이벤트들"에서 id가 1, 2인 이벤트는 **절대 삭제하지 말아주세요**. 편집해서 사용해주시기 바랍니다.
- 현재 Heroku 무료 플랜을 사용중이신 관계로 **트래픽이 초과**되면 서버가 다운될 수 있으니, Heroku에 가입한 이메일을 꼭 잘 확인해주셔야 합니다. "[Action Required] - Your app(s) using free dyno hours will stop running soon"라는 제목의 이메일이 오면, https://dashboard.heroku.com/apps/psnm/resources 에서 Change Dyno Type 을 누르시고 그 다음 단계 플랜을 선택해주시면 됩니다. 
- Cloudinary도 마찬가지로 무료 플랜을 사용중이신 관계로 **용량이 초과**되면 더이상 이미지를 업로드하기 어려울 수 있습니다. 하지만 이미지 업로드는 사용자가 아닌 관리자 측에서만 진행되므로 Heroku만큼 이메일을 확인해주실 필요는 없습니다. 용량이 초과될 경우 https://cloudinary.com에 들어가서 플랜을 업그레이드하시거나 기존에 업로드된 사진들을 삭제해주셔야 합니다.
- 문자 인증을 하지 않는 관계로 특정 휴대폰번호를 아무나 제출할 수 있습니다. 그런데 선택하신 중복방지기능이 중복된 휴대폰번호 입력을 차단하는 것이기 때문에, 만약 휴대폰번호 주인이 아닌 사람이 번호를 제출하면, 이후 번호의 진짜 주인은 제출을 못할 수 있습니다.



### 그외 





> 개발 환경 설정 (개발자용)
>
> - `rvm use 2.6.6@my_app_xyz`
> - `bundle exec rails app:update:bin`

