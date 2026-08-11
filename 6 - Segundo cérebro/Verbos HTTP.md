
06-08-2026 15:15

Tags: [[Web]], [[Desenvolvimento]], [[Informática]]
Status: #jovial 

### Definição

Verbos HTTP[^1] consistem em ==explicitações verbais do tipo de ação que será tomada a partir do processamento das requisição==[^2]. Além de definirem a abordagem específica a ser tomada pela requisição, ==definem também o que é esperado pelo cliente na response==[^3].

Os principais Verbos são: GET[^4], PUT[^5], POST[^6] e DELETE[^7].
Porém, para casos mais específicos podem ser usados ainda: HEAD[^8], CONNECT[^9], OPTIONS[^10] e TRACE[^11]
### Relevância

Por se tratar do Token primário da requisição, é ele que define toda a semântica da requisição. A especificação, estrutura, tamanho e retorno esperado dependem de qual verbo esta sendo utilizado. 

A definição correta e boa aplicação dos verbos HTTP são fundamentais para uma comunicação eficiente entre webservices[^12]. A boa aplicação destes verbos reflete a estruturação do webservice, do cliente e da mensagem, devendo ser adaptada caso a caso para fins de otimização e segurança.


### Referências:

[^1]: [[Protocolo HTTP]]

[^2]: [[Requests]]

[^3]: [[Responses]]

[^4]: [[GET (Verbo HTTP)]]

[^5]: [[PUT (Verbo HTTP)]]

[^6]: [[POST (Verbo HTTP)]]

[^7]: [[DELETE (Verbo HTTP)]]

[^8]: [[HEAD (Verbo HTTP)]]

[^9]: [[CONNECT (Verbo HTTP)]]

[^10]: [[OPTIONS (Verbo HTTP)]]

[^11]: [[TRACE (Verbo HTTP)]]

[^12]: [[Webservices]]

[[IETF Verbos HTTP]]

[[0208 Os Verbos HTTP e o REST]]