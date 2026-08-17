
14-08-2026 18:01

Tags: [[Web]], [[Desenvolvimento]], [[Tratamento de Dados]]
Status: #jovial 

### Definição

O verbo HTTP[^1] CONNECT define uma requisição[^2] que tem por finalidade ==estabelecer um túnel de conexão[^3] entre o cliente e o servidor alvo==. 

### Relevância

É apenas por meio de uma requisição CONNECT que uma conexão entre endpoints é formada e a troca de informações viabilizada. O verbo foi definido especificamente para esta finalidade e é a porta de entrada para qualquer comunicação no protocolo HTTP[^4].

### Considerações importantes

Uma requisição do tipo CONNECT possui uma semântica única. A estrutura do request target consiste apenas do ==host e da porta para conexão==.

Exemplo:

CONNECT server.example.com:80 HTTP/1.1
Host: server.example.com

O servidor deve ter uma ==lista de portas mapeadas para estabelecimento de tuneis de comunicação==, a fim de se proteger de conexões mal intencionadas. Por exemplo, caso a porta alvo da requisição seja a 25, porta reservada para o trafego no protocolo SMTP, isso pode fazer com que o servidor fique sujeito a receber emails maliciosos ou SPAM. ==Caso a requisição não informe ou contenha uma porta inválida, o servidor alvo deve recusar a requisição e enviar um status code 400==[^5]. 


### Referências:

[^1]: [[Verbos HTTP]]

[^2]: [[Requests]]

[^5]: [[Túnel de Conexão]]

[^4]: [[Protocolo HTTP]]

[^5]: [[Status Code 400 (Bad Request)]]

[[IETF CONNECT (Verbo HTTP)]]

[[0209 Os Verbos HTTP menos conhecidos]]