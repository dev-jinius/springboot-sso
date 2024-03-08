# Springboot SSO Project

## Overview
Spring Boot API 서버로, OAuth2.0에서 Resource Server 역할을 한다.
Keycloak을 인증 서버로 두고, Keycloak adapter 라이브러리를 사용하여 Keycloak 서버와 통신한다.
Keycloak은 사용자 인증 및 토큰 발급을 한다.
Resource Server인 이 프로젝트는 Keycloak 토큰 검증 및 권한 확인을 하며,
View 개발 이전에 임시로 Postman을 사용하여 로그인 API 호출을 한다.

## Skills
* Spring Boot
* Java
* Maven
* Spring Security
* OAuth2.0
* Keycloak

## 역할
* 사용자 클라이언트 : Postman
* Keycloak client : Springboot
* 인증 서버 : Keycloak

## 회원가입, 로그인 기능 구현
