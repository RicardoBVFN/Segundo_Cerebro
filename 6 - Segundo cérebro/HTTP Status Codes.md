
22-01-2026 19:56

Tags: [[Web]], [[Tratamento de Dados]], [[Desenvolvimento]]
Status: #Maduro 

### Definição

São status codes ==mensagens numéricas que indicam estados da comunicação entre cliente e servidor==.

Podem indicar uma comunicação bem sucedida, um estado de carregamento/espera, operação realizada com sucesso ou erro. Cada status possui seu valor numérico específico que é ==retornado para o cliente durante sua comunicação com o web service==[^1].

### Relevância

Além de serem úteis para o monitoramento da comunicação entre cliente e servidor, as status codes são fundamentais para o bom funcionamento de um web service.

O uso apropriado destas mensagem permite um bom entendimento do cliente em relação ao status da sua requisição. Caso ela tenha se perdido no caminho, tenha sido mal elaborada, esteja sendo processada ou para quase qualquer outro estado, uma status code pode ser enviada para identificar essa situação para o cliente.

Além disso, o tipo de erro devolvido pelo sistema facilita de forma considerável o processo de debugging e refinamento do código por pare do desenvolvedor.



### Referências:

[^1]: [[Webservices]]

[[Requests]]

[[Responses]]

[[0207 HTTP Status Codes]]

[[Understending+RESTFul+API's++Resource.pdf]]