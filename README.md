# AWS_Visualization

## Amazon QuickSight를 사용하여 데이터 시각화

이 프로젝트에서는 Amazon S3 및 Amazon Quicksight를 사용하여 대규모 데이터 세트에서 시각화를 생성하는 방법을 알아봅시다.
Amazon.com에서 가장 잘 팔리는 50,000개 제품의 데이터 세트를 사용하여 작업할 진행한다.

### 1단계: 데이터 세트 다운로드
- "Amazon Bestseller Dataset" CSV 파일과 "manifest.json" 파일을 다운로드


### 2단계: Amazon S3에 데이터 세트 저장

- Amazon S3 콘솔을 열고 "버킷 생성"을 선택
- 버킷 이름을 지정하고(예: "plintan-amazon-project-visualization") 설정을 기본값으로 유지
- CSV 파일과 "manifest.json" 파일을 버킷에 업로드
- "manifest.json" 파일의 URL을 데이터세트의 S3 URL로 변경

![image](https://github.com/plintAn/AWS_Visualization/assets/124107186/fba3f05e-9e83-4d0a-9b80-072eec407af7)


### 3단계: S3 버킷을 Amazon Quicksight와 연결

- AWS 관리 콘솔을 열고 Amazon Quicksight로 이동
- 계정이 없다면 Enterprise 버전의 무료 평가판에 등록
- Amazon S3를 선택하고 생성한 S3 버킷 상자를 선택
- "manifest.json" 파일에 대한 링크를 입력하고 Quicksight에 연결
- 시각화 생성을 시작하려면 "대화형 시트"를 선택

- ![image](https://github.com/plintAn/AWS_Visualization/assets/124107186/2148b8e2-4f2b-4226-a742-ab8eb645569c)

### 4단계: 시각화 만들기

- 필드를 그래프로 끌어 시각화(예: 가장 인기 있는 브랜드)를 생성
- 원하는 대로 그래프를 정렬, 필터링 및 사용자 정의
- 막대 차트, 원형 차트, 선 그래프 등과 같은 다양한 유형의 그래프를 사용 가능하다

![AWS_Quick1](https://github.com/plintAn/AWS_Visualization/assets/124107186/9c28ba11-03a0-4b6e-a712-e7e187a83c9c)

Output

![AWS_Quick3](https://github.com/plintAn/AWS_Visualization/assets/124107186/c4557de8-5659-48ff-9598-9c1c975eeac8)



