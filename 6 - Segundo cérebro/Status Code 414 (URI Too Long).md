
24-02-2026 17:43

Tags: [[Web]], [[Desenvolvimento]], [[Tratamento de Dados]]
Status: #Maduro 

### Definição

O status code[^1] 414[^2] indica que o servidor se recusou a processar a requisição[^3] pois a URI[^4] informada é muito extensa ou apresenta alguma irregularidade.

Este tipo de erro ocorre normalmente em poucas situações. Quando o cliente, de forma inapropriada, converteu uma requisição POST em GET, gerando uma quantidade enorme de parâmetros. Quando a URI gera um loop infinito (uma referência a um elemento que se refere ao antecedente e este ao sucessor, por exemplo). Por fim, quando o servidor está sob ataque e o atacante tenta buscar aberturas para invadir o sistema.

### Relevância

O envio desse status para o cliente quando necessário é crucial para indicar com mais precisão o erro cometido e facilitar o processo de correção para o reenvio da requisição.


### Referências:

[^1]: [[HTTP Status Codes]]

[^2]: [[Status Codes 4xx (Client Error)]]

[^3]: [[Requests]]

[^4]: [[URI]]

[[IETF Status Code 414]]

[[0207 HTTP Status Codes]]

[[Understending+RESTFul+API's++Resource.pdf]]
