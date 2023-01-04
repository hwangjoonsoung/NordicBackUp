### 개발환경
- Spring boot
- Gradle
- JSP
- Mybatis
- Mysql
</p>

### <p><b>프로젝트 개요</b>
nordic은 rest api를 이용한 노르딕워킹 동호회 웹 어플리케이션 입니다<br>
이용자는 미션을 수행하는 것으로 포인트를 적립할 수 있고 <br>
그 포인트로 상품을 구매할 수 있습니다.<br>

### <p><b>프로젝트 담당</b>
스웨거<br>
![스크린샷_20230103_012131](https://user-images.githubusercontent.com/103257619/210304675-8ad9089f-6bb0-44c5-a15f-db93a55dee06.png)<br>
미션 등록<br>
![스크린샷_20230103_011107](https://user-images.githubusercontent.com/103257619/210304462-8de71d3a-3310-4955-bd13-048bdbcaa3ab.png)<br>
미션 목록 / 검색<br>
![스크린샷_20230103_011220](https://user-images.githubusercontent.com/103257619/210304509-904805d3-fe66-477d-904b-e0d87ffa4760.png)<br>
상세 미션<br>
![스크린샷_20230103_011236](https://user-images.githubusercontent.com/103257619/210304634-42b48866-9587-4ec8-ad0f-f035db251c6c.png)<br>
미션 삭제<br>
![스크린샷_20230103_011244](https://user-images.githubusercontent.com/103257619/210304636-4ecff629-6738-4f55-a84c-5f9ac16cac46.png)<br>
미션 수정<br>
![화면 캡처 2023-01-03 131111](https://user-images.githubusercontent.com/103257619/210304645-23edf965-b44d-43c5-8e23-0c6ca9ba5b3a.png)<br>

### <p><b>프로젝트 회고</b>
1. spring security를 해보고싶었는데 못했던 점...<br>
2. 한번의 요청으로 image를 다수로 불러오고 싶었는데 실패...<br>
3. DB 정규화 : 직렬화를 통해 1:N관계인 DB를 1:1로 변경함...<br>
4. 리펙토링 하는 과정애서 필요없는 부분을 삭제를 한해서 스파게티코드가 되어버...<br>
5. 하나의 문제에 너무 많은 시간을 할애함...<br>

### <p><b>프로젝트 작업 file</b>
-controller<br>
https://github.com/hwangjoonsoung/RestNordic/tree/develop/src/main/java/com/nordic/api/missionmaster<br>
-service<br>
https://github.com/hwangjoonsoung/RestNordic/tree/develop/src/main/java/com/nordic/service/missionmaster<br>
-dao<br>
https://github.com/hwangjoonsoung/RestNordic/tree/develop/src/main/java/com/nordic/repository/missionmasterrepo<br>
-dto<br>
https://github.com/hwangjoonsoung/RestNordic/tree/develop/src/main/java/com/nordic/dto/missionmasterbean<br>
-config<br>
swagger : https://github.com/hwangjoonsoung/RestNordic/blob/develop/src/main/java/com/nordic/config/SwaggerConfig.java<br>
cors : https://github.com/hwangjoonsoung/RestNordic/blob/develop/src/main/java/com/nordic/config/security/CorsConfig.java<br>

### <p><b>snyk</b>
![image](https://user-images.githubusercontent.com/103257619/207895324-aea6a020-1e23-4ba5-b4da-d672a45b4d7c.png)  
snyk돌렸는데 발생한 보안취약점...insight는 못해봤다. fixed in이 알려준대로 했는데 빌드 불가능... 해결하자

### <p><b>front</b>
https://github.com/hwangjoonsoung/RestNordicFront  
