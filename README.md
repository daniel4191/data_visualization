## 1.개발환경
<hr>
<br>
- 언어 python(3.8.2), ipython 8.4.0, json5 0.9.6, jsonschema 4.16.0<br>
- 라이브러리: pandas 1.4.4, googlemaps 4.7.3, folium 0.14.0

## 2.이 레파지토리의 목적
<hr>
<br>
아내와 함꼐 경상도 및 부산 여행을 가기전에 5일간의 일정동안, 돌아다녀야할 곳을 리스트업을 했습니다.<br>
하지만 방문해야할 곳이 너무 많고, 너무 위치가 제각각이라 짜임새있게 돌아다니는 것이 단순히 주소만 보고 판별을 하기에는 한계가 있더라구요.<br>
이 한계를 극복하기 위해서 주소에 대한 시각화를 했습니다.<br>
결과적으로 시각화하고나선 경로를 짜는데 20분도 안걸렸으며 더 이상 정리할 필요도 없었습니다.


## 3.포트폴리오 설명
<hr>
<br>
기본적으로 메인코드는 data_visualization.ipynb에 들어있으며 각각의 jupyter notebook 탭에 주석처리로 설명이 되어있습니다.<br>
json은 아직 명확히 다룰줄 몰랐고, 사실상 시간이 지난 후 해당 json파일은 서울에 관련된 위도 경도 정보가 집약되어있는것이므로 생략해도 무방할듯 합니다.<br>
실제로 시연해보고 싶으시다면 구글에서 발급받는 api 키를 입력하셔야 작동이 됩니다.<br>
가장 포인트가 되는것이 여행지의 타입 구분이였습니다. 그래야 비슷한 지역에서도 동선을 짜기에 명확하다고 판단했기 때문입니다.<br>
여행지는 파랑, 식사장소는 빨강, 카페는 보라, 숙소는 노랑 색으로 핀처리를 했으며 각각의 핀을 눌렀을때는 해당 위치의 상호명이 뜨게끔 작업했습니다.<br><br>

## 4.포트폴리오 스크린샷
<hr>
<br>
<img src="https://user-images.githubusercontent.com/93903127/208009033-d68b9120-87f0-49d8-8d18-ec5c081e56ca.png" style="width: 500px;" alt="screen_shot1">
<img src="https://user-images.githubusercontent.com/93903127/208009056-11dc40a8-a810-4842-bc11-59a78c62408e.png" style="width: 500px;" alt="screen_shot2">
<img src="https://user-images.githubusercontent.com/93903127/208009064-5002d213-bf7e-4311-bf16-3dd3ae18f412.png" style="width: 500px;" alt="screen_shot3">
<hr>
완성은 2022년 8월 15일즈음에 완료하여 블로그에 업로드하였으나, 깃에 옮기는 것이 늦어짐
<br>
writted in 16/Dec/2022