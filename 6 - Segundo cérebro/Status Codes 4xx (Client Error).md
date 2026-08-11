
29-01-2026 18:17

Tags: [[Web]], [[Desenvolvimento]], [[Tratamento de Dados]]
Status: #jovial 

### Definição

Os status codes[^1] da casa das quatro centenas indicam situações em que o cliente ao enviar a requisição[^2] cometeu um erro que resultou no não processamento da mesma.


> [!NOTE] Definição da IETF
> "The 4xx (Client Error) class of status code indicates that the client
   seems to have erred.  Except when responding to a HEAD request, the
   server SHOULD send a representation containing an explanation of the
   error situation, and whether it is a temporary or permanent
   condition.  These status codes are applicable to any request method.
   User agents SHOULD display any included representation to the user."
   .
   [Link](https://datatracker.ietf.org/doc/html/rfc7231#section-6.5)

### Relevância

Essa categoria de status é de vital importância para o usuário. Uma mensagem corretamente utilizada pode ==auxiliar o desenvolvedor no processo de debug do webservice[^3] bem como na verificação de bom funcionamento do mesmo==.


### Referências:

[^1]: [[HTTP Status Codes]]

[^2]: [[Requests]]

[^3]: [[Webservices]]

[[0207 HTTP Status Codes]]

[[Understending+RESTFul+API's++Resource.pdf]]