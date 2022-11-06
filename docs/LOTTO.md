# 🚀 3단계 - 로또(자동)

## 로또 번호 생성기(LottoNumberGenerator)

- 로또 번호 후보는 1 ~ 45 이다.
- 로또 한 장에는 6개의 번호가 들어간다.

## 구입 금액 입력받기

- 로또 한 장의 가격은 1000 원이다.
- 구매하고 남은 금액이 1000 원보다 작다면 로또를 구매할 수 없다.

## 당첨 번호 입력기

- 총 6 개의 번호를 입력 받는다.

## 당첨 통계 보여주기

- 구매할 때 발급받은 로또 번호와 당첨 번호를 비교해서 일치 개수 별로 당첨금과 개수를 계산한다.
    - 3개 일치하면 당첨금은 5000 원이다.
    - 4개 일치하면 당첨금은 50000 원이다.
    - 5개 일치하면 당첨금은 150000 원이다.
    - 6개 일치하면 당첨금은 2000000000 원이다.
- 번호 일치 개수 멸로 로또 장 수를 계산해서 최종적으로 수익률을 소수점 두 자리까지 표시하는 실수로 나타난다.
    - 수익률은 (사용자가 입력한 구입 금액)/(당첨금 총 합) 값이 된다.

