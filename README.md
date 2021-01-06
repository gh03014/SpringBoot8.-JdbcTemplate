개발환경: jdk11, 스프링부트 2.3.7Release, 인텔리제이(20.03), Windows10

1. starter-jdbc 라이브러리를 사용하여 스프링부트에서 JdbcTemplate 구현
2. @SpringBootTest 어노테이션으로 스프링 컨테이너와 테스트를 함께 실행
3. @Transactional 어노테이션으로 테스트가 끝난 후에 DB를 다시 rollback 한다
