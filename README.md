# socket-chat

## Testando o chat
1. Entre no diretório do projeto
2. Rode o comando a seguir para rodar o servidor:

`./server`

3. Após o servidor estar funcionando, abra outro terminal e use o comando a seguir para rodar o Client A:

`./client_a`

4. Depois disso, use o comando a seguir para rodar o Cliente B:

`./client_b`

5. Agora mande uma mensagem através do terminal do client_a e observe a mensagem chegando no terminal do client_b, depois envie uma mensagem do client_b e observe chegando no client_a.

6. Depois veja o terminal do server e observe que cada mensagem enviada passa por lá.

## Limitações:
- Atualmente um cliente não pode enviar duas mensagens simultâneas
- Para que um cliente possa enviar uma mensagem, é necessário que ele receba uma mensagem antes, com execção da primeira mensagem
