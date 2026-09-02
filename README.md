<div align="center">

# 이하늘 · Lee HaNeal

**문제를 찾아서 끝까지 고치는 백엔드 중심 풀스택 개발자**

[![Portfolio](https://img.shields.io/badge/Portfolio-12161C?style=flat-square&logo=vercel&logoColor=5EE1C4)](https://leehaneal.github.io/my-portfolio)
[![Email](https://img.shields.io/badge/Email-12161C?style=flat-square&logo=gmail&logoColor=F2A93B)](mailto:harull817@naver.com)
[![GitHub](https://img.shields.io/badge/GitHub-12161C?style=flat-square&logo=github&logoColor=E7E5DE)](https://github.com/LeeHaNeal)

</div>

<br>

### 지금 이런 걸 봅니다

Java · Spring Boot로 서버를 설계하고, React로 그 API를 소비하는 화면까지 직접 만듭니다.
디버깅할 때 우회로보다는 원인을 찾는 쪽을 택합니다.

<br>

### Stack

<div align="center">

![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white)
![SpringBoot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![SpringSecurity](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![MyBatis](https://img.shields.io/badge/MyBatis-1F262A?style=for-the-badge)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Axios](https://img.shields.io/badge/Axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

<br>

### Fixed, not worked around

| Project | Before | After |
|---|---|---|
| 올마켓 | 결제 승인 시점에 재고를 차감하는 구조라 동시 주문 시 마지막 재고 오버셀 위험 | 조건부 원자적 업데이트(재고 >= 수량)로 부족 시 트랜잭션 롤백·결제 실패 처리 |
| ReadForce | Gemini 응답이 마크다운·제어문자로 깨져 파싱 실패 | 전처리 + 복구 fallback으로 안정화 |
| 칼로몽 | 프론트 계산값(실수)·백엔드 필드(정수) 타입 불일치 | 요청 포맷 재정의로 저장 안정성 확보 |
| 칼로몽 | 챌린지 완료해도 포인트 미반영 | 완료 처리 · 점수 누적 로직 구현 |
| ReadForce | 회원 현황 확인할 관리자 화면 없음 | 조회·상태변경·삭제 관리자 페이지 구현 |
| 티켓 예매 | 동시 예매 1000건 중 최대 321건이 InnoDB 데드락으로 실패 | 예약 INSERT/재고 UPDATE 트랜잭션 분리 + 재시도 로직으로 완전 해결 (Failures: 0) |

<br>

### Projects

<table>
<tr>
<td width="50%" valign="top">

**🟩 [Calomong](https://github.com/LeeHaNeal/Calomong)**
개인 맞춤형 건강관리 웹 서비스
`Spring Boot` `Oracle` `React`
2025.04 – 2025.05 · 팀장/백엔드 (챌린지·운동·커뮤니티 화면 병행)

</td>
<td width="50%" valign="top">

**🟦 [ReadForce](https://github.com/LeeHaNeal/ReadForce)**
AI 기반 문해력 진단 웹 서비스
`Spring Boot` `PostgreSQL` `Gemini API`
2025.05 – 2025.06 · 팀장/백엔드 (챌린지·관리자 화면 병행)
🏆 부트캠프 8팀 중 우수상

</td>
</tr>
<tr>
<td width="50%" valign="top">

**🟨 [선착순 티켓 예매 시스템](https://github.com/LeeHaNeal/ticket-reservation)**
Redis 기반 동시성 제어 티켓 예매 백엔드 · React 프론트
`Spring Boot` `Spring Security` `MySQL` `Redis` `React`
2026.08 – 2026.09 · 개인 프로젝트 (동시성 제어·캐싱·JWT 인증)
동시 요청 1,000건 중 재고 100개 정확히 소진 검증 (오버셀 0건)

</td>
<td width="50%" valign="top">

**🟪 [올마켓 (결제 연동 주문 시스템)](https://github.com/LeeHaNeal/order-system)**
Provider 패턴으로 mock/실PG 전환 가능한 이커머스 주문 시스템
`Next.js 15` `TypeScript` `Prisma` `PostgreSQL(Neon)` `토스페이먼츠`
2026.09 · 개인 프로젝트 (기획·설계·구현·배포 전체 수행)
🔗 [라이브 데모](https://ohmarket-store.vercel.app)

</td>
</tr>
</table>
