
29-01-2026 11:36

Tags: [[Web]], [[Desenvolvimento]], [[Tratamento de Dados]]
Status: #Maduro 

### Definição

O status code[^1] 307[^2] indica que ==o recurso requisitado[^3] se encontra temporariamente em outra URI[^4]==. Como esse destino é temporário e pode ser alterado, ==o usuário deve permanecer na URI original da requisição a fim de poder realizar novas requisições==.

Diferentemente do status code 302[^3], quando um brouser reecebe um status 307 do servidor ele ==deve obrigatoriamente manter o método HTTP original e apenas redirecioná-lo para o novo destino==. Ele surgiu justamente para solucionar a confusão causada pela mudança de método com o 302.
### Relevância

Esta menagem é importante para alertar o usuário sobre como sua requisição esta sendo processada e permitir que o mesmo possa escolher como prosseguir. ==Muito presente em APIs, sistemas de pagamento e webservices[^4] modernos== devido a seu comportamento previsível.


### Referências:

[^1]: [[HTTP Status Codes]]

[^2]: [[Status Codes 3xx]]

[^3]: [[Status Code 302 (Found)]]

[^4]: [[Webservices]]

[[IETF Status Code 307]]

[[0207 HTTP Status Codes]]

[[Understending+RESTFul+API's++Resource.pdf]]