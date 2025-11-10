# 한밭대학교 인공지능소프트웨어학과 퍼레이드팀

**팀 구성**
- 20231052 김현정
- 20231051 김현빈
- 20231080 한예린

## <u>Teamate</u> Project Background
- ### 필요성
  - 공항 내 짐 운반 자동화의 수요 증가
  공항 이용객은 다중 인파 속에서 캐리어를 직접 운반해야 하며, 피로와 불편함이 큼.
  인물 추적 기반 운반 로봇이 사용자의 뒤를 따라가며 짐을 자동으로 운반하면 이용 편의성이 대폭 향상됨.
  분실 및 보안 문제 해결
  공항은 혼잡한 공간이므로 캐리어 분실 위험이 높음.
  로봇이 실시간으로 사용자의 위치를 추적하고 자신의 위치를 인식(SLAM) 하면 분실 방지 및 보안 강화 가능.
스마트 공항 구축을 위한 핵심 기술 기반
인물 추적(DeepSORT), 위치 인식(SLAM), ROS2 제어 시스템 등은
향후 스마트 로보틱스 및 무인 운반 시스템 기술의 기반이 됨.

- ### 기존 해결책의 문제점

  - DeepSORT 기반 추적의 한계
    - ID Switching 문제:
      사람이 가려지거나 유사한 외형의 인물이 있을 때,
      다른 ID로 인식되어 추적이 끊기거나 잘못된 대상 추적 발생.

    - 단일 객체 전용 추적 불가:
      DeepSORT는 기본적으로 MOT (Multi-Object Tracking) 구조로 되어 있어,
      하나의 대상만 지속적으로 추적하는 데에는 비효율적.

  - LiDAR SLAM의 한계

    유리 환경에서 위치 인식 불가:
    유리는 투명/반투명 특성 때문에 LiDAR의 레이저가 통과하거나 굴절되어
    장애물로 인식되지 않음.
    ➜ 실내 공항 환경에서 정확한 위치 추정이 어려움.
    
  
## System Design
  - ### System Requirements
    <img width="866" height="410" alt="image" src="https://github.com/user-attachments/assets/11c53c58-16ab-49a6-9c5f-94b55b993156" />

    
## Case Study
  - ### Description
  
  
## Conclusion
  - ### OOO
  - ### OOO
  
## Project Outcome
- ### 20XX 년 OO학술대회 

