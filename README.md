
# Spring Boot Email Configuration

Este projeto demonstra como configurar o envio de e-mails usando o Spring Boot com um servidor SMTP do Gmail.

## Configuração

Para que o envio de e-mails funcione corretamente, você precisa configurar suas credenciais de e-mail no arquivo `application.properties`.

### Passos para Configurar as Credenciais

1. **Abra o arquivo `application.properties`:**

   O arquivo `application.properties` está localizado em `src/main/resources/application.properties`.

2. **Adicione as seguintes propriedades ao arquivo:**

   ```properties
   spring.mail.host=smtp.gmail.com
   spring.mail.port=587
   spring.mail.username=SEU_EMAIL@gmail.com
   spring.mail.password=SUA_SENHA
   spring.mail.properties.mail.smtp.auth=true
   spring.mail.properties.mail.smtp.starttls.enable=true


