
11-08-2026 20:46

Tags: [[Web]], [[Desenvolvimento]], [[Tratamento de Dados]]
Status: #jovial 

### Definição

Uma requisição[^1] do tipo POST tem como finalidade ==enviar informações em anexo no seu body[^2], normalmente na forma de entidades inteiras, para serem processadas pelo servidor alvo da requisição==. Este processamento pode ser tanto de ==bloqueio, alteração ou criação de um elemento alvo neste servidor==, sendo esta finalidade tratada no header[^3] da requisição.

### Relevância

Juntamente com o GET[^4], ==este é um dos tipos de requisição mias utilizados em web services==[^5]. Aplicado principalmente para criar ou atualizar elementos no servidor, tais como usuários, produtos, credenciais de acesso, dentre outros.

### Considerações importantes

Para tornar explícita a semântica aceita para o cliente, ==o servidor deve devolver um status code[^6] correspondente à ação realizada== a partir do processamento da requisição post enviada.

Exemplo: 201[^7] para criação de uma usuário (acompanhado de um location header contendo o meio de localizar elemento primário criado), 202[^8] para login, etc.

Além disso, se o processamento de uma requisição POST gerar um elemento idêntico a um já existente, ==o servidor deve responder o cliente com um status code 303[^9] contendo o endereço deste elemento já existente==. Dessa forma, o resultado desta requisição pode ser ==mais facilmente armazenado em cache== e este formato é mais alinhado com ==cache compartilhado==, o que aumenta a eficiência na comunicação entre cliente e servidor.


### Referências:

[^1]: [[Requests]]

[^2]: [[Request Message Body]]

[^3]: [[Request Headers]]

[^4]: [[GET (Verbo HTTP)]]

[^5]: [[Webservices]]

[^6]: [[HTTP Status Codes]]

[^7]: [[Status Code 201 (Created)]]

[^8]: [[Status code 202 (Accepted)]]

[^9]: [[Status Code 303 (See Other)]]

[[IETF POST (Verbo HTTP)]]

[[0208 Os Verbos HTTP e o REST]]
