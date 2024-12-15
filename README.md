# CAPM(Certified Associate in Project Management) 자격증 도우미

CAPM 도우미는 프로젝트 관리의 기초를 학습하고 시험 준비를 지원하기 위한 도구와 자료를 제공합니다. 이 프로젝트는 CAPM 자격증 취득을 목표로 하는 학습자에게 실질적인 도움을 제공합니다.

---

## **목차**

1. [CAPM 자격증 개요](#capm-자격증-개요)
2. [학습 전략](#학습-전략)
3. [CAPM 실습 및 도구](#capm-실습-및-도구)
4. [CAPM 도우미 기능](#capm-도우미-기능)
5. [폴더 및 파일 구조](#폴더-및-파일-구조)
6. [기여 방법](#기여-방법)
7. [라이선스](#라이선스)
8. [문의](#문의)

---

## **CAPM 자격증 개요**

### 주요 정보
- **주관 기관**: PMI(Project Management Institute)
- **시험 언어**: 영어, 한국어 등
- **시험 형식**: 150문항, 다지선다형, 3시간
- **합격 기준**: 점수는 공개되지 않으며 PMI의 내부 기준에 따라 평가됨.
- **자격 요건**:
  - 고등학교 졸업(또는 이에 준하는 학력)
  - 23시간의 프로젝트 관리 교육 수료

### 시험 내용
- PMI의 PMBOK® Guide 기반으로 출제
- 5가지 주요 프로세스 그룹 및 10가지 지식 영역 포함:
  - **프로세스 그룹**: 시작, 계획, 실행, 감시 및 통제, 종료
  - **지식 영역**: 통합, 범위, 일정, 비용, 품질, 자원, 커뮤니케이션, 리스크, 조달, 이해관계자 관리

---

## **학습 전략**

### 학습 자료
- **공식 교재**:
  - PMBOK® Guide (Project Management Body of Knowledge)
- **추천 참고서**:
  - CAPM Exam Prep by Rita Mulcahy
  - CAPM 공식 연습 문제집

### 학습 계획
| 주차  | 학습 내용                      | 주요 활동                                           |
|-------|--------------------------------|-----------------------------------------------|
| 1주차 | 프로젝트 관리 개요              | PMBOK® Guide Chapter 1~2 읽기, 요약 정리         |
| 2주차 | 프로젝트 환경 및 조직 구조       | 기업 거버넌스와 프로젝트 라이프사이클 학습       |
| 3주차 | 프로젝트 관리 프로세스          | 5가지 프로세스 그룹별 활동 정리                 |
| 4주차 | 프로젝트 통합 및 범위 관리       | 범위 정의 및 요구사항 수집 사례 학습            |
| 5주차 | 프로젝트 일정 및 비용 관리       | 일정 관리 도구 실습(MS Project, Gantt 차트)     |
| 6주차 | 품질, 자원 및 커뮤니케이션 관리  | 품질 관리 사례, 커뮤니케이션 계획 실습          |
| 7주차 | 리스크, 조달 및 이해관계자 관리  | 리스크 식별 및 완화 전략 사례 분석              |
| 8주차 | 공식 문제 풀이 및 모의시험       | 연습 문제 풀이, 시험 시간 관리 연습             |

---

## **CAPM 실습 및 도구**

### 프로젝트 관리 도구 실습
1. **MS Project**:
   - 프로젝트 일정 작성 및 Gantt 차트 생성
   - 자원 할당 및 과제 추적

2. **Trello / Jira**:
   - 애자일 방식의 간단한 프로젝트 관리
   - 작업 보드 활용

3. **Excel**:
   - 리스크 로그와 커뮤니케이션 매트릭스 작성

---

## **CAPM 도우미 기능**

### 1. 요약 자료 생성기
- 프로젝트 관리 주제에 대한 간단한 요약 제공
  ```python
  def generate_summary(topic):
      summaries = {
          "project_scope": "범위 관리는 프로젝트의 요구사항을 정의하고 범위를 문서화하며 관리하는 프로세스입니다.",
          "risk_management": "리스크 관리는 프로젝트의 불확실성을 식별하고 분석하며 대응 전략을 개발하는 것입니다.",
          "stakeholder_management": "이해관계자 관리는 프로젝트 성공에 영향을 미치는 개인 또는 그룹을 식별하고 관리하는 활동입니다."
      }
      return summaries.get(topic, "해당 주제에 대한 요약이 없습니다.")

  print(generate_summary("project_scope"))
  ```

### 2. 연습 문제 생성기
- 도메인별 연습 문제 생성:
  ```python
  def generate_practice_question(domain):
      questions = {
          "1": "프로젝트 관리의 5가지 프로세스 그룹은 무엇인가요?",
          "2": "프로젝트 라이프사이클의 주요 특징을 설명하세요.",
          "3": "WBS(Work Breakdown Structure)의 목적은 무엇인가요?",
          "4": "프로젝트 리스크를 식별하는 주요 기법은 무엇인가요?",
          "5": "이해관계자 분석에서 RACI 차트의 구성 요소를 설명하세요."
      }
      return questions.get(domain, "올바른 도메인을 입력하세요.")

  print(generate_practice_question("3"))
  ```

### 3. 시험 시뮬레이션
- CAPM 시험 환경을 반영한 모의시험 제공:
  - 150문항, 3시간 제한
  - 문제 풀이 후 정답 및 해설 제공

### 4. 학습 일정 생성기
- 사용자 입력에 따라 맞춤형 학습 계획 작성:
  ```python
  def create_study_plan(duration_weeks):
      topics = [
          "프로젝트 관리 개요", "프로젝트 환경 및 조직 구조",
          "프로세스 그룹", "통합 및 범위 관리", "일정 및 비용 관리",
          "품질, 자원 및 커뮤니케이션 관리", "리스크, 조달 및 이해관계자 관리"
      ]
      weekly_plan = {f"Week {i+1}": topic for i, topic in enumerate(topics[:duration_weeks])}
      return weekly_plan

  print(create_study_plan(6))
  ```

---

## **폴더 및 파일 구조**

```
CAPM_Helper/
├── README.md               # 프로젝트 설명서
├── src/                    # 소스 코드 디렉터리
│   ├── helpers.py          # 요약 및 연습 문제 생성기
│   ├── simulator.py        # 모의시험 생성기
├── resources/              # 학습 자료 및 연습 문제
│   ├── project_scope.md    # 범위 관리 요약
│   ├── risk_management.md  # 리스크 관리 요약
├── tests/                  # 테스트 스크립트
│   ├── test_helpers.py     # 헬퍼 테스트
│   ├── test_simulator.py   # 모의시험 테스트
└── requirements.txt        # 의존성 파일
```

---

## **기여 방법**

1. 저장소를 포크:
   ```bash
   git clone https://github.com/your-repo/capm-helper.git
   cd capm-helper
   ```
2. 새로운 브랜치 생성 후 수정:
   ```bash
   git checkout -b feature-name
   ```
3. 브랜치 푸시:
   ```bash
   git push origin feature-name
   ```
4. 풀 리퀘스트 열기.

---

## **라이선스**

이 프로젝트는 MIT 라이선스에 따라 배포됩니다.

---

## **문의**

질문이나 피드백은 **[your-email@example.com](mailto:your-email@example.com)**으로 연락주세요.

