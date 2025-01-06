# AIFFEL_quest_rs
- 맹성찬이 AIFFEL에서 수행하는 퀘스트를 위한 레파지토리입니다.
- 레포지토리 구조도를 작성합니다.   
  - 레포지토리의 구조는 배포된 과정별 시간표를 참고합니다.
    - MainQuest폴더는 공통, 나머지는 C퀘스트가 있는 파트를 기준으로 폴더를 구성합니다.
    - 예를들어 코어의 경우 MainQuest, Python, Fluttet, Exploration 네 개의 폴더를 구성합니다.
    - 리서치의 경우 MainQuest, Exploration, GoingDeeper 세 개의 폴더를 구성합니다.
    - 각 폴더의 하위에 퀘스트 갯수만큼 폴더를 추가해야 하고, 각각의 하위 폴더는 .ipynb파일과 README.md파일을 포함해야 합니다.
    - 주의: 시간표에 따라 달라질 수 있으니 시간표 참고!!
```
# 디렉토리 구조는 본 코드블럭을 참고하여 작성합니다.
# README파일에 작성할 땐 bash코드펜스에 넣어야 구조를 볼 수 있습니다 :)
AIFFEL_quest_rs
├── MainQuest
│   ├── Main_QUEST_01
│   │   ├── .ipynb
│   │   └── README.md
.		.
.		.
.		.
│   └── Main_QUEST_05
│       ├── .ipynb
│       └── README.md
.
.
.
├── Exploration
│   ├── EXPLORATION_01
│   │   ├── .ipynb
│   │   └── README.md
│   .
│   .
│   .
│   └── EXPLORATION_07
│       ├── .ipynb
│       └── README.md
.
.
.
└── GoingDeeper
    ├── GOINGDEEPER_01
    │   ├── .ipynb
    │   └── README.md
    .
    .
    .
    └── GOINGDEEPER_09
        ├── .ipynb
        └── README.md
```
