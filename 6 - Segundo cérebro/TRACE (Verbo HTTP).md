
18-08-2026 10:37

Tags: [[Web]], [[Desenvolvimento]], [[Tratamento de Dados]]
Status: #jovial 

### Definição

O verbo[^1] TRACE define uma requisição[^2] cujo objetivo é receber um ==loop-back contendo a exata mesma mensagem recebida pelo servidor== reverente a esta mesa requisição. Esta deve ser devolvida na forma  de body[^3] de uma response[^4] contendo um status code 200[^5].

### Relevância

A principal função de uma requisição TRACE é o ==debub==. Por meio dela, é possível verificar tanto a integridade do túnel de conexão[^6] quanto quais headers[^7] são adicionados a esta requisição antes de chegar ao servidor destino.

### Considerações relevantes

Atualmente, ==a maioria dos servidores web desabilitam o recebimento e envio de requisições TRACE devido aos riscos de segurança envolvidos==. Por carregar todos os headers necessários parta que uma requisição chegue ao servidor de destino, um atacante pode interceptar uma requisição TRACE e se apossar de informações sensíveis atreladas a mesma nestes headers. Portanto, a fim de preservar a integridade e segurança dos endpoints, a melhor alternativa é utilizar ==ferramentas internas de visibilidade== para monitorar a comunicação entre estes webservices[^8].


### Referências:

[^1]: [[Verbos HTTP]]

[^2]: [[Requests]]

[^3]: [[Response Message Body]]

[^4]: [[Responses]]

[^5]: [[Status Code 200 (OK)]]

[^6]: [[Túnel de Conexão]]

[^7]: [[Request Headers]]

[^8]: [[Webservices]]

[[TRACE.pdf]]

[[IETF TRACE (Verbo HTTP)]]

[[0209 Os Verbos HTTP menos conhecidos]]