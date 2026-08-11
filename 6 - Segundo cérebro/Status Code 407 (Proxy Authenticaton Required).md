
13-02-2026 11:53

Tags: [[Web]], [[Desenvolvimento]], [[Tratamento de Dados]]
Status: #Maduro 

### Definição

O status code[^1] 407[^2], de forma similar ao status code 401[^3], indica que o cliente necessita de uma autorização adicional para completar o processamento de sua requisição[^4]. ==Entretanto, neste caso em específico , a autorização necessária se refere a uma autenticação referente ao uso de um servidor proxy==.

O servidor proxy deve devolver um Proxy-Authenticate header[^5] contendo um critério de validação para o cliente enquanto este deve reenviar sua requisição com um Proxy-Authenticate header[^6] contendo a nova autenticação requerida.

### Relevância

O envio desse status para o cliente quando necessário é crucial para indicar com mais precisão o erro cometido e facilitar o processo de correção para o reenvio da requisição e recebimento da informação desejada.


### Referências:

[^1]: [[HTTP Status Codes]]

[^2]: [[Status Codes 4xx (Client Error)]]

[^3]: [[Status Code 401 (Unauthorized)]]

[^4]: [[Requests]]

[^5]: [[Response headers]]

[^6]: [[Request Headers]]

[[IETF Status Code 407]]

[[0207 HTTP Status Codes]]

[[Understending+RESTFul+API's++Resource.pdf]]