# [Pet Fortune](https://pet-fortune.com)

## 🐾 프로젝트 소개
Pet Fortune은 반려동물을 위한 운세 서비스를 제공하는 웹 애플리케이션입니다. 사용자들에게 반려동물의 사주, 궁합, 전생 등의 정보를 제공하여 반려동물에 대한 새로운 시각과 재미를 선사합니다.

## 📌 서비스 개요

| **항목** | **내용** |
|:-------:|:--------|
| 서비스명 | 반려동물 신점 사주 |
| 주요 컨셉 | 신점 컨셉으로 LLM을 활용한 반려동물 사주 풀이 |
| 주요 타겟 | 20~40대 반려동물 보호자 |
| 목표 | 기본 무료 사주 + 광고 수익 + 프리미엄 리딩 유료 수익 |

## ✨ 핵심 기능
- **반려동물 사주 분석**: 반려동물의 출생 정보를 바탕으로 성격, 행운, 건강 등에 대한 사주 분석
- **반려동물 궁합 확인**: 여러 반려동물 간의 궁합 또는 반려인과의 궁합 분석
- **반려동물 전생 탐색**: 반려동물의 과거 삶과 인연에 대한 흥미로운 이야기 제공

## 🛠️ 개발 환경

### 💻 Backend
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.2.3-green)](https://spring.io/projects/spring-boot)
[![Java](https://img.shields.io/badge/Java-17-orange)](https://www.oracle.com/java/)
[![JPA](https://img.shields.io/badge/JPA-yellow)](https://www.oracle.com/java/technologies/persistence-jsp.html)
[![QueryDSL](https://img.shields.io/badge/QueryDSL-5.0.0-brightgreen)](http://querydsl.com/)
[![Spring%20Cloud](https://img.shields.io/badge/Spring%20Cloud-2023.0.0-purple)](https://spring.io/projects/spring-cloud)
[![Netflix Eureka](https://img.shields.io/badge/Netflix%20Eureka-blue)](https://github.com/Netflix/eureka)

### 🖥️ Frontend
[![Vue.js](https://img.shields.io/badge/Vue.js-3.0-green)](https://vuejs.org/)
[![Vuex](https://img.shields.io/badge/Vuex-4.0-darkgreen)](https://vuex.vuejs.org/)
[![Vue Router](https://img.shields.io/badge/Vue%20Router-4.0-yellowgreen)](https://router.vuejs.org/)
[![Axios](https://img.shields.io/badge/Axios-1.6.0-orange)](https://axios-http.com/)

### 🔧 Infrastructure
[![Docker](https://img.shields.io/badge/Docker-blue)](https://www.docker.com/)
[![Docker Compose](https://img.shields.io/badge/Docker%20Compose-lightblue)](https://docs.docker.com/compose/)
[![Jenkins](https://img.shields.io/badge/Jenkins-red)](https://www.jenkins.io/)
[![Linux](https://img.shields.io/badge/Linux-gray)](https://www.linux.org/)

## 🏗️ 아키텍처 특징

### 🧩 마이크로서비스 아키텍처
Pet Fortune은 마이크로서비스 아키텍처를 기반으로 설계되었습니다. 각 서비스(사주, 궁합, 전생)는 독립적으로 개발, 배포, 확장될 수 있는 구조를 가지고 있어 유연한 서비스 운영이 가능합니다.

### ⚖️ 로드 밸런싱
Netflix Eureka를 활용하여 서비스 디스커버리 및 로드 밸런싱을 구현하여 다음과 같은 이점을 확보했습니다:
- 트래픽 분산을 통한 서버 부하 감소
- 높은 가용성과 장애 대응 능력
- 서비스 인스턴스 자동 등록 및 관리

### 🤖 AI 기반 운세 생성
LLM(Large Language Model) API를 활용하여 반려동물 운세 콘텐츠를 생성합니다:
- 개인화된 맞춤형 운세 결과 제공
- 다양한 반려동물 종류 및 특성 고려
- 자연스러운 텍스트 생성을 통한 사용자 경험 향상

## 📊 성능 최적화

### 🧪 스트레스 테스트
서비스 안정성 확보를 위해 스트레스 테스트를 진행했습니다:
- JMeter를 활용한 부하 테스트 구현
- 동시 사용자 약 1,000명 처리 가능한 시스템 검증
- 유레카 서비스를 통한 효율적인 로드 밸런싱 구현

## 🚀 확장성 계획
- 향후 트래픽 증가에 대비한 서버 확장 구조 설계
- 마이크로서비스 아키텍처를 통한 유연한 서비스 확장 가능성 확보

## 📈 향후 개발 계획
- 모바일 앱 출시 (iOS, Android)
- 반려동물 커뮤니티 기능 확장
- AI 기반 반려동물 행동 분석 기능 추가

## 👥 팀 구성
- 프론트엔드 엔지니어, 디자이너, 기획, 프롬프트 엔지니어: [@thdus12](https://github.com/thdus12)
- 프론트엔드 엔지니어, 백엔드 엔지니어, 인프라: [@jaebum7396](https://github.com/jaebum7396)

## 📞 Contact Us
- Email: petfortune8996@gmail.com
- Instagram: [@pet._.fortune](https://www.instagram.com/pet._.fortune)
