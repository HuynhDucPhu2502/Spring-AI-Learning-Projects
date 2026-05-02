# Spring AI Learning Projects

This repository is used to learn and experiment with `Spring Boot` and `Spring AI` through small, focused projects. Each project lives in its own folder.

## Structure

- `1-openai`: the first project, focused on basic OpenAI model integration with Spring AI

## Requirements

- Java `21`
- Maven Wrapper (`mvnw`, `mvnw.cmd`) included in each project
- An API key for the model provider when a project makes real external calls

## Run the First Project

```powershell
cd .\1-openai
.\mvnw.cmd spring-boot:run
```

## Notes

- Do not commit API keys, local config files, or build output.
- For machine-specific configuration, prefer:
  - `application-local.properties`
  - `.env`

## Planned Topics

Possible next projects in this repository:

- `2-chat-client`
- `3-prompt-template`
- `4-rag-basic`
- `5-tools-agents`
