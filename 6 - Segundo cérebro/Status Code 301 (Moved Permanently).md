
29-01-2026 10:58

Tags: [[Web]], [[Desenvolvimento]], [[Tratamento de Dados]]
Status: #Maduro 

### Definição

O status code[^1] 301[^2] indica que ==o recurso requisitado pela request[^3] só pode ser obtido em outra URI[^4]==. Isso diz que ==o usuário será redirecionado permanentemente para outro local a fim de prosseguir com o processamento de sua requisição==. Caso autorizado pelo usuário, esse processo pode ser realizado de forma automática, caso contrário, uma mensagem explicita deve ser apresentada ao mesmo informando do redirecionamento e pedindo sua autorização para o fazer. Essa request pode ser cacheada, contanto que autorizada previamente.

Este status, por ser mais antigo, ==não garante a preservação do método utilizado originalmente na requisição, podendo gerar erros por conversão inapropriada no encaminhamento de requisição==. O erro mais comum é a conversão indevida de uma requisição POST em uma GET ao ser encaminhada.
### Relevância

Serve para manter o usuário informado quanto ao processamento de sua requisição, bem como permitir que ele decida se quer ser redirecionado para outro local antes de o fazer. ==Muito presente em navegações simples e sistemas legado==.


### Referências:

[^1]: [[HTTP Status Codes]]

[^2]: [[Status Codes 3xx]]

[^3]: [[Requests]]

[^4]: [[URI]]

[[IETF Status Code 301]]

[[0207 HTTP Status Codes]]

[[Understending+RESTFul+API's++Resource.pdf]]