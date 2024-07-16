# Travel Yaml Importer
### 설명
Spring Framework 의 EnvironmentPostProcessor Cycle에 특정 path 의 Yaml 기반으로 Configure Property 를 로드하는 기능을 하는 모듈이다.
yaml 파일명만으로 의존 관계를 자동으로 설정 가능하도록 기능을 제공한다. 이 모듈은 Spring Framework 를 사용하는 어떠한 프로젝트에서도 사용할 수 있다.


###
아래 코드처럼 submodule 설정을 부모 module 에서 properties 설정 파일에서 할  수 있는데  의존성을 매번 설정해야 하는 번거로움과 독립성을 해치는 이유로 yaml-import 모듈을 별도로 두게 되었다. 
```properties
spring.profiles.include=xxx
```
