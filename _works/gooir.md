---
# preview details
layout: works-single
title: "CareMind: ISMS-P 기반 의료 보안 시스템 구축"
category: "Cloud Security"
category_slug: cloud-security
image: assets/img/works/caremind_main.jpg # 나중에 실제 캡처본으로 교체하세요!
short_description: ISMS-P 인증 기준을 준수하며 AWS 클라우드 내 망 분리 및 다층 방어 체계를 구축한 의료 정보 서비스 프로젝트입니다.

# full details
live_preview: "#"
full_image: assets/img/works/caremind_detail.jpg # 상세 페이지 메인 이미지
info:
  - label: Year
    value: 2026
  - label: Role & Tech
    value: 인프라 보안 설계 및 기획, AWS (VPC/EC2/RDS)

description1:
  show: yes
  title: Project Goal
  text: "<p>환자의 민감 정보를 다루는 의료 서비스의 특성을 고려하여, <b>ISMS-P 인증 기준</b>을 충족하는 강력한 보안 메커니즘 구축을 목표로 삼았습니다.</p>
  <p>단일 서버 구조의 위험성을 제거하기 위해 웹-DB 인프라를 분리(Decoupling)하고, VPC 망 분리를 통해 외부 공격자가 데이터베이스에 직접 접근할 수 없는 다층 방어 구조(Defense in Depth)를 설계했습니다.</p>"

gallery:
  - assets/img/works/vpc_design.jpg # VPC 설계도 등 이미지
  - assets/img/works/login_2fa.jpg  # 2차 인증 화면 등 이미지
  - assets/img/works/role_based.jpg # 권한별 화면 이미지

description2:
  title: "Project Result & Troubleshooting"
  text: "<p><b>핵심 성과:</b> AWS RDS 프라이빗 서브넷 배치와 보안 그룹(3306) 통제로 데이터 보안을 극대화했으며, Bcrypt 단방향 암호화와 사원번호 기반 2FA를 도입해 계정 탈취 위협을 원천 차단했습니다. 또한 의사/행정직 구분에 따른 RBAC(직무 기반 권한 제어)를 구현하여 직무 분리 원칙을 준수했습니다.</p>
  <p><b>기술적 해결:</b> 인프라 분리 과정에서 발생한 'Access Denied' 통신 장애를 보안 그룹 인바운드 규칙 재설정과 GRANT 권한 최적화를 통해 해결했습니다. 보안 강화와 시스템 가용성 사이의 균형을 맞추며 실무적인 보안 가시성을 확보한 프로젝트였습니다.</p>"


---