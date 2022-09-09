# 2022 KMU Autonomous Driving Contest
![KakaoTalk_20220905_123213452](https://user-images.githubusercontent.com/86957779/188356066-86a6b1a5-ec2c-40ee-a062-2954adb32ee6.jpg)

# 개선 점
* 곡선구간의 차선인식 개선, 차선이 1개만 인식됬을 경우의 알고리즘 개선 방법
> 인공지능 기반, 차선 인식 모델 찾아서 하는 것을 추천, 이에따른 곡률 계산과 각도 계산, Stanley Method는 코드 참고
* 평행주차를 위한 현재 위치 인식 및 경로 및 궤적 생성, 이에 따른 경로 추종
> SLAM, AMCL로 현재 위치 추정, 맵 상에서의 Waypoint를 기록하여 이에 따른 궤적을 생성하고 추종하는 알고리즘 제작 필요
