# Amazon Lookout for Vision 워크샵

Amazon Lookout for Vision은 컴퓨터 비전 (CV)을 이용하여 시각적 표현에서 결함과 이상을 발견하는 기계 학습 (ML) 서비스입니다. Amazon Lookout for Vision을 사용하면 제조 회사는 대규모 객체 이미지 간의 차이점을 빠르게 식별하여 품질을 높이고 운영 비용을 줄일 수 있습니다. 본 워크샵은 Lookout for Vision 모델을 교육하고 호스팅하기 위해 boto3 python SDK를 사용하는 예제를 처음부터 끝까지 수행해봅니다. 콘솔 전용 시작 안내서로 https://docs.aws.amazon.com/lookout-for-vision/latest/developer-guide/getting-started.html 을 참조하세요.

## 단계:

1. 우선 다음의 Cloudformation 템플릿을 실행합니다 - [<img src="https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png">](https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/new?stackName=l4vworkshopstack&templateURL=https://shreyasvathul.s3.us-east-2.amazonaws.com/SampleLFVTemplate2.yaml)
(위치가 us-east-1인지 확인하세요.)

2. AWS 콘솔에서 SageMaker로 이동하여 측면 메뉴에서 노트북 인스턴스를 클릭합니다

3. 아래와 같이 "Open Jupyter" 버튼을 클릭합니다
![](openjupyter.png)

4. "Amazon Lookout for Vision Lab.ipynb" 노트북을 클릭해서 여세요
<img src="insidejupyter.png" width="50%">
5. 노트북 지침을 따르며 예제를 완료하세요

6. 노트북 단계를 진행하면서 특히 다음의 경우 콘솔에서 변경 사항을 확인합니다. 

- 프로젝트 생성 
- 데이터셋 생성 
- 모델 훈련 
- 모델 평가
- 모델 적용
