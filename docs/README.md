# 기능 구현 
## 1. 구입 금액 입력
* ~~1000원 단위로 받기~~
  * ~~`IllegalArgumentException` 후 다시 입력 받기~~
    * ~~1000원으로 나누어 떨어지지 않으면~~
    * ~~음수로 나누어 떨어지지 않으면~~
    * ~~숫자가 아닌 수를 입력한 경우~~
## 2. 구매한 로또 출력
* ~~구입 금액 기준 발행한 로또 수량 및 번호 출력 (오름차순)~~
## 3. 당첨 번호 입력
* ~~쉼표 기준으로 구분~~
  * ~~숫자를 입력하지 않은 경우  OR 로또 숫자 범위에서 벗어난 경우 => `IllegalArgumentException` 후 다시 입력 받기~~
## 4. 보너스 번호 입력
* ~~번호 입력~~ 
  * ~~숫자를 입력하지 않은 경우 OR 로또 숫자 범위에서 벗어난 경우  => `IllegalArgumentException` 후 다시 입력 받기~~
## 5. 당첨 통계 출력 
* ~~구매한 로또와 당첨 번호를 비교하여 로또 당첨 통계~~
* 출력
## 6. 총 수익률 출력
* ~~투자금액 대비 얼마를 벌었는지 수익률 계산~~ 
* ~~출력~~

# 에러
* 사용자가 잘못 입력한 경우  IllegalArgumentException + [ERROR]로 시작하는 에러 메시지 출력
* `[ERROR] 로또 번호는 1부터 45 사이의 숫자여야 합니다.`

# 커밋 컨벤션
* feat: 기능 구현
* docs: 리드미 생성/수정
* fix: 기능 에러 수정
* refactor: 구조 수정
* chore: 자잘한 코드 수정 (오타 등.)