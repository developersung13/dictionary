# Dictionary (Web)

1. **크로스 브라우징**(Cross Browsing)
> 최대한 많은 웹 브라우저에서 정상적으로 작동하는 웹 페이지를 개발하는 방법론 중 하나이다.
<br />

2. **폴리필**(Polyfill)
> 브라우저가 지원하지 않는 코드를 브라우저에서 사용할 수 있도록 변환한 코드 조각이나 플러그인을 말한다.
>
> e.g., `core.js`, `polyfill.io`
<br />

3. **트랜스파일**(Transfile)
> 최신 버전의 코드를 예전 버전의 코드로 변환하는 과정을 말한다.
> 
> e.g., `Babel`
<br />

4. **AJAX**(Asynchronous Javascript And XML)
> - JavaScript와 XML을 이용한 비동기적 정보 교환 기법
> - 웹 페이지의 전체가 리로드 되지 않고, 페이지의 일부분만을 서버에서 가져와 웹 페이지 화면을 동적으로 변경하는 방식
> ## 장점
> 1. **비동기 처리**
> - **페이지의 새로고침 없이 데이터 갱신** : 전체 페이지를 다시 로드하지 않고도 필요한 부분만 업데이트 할 수 있습니다. 이는 사용자 경험을 크게 향상시킵니다.
> - **빠른 응답 시간** : 서버와의 통신이 비동기적으로 이뤄지기 때문에 사용자 인터페이스가 더 빠르게 반응할 수 있습니다.
> 2. 향상된 사용자 경험
> - **인터랙티브한 UI** : AJAX를 사용하면 사용자 인터페이스가 더 동적이고 반응성 있게 만들어질 수 있습니다.
> - **연속적인 데이터 전송** : 사용자는 데이터를 입력하거나 요청할 때마다 전체 페이지가 리프레시 되지 않기 떄문에 더 나은 경험을 제공받습니다.
> ## 단점
> 1. **브라우저 호환성 문제**
> - **다양한 브라우저 지원** : 모든 브라우저가 AJAX를 동일하게 지원하지 않기 때문에, 특정 브라우저에서는 예상치 못 한 문제가 발생할 수 있습니다. 이는 특히 구형 브라우저에서 문제가 될 수 있습니다.
> 2. **보안 문제**
> - **크로스 사이트 스크립팅(XSS)** : 잘못된 입력 검증이나 서버 설정으로 인해 보안 취약점이 발생할 수 있습니다.
> - **CSRF(Cross-Site Request Forgery)** : AJAX 요청을 악용한 공격으로부터 보호하기 위한 추가적인 보안 조치가 필요합니다.
<br />

5. **CBD**(Component Based Development)
> 재사용할 수 있는 컴포넌트를 개발 또는 조합해서 하나의 애플리케이션을 만드는 개발 방법론이다.
<br />

6. **웹 사이트**(Website)
> 사용자와 상호 작용 없이 단방향으로 정보를 제공하며, HTML에 링크가 연결된 웹 페이지의 모음으로 콘텐츠가 동적으로 업데이트 되지 않는 웹이다.
<br />

7. **웹 애플리케이션**(Web Application)
> 사용자와 상호 작용하는 양방향 소통이 이뤄지는 웹이다.
<br />

8. **NaN**(Not A Number)
> 연산 과정에서 잘못된 입력을 받았음을 나타내는 기호이다.
<br />

9. **JsDoc**
> 모듈, 네임스페이스, 클래스, 메소드, 매개변수 등에 대한 API 문서 생성 도구이다.
<br />

10. **propTypes**
> 리액트에서 컴포넌트 props의 타입을 검사하기 위해 사용하는 속성이다.
<br />

11. **슈퍼셋**(Superset)
> 기존 언어에 새로운 기능과 문법을 추가해서 보완하거나 향상하는 것을 말한다. 슈퍼셋 언어는 기존 언어와 호환되며, 일반적으로 컴파일러 등으로 기존 언어 코드로 변환되어 실행된다.
>
> 슈퍼셋 언어 e.g., `TypeScript`
<br />

12. ECMAScript 표준을 따르는 **JavaScript의 7가지 데이터 타입**
> ## Primitive Types
> 1. undefined
> 2. null
> 3. Boolean
> 4. String
> 5. Symbol
> 6. Numeric(Number와 BigInt)
> ## Object Type
> 7. Object
<br />

13. **암묵적 타입 변환**(Implicit coercion conversion)
> 개발자가 의도적으로 타입을 명시하거나 바꾸지 않았는데도 컴파일러 또는 엔진 등에 의해서 런타임에 타입이 자동으로 변경되는 것을 말한다.
<br />

14. **타입 시스템**(Type System)
> 타입 검사기가 프로그램에 타입을 할당하는데 사용하는 규칙 집합
<br />

15. **타입 애너테이션**(Type Annotation)
> 변수나 상수 혹은 함수의 인자와 반환 값에 타입을 명시적으로 선언해서 어떤 타입 값이 저장될 것인지를 컴파일러에게 직접 알려주는 문법이다.
<br />

16. **덕 타이핑**(Duck Typing)
> 동적 타이핑의 한 종류로, 객체의 변수 및 메소드의 집합이 객체의 타입을 결정하는 것을 말한다.
<br />

17. **트리쉐이킹**(Tree shaking)
> 사용하지 않는 코드를 제거하는 방식이다.
<br />

18. **IIFE**(Immediately Invoked Function Expression, 즉시 실행 함수)
```javascript
// e.g.
(function(name) {
    console.log('Hello, ' + name + '!')
})("World");
```
<br />

19. **번들링**(Bundling)
> HTML, CSS, JavaScript를 각각의 모듈로 보고 이를 조합해 하나의 묶음으로 만드는 것이다. 즉, 번들링은 묶음의 개념이며 파일을 묶는 작업 그 자체를 의미한다. 더 정확히 말하자면, 모듈 간의 의존성을 파악해 이를 바탕으로 그룹화를 하는 작업이다.
<br />

20. **번들러**(Bundler)
> 웹 애플리케이션을 개발하기 위해 필요한 HTML, CSS, JavaScript 등의 파편화된(모듈화된) 자원들을 모아서, 하나 혹은 최적의 소수 파일로 결합(번들링)하는 도구이다.
<br />

21. **렉시컬 스코프**(Lexcical Scope)
> 코드가 작성된 위치에 따라 스코프가 정해지는 것을 의미합니다. 즉, 함수가 어디서 정의되었으냐에 따라 해당 함수의 유효 범위가 결정됩니다. 정적 스코프라고도 불리며, 이는 변수의 스코프가 코드 작성 시 결정된다는 의미입니다.
<br />

22. **상위 스코프**
> 함수가 정의된 위치에서부터 가장 가까운 외부 스코프를 말합니다.

23. **클로저**(Closure)
> 클로저는 함수와 함수가 선언된 어휘적 환경(lexical environment)의 조합을 의미합니다. 이를 통해 함수가 생성될 때의 스코프와 변수를 기억하여, 생성된 이후에도 그 스코프에 접근할 수 있게 하는 것을 의미합니다.
>
> Closure의 사전적 의미는 폐쇄입니다. 클로저의 핵심은 스코프를 이용하여 변수의 접근 범위를 **폐쇄**하는 것에 있으며, 내부 함수가 자신이 선언된 어휘적 환경을 **기억**한다는 것입니다. 이는 내부 함수가 외부 함수의 스코프에 있는 변수에 접근할 수 있게 합니다.
>
> ## 구성요소
> 1. **함수** : 내부 함수로, 자신이 선언된 환경 내의 변수에 접근할 수 있습니다.
> 2. **어휘적 환경** : 함수가 선언된 위치의 스코프입니다. 이 환경은 함수가 생성될 때의 변수와 그 값들을 포함합니다.
>
> ## 장점
> 1. **전역변수 사용의 최소화**
> - 전역변수가 많으면 의도치 않게 어디에서든 접근하는 상황이 발생할 수 있는데, 클로저를 이용하면 전역변수를 최소한으로 사용함으로써 이러한 실수나 예외적인 상황을 방지할 수 있습니다.
> 2. **데이터 보존 가능**
> - 클로저 함수는 외부 함수의 실행이 끝나더라도 외부 함수 내 변수를 사용할 수 있습니다. 따라서 특정 데이터를 스코프 안에 가두어 둔 채로 계속 사용할 수 있게 하는 폐쇄성을 갖습니다.
> 3. **모듈화를 통한 코드 재사용의 편리**
> - 클로저 함수를 각각의 변수에 할당하면, 각자 독립적으로 값을 사용하고 보존할 수 있습니다. 이와 같이 힘수의 재사용성을 극대화하고 함수 하나를 독립적인 부품의 형태로 분리하는 것을 모듈화라고 합니다. 클로저를 통해 데이터와 메소드를 묶어다닐 수 있기에 클로저는 모듈화에 유리합니다.
> 4. **정보 접근의 제한(캡슐화, Encapsulation)**
> - 클로저 모듈 패턴을 사용해 객체에 담아 여러 개의 함수를 리턴하도록 만들어 정보의 접근을 제한할 수 있는데, 이률 캡슐화라고 합니다.
> ## Closure 예시 코드 #1
> ```javascript
> function outerFunction() {
>   let outerVariable = 'I am outside!';
>
>   function innerFunction() {
>     console.log(outerVariable); // 외부 함수의 변수를 참조
>   }
>
>   return innerFunction;
> }
>
> const myClosure = outerFunction();
> myClosure(); // "I am outside!" 출력
> ```
> ## Closure 예시 코드 #2
> ```javascript
> function outer() {
>   let message = 'Hello! ';
>
>   return function inner(name) { // inner함수는 클로저
>	  return message = message + name;
>	}
> }
>
> let greeting = outer(); // 외부함수 호출. 변수 greeting은 inner 함수를 참조
> console.log(greeting('Janet')); // "Hello! Janet" 출력
> ```
> - `outer 함수`는 종료됐지만, `outer 함수` 함수 내부 변수인 `message`는 `inner 함수`를 통해 접근 가능하다. 여기서의 `inner 함수`가 바로 클로저이다.
> - 이는 클로저의 특성으로 `inner 함수`가 선언될 때 그 주변의 어휘적 환경 즉, `outer 함수`의 어휘적 환경과 함께 묶였기 때문에 클로저에서 `message`라는 변수를 참조할 수 있게 된다.
<br />

24. **`forEach 함수`와 `map 함수`의 차이점**
> ## `forEach`
> - 배열의 요소를 반복합니다.
> - 각 요소에 대해 콜백을 실행합니다.
> - 값을 반환하지 않습니다.
> ```javascript
> const a = [1, 2, 3];
> const doubled = a.forEach((num, index) => {
>   ...   
> });
>
> // doubled = undefined
> ```
> ## `map`
> - 배열의 요소를 반복합니다.
> - 각 요소에서 함수를 호출하여 결과로 새 배열을 작성하여 각 요소를 새 요소에 매핑합니다.
> ```javascript
> const a = [1, 2, 3];
> const doubled = a.map((num, index) => {
>   return num * 2;
> });
>
> // doubled = [2, 4, 6]
> ```
> - `forEach 함수`와 `map 함수`의 가장 큰 차이점은 `map 함수`는 새로운 배열을 반환한다는 것입니다. 결과가 필요하며, 원본 배열은 변경하고 싶지 않다면 `map 함수`를 선택해야 하고, 단순히 배열을 반복하고자 한다면 `forEach 함수`가 좋은 선택입니다.
<br />

25. **익명 함수의 사용사례**
> - 익명함수는 IIFE로 사용되어 지역 범위 내에서 일부 코드를 캡술화하므로 선언된 변수가 전역 범위로 누출되지 않도록 합니다.
> ```javascript
> (function() {
>   ...
> })()
> ```
>
> - 한 번 사용되고 다른 곳에서는 사용할 필요가 없는 콜백으로 사용됩니다. 함수 본체를 찾기 위해 다른 곳을 찾아볼 필요 없이 코드를 호출하는 코드 바로 안에 핸들러가 정의되어 있으면 코드가 보다 독립적이고 읽기 쉽게 보입니다.
> ```javascript
> setTimeout(function() {
>   console.log('Hello World!');
> }, 1000);
> ```
>
> - 함수형 프로그래밍 또는 `Lodash`에 대한 인수(콜백과 유사)로 사용됩니다.
> ```javascript
> const arr = [1, 2, 3];
> const double = arr.map(function(element) {
>   return element * 2;
> });
> 
> console.log(double);
> ```
<br />

26. **Lodas**
> 배열, 숫자, 객체, 문자열 등의 데이터로 작업할 때 번거로움을 없애고 쉽게 다룰 수 있도록 하는 JavaScript의 인기 라이브러리 중 하나로 `debounce` 및 `throttle`을 간편하게 구현할 수 있도록 도와준다.
> ```javascript
> var myFriend = [
>  { name: 'kys', job: 'developer', age: 27 },
>  { name: 'cys', job: 'webtoons man', age: 27 },
>  { name: 'yhs', job: 'florist', age: 26 },
>  { name: 'chj', job: 'nonghyup man', age: 27 },
>  { name: 'ghh', job: 'coffee man', age: 27 },
>  { name: 'ldh', job: 'kangaroo father', age: 27 },
>  { name: 'hsy', job: 'monk', age: 27 },
> ];
> 
> // 콜백함수를 통해 나이가 26인 객체가 처음으로 나오는 index 반환
> _.findIndex(myFriend, function(friend) {
>   return friend.age === 26;
> });
> // -> 2
> ```
<br />

27. **debounce 와 Throttle**
> ## Debounce
> Debounce는 이벤트가 계속해서 발생할 때, 마지막 이벤트가 발생하고 일정 시간이 지난 후에만 특정 작업을 수행합니다. 예를 들어, 사용자가 입력 필드에 타이핑할 때마다 API 요청을 보내고 싶지 않고 사용자가 입력을 멈춘 후에만 요청을 보내고 싶을 때 주로 사용됩니다.
> - **동작 방식** : 이벤트가 발생할 때마다 타이머를 리셋하고, 타이머가 끝날 때 작업을 수행합니다.
> - **사용 예시** : 검색 입력, 창 크기 조정 시 작업
>
> ## Throttle
> Throttle은 일정한 간격으로 이벤트를 처리하는 방법입니다. 이벤트가 계속해서 발생하더라도 지정된 시간 간격으로만 특정 작업을 수행합니다. 예를 들어, 스크롤 이벤트에서 일정 시간 간격으로만 작업을 수행하여 성능을 향상시킬 때 주로 사용됩니다.
> - **동작 방식** : 최초 이벤트가 발생한 후 일정 시간이 지나기 전에는 추가 이벤트(들)을 무시합니다.
> - **사용 예시** : 스크롤, 리사이즈 이벤트 핸들링
<br />

28. **MVC 패턴**
> MVC 패턴은 소프트웨어 디자인 패턴 중 하나로, 애플리케이션을 세 가지 주요 컴포넌트로 나누어 설계합니다. 이는 코드의 재사용성과 유지 보수성을 향상시키기 위한 목적으로 사용됩니다.
> 1. **Model** : 애플리케이션의 데이터와 그 데이터를 처리하는 비즈니스 로직을 담당합니다. 데이터베이스와의 상호작용, 데이터 검증 등을 포함합니다.
> 2. **View** : 사용자에게 데이터를 표시하는 부분입니다. 사용자 인터페이스(UI) 요소를 관리하며, 모델로부터 데이터를 받아와 사용자에게 보여줍니다.
> 3. **Controller** : 사용자 입력(요청)을 처리하고, 이를 모델과 뷰에 전달합니다. 컨트롤러는 모델의 상태를 변경하거나 뷰를 업데이트하는 로직을 포함합니다.
>
> <img width="1282" alt="Screenshot 2024-07-10 at 1 58 05 AM" src="https://github.com/developersung13/dictionary/assets/56868605/3a02867f-a458-4673-bb31-341b00ee5802">
> <img width="846" alt="Screenshot 2024-07-10 at 1 57 38 AM" src="https://github.com/developersung13/dictionary/assets/56868605/b224f11f-09f3-4a46-8b52-4d974261a00c">
<br />

29. **FLUX 패턴**
> Flux 패턴은 Facebook이 개발한 애플리케이션 아키텍처 패턴으로, 주로 Client Side 웹 애플리케이션에서 단방향 데이터 흐름을 구현하는 방법을 정의합니다.
>
> ## 구성요소
> 1. **Action** : 애플리케이션 내에서 발생하는 이벤트나 사용자 인터랙션을 나타냅니다.
> 2. **Dispatcher** : 모든 액션을 수신하고, 이를 스토어에 전달하는 중앙 허브 역할을 합니다.
> 3. **Store** : 애플리케이션의 상태와 비즈니스 로직을 포함하며, 상태 변경 시 뷰에 변경 사항을 통지합니다.
> 4. **View** : 사용자 인터페이스를 담당하며, 상태 변경에 따라 화면을 업데이트합니다.
>
> ![1_6gzKauaLur48CJh-iwEFAQ](https://github.com/developersung13/dictionary/assets/56868605/5405bf07-504f-41a5-95b8-e0b1f3689a5f)
<br />

30. **자바스크립트의 호스트 객체와 내장 객체**
> ## 내장 객체
> - 내장 객체는 ECMAScript 사양에 정의된 객체들로, 자바사크립트 엔진이 실행될 때 기본적으로 제공되는 객체들입니다. 이들은 자바사크립트 언어 자체의 일부이며, 어떤 환경에서든 동일하게 동작하니다.
>
> ### e.g.
> - `Object`, `Array`, `Function`, `String`, `Number`, `Date`, `Math`, `RegExp`
> 
> ## 호스트 객체
> - 호스트 객체는 자바스크립트 환경(호스트 환경)에 의해 제공되는 객체들입니다. 이들은 자바스크립트가 실행되는 특정 환경(예: `Web Broswer`, `Node.js`)에 따라 다릅니다. 호스트 객체는 자바스크립트가 해당 환경과 상호작용할 수 있게 해 줍니다.
>
> ### e.g.
> #### Web Broswer
> - `window`, `document`, `XMLHttpRequest`, `console`, `localStorage`
> ### Node.js
> - `process`, `Buffer`, `fs`, `http`
>
> ## 차이점
> - 내장 객체는 모든 환경에서 일관된 동작을 제공하는 반면, 호스트 객체는 자바스크립트가 실행되는 환경에 특화된 기능을 제공하는 데 사용됩니다.
<br />

31. **call과 apply 함수**
> - 자바스크립트에서 `call`과 `apply`는 모두 함수를 호출할 때 사용되며, 함수의 `this` 값을 설정할 수 있게 해 줍니다. 이 두 함수는 비슷한 목적을 가지고 있지만, 인자를 전달하는 방식에서 차이가 있습니다.
> - `call 함수`는 함수를 호출하면서 `this` 값과 각각의 인수를 명시적으로 전달하는데, `call`은 쉼표로 구분된 인수를 두 번째 인수로 취하고 `apply`는 인수의 배열을 두 번째 인수로 취합니다. `call`은 단어의 첫 글자인 `C`: `Comma`로 구분되며, `apply`는 단어의 첫 글자인 `A`: `Arguments`로 구분된다는 사실을 기억하시면 좋습니다.
> ```javascript
> function add(a, b) {
>   return a + b;   
> }
> console.log(add.call(null, 1, 2)); // 3
> console.log(add.apply(null, [1, 2])); // 3
> ```
<br />

32. **HMR**(Hot Module Replacement | Reloading)
> 모듈(코드) 전체를 다시 로드하지 않고 변경사항을 런타임에 교체하는 편의 기능이다.
<br />

33. **Funnel**
> 사용자에게 복잡한 값을 입력받을 때, 여러 화면이나 단계로 쪼개어서 입력받는 흐름
<br />

34. **Module**
> 프로그래밍 관점에서 특정 기능을 갖는 작은 코드 단위이다. 코드들을 기능에 따라 작은 코드 단위로 만듦으로써, 재사용성이 높아지고, 유지보수가 쉬워진다.
<br />

35. **Webpack**
> 웹팩은 웹 애플리케이션에서 사용하는 수많은 리소스를 하나의 파일로 병합 및 압축해 주는 **모듈 번들러**이다.
>
> ## 등장 배경
> 1. 파일 단위의 자바스크립트 모듈 관리의 필요성
> 2. 웹 애플리케이션의 빠른 로딩 속도와 높은 성능
<br />

36. **Loader**
> 로더는 웹팩이 웹 애플리케이션을 해석할 때 자바스크립트 파일이 아닌 웹 자원(HTML, CSS, Images, 폰트 등)들을 변환할 수 있도록 도와주는 속성입니다.
<br />
