#  [ REST API 실습 ] ([http://github.com/spring-jeongwon/demo.git](https://github.com/spring-jeongwon/demo/tree/rest))
  ## SpringBoot 실습환경 구성
    - 윈도우즈
    - IntelliJ IDEA 2023 Ultimate
    - Git
    - OpenJDK 17
   
 ##  실습 Spring 관련 스택 build.gradle
    -  // Basic
      implementation 'org.springframework.boot:spring-boot-starter-data-jpa'
      implementation 'org.springframework.boot:spring-boot-starter-thymeleaf'
      implementation 'org.springframework.boot:spring-boot-starter-web'
      compileOnly 'org.projectlombok:lombok'
      developmentOnly 'org.springframework.boot:spring-boot-devtools'
      runtimeOnly 'com.mysql:mysql-connector-j'
      annotationProcessor 'org.springframework.boot:spring-boot-configuration-processor'
      annotationProcessor 'org.projectlombok:lombok'
      testImplementation 'org.springframework.boot:spring-boot-starter-test'
  
      // Lombok(Log4j)
      testCompileOnly 'org.projectlombok:lombok'
      testAnnotationProcessor 'org.projectlombok:lombok'
  
      // Querydsl
      implementation 'com.querydsl:querydsl-jpa:5.0.0:jakarta'
      annotationProcessor 'com.querydsl:querydsl-apt:5.0.0:jakarta'
      annotationProcessor 'jakarta.annotation:jakarta.annotation-api'
      annotationProcessor 'jakarta.persistence:jakarta.persistence-api'
  
      // ModelMapper
      implementation 'org.modelmapper:modelmapper:3.1.0'
  
      // Thymeleaf
      implementation 'nz.net.ultraq.thymeleaf:thymeleaf-layout-dialect'
  
      // @Valid(validation)
      implementation 'org.springframework.boot:spring-boot-starter-validation'
  
      // Swagger
      implementation 'org.springdoc:springdoc-openapi-starter-webmvc-ui:2.0.2'
      implementation 'org.springframework.restdocs:spring-restdocs-mockmvc'

  ## 실습 순서
    - SpringBoot 개발환경 구성
      > IntelliJ IDEA - Spring 프로젝트 생성
    - REST API 구현 (온라인 강좌 URI 설계와 구현 실습)
      > DB Schema 설계와 API 엔드포인트
      > Entity 와 Repository 생성
      > Repostory - Service - Controller 연동
    - API 동작 확인과 API 문서화 실습
      > IntelliJ 에서 API 동작확인
      > Swagger_ui 문서 작성
      > RestDocs로 문서 작성 실습
    - HETEOAS 연동 실습
    
  
  
