
30-01-2026 17:51

Tags: [[Web]], [[Desenvolvimento]], [[Tratamento de Dados]]
Status: #Maduro 

### Definição

O status code[^1] 403[^2] indica que ==as credenciais enviadas na requisição[^3] são inválidas e o cliente está proibido de acessar a informação requisitada==. Diferentemente do status code 401[^4], uma mensagem de 403 indica uma ==restrição mais severa quanto ao acesso do cliente a informação requisitada==.

Caso o servidor deseje não informar a existência da informação proibida para o cliente ele deve enviar um status code 404[^5].

### Relevância

O envio desse status para o cliente quando necessário é crucial para indicar com mais precisão o erro cometido e facilitar o processo de correção para o reenvio da requisição. É muito aplicado a senários de ==consultas de materiais sensíveis, acessos a sites protegidos, dentre outros==.


### Referências:

[^1]: [[HTTP Status Codes]]

[^2]: [[Status Codes 4xx (Client Error)]]

[^3]: [[Requests]]

[^4]: [[Status Code 401 (Unauthorized)]]

[^5]: [[Status Code 404 (Not Found)]]

[[IETF Status Code 403]]

[[0207 HTTP Status Codes]]

[[Understending+RESTFul+API's++Resource.pdf]]