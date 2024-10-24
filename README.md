# java-calculator-precourse
## 🚀구현할 기능
#1. 입력 및 출력을 담당하는 코드 구현
#2. 구분자와 피연산자를 포함하는 Calculator 객체를 구현
#3. 문자열에서 숫자를 추출하는 파싱 구현
   - 첫번째와 두번째 문자가 //일 경우, 세번째 문자를 커스텀 구분자로 등록
   - 첫번째 문자가 숫자 또는 커스텀 구분자 등록 후이면, 구분자를 기준으로 숫자 파싱
#4. 숫자들을 덧셈 연산하는 로직 구현
   - List를 이용하여 여러 숫자들을 덧셈할 수 있도록 구현
#5. 서비스 로직를 호출하는 컨트롤러 구현

### 예외처리
1. 첫번째 문자가 숫자도 아니고 "//"도 아닌 경우 (식에 포함)
2. 구분자가 두 번 이상 사용된 경우
3. 구분자 입력 후, \n이 입력되지 않은 경우 (식에 포함)
4. //과 \n 사이에 구분자가 ""이거나 문자열인 경우
5. 설정된 구분자 이외의 구분자가 입력된 경우 (식에 포함)

## ⚙️도입한 부분
### 디자인 패턴
1. MVC 패턴을 적용하여 레이어드 아키텍처에 부합하는 코드 작성
2. 레이어드 아키텍처에 의해 참초의 역전이 일어나지 않도록 구현

### 테스트 코드
1. given-when-then에 따른 테스트 코드 작성
2. Fixture을 이용한 테스트 시 사용될 데이터의 일관성 보장

### git
1. 세밀하게 coomit을 남겨 롤백에 유리하도록 git 활용
2. AngularJS commit convection 사용

## 🧐고민한 부분

