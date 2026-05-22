# Slack POC — Java

Slack integration proof of concept using Java and Spring Boot. Supports sending messages to channels and direct messages.

## Tech Stack

- **Language:** Java 17
- **Framework:** Spring Boot 3.0.6
- **Integration:** Slack API (Web API)

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/api/messaging/slack/channel` | Send message to a Slack channel |
| POST | `/api/messaging/slack/dm` | Send direct message to a user |

## Getting Started

```bash
mvn clean install
mvn spring-boot:run
```

The server runs on `http://localhost:8080`.

## License

Proprietary — Brilworks Software
