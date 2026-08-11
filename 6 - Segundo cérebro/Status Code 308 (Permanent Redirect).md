
30-01-2026 11:53

Tags: [[Web]], [[Desenvolvimento]], [[Tratamento de Dados]]
Status: #Maduro 

### Definição

O status code[^1] 301[^2] indica que ==o recurso requisitado pela request[^3] só pode ser obtido em outra URI[^4]==. Isso diz que ==o usuário será redirecionado permanentemente para outro local a fim de prosseguir com o processamento de sua requisição==.

Caso autorizado pelo usuário, esse processo pode ser realizado de forma automática. Caso contrário, uma mensagem explicita deve ser apresentada ao mesmo informando do redirecionamento e pedindo sua autorização para o fazer. Essa request pode ser cacheada, contanto que autorizada previamente.

Este status surgiu recentemente como solução para corrigir erros frequentes causados pela conversão indevida de método no encaminhamento de requisições. ==Diferentemente do status code 301[^4], ao receber um status code 308 o browser é obrigado a manter o mesmo método da requisição original durante o encaminhamento da mesma==.

### Relevância

Serve para manter o usuário informado quanto ao processamento de sua requisição, bem como permitir que ele decida se quer ser redirecionado para outro local antes de o fazer. ==Muito presente em sistemas de pagamento, APIs e webservices[^5] modernos==.


### Referências:

[^1]: [[HTTP Status Codes]]

[^2]: [[Status Codes 3xx]]

[^3]: [[Requests]]

[^4]: [[Status Code 301 (Moved Permanently)]]

[^5]: [[Webservices]]

[[IETF Status Code 308]]

[[0207 HTTP Status Codes]]

[[Understending+RESTFul+API's++Resource.pdf]]