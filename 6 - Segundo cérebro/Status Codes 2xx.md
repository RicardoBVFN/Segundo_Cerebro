

23-01-2026 10:29

Tags: [[Web]], [[Desenvolvimento]], [[Tratamento de Dados]]
Status: #Maduro 

### Definição

O status codes[^1] da casa dos duzentos representam sucesso total ou parcial do processo de requisição[^2]. Podem ser retornados na própria response[^3] do servidor ou durante a comunicação do cliente com o mesmo.


> [!NOTE] Definição IETF
> "The 2xx (Successful) class of status code indicates that the client's
   request was successfully received, understood, and accepted."
   .
   [Link](https://datatracker.ietf.org/doc/html/rfc7231#section-6.3)

### Relevância

Mesmo que indiquem operações bem sucedidas no tratamento de requisições, os status code 2xx são relevantes também para validar se operações requisitadas foram bem sucedidas, se o processo pelo qual a response passou foi o desejado, dentre outros parâmetros das regras de negócio da aplicação.



### Referências:

[^1]: [[HTTP Status Codes]]

[^2]: [[Requests]]

[^3]: [[Responses]]

[[0207 HTTP Status Codes]]

[[Understending+RESTFul+API's++Resource.pdf]]