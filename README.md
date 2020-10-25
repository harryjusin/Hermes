# [Project Mercury]
***

사회적 거리두기를 위한 공석 인디케이터 제작 프로젝트

by _양선형,오승준,장원준,정주신,조수환_

## Project Mercury는 무엇인가요?

2020년,코로나바이러스-19가 확산되면서 사회적거리두기가 실시되고 있습니다.

단체급식시설에서 가림막을설치하고,이러한 여유가없는곳은 물리적으로 거리를 두어 대응하고 있죠.


제가 다니고있는 학교의 급식실에서는 한테이블에 한줄만,한칸씩 띄워 앉고있습니다.


이로인해 인원대비 사용가능한 자리가 줄어들었고 빈자리를 찾는 것 또한 혼잡해졌습니다.


이를 해결하고자 OpenCV를 이용하여 실시간 이미지 프로세싱을 통해 빈자리를 알아내고


최종적으로 ***사용가능한 좌석을 표시*** 하는것이 해당 프로젝트의 목표입니다!


그래서 전령의 신 헤르메스에서 따온 이름입니다. ***Project Mercury!***

### 어떻게 만들어 지나요?
계획은 이렇습니다.

* Pytoch+YOLO5를 이용하여 물체인식을합니다. 저희가 필요한 정보는 책상,사람,식판 정도가 되겠지요.

  아마 이부분에서 머신러닝이 들어가지 않을까 싶습니다.아니면 aruco marker를 이용할수도 있구요.

* 이후 책상 하나를 그룹화시켜 1그룹안에 몇명이 앉아있어야 하는지, 지금은 몇명이 앉아있는지 확인합니다.

* 이러한 그룹들의 정보를 모아,최종적으로 LED메트릭스,혹은 디스플레이에 투사시킵니다.

> 참쉽죠?

***

