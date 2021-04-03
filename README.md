# Amazon Lookout for Vision 워크샵

Amazon Lookout for Vision은 컴퓨터 비전 (CV)을 사용하여 시각적 표현에서 결함과 이상을 발견하는 기계 학습 (ML) 서비스입니다. Amazon Lookout for Vision을 사용하면 제조 회사는 대규모 객체 이미지 간의 차이점을 빠르게 식별하여 품질을 높이고 운영 비용을 줄일 수 있습니다. 이 워크샵은 Lookout for Vision 모델을 교육하고 호스팅하기 위해 boto3 python SDK를 사용하는 예제를 처음부터 끝까지 실행합니다. 콘솔 전용 시작 안내서로 https://docs.aws.amazon.com/lookout-for-vision/latest/developer-guide/getting-started.html을 참조하세요.

## 단계:

1. 다음의 Cloudformation 템플릿을 실행합니다 - [<img src="https://s3.amazonaws.com/cloudformation-examples/cloudformation-launch-stack.png">](https://console.aws.amazon.com/cloudformation/home?region=us-east-1#/stacks/new?stackName=l4vworkshopstack&templateURL=https://shreyasvathul.s3.us-east-2.amazonaws.com/SampleLFVTemplate2.yaml)
(위치가 us-east-1인지 확인하세요.)

2. Navigate to SageMaker on your AWS console and click Notebook instances on the side menu

3. Click "Open Jupyter" as shown below 
![](openjupyter.png)

4. Click to open the "Amazon Lookout for Vision Lab.ipynb" notebook 
<img src="insidejupyter.png" width="50%">

4. Follow instructions in the notebook to complete the lab

5. As you go through steps in the notebook, notice changes in the console, specifically when: 

- Creating a project
- Creating a dataset
- Training your model
- Evaluating your model
- Using your model
