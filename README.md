# DeepFake Detection (2023.04. - 2023.09.)

교내 캡스톤 디자인 프로젝트로 진행했던 딥페이크 탐지 프로젝트입니다.

이미지 또는 비디오(영상) 프레임에서 딥페이크 유무를 판별하여 사용자에게 딥페이크 확률을 계산하여 보여줍니다.

--- 
# Flow Chart
![image](https://github.com/PaulHwang98/DeepfakeDetection/assets/164970413/0e38af43-b694-4696-ae17-0d53f087cbbc)

입력이 비디오 또는 이미지냐에 따라 서비스 흐름이 분기됩니다.

---
또한 아래와 같이 간단한 웹 어플리케이션을 제작하여 브라우저를 통해 결과를 확인할 수 있도록 하였습니다.

![image](https://github.com/PaulHwang98/DeepfakeDetection/assets/164970413/96dce215-9080-4745-915d-776fa192fad6)

![image](https://github.com/PaulHwang98/DeepfakeDetection/assets/164970413/ab7c9043-d32e-4918-bb5b-4c6918d04cd3)

백엔드 프레임워크로 Django를 사용하였습니다.

--- 
# 데이터 셋
AIHub의 한국인 딥페이크 변조 영상에서 프레임을 캡쳐하여 원본 이미지 25,000장, 변조 이미지 25,000장을 학습 및 검증 데이터로 사용하였습니다.
- https://www.aihub.or.kr/aihubdata/data/view.do?currMenu=&topMenu=&aihubDataSe=data&dataSetSn=55
--- 
# 모델
