# 김예찬 | 정보보안 프로젝트 포트폴리오

국민대학교 정보보안암호수학과에서 진행한 암호 구현, 부채널 분석, 보안 자동화 프로젝트와 실습 코드를 모았습니다.

## 대표 프로젝트

| 프로젝트 | 맡은 일과 결과 | 코드 |
| --- | --- | --- |
| **PEPSI AES-128 부채널 방어 경진대회** | C로 구현한 AES 마스킹·셔플링 코드의 실행 오버헤드와 일부 파형의 정보 누출을 분석했습니다. 수정 후보를 만들어 비교했고, 대회에서 1위를 했습니다. | [마스킹 소스](https://github.com/Kimyechan2154/school/blob/main/PEPSI/Masking/masking.c) · [경진대회 후보 및 검증 자료](pepsi-masking.zip) |
| **CORE 리버싱 에이전트** | 팀 프로젝트에서 LLM·Solver 파트를 맡아 OpenAI SDK 연동, 풀이 코드 생성, 오류 시 재시도 로직을 구현했습니다. | [담당 코드 및 모의 테스트](core-reversing.zip) |
| **미니 TLS** | Python으로 교육용 핸드셰이크와 메시지 암호화 흐름을 구현했습니다. | [프로토콜 소스](security-protocol.zip) |

## GitHub에서 바로 볼 수 있는 코드

| 프로젝트 | 코드에서 볼 수 있는 내용 | 소스 |
| --- | --- | --- |
| **AES CPA·DPA 분석 도구** | CPA는 AES 중간값의 해밍 가중치와 전력 파형의 Pearson 상관계수로 키 후보를 비교합니다. DPA는 파형을 두 그룹으로 나눠 평균 차이를 계산합니다. | [CPA](https://github.com/Kimyechan2154/school/blob/main/PEPSI/CPA/main.c) · [DPA](https://github.com/Kimyechan2154/school/blob/main/PEPSI/DPA/main.c) |
| **Enigma 로터 암호기** | 북악스터디에서 C로 구현했습니다. 단어 단위 입력을 문장 단위로 확장해 공백과 문장부호를 보존하고, 로터 회전과 더블 스테핑을 구현했습니다. | [C 소스](https://github.com/Kimyechan2154/school/blob/main/anigma/main.c) |
| **AES 구현 방식 비교 웹 실습** | JavaScript로 AES 라운드의 중간값을 단계별로 보여주고, T-table·Bitslicing·AES-NI·Masking의 차이를 실습 패널에서 설명합니다. | [프로젝트](https://github.com/Kimyechan2154/aes-implementation-methods) · [JavaScript](https://github.com/Kimyechan2154/aes-implementation-methods/blob/main/dist/app.js) |
| **AES 기본 구현 및 하이딩 실습** | C로 작성한 AES 라운드와 키 스케줄, 더미 연산과 처리 순서 섞기를 적용한 하이딩 실습을 볼 수 있습니다. | [AES 기본 구현](https://github.com/Kimyechan2154/school/blob/main/PEPSI/AES-8bit/aes_impl.c) · [하이딩](https://github.com/Kimyechan2154/school/blob/main/PEPSI/Hiding/hiding.c) |

## 전체 코드

각 ZIP을 내려받아 압축을 풀면 프로젝트 폴더와 코드가 나옵니다. 실행 방법과 검증 기록은 포함된 각 프로젝트의 README를 참고하세요.

| 코드 묶음 | 내용 |
| --- | --- |
| [ai-security.zip](ai-security.zip) | Pandas와 분류 성능지표 Jupyter 실습 |
| [core-reversing.zip](core-reversing.zip) | OpenAI SDK 연동 예제, 풀이 코드 생성 및 재시도 로직, 모의 테스트 |
| [lea-analysis.zip](lea-analysis.zip) | LEA-128 시뮬레이션과 CPA·DPA 분석 실험 |
| [pepsi-labs.zip](pepsi-labs.zip) | CPA 로컬 실습, 웹 데모 및 하이딩 실습 웹앱 |
| [pepsi-masking.zip](pepsi-masking.zip) | AES-128 마스킹·셔플링 후보, 검증 스크립트, ROUND1·FULL HEX |
| [security-audit.zip](security-audit.zip) | 5G/Linux 및 DBMS 보안 점검 스크립트 |
| [security-protocol.zip](security-protocol.zip) | 미니 TLS 및 Python 소켓 실습 |
| [security-software.zip](security-software.zip) | GF(2⁸), 행렬 연산, HW1 실습 |
| [web-learning.zip](web-learning.zip) | TypeScript 타입 단언·타입 가드 실습 |

## 공개본 범위

확보한 산출물 중 포트폴리오에 쓰는 코드를 골랐습니다. 개인 PC 경로와 실습용 사설 IP는 예시 값으로 바꿨고, 수업 배포 코드의 주석 사본과 로컬 문서 생성에만 쓰던 스크립트는 제외했습니다. 팀 코드의 라이선스와 저작권 표기는 포함된 원문을 확인할 수 있습니다.
