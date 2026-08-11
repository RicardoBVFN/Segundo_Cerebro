

22-01-2026 15:44

Tags: [[Web]], [[Desenvolvimento]], [[Tratamento de Dados]]
Status: #Maduro 

### Definição

Representam o restante do corpo do cabeçalho de uma response[^1]. Contem ==informações referentes ao tratamento da sua respectiva requisição==[^2].

Em conjunto com a status line[^3], forma a response message header[^4]. 

Em casos normais, informações como data de envia da response, status da conexão com o cliente, dados do servidor conectado e tipo de conteúdo enviado sempre estarão presentes. Outras informações que podem estar presentes são ETags, tamanho do arquivo retornado, ultima data de modificação do arquivo retornado, dentre outras.
### Exemplos

```
// exemplo em uma response html

Date: Sun, 08 Feb xxxx 01:11:12 GMT
Server: Apache/1.3.29 (win 32)
Last-Modified: Sat, 07 Feb xxxx
ETag: "0-23-4024c3a5"
Accepted-Ranges: bytes
Content-Length: 35
Connection: close
Content-Type: text/html
```

### Relevância

Os response headres são importantes pois apresentam uma série de informações relevantes tanto para o rastreamento da informação recebida quanto para debugging caso haja algum erro na conexão ou na resposta recebida.


### Referências:

[^1]: [[Responses]]

[^2]: [[Requests]]

[^3]: [[Status Line]]

[^4]: [[Response Message Header]]

[[0205 Entendendo Request e Response]]

[[Understending+RESTFul+API's++Resource.pdf]]