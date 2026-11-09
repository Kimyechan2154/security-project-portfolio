# 김예찬 | 정보보안 프로젝트 포트폴리오

국민대학교 정보보안암호수학과에서 진행한 암호 구현, 부채널 분석, 보안 자동화 프로젝트와 실습 코드를 모았습니다.

## 주요 프로젝트

| 프로젝트 | 맡은 일과 결과 | 코드 |
| --- | --- | --- |
| PEPSI AES-128 부채널 방어 경진대회 | 마스킹과 셔플링을 결합한 C 구현의 실행 오버헤드와 일부 파형의 취약점을 분석하고, 수정 후보를 만들어 비교했습니다. 대회 1위를 수상했습니다. | [대회 코드·검증 자료](pepsi-masking.zip) |
| CORE 리버싱 에이전트 | 팀 프로젝트에서 LLM·Solver 파트를 맡아 OpenAI SDK 연동, 풀이 코드 생성, 오류 시 재시도 로직을 구현했습니다. | [SDK 연동 및 독립 구현](core-reversing.zip) |
| 미니 TLS | Python으로 교육용 핸드셰이크와 메시지 암호화 흐름을 구현했습니다. | [보안 프로토콜 실습](security-protocol.zip) |

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

## 관련 저장소

- [학교 프로젝트 및 PEPSI 원본](https://github.com/Kimyechan2154/school)
- [GreenTime JEJU 팀 프로젝트](https://github.com/epoko77-ai/im-not-ai)

## 공개본 범위

확보한 산출물 중 포트폴리오에 쓰는 코드를 골랐습니다. 개인 PC 경로와 실습용 사설 IP는 예시 값으로 바꿨고, 수업 배포 코드의 주석 사본과 로컬 문서 생성에만 쓰던 스크립트는 제외했습니다. 팀 코드의 라이선스와 저작권 표기는 포함된 원문을 확인할 수 있습니다.
