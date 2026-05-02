[![hits](https://myhits.vercel.app/api/hit/https%3A%2F%2Fgithub.com%2FPong0882?color=blue&label=hits&size=medium&base_count=8080)](https://myhits.vercel.app)

# Hi there 👋

[![Solved.ac Profile](http://mazassumnida.wtf/api/v2/generate_badge?boj=pong0882)](https://solved.ac/pong0882/)
[![Solved.ac Profile](http://mazassumnida.wtf/api/v2/generate_badge?boj=HelloPong)](https://solved.ac/HelloPong/)

---

- 🏫 삼성 SSAFY 13기 Java 전공트랙 수료 (1,620시간)
- 🏆 SSAFY 자율 프로젝트 1위 · 공통 프로젝트 3위
- 📜 정보처리기사 · SQLD


---

# 🛠 Tech Stack

## 🧑‍💻 Languages

![Java](https://img.shields.io/badge/Java_17-ED8B00?style=flat&logo=openjdk&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white)

## 🧱 Backend

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat&logo=springsecurity&logoColor=white)
![Spring Cloud](https://img.shields.io/badge/Spring_Cloud-6DB33F?style=flat&logo=spring&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-59666C?style=flat&logo=hibernate&logoColor=white)
![MyBatis](https://img.shields.io/badge/MyBatis-000000?style=flat&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat&logo=jsonwebtokens&logoColor=white)

## 🗄 Database & Search

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-005571?style=flat&logo=elasticsearch&logoColor=white)

## 📡 Messaging

![Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)

## ⚙️ DevOps & Infrastructure

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat&logo=jenkins&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white)
![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?style=flat&logo=amazonec2&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)
![MinIO](https://img.shields.io/badge/MinIO-C72E49?style=flat&logo=minio&logoColor=white)

## 🧰 Tools

![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)
![GitLab](https://img.shields.io/badge/GitLab-FC6D26?style=flat&logo=gitlab&logoColor=white)
![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat&logo=jira&logoColor=white)
![IntelliJ](https://img.shields.io/badge/IntelliJ_IDEA-000000?style=flat&logo=intellijidea&logoColor=white)

---

# 🚀 Featured Projects

## 1. 🚑 SSAIREN — AI 기반 구급활동 자동화 플랫폼 `SSAFY 자율 1위`

응급 현장 대화를 Faster-Whisper로 실시간 전사하고, Qwen2.5 LoRA 모델이 CC/Hx/증상/바이탈을 JSON으로 추출해 구급활동일지 초안을 자동 생성합니다.  
구급대원 인터뷰를 통해 환자 민감정보 외부 전송 불가를 확인하고 Google STT를 포기, 완전 온프레미스 AI 구조를 채택했습니다.  
GPU 없는 EC2 환경에서 GGUF Int4 양자화 + Cloudflare Tunnel로 개인 노트북을 AI 추론 서버로 구성해 현장 사용 가능한 속도를 확보했습니다.

## 2. 📚 Assistudy — AI 기반 순공부시간 기록 플랫폼 `SSAFY 공통 3위`

MediaPipe 온디바이스 AI로 눈 깜빡임·시선·고개·하품을 실시간 분석해 딴짓 시간을 자동 제외하고 순공부시간만 기록합니다.  
팀장 겸 PM으로 6인 팀 전 직군 일정을 총괄했고, 모놀리식 → MSA 전환(4개 서비스)을 마일스톤으로 설정해 팀원 반발을 설득하며 완성했습니다.  
Kafka 비동기 로그 파이프라인으로 로그 유실 문제를 해결했고, Grafana 모니터링으로 RAM 초과 장애를 사전에 감지해 RAM Swap으로 대응했습니다.

## 3. 🌍 TripLog — 카카오맵 기반 여행 일정 계획 플랫폼

카카오맵으로 관광지를 탐색하고 드래그앤드롭으로 일정을 구성하면 Tmap API가 이동 거리·시간을 자동 계산합니다.  
4중 JOIN + N+1 구조를 직접 발견하고 ResultMap → 역정규화 → Elasticsearch + nori 형태소 분석기까지 10가지 방식을 단계적으로 실험했습니다.  
검색 응답시간 420ms → 24ms (94% 개선), 처리량 225 RPS → 849 RPS (3.7배 향상).

## 4. 🌊 MyOcean — OCEAN 기반 AI 페르소나 자아 탐색 플랫폼

Big Five 성격 이론 기반으로 게임·일기·AI 대화를 통해 사용자의 내면을 5가지 페르소나로 시각화합니다.  
Jenkins 블루그린 무중단 배포 파이프라인(헬스체크 → Nginx 트래픽 전환 → 자동 롤백)을 구현하고, AWS EC2 2대를 애플리케이션/데이터 인프라로 분리했습니다.  
Kafka Sink Connector로 코드 없이 토픽 데이터를 MinIO 4노드 분산 스토리지에 자동 적재하는 파이프라인을 구축했습니다.

## 5. 🍹 주르륵 — 보유 재료 기반 칵테일 큐레이션 서비스

"내가 가진 재료로 뭘 만들 수 있을까?"라는 질문에서 출발한 1인 개발 프로젝트입니다.  
GROUP BY + HAVING COUNT로 보유 재료 완전 매칭 칵테일을 필터링하고, LEFT JOIN으로 재료 1개 부족 칵테일도 함께 표시합니다.  
Spring MVC / JPA를 처음 적용하며 계층 분리와 다대다 관계 설계를 직접 체득한 첫 번째 Spring 프로젝트입니다.
