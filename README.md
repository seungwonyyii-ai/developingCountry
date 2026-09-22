# developingCountry

> 개발 선진국이 되는 그날까지! 🚀

### 요약

입금과 출금부터 이자, 환율, 저축액, 수수료까지 계산할 수 있는 간단한 Python 금융 계산기입니다.  
각 기능을 별도의 함수로 구현하고 `main.py`에서 불러와 실행합니다.

### 주요 기능

| 기능 | 함수 | 설명 |
|---|---|---|
| 입금 | `deposit()` | 입금 후 잔액을 계산합니다. |
| 출금 | `withdraw()` | 출금 후 잔액을 계산합니다. |
| 이자 계산 | `calculate_interest()` | 잔액과 이율을 바탕으로 이자를 계산합니다. |
| 환율 계산 | `exchange_money()` | 금액에 환율을 적용합니다. |
| 월 저축액 계산 | `monthly_saving()` | 목표 금액에 필요한 월 저축액을 계산합니다. |
| 수수료 계산 | `calculate_fee()` | 금액과 수수료율로 수수료를 계산합니다. |

### 프로젝트 구조

```text
developingCountry/
├── main.py
├── README.md
└── functions/
    ├── deposit.py
    ├── withdraw.py
    ├── interest.py
    ├── exchange.py
    ├── saving.py
    └── fee.py
```

### 실행 방법

1. 프로젝트 파일을 내려받습니다.
2. 터미널에서 프로젝트 폴더로 이동합니다.
3. 다음 명령어를 입력합니다.

```bash
python main.py
```

### 프로젝트 목표

- 함수를 기능별로 나누어 구현하기
- 다른 파일의 함수를 `import`하여 사용하기
- Git을 활용해 작업 내용 관리하기
- 팀원과 역할을 나누고 하나의 프로그램으로 합치기