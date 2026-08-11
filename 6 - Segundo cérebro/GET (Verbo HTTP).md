
07-08-2026 12:08

Tags: [[Web]], [[Desenvolvimento]], [[Tratamento de Dados]]
Status: #jovial 

### Definição

O verbo HTTP[^1] GET é utilizado quando o objetivo da requisição[^2] é ==obter alguma informação dentro do servidor==. Esta obtenção é realizada por meio da ==transferência de uma representação atual deste elemento  requisitado== no corpo de uma response[^3] contendo, normalmente, um status code 200[^4].

Não possui body[^7] e seus parâmetros são todos passados pela URL.

### Relevância

O método GET é o ==mecanismo primário de comunicação no protocolo HTTP==[^5] e o ==principal alvo de otimizações de performance==. sua estrutura é a base para outros verbos de requisição de informação e é sem dúvida o verbo mais utilizado de todos, juntamente com POST[^6].

### Considerações importantes

Mesmo sendo tentador imaginar a estruturação dos parâmetros para se chegar a determinado recurso como seu caminho em um sistema de arquivos ou uma arvore de recursos, esta não é uma restrição do método.

Mesmo a maioria dos recursos alvos de requisições GET de fato estarem estruturados em um sistema de arquivos, ==o único que precisa saber disso é o servido que os contém==. A requisição destes recursos pode ser (e é recomendado que seja) feita por meio de um comando a uma ==interface==[^8] fornecida pelo endpoint alvo da requisição. 

Dessa forma, ==os recursos e mecanismos internos do servidor permanecem encapsulados== e a informação pode ser retornada para o requisitante de forma segura e com a mesma eficiência.


### Referências:

[^1]: [[Verbos HTTP]]

[^2]: [[Requests]]

[^3]: [[Responses]]

[^4]: [[Status Code 200 (OK)]]

[^5]: [[Protocolo HTTP]]

[^6]: [[POST (Verbo HTTP)]]

[^7]: [[Request Message Body]]

[^8]: [[Interfaces]]

[[IETF GET (Verbos HTTP)]]

[[0208 Os Verbos HTTP e o REST]]