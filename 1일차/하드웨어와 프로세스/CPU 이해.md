# CPU 이해

## 내부 구조

| 구성요소 | 역할 |
|---------|------|
| ALU | 산술/논리 연산 수행 |
| CU | 명령어 해석, 제어 신호 전달 |
| 레지스터 | CPU 내부 초고속 임시 저장 |

## 주요 레지스터
| 레지스터 | 역할 |
|---------|------|
| PC (Program Counter) | 다음 명령어 주소 |
| IR (Instruction Register) | 현재 명령어 저장 |
| SP (Stack Pointer) | 스택 최상단 주소 |

## 명령어 처리 사이클
 Fetch - Decode - Execute - Write Back
 인출     해석      실행       저장

 ## 클록 속도
- 1GHz = 초당 10억 사이클
- 클록↑ = 더 많은 명령어 처리 가능

> 💡 CPU는 Fetch→Decode→Execute 사이클을 반복하며 명령어를 처리한다.