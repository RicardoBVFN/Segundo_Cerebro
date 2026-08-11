
24-02-2026 17:27

Tags: [[Web]], [[Desenvolvimento]], [[Tratamento de Dados]]
Status: #Maduro 

### Definição

O status code[^1] 413[^2] ocorre quando ==o servidor se recusa ou não é capaz de processar a requisição[^3] pois seu conteúdo é muito extenso==. Caso o protocolo permita, a requisição deve ser descartada, caso contrário, a conexão deve ser interrompida.

Caso este estado seja temporário, por qualquer motivo que seja, o servidor pode enviar um retry after header[^4] para que o usuário possa tentar novamente após determinado período de tempo.

### Relevância

O envio desse status para o cliente quando necessário é crucial para indicar com mais precisão o erro cometido e facilitar o processo de correção para o reenvio da requisição.


### Referências:

[^1]: [[HTTP Status Codes]]

[^2]: [[Status Codes 4xx (Client Error)]]

[^3]: [[Requests]]

[^4]: [[Response headers]]

[[IETF Status Code 413]]

[[0207 HTTP Status Codes]]

[[Understending+RESTFul+API's++Resource.pdf]]