

22-01-2026 10:20

Tags: [[Web]], [[Tratamento de Dados]], [[Desenvolvimento]]
Status: #Maduro 

### Definição

Consiste no cabeçalho de uma requisição[^1]. Em uma requisição HTTP[^2], é formado pela request line[^3] e pelas request header[^4]

### Exemplos

```
// exemplo em uma requisição http

GET /doc/test.html HTTP/1.1 // request line
Accept: image/gif, image/jpeg, */*  //
Accept-Language: en-us              //
Accept-Encoding: gzip, deflate      // request readers
User-Agent: Mozilla/4.0             //
Content-Length: 35                  //
```

### Relevância

O cabeçalho da requisição é de vital importância pois nele estão contidas as ==informações referentes a referenciação do remetente, protocolo de comunicação adotado bem como as formatações desejadas== para as informações requisitadas ao servidor. 


### Referências:

[^1]: [[Requests]]

[^2]: [[Protocolo HTTP]]

[^3]: [[Request Line]]

[^4]: [[Request Headers]]

[[0205 Entendendo Request e Response]]

[[Understending+RESTFul+API's++Resource.pdf]]