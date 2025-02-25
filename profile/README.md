<p align="center"> 
  <img height="200px" 
       src="https://avatars.githubusercontent.com/u/189394862?s=400&u=665c7579b2577c8f5575bef64ae2ac89498e9e6e&v=4"
       style="border: 3px solid #4A90E2; border-radius: 50%;">
</p>

# 📌 Projeto - Sistema de Hospitais Pediátricos (PEWS)

Este projeto tem como objetivo desenvolver um sistema para hospitais pediátricos utilizando a escala PEWS (Pediatric Early Warning Score) para monitoramento de pacientes.

## 🛠 Tecnologias Utilizadas

### 🎨 UX/UI
- [Figma](https://www.figma.com/) - Protótipos e Design

### 💻 Front-end
- [Flutter](https://flutter.dev/) - Desenvolvimento mobile e web

### 🚀 Back-end
- [Java](https://www.java.com/)
- [Spring Boot](https://spring.io/projects/spring-boot)

### 🗄 Banco de Dados
- [PostgreSQL](https://www.postgresql.org/)
- [Docker](https://www.docker.com/) - Containerização

## 📌 Como Executar o Projeto

### 🔧 Pré-requisitos
Antes de começar, certifique-se de ter instalado:
- [Docker](https://www.docker.com/get-started)
- [Java 17+](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html)
- [Flutter](https://flutter.dev/docs/get-started/install)
- [PostgreSQL](https://www.postgresql.org/download/)
- [Maven](https://maven.apache.org/download.cgi)

### 🚀 Rodando o Backend
1. Clone o repositório:
   ```sh
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```
2. Acesse a pasta do backend:
   ```sh
   cd backend
   ```
 3. Compile o projeto executando o seguinte comando no mesmo diretório que está o `pom.xml`:
     ```sh
     cd backend\pews.back
     mvn clean package
     ```
4. Execute o Docker Compose para subir o banco de dados:
   ```sh
   docker-compose up -d
   ```
5. Inicie a aplicação Spring Boot:
   ```sh
   ./mvnw spring-boot:run
   ```

### 📱 Rodando o Frontend
1. Acesse a pasta do frontend:
   ```sh
   cd frontend
   ```
2. Instale as dependências:
   ```sh
   flutter pub get
   ```
3. Execute o projeto:
   ```sh
   flutter run
   ```


## Autores

Este projeto conta com a colaboração dos seguintes estudantes:

<p align="center">
  <a href="https://www.github.com/cDanx" target="_blank">
    <img height="200px" src="https://avatars.githubusercontent.com/u/110854412?v=4">
  </a>
    <a href="https://github.com/gabfarmarcondes" target="_blank">
    <img height="200px" src="https://avatars.githubusercontent.com/u/39389389?v=4">
  </a>
    <a href="https://www.github.com/Zidani135" target="_blank">
    <img height="200px" src="https://avatars.githubusercontent.com/u/49240429?v=4">
  </a>
</p>

## Licença

Este projeto é licenciado sob a [Licença MIT](https://opensource.org/license/mit/).
