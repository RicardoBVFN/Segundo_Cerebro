

22-01-2026 18:37

Tags: [[Web]], [[Desenvolvimento]], [[Tratamento de Dados]]
Status: #Maduro 

### Definição

Consiste nas informações de busca passadas pelo cliente na requisição[^1] a respeito da informação que ele deseja obter do servidor. Normalmente são informações de identificação, como ID, path, etc. Se localiza logo abaixo da request message header[^2].
### Exemplos

```
GET /doc/test.html HTTP/1.1         //
Accept: image/gif, image/jpeg, */*  //
Accept-Language: en-us              // request message header
Accept-Encoding: gzip, deflate      //
User-Agent: Mozilla/4.0             //
Content-Length: 35                  //

bookId=12345&author=Tan+Ah+Tech // request message body
```

### Relevância

A boa elaboração da request message body é fundamental para uma comunicação eficiente entre cliente e servidor, já que é ela que vai ==auxiliar o mecanismo do web service[^3] na busca ou tratamento da informação do cliente==. 

Além disso, a estruturação correta bem como a proteção de sua informação, garantem o bom funcionamento do servidor e previnem comportamento inesperados tanto da parte do servidor quanto do cliente.


### Referências:

[^1]: [[Requests]]

[^2]: [[Request Message Reader]]

[^3]: [[Webservices]]

[[0205 Entendendo Request e Response]]

[[Understending+RESTFul+API's++Resource.pdf]]