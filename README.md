중간고사: 클러스터링 분석 문제
학습관리시스템에 자신의 Python 코드와 데이터 파일이 저장된 github classroom repository link를 제출하시오 (코드는 github codespace에서 실행되어야 함)
과제 마감: 04.26 (금) 15:00

목표: Python과 scikit-learn을 사용하여 클러스터링 분석을 수행하여 데이터에 숨겨진 그룹을 발견합니다.

문제 정의 및 데이터 선택:
* 		문제 정의: 범죄 발생 시간대 및 요일 데이터를 클러스터링하여 범죄가 가장 많이 발생하는 시간대와 요일 패턴을 분석
    * 클러스터링을 사용하여 해결하고자 하는 자신만의 문제를 정의하세요. 예를 들어, 소비자 행동 분석, 지역별 인구 분포 분석, 교통 데이터를 통한 출퇴근 패턴 분석 등이 있을 수 있습니다.
    * 문제 정의에는 분석하고자 하는 목적과 예상되는 결과를 포함해야 합니다.
* 		데이터 선택: 경찰청_범죄 발생 시간대 및 요일 (https://www.data.go.kr/data/3074459/fileData.do)
    * 대한민국 공공 데이터 포털 https://www.data.go.kr/에서 문제 해결에 적합한 데이터셋을 찾으세요.
    * 선택한 데이터셋의 구조와 해당 데이터가 문제 해결에 어떻게 도움이 될 수 있는지 설명하세요.

데이터 전처리 및 클러스터링 수행:
    * 데이터 전처리:
    * 데이터를 로드하고 필요한 경우 결측치 처리, 데이터 정규화, 변수 선택 등의 전처리 작업을 수행하세요.
    * K-means 클러스터링 적용:
    * K-means 클러스터링 알고리즘을 사용하여 데이터를 클러스터링하세요.
    * 엘보우 방법을 사용하여 최적의 클러스터 수, K를 결정하고, 클러스터 수에 따른 WCSS를 그래프로 나타내세요.
    * 결정된 K 값으로 K-means 알고리즘을 초기화하고 클러스터링을 수행하세요.

결과 분석 및 평가:
* 		클러스터 분석:
    * 각 클러스터의 중심점을 분석하고, 중심점을 바탕으로 각 클러스터의 특성을 설명하세요.
    * 클러스터를 시각화하여 각 클러스터가 어떻게 구성되어 있는지 보여주는 산점도를 작성하세요.
* 		평가:
    * 실루엣 점수를 사용하여 클러스터링의 효과를 평가하세요. 실루엣 점수가 클러스터링 결과에 대해 어떤 정보를 제공하는지 설명하세요.

필수 사항:
* 해결책은 Visial Studo의 Jupyter Notebook에서 구현해야 합니다.
* 수행하는 단계를 설명하기 위해 코드에 적절한 주석을 달아야 합니다.
* 모든 플롯과 시각화는 결과 해석과 함께 포함되어야 합니다.

