# coffee-react-test

## 왜 react-testing-library를 사용하는가?

Jest는 자바스크립트 테스트 프레임워크로 자바스크립트를 전반적으로 테스트하기 위한 프레임워크다.  
리액트도 자바스크립트 이지만 JSX를 사용하고 있으므로 일반적인 자바스크립트가 아니고 JSX로 HTML의 DOM을 다루기 때문에  
단순한 자바스크립트의 테스트로 정확한 오류를 잡아내기는 어렵다.  
이런 문제를 해결하고자 @testing-library는 UI 컴포넌트를 테스트하는데 도움을 주는 DOM 테스팅 라이브러리이다.

## husky와 lint-staged

husky는 **package.json 파일에서 githook을 사용**할 수 있게 해준다. githook은 깃에 특정 이벤트(소스 코드 커밋, 푸시 등)를 감지하여 이벤트를 실행하기 전에 특정 동작을 수행할 수 있도록 도와준다.

lint-staged는 **깃의 stage된 파일들에 특정 동작을 수행**할 수 있도록 해준다.
