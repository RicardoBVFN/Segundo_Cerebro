
29-01-2026 11:09

Tags: [[Web]], [[Desenvolvimento]], [[Tratamento de Dados]]
Status: #Maduro 

### Definição

O status code[^1] 302[^2] indica que ==o recurso requisitado[^3] se encontra temporariamente em outra URI[^4]==. Como esse destino é temporário e pode ser alterado, ==o usuário deve permanecer na URI original da requisição a fim de poder realizar novas requisições==.

Diferentemente do status code 307[^5], quando o brouser recebe um status 302 ele ==pode alterar o método da requisição, comprometendo a comunicação entre cliente e servidor==.

### Relevância

Esta menagem é importante para alertar o usuário sobre como sua requisição esta sendo processada e permitir que o mesmo possa escolher como prosseguir. Muito presente em ==aplicações legado ou navegações simples==.


### Referências:

[^1]: [[HTTP Status Codes]]

[^2]: [[Status Codes 3xx]]

[^3]: [[Requests]]

[^4]: [[URI]]

[^5]: [[Status Code 307 (Temporary Redirect)]]

[[IETF Status Code 302]]

[[0207 HTTP Status Codes]]

[[Understending+RESTFul+API's++Resource.pdf]]