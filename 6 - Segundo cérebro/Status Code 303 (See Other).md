
12-08-2026 10:37

Tags: [[Web]], [[Desenvolvimento]], [[Tratamento de Dados]]
Status: #jovial 

### Definição

O status code[^1] 303[^2] é retornado quando o servidor ==redireciona o cliente para um recurso diferente do que ele almejava em sua requisição==[^3].

### Relevância

Sendo ==um dos status de redirecionamento mais utilizados==, o status code 303 se mostra muito útil principalmente no contexto de ==otimização computacional do servidor==. 

### Considerações importantes

O redirecionamento ==deve gerar uma response[^4] indireta contendo URI do novo recurso em seu location header==[^5]. Em posse desta informação, o cliente pode realizar uma ==nova requisição consultiva (GET[^6] ou HEAD[^7]) que deve também ser redirecionada== e a resposta a esta requisição servir como ==resposta à original==, lembrando o conceito de ==recursão==[^8].

Este status code pode ser usado para qualquer tipo de método HTTP[^9], mas é principalmente utilizado para ==permitir que a resposta a uma requisição POST[^10] possa ser redirecionada==. Fazendo isso, além de ==reduzir a carga computacional do servidor==, por se tratar de uma entidade já existente, permite que a informação retornada por essa requisição seja mais facilmente ==armazenada em forma de cache==, trazendo eficiência para a comunicação entre cliente e servidor.



### Referências:

[^1]: [[HTTP Status Codes]]

[^2]: [[Status Codes 3xx]]

[^3]: [[Requests]]

[^4]: [[Responses]]

[^5]: [[Response headers]]

[^6]: [[GET (Verbo HTTP)]]

[^7]: [[HEAD (Verbo HTTP)]]

[^8]: [[Recursão]]

[^9]: [[Verbos HTTP]]

[^10]: [[POST (Verbo HTTP)]]

[[IETF Status Code 303 (See Other)]]
