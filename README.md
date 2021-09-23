### Termos e acordos

Ao iniciar este projeto, você concorda com as diretrizes do Código de Ética e Conduta e do Manual da Pessoa Estudante da Trybe.

# Boas vindas ao repositório do projeto WebChat!

> ## ⚠️ IMPORTANTE ⚠️ : Os testes desse projeto foram implementados pela Trybe, porém a aplicação foi feita por Qu4k3r

---

## Sumário

- [Habilidades](#habilidades)
  - [O que foi desenvolvido](#o-que-foi-ser-desenvolvido)
  - [Conexão com o banco](#conexão-com-o-banco)
  - [Modelo de histórico do chat para que as mensagens persistam](#)
  - [Testes](#)
- [Avisos Finais](#avisos-finais)

## Habilidades

- Conseguir desenvolver um server socket usando o socket.io;

- Emitir eventos personalizados usando o socket.io;

- Usar o pacote `socket.io` do Node.js para criar aplicações que trafeguem mensagens através de sockets.

---

## O que foi desenvolvido
Este projeto apresenta um _chat_ online e ao utilizar essa aplicação um usuário deverá ser capaz de:

 - Usar um front-end para enviar mensagens a clientes conectados;
 - Visualizar o histórico de mensagens da conversa;
 - Visualizar os usuários online no momento;
 - Alterar o nome de usuário no chat em tempo real;

 Através do cliente é possível enviar e receber mensagens, trocar seu nome, ver usuários online.

O MVC é usado para renderizar as mensagens do histórico e usuários online, com ambos vindo do servidor.

O desenho abaixo demonstra como o projeto pode ser estruturado! 🧑‍🎨

![image](./exemplo.png)

---

## Conexão com o banco de dados:
As variáveis de ambiente receberão os seguintes valores

```
DB_URL=mongodb://localhost:27017/webchat/    // conexão local com o MongoDB
DB_NAME=webchat                             // nome do database
```

---

## Modelo de histórico do chat para que as mensagens persistam.

### Exemplo de um documento:
    ```js
    {
      message: 'Lorem ipsum',
      nickname: 'xablau',
      timestamp: '2021-04-01 12:00:00'
    }
    ```

---

## Testes

Para executar os testes localmente, você pode rodar o comando `npm test`.

Caso prefira testar um requisito por vez pode executar o teste da seguinte forma: `npm test tests/req1` (esse exemplo testa apenas o requisito 1)

⚠️ Antes de executar os testes requisitos, principalmente do requisito 4, feche o seu navegador, pois ele pode afetar a execução dos testes.

---

## Avisos Finais

Não se esqueça de avaliar sua experiência preenchendo o formulário. Leva menos de 3 minutos! (É possível que o link não esteja mais disponível).

[FORMULÁRIO DE AVALIAÇÃO DE PROJETO](https://be-trybe.typeform.com/to/ZTeR4IbH)
