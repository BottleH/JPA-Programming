# Spring Boot + JPA

## 1. 자바 ORM 표준 JPA 프로그래밍

### 1-1. JPA 소개

___

#### 1-1-1. SQL 중심적인 개발의 문제점

- SQL에 의존적인 개발을 피하기 어려움
- 객체답게 모델링 할수록 매핑 작업만 늘어난다.

위와 같은 문제점으로 인해 자연스레 의문이 든다.

❓ 객체를 자바 컬렉션에 저장 하듯이 DB에 저장할 수는 없을까?

이를 해결해 주는 것이 바로 

__*JPA-Java Persistence API*__

#### 1-1-2. JPA와 ORM

__JPA__

- Java Persistence API
- 자바 진영의 ORM 기술 표준

__ORM__
- Object-relational mapping(객체 관계 매핑)
- 객체는 객체대로 설계
- 관계형 데이터베이스는 관계형 데이터베이스대로 설계
- ORM 프레임워크가 중간에서 매핑
- 대중적인 언어에는 대부분 ORM 기술이 존재