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