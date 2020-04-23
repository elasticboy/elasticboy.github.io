---
layout: post
title:  "Cloud Practitioner Module05"
date:   2020-04-23T04:25:52-00:00
author: dhp.lee
categories: Aws
tags: lorem
---

### AWS Security

기본정보
- 데이터를 안전하게 유지
-- 복원력이 뛰어난 인프라
-- 철저한 보안
-- 강력한 보안 조치

지속적인 개선
- 빠른 혁신
- 지혹적으로 발전하는 보안 서비스

필요한 것에 대해 지불
- 고급 보안 서비스
- 실시간으로 발생하는 위험 해결
- 더 저렴한 운영 비용으로 요구 사항 충족

거버넌스 지원 기능
- 높은 수준의 보안
- 추가 감독
- 보안 통제
- 중앙 자동화

AWS 책임 공유 모델
- AWS 보안 제어 기능 상속
- 제어 기능 계층화
- 자체 규정 준수 및 인증 프로그램 강화

로깅 도구 사용하여 완벽하게 파악

네트워크 보안
- 기본 제공 방화벽
- 전송 중 암호화
- 비공개/전용 연결
- DDos 완화

인벤토리 및 구성관리
- 배포 도구
- 인벤토리 및 구성도구
- 템플릿 정의 및 관리 도구

데이터 암화화
- 암호화 기능
- 키 관리 옵션 (AWS Key Management Service)
- 하드웨어 기반 암호화 키 스토리지 옵션 (AWS CloudHSM)

엑세스 제어 및 관리
- Identy and Access Management(IAM)
- Multi-Factor Authentification(MFA)
- 기업 디렉터리와의 통합 및 연동
- Amazon Cognito
- AWS SSO

위험 요소를 줄이기 위한 도구 및 기능
- API 호춫에 대한 심층적인 가시성
- 로그 집계 및 옵션
- 알림 제공

AWS Marketplace
- AWS 고객에게 소프트웨어를 마케팅/판매할수 있는 공인 파트너
- AWS에서 실행할 수 있는 온라인 소프트웨어 스토어


`공통 책임 모델`

모두 책임을 부담

애플리케이션 전체를 살펴본 후 나눔
책임 분산,,

- 물리적 보호를 제공
- 독점적인  네트워크 사용=> VPC를 사용하여 보호
- AWS 하이퍼바이저에 대한 보안을 감시하고 확장성을 높임
예시
- EC2
- 게스트와 하이퍼바이즈를 분리하는 선에 있다
- AWS는 앰과 사용자의 데이터에서 전혀 모름

Physical, Network, Hypervisor
GuestOS, Application, User Data

로 나뉨

`Identy and Access Management`

- 사용자, 그룹, 역할

사용자
- AWS IAM 
-- 자격 증명은 영구적
-- 시스템에서 명명된 사용자와 함께함

그룹
- 사용자 모임

역할
- 정
- 권한이 아니다!
- 인증 방법임
- 역할이 있는 자격증명은 일시적인 경향
- 단순히 인증

<a href="/assets/cloud_practitioner/cloud_practitioner_iam.png" data-lightbox="falcon9-small" data-title="Check out the Falcon 9 from SpaceX">
  <img src="/assets/cloud_practitioner/cloud_practitioner_iam.png" title="cloud_practitioner">
</a>

