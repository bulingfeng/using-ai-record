# Codex 使用记录

## 创建AGENT.md

这个文件的目的是为了约束和给 Agent 一些指导。下面是我自己的 AGENT.md

```markdown
# Project Agent Notes

# Codex Agent Instructions

## Tech Stack
- Java 17
- Spring Boot 3.x
- Maven
- MySQL
- Redis

## Coding Rules
- Use constructor injection
- No field injection
- No Lombok
- Prefer immutable objects
- Use Optional only for return values

## Architecture
- Controller → Service → Repository
- Controllers must not contain business logic
- Services must be transactional where appropriate

## Testing
- JUnit 5
- Mockito
- Minimum coverage for new code: 80%

## Git Rules
- Do not commit or push unless explicitly requested
- Use Conventional Commits

## Restrictions
- Do NOT modify database schema
- Do NOT change existing public APIs
- Do NOT introduce new dependencies without approval

## DATABASE

my database is mysql, host=127.0.0.1,port=3306,user=root,password=123456

```

