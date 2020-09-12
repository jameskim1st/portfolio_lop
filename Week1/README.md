# Process Mining
- Process 수행에 관한 event log 데이터를 기반으로 실제 비즈니스 프로세스를 발견하고 분석하는 기술

![processmining](https://m.blog.naver.com/2011topcit/90181758724?view=img_1)

## Process Mining의 입력 데이터
- Event log의 구조
- 필수 속성 (3가지)
- 선택(추가) 속성

### Event log의 구조
- Process Mining은 입력 data 구조를 가지는 event log만 확보되면 수행 가능

### 필수 속성
1. Case ID : 각각의 event는 Case ID를 통해 하나의 Case(프로세스 인스턴스)에 연결
2. Activity : Activity는 분석대상 프로세스의 한 단계(step)를 나타냄
3. Time Stamp : Activity가 수행된(즉, event가 발생한) 시점을 나타내는 time stamp속성을 Event log에 포함해야 함

### 선택(추가) 속성
- 선택 속성은 제기된 질문들에 답할 때 적절하게 활용되어야 함
- **가능하다면 분석의 가치를 높이고 통찰력 발견에 도움을 줄 수 있는 많은 선택 속성들을 포함하는 것이 바람직함**
