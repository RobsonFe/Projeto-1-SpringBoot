# Projeto-1-SpringBoot

Este é um projeto de exemplo criado com o Spring Boot e o Maven. Ele demonstra como criar um serviço da web simples que responde com uma mensagem "Hello World", mas permite personalizar a saudação fornecendo um parâmetro `name`.

## Pré-requisitos

- [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/javase-downloads.html) - Certifique-se de que você tenha o JDK instalado em sua máquina.
- [Maven](https://maven.apache.org/download.cgi) - Certifique-se de que você tenha o Maven instalado em sua máquina.

## Como Executar

Siga as etapas abaixo para executar o aplicativo:

1. Clone este repositório para a sua máquina local:

   ```bash
   git clone https://github.com/RobsonFe/Projeto-1-SpringBoot.git
   ```

2. Navegue até o diretório do projeto:

   ```bash
   cd Projeto-1-SpringBoot
   ```

3. Compile o projeto usando o Maven:

   ```bash
   mvn clean package
   ```

4. Execute o aplicativo Spring Boot:

   ```bash
   java -jar target/Projeto-1-SpringBoot.jar
   ```

O aplicativo será iniciado e estará disponível em [http://localhost:8080](http://localhost:8080).

## Uso

- Acesse [http://localhost:8080/greeting](http://localhost:8080/greeting) para obter a saudação padrão "Hello, World!".
- Para personalizar a saudação com um nome específico, adicione o parâmetro `name` à URL, por exemplo: [http://localhost:8080/greeting?name=Robson](http://localhost:8080/greeting?name=Robson).

## Estrutura do Projeto

- `GreetingController.java`: Este arquivo contém o controlador Spring que define a lógica para responder às solicitações na URL `/greeting` e permite a personalização da saudação com o parâmetro `name`.
- `Greeting.java`: Uma classe de modelo simples para representar a resposta JSON com um ID e uma mensagem de saudação.

## Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).
