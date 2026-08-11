
05-09-2025 10:39

Tags: [[Web]], [[Desenvolvimento]], [[Tratamento de Dados]]
Status: #Maduro 


### Definição

Camada 7 do modelo OSI[^1], sendo a camada mais próxima do usuário final. Responsável por realizar a interface entre as aplicações do computador e a recepção (ou envio) de dados entre dispositivos. Também está presente no modelo TCP/IP[^2]

Seque uma lógica de cliente e servidor[^3], na qual o host que solicita informações atua como cliente enquanto o host que envia informações atua como servidor. Esses papeis não são fixos, o host que outrora solicitou informações (cliente) pode tornar a responder requisições (servidor).
### Relevância

Por agir como intermediadora entre a aplicação e o sistema de transferência, é nesta camada que serão realizados os protocolos de transferência de dados. Como exemplo é possível citar os HTTP[^4] e HTTPS[^5] para web e FTP[^6] para arquivos.

Além disso, a camada 7 também determina o acesso de usuários. Sejam operadores ou outros sistemas, todos tem seus privilégios validados nesta camada. Assim, a boa configuração desta camada, bem como o domínio de seu funcionamento, é fundamental para garantir a segurança da rede.


### Referências:

[^1]: [[Modelo OSI de Comunicação]]

[^2]: [[Modelo TCP/IP]]

[^3]: [[Arquitetura Cliente Servidor]]

[^4]: [[Protocolo HTTP]]

[^5]: [[Protocolo HTTPS]]

[^6]: [[Protocolo FTP]]
