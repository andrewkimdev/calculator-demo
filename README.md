# calculator-demo

HTML/CSS/JavaScript로 만든 공학용 계산기

## 기능

### 기본 연산
- 사칙연산: +, −, ×, ÷
- 괄호 연산
- 거듭제곱: ^ 또는 pow(x,y)

### 삼각함수
- sin, cos, tan

### 지수/로그 함수
- exp (eˣ)
- ln (자연로그)
- log (상용로그)
- sqrt (제곱근)

### 상수
- π (원주율)
- e (자연상수)

## 실행 방법

```bash
# 로컬 서버 실행
python -m http.server 8080

# 또는
npx serve .
```

브라우저에서 http://localhost:8080 접속

## 사용 예시

| 입력 | 결과 |
|------|------|
| `sin(π/2)` | 1 |
| `exp(1)` | 2.718... |
| `pow(2,3)` | 8 |
| `2^3` | 8 |
| `sqrt(16)` | 4 |
| `log(100)` | 2 |
| `ln(e)` | 1 |
