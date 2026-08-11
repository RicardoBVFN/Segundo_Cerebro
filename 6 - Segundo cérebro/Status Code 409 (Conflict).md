
23-02-2026 16:37

Tags: [[Web]], [[Desenvolvimento]], [[Tratamento de Dados]]
Status: #Maduro 

### Definição

O status code[^1] 409[^2] é utilizado quando ==a requisição[^3] não pode ser processada devido a um estado conflitante do recurso alvo em relação a ação requisitada pela mesma==.

Sua aplicação sugere que o usuário é capaz de identificar o conflito em questão e submeter novamente a requisição por conta própria. Portanto, ==é esperado que o servidor conceda informações esclarecedoras a respeito do conflito em sua response==[^4].

### Relevância

Este status code normalmente é utilizado no contexto de requisições de alteração/cadastramento. Um exemplo comum é no versionamento de documentos. Caso um usuário queira submeter uma alteração em um repositório e o arquivo a ser editado já sofreu alterações (merge conflict) o status code retornado deve ser 409.


### Referências:

[^1]: [[HTTP Status Codes]]

[^2]: [[Status Codes 4xx (Client Error)]]

[^3]: [[Requests]]

[^4]: [[Responses]]

[[IETF Status Code 409]]

[[0207 HTTP Status Codes]]

[[Understending+RESTFul+API's++Resource.pdf]]