

22-01-2026 16:04

Tags: [[Web]], [[Desenvolvimento]], [[Tratamento de Dados]]
Status: #Maduro 

### Definição

Consiste no cabeçalho de uma response[^1]. É formada pela status line[^3] e pelos response headers[^4].
### Exemplos

```
// exemplo de uma response header no protocolo http

HTTP/1.1 200 OK // status line
Date: Sun, 08 Feb xxxx 01:11:12 GMT    //
Server: Apache/1.3.29 (win 32)         //
Last-Modified: Sat, 07 Feb xxxx        //
ETag: "0-23-4024c3a5"                  //  response headers
Accepted-Ranges: bytes                 //
Content-Length: 35                     //
Connection: close                      //
Content-Type: text/html                //
```

### Relevância

O response reader é de vital importância par a manutenção de web services pois nele estarão contidos os ==principais dados referentes a conexão entre cliente e servidor, bem como as informações referentes à reposta deda pelo servidor==.

os dados contidos nesse cabeçalho facilitam bastante o processo de debugging caso haja algum erro na conexão entre cliente servidor ou na informação recebida.



### Referências:

[^1]: [[Responses]]

[^2]: [[Protocolo HTTP]]

[^3]: [[Status Line]]

[^4]: [[Response headers]]

[[0205 Entendendo Request e Response]]

[[Understending+RESTFul+API's++Resource.pdf]]