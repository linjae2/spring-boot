# jobrunr

2025.04.25 실습

- 테스트 환경 구성에 따른 의존성 등록
- StorageProvider 구성 유무에 따른 정상 동작 여부

- jobrunr-spring-boot-3-starter 버전에 따른 필요 의존성

```groovy
  implementation 'org.jobrunr:jobrunr-spring-boot-3-starter:7.5.0'
  implementation 'com.fasterxml.jackson.datatype:jackson-datatype-jsr310'
  //implementation 'org.jobrunr:jobrunr-spring-boot-3-starter:6.2.3'
```