# Kpro - High Quality Korean Test Question Dataset
___
## About Kpro
**Kpro**는 '인사혁신처 사이버국가고시센터'에서 제공하는 '국가공무원 필기시험 문제' 데이터를 정형화하여, 언어 모델(Language Model) 학습 등에 활용할 수 있도록 제공하는 오픈소스 프로젝트입니다.


## Data description

각 파일은 `where`, `subject`, `question`, `choices`, `answer`, `question_type`, `question_positive`의 columns으로 구성되어있습니다. (.tsv)
- `where`: 해당 문제의 출처
- `subject`: 과목 명
- `question`: 문제 및 제시문
- `choices`: 문제 선택지
- `answer`: 정답 번호(One-index)
- `question_type`: 문제 유형 (`describe, choose_all, choose, list, connect, blank`)
- `question_positive`: 문제 설명이 옳은 것(긍정)을 고르는 지의 여부(`1, -1, 0`)


## Current Progress
#### 2023.05.27
2023년도 국가공무원 9급 문제 수록
