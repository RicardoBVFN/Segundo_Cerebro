
14-08-2026 11:46

Tags: [[Web]], [[Desenvolvimento]], [[Tratamento de Dados]]
Status: #jovial 

### Definição

O verbo HTTP[^1] DELETE define uma requisição[^2] cujo intuito é ==excluir, arquivar ou remover um determinado recurso do servidor alvo==. 
### Relevância

Por seu caráter expresso de deleção, é muito aplicado em sistemas de manutenção de recursos a fim de trazer ==rastreabilidade e definição da autoria da ação de deleção sobre determinado recurso==. Um bom exemplo é o controle de versionamento no GitHub, no qual o usuário que fizer uma deleção em um repositório o fará por meio de uma requisição DELETE, tendo seus dados identificados e expostos no histórico de commits.

### Considerações importantes

Demais elementos associados, bem como outras representações deste recurso podem ou não ser deletadas por esta requisição, dependendo apenas do mecanismo de implementação interno do servidor.

Mesmo não havendo uma definição formal para a semântica de uma requisição DELETE, é de bom senso interpretar que elementos presentes em seu body[^3] não devem ser processados já que para o processamento da deleção é necessário apenas o location header[^4]. ==Servidores não devem processar, muito menos criar, elementos a partir de representações recebidas em uma requisição DELETE==. A presença de tais características pode ser um forte indício de um request smuggling attack[^5].

Uma response[^6] referente a uma requisição DELETE não pode ser armazenada em cache. ==Caso esta passe por algum cache do elemento deletado este deve ser invalidado==.


### Referências:

[^1]: [[Verbos HTTP]]

[^2]: [[Requests]]

[^3]: [[Response Message Body]]

[^4]: [[Request Headers]]

[^5]: [[Request Smuggling Atack]]

[^6]: [[Responses]]

[[IETF DELETE (Verbo HTTP)]]

[[0208 Os Verbos HTTP e o REST]]