# Budgeting

Como uma parte do projeto final do Bootcamp CI&T: Java AI Copilot. Esse projeto serve como um desenvolvimento de uma API Inteligente para auxiliar no reconhecimento de fala que contém a descrição dos gastos financeiros. O projeto também conta com integração do Spring Boot e Inteligência Artificial utilizando Spring AI.

## O que foi utilizado no projeto:
- Java 25
- Spring Boot 4.1.1
- MySQL
- OpenAI API
- Spring AI
- ChatClient
- Spring Web
- Lombok
- Docker e Docker Compose
- Tool Calling para executar as funções reais
- Transcrição de áudio
- Speech API
- Endpoint de transcrição de aúdio
- Persistência de dados
- Endpoint REST

## Principais desafios:
Devido à limitação de créditos da OpenAI, não foi possível realizar testes de integração com a API de reconhecimento de fala. Por isso, o projeto foi desenvolvido com foco em testes unitários e simulação de respostas da API.

## Estrutura do Projeto:
O projeto está estruturado da seguinte forma:
- `src/main/java`: Contém o código-fonte da aplicação.
- `src/test/java`: Contém os testes unitários da aplicação.
- `build.gradle`: Arquivo de configuração do Gradle, que gerencia as dependências e plugins do projeto.

## Como realizar a configuração da OpenAI API:
Para configurar a OpenAI API, siga os passos abaixo:
1. Crie uma conta na OpenAI e copie a sua chave de API.
2. No arquivo `application.properties`, adicione a seguinte linha, substituindo `YOUR_API_KEY` pela sua chave de API:
```
   spring.ai.openai.api-key=${OPENAI_API_KEY}
```

## Como executar o projeto:
1. Clone o repositório do projeto:
```bash
git clone https://github.com/gameplaybiel/budgeting
```

2. Certificar se o Java 25 e Gradle estão instalados corretamente.

## Autor
Gabriel Conceição - [LinkedIn](https://www.linkedin.com/in/gabrielconceicao18/)