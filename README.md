# MongoDB Replica Set Docker로 구현
## Replica Set
![스크린샷 2023-07-16 오전 2 08 55](https://github.com/Rojojun/replica-set-with-docker/assets/72805486/59fb808a-c2b9-4e98-a1e3-008dbfb4e909)
- 하나가 죽더라도 지속적인 운영이 가능
- HA(High Availability) 고가용성
- 실제 현업에서 많이 사용함
## 왜 Docker로?
- 개개인의 PC에 따른 환경설정 번거로움
- Replica Set을 위해 최소 3개 정도의 DB 구축 필요
> 불필요한 설정을 최소화 시키고 개발에 포커스를 맞춰 속도 증가하기 위함!
## 파일
`docker-compose.yml` 파일에 도커의 내용을 정의

**주의** 도커에 대한 전문지식을 가진게 아닌 알음알음 하며 한 내용으로서 정답은 아님
