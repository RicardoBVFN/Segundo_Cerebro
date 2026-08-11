
19-01-2026 15:45

Tags: [[Web]], [[Desenvolvimento]], [[Tratamento de Dados]]
Status: #Maduro 

### Definição

Consiste em um estilo de arquitetura de software para sistemas distribuídos de hipermídia (link e troca de informações).

Por definição, estes sistemas devem seguir uma série de requisitos, sendo eles:

-  **Cliente/servidor**: um serviço REST deve ter as ==interfaces[^1] de cliente e servidor separadas.==
- **Stateless server**: o servidor não deve armazenar o estado do cliente, as ==requisições enviadas pelo cliente devem ser suficientes para atender a demanda do servidor==.
- **Cacheable**: aplicações REST podem armazenar certos dados fornecidos ao cliente no formato de cache para uso posterior do serviço, com tanto que o mesmo deixe ==explícito para o usuário que este recurso é implementado, e este decida se deseja fazer uso do mesmo ou não.==
- ==**Interface uniforme**==: a comunicação entre cliente e servidor é feita somente por meio de uma interface uniforme, na qual os recursos são identificado por meio de URIs[^2], a manipulação de recursos é feita a partir de suas representações (análogo a objeto[^3]), as mensagens são auto descritivas e é aplicado o sistema de HATEOAS[^4].
- **Constituição em camadas**: os sistemas REST devem ser constituídos por múltiplas camadas, ==aumentando a modularidade== e fazendo com que suportem serviços como ==firewalls, criptografia, validação de dados, dentre outros==.

### Relevância

Atualmente, quase toda a estrutura de serviços web se da por meio da comunicação paralela entre cliente e servidor, tendo o ==REST como padrão de mercado== implementado.

A comunicação entre serviços e entre usuários e servidor sempre demandou padronização, tanto no formato das requisições[^5] quanto no formato dos dados. Anteriormente, empregava-se o SOAP[^6], uma outra estrutura de comunicação cliente/servidor e entre serviços. Mesmo com as limitações quanto à estruturação dos dados e quanto ao meio de comunicação, o SOAP ainda foi um sucesso pois sanava uma demanda real por padronização na era de reestruturação da internet.

Com o tempo surgiu o REST. Por se tratar de um modelo arquitetural, diferentemente do SOAP, minimalista e eficiente, sua popularização no meio web foi exponencial. ==Por aceitar múltiplos formatos de mídia== (JSON, XML, HTML, dentre outros) e por ==não ter necessidade de "envelopar" os dados para que estes sejam enviados==, o REST surgiu como uma ==alternativa simples e direto ao ponto para comunicação entre serviços web==.

Hoje, o modelo REST domina o meio de desenvolvimento web. Implementar e consumir serviços REST tornou-se habilidade fundamental para qualquer desenvolvedor web.



### Referências:

[^1]: [[Interfaces]]

[^2]: [[URI]]

[^3]: [[Objeto]]

[^4]: [[Hypermedia as the engine of application state (HATEOAS)]]

[^5]: [[Requests]]

[^6]: [[SOAP]]

[[0204 O que é REST]]