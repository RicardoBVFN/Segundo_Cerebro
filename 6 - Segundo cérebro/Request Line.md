

22-01-2026 09:32

Tags: [[Web]], [[Tratamento de Dados]], [[Desenvolvimento]]
Status: #Maduro 
### Definição

Consiste na primeira linha de uma requisição[^1] HTTP[^2]. ==Define o protocolo que será usado== (GET e POST por exemplo) bem como ==contém informações referentes o endereço do remetente==.

Em conjunto com os request headers[^3], constitui o request message reader[^4] (o cabeçalho da requisição).

### Exemplo

```
GET /doc/test.html HTTP/1.1
```

### Relevância

A informações presentes na request line são de fundamental importância para a comunicação entre cliente e servidor. Nela são definidos os parâmetros básicos de formato da requisição bem como são passadas as primeira informações a respeito do requisitante.


### Referências:

[^1]: [[Requests]]

[^2]: [[Protocolo HTTP]]

[^3]: [[Request Headers]]

[^4]: [[Request Message Reader]]

[[0205 Entendendo Request e Response]]

[[Understending+RESTFul+API's++Resource.pdf]]