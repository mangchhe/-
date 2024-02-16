# OOP

- [일급 컬렉션 (First Class Collection)의 소개와 써야할 이유](https://jojoldu.tistory.com/412) → [Summary][2]

# Spring

- [Spring Boot에서 S3에 파일을 업로드하는 세 가지 방법](https://techblog.woowahan.com/11392)
  - Stream, MultipartFile, Aws Multipart Upload
- [정산지기를 향한 첫걸음 (feat. 파일럿 프로젝트)](https://techblog.woowahan.com/2668/) → [Summary][1]
  - `@Where(clause = "delete = 0")`, totalCount 캐싱, 권한 관리, chunkSize, 코드 리뷰

# Kotlin

- [Kotlin으로 Spring AOP 극복하기!](https://tech.kakaopay.com/post/overcome-spring-aop-with-kotlin/)
  - Trailing Lambdas, Reverse Argument, Self Invocation

# JPA

- [응? 이게 왜 롤백되는거지?](https://techblog.woowahan.com/2606/)
  - Propagation, Transaction, Rollback, Try-Catch
 
# DB

- [캐시 문제 해결 가이드 - DB 과부하 방지 실전 팁](https://toss.tech/article/cache-traffic-tip)
  - Cache Stampede, Jitter, Cahce Penetration, Null Object Pattern, Failover, Hotkey, Distributed Lock for cache hit

# Log

- [토스ㅣSLASH 23 - 분산 추적 체계 & 로그 중심으로 Observability 확보하기](https://youtu.be/Ifz0LsfAG94?feature=shared) → [Summary][3]
  - L7 Load Balancer, X-Forwarded-For, Proxy Protocol, Global Trace Id, MDC, Istio

# Culture

- [공통시스템개발팀 코드 리뷰 문화 개선 이야기](https://techblog.woowahan.com/7152/)
  - D-n 규칙, Pn 규칙, pre-commit

# Performance

- [채널톡 실시간 채팅 서버 개선 여정 - 1편 : 레디스의 'Pub/Sub'](https://channel.io/ko/blog/real-time-chat-server-1-redis-pub-sub)
  - Redis, Socket.io, broadcast - O(NM)

[1]: ./summary/1.md
[2]: ./summary/2.md
[3]: ./summary/3.md
