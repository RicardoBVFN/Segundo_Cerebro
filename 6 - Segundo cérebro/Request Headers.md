

22-01-2026 09:53

Tags: [[Web]], [[Desenvolvimento]], [[Tratamento de Dados]]
Status: #Maduro 

### Definição

Consiste no restante do corpo do cabeçalho de uma requisição[^1] HTTP[^2]. Se encontra logo abaixo da request line[^3] e ==contém todos os parâmetros de aceitação e formatação da response[^4] esperados pelo cliente==.

Em conjunto com a request line, forma a request message header[^5] (cabeçalho da requisição).

### Exemplo

```
Accept: image/gif, image/jpeg, */*
Accept-Language: en-us
Accept-Encoding: gzip, deflate
User-Agent: Mozilla/4.0
Content-Length: 35
```

### Relevância

Os request headers são de extrema importância para a comunicação eficiente entre cliente servidor. São os parâmetros de formatação por ele passados que facilitam a busca do servidor pela informação. Além disso, ==garantem que a resposta devolvida atende aos requisitos de formatação do cliente, preservando a integridade do bom funcionamento da aplicação==.


### Referências:

[^1]: [[Requests]]

[^2]: [[Protocolo HTTP]]

[^3]: [[Request Line]]

[^4]: [[Responses]]

[^5]: [[Request Message Reader]]

[[0205 Entendendo Request e Response]]

[[Understending+RESTFul+API's++Resource.pdf]]