# Docker Compose

> Docker Compose를 통해 여러 개의 컨테이너를 관리한다.

### 1. Docker Compose의 장점

- 한 번에 여러 컨테이너 설정하기
- 빠른 서비스 실행
- 같은 네트워크에서 쉽게 연결

### 2. docker-compose로 실행
```bash
cd ~/spring-boot-sample
docker-compose up
docker-compose down
```

### 3. redis 연결 테스트
- http://localhost:8080 정상 동작 확인
- http://localhost:8080/test-cache redis를 사용한 5초 단위 캐시 적용 확인
