
23-02-2026 17:01

Tags: [[Web]] [[Desenvolvimento]], [[Tratamento de Dados]]
Status: #Maduro 

### Definição

O status code[^1] 410[^2] é empregado quando ==o acesso ao recurso alvo da requisição[^3] não é mais possível==. Diferentemente do status code 404[^4], quando se é retornado um status code 410 entende-se que ==o bloqueio do acesso ao recurso é permanente==.

### Relevância

Este status code é empregado normalmente quando os administradores do servidor deliberadamente decidem bloquear o acesso a determinado recurso. Realizar uma manutenção, se proteger de um ataque ou simplesmente para que o conteúdo pertencente a um cliente que não mais é sócio dos mantenedores do servidor possa ser acessado são alguns exemplos de aplicações frequentes.

É importante ressaltar que ==este status não deve ser utilizado de forma indiscriminada==, a fim de não gerar confusão, e sim ser alternado com o erro 404 bem como os demais.


### Referências:

[^1]: [[HTTP Status Codes]]

[^2]: [[Status Codes 4xx (Client Error)]]

[^3]: [[Requests]]

[^4]: [[Status Code 404 (Not Found)]]

[[IETF Status Code 410]]

[[0207 HTTP Status Codes]]

[[Understending+RESTFul+API's++Resource.pdf]]