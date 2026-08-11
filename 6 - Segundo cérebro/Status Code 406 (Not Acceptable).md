
30-01-2026 18:32

Tags: [[Web]], [[Desenvolvimento]], [[Tratamento de Dados]]
Status: #Maduro 

### Definição

O status code[^1] 406[^2] indica que ==o servidor falhou em localizar uma representação da informação requisitada que atenda os critérios de aceitação enviados na requisição[^3] e não deseja enviar a informação "default"==.

O servidor deve enviar na response do status 406 uma lista de representações encontradas para a informação requisitada a fim de que o usuário possa selecionar a opção que mais lhe seja satisfatória. ==A depender das permissões fornecidas pelo usuário, esse processo pode ser feito de forma automática==.

### Relevância

O envio desse status para o cliente quando necessário é crucial para indicar com mais precisão o erro cometido e facilitar o processo de correção para o reenvio da requisição e recebimento da informação desejada.


### Referências:

[^1]: [[HTTP Status Codes]]

[^2]: [[Status Codes 4xx (Client Error)]]

[^3]: [[Requests]]

[[IETF Status Code 406]]

[[0207 HTTP Status Codes]]

[[Understending+RESTFul+API's++Resource.pdf]]