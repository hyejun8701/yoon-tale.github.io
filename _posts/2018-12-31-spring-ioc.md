---
layout: post
title: 'Spring IoC 컨테이너'
author: Yoon Hye-Jun
date: 2018-12-31 13:35
---

- Inversion of Control 제어의 역전, 스프링의 주요 기능이다.
- POJO객체를 구성하고 관리한다.
- 미리 생성된 bean이 필요로하는곳에 주입되는 방식이다.

1. 빈(bean)과 POJO인스턴스는 모두 자바클래스로 생성한 객체인스턴스를 가르킨다.
2. 컴포넌트(component)와 POJO클래스는 객체인스턴스를 생성하는데 필요한 자바클래스를 가르킨다.

### *IoC 컨테이너는 @애너테이션을 붙인 자바클래스를 스캐닝(탐색)하여 POJO인스턴스, 즉 빈을 구성한다.*

##### 자바 구성 클래스
> @Configuraton, @Bean

##### 자바 컴포넌트 구성
> @Component, @Repository, @Service, @Controller

