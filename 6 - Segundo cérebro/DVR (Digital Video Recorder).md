
02-09-2025 14:44

Tags: [[História da Tecnologia]]; [[Informática]]
Status: #Maduro 


### Definição

DVRs consistiam em receptores de sinal analógico integrados com hardware adicional cuja função era gravar por meio de uma placa de captura[^1] programas de TV a cabo, armazená-los em um HD[^2] para posteriormente serem reassistidos.

### Relevância

Os DVRs foram o primeiro caso de aplicação expressiva de sistemas para *set top box*, modelo idealizado pelos desenvolvedores da linguagem Java[^3] quase uma década antes de sua popularização por meio do Tivo.

Sua menção na história se tornou simbólica pois o Tivo utilizavam um sistema operacional a base de Linux[^4] que seguia a licença GPL[^5] v2. A princípio, como o software estava seguindo as demandas da licença, usuários poderiam adquirir um tivo, realizar modificações em seu sistema e assim usar uma versão customizada independente da versão original. Todavia, a empresa por traz do tivo não tinha interesse em permitir que o seu produto pudesse ser utilizado de forma modificada, ao mesmo tempo em que ainda desejava utilizar a distribuição Linux em seus dispositivos.

Assim, por meio do aproveitamento de uma brecha nas normas da licença GLP v2, uma atualização do Tivo foi lançada, dessa vez equipada com um componente de hardware adicional que aplicava um protocolo de hashing[^6] no software do sistema. Esse componente armazenava uma assinatura de originalidade do sistema, que consistia no hashing do mesmo, e não permitia que o dispositivo funcionasse caso o software apresentasse uma assinatura diferente da do original. Essa modificação, a pesar de ideologicamente ir de encontro aos propósitos da GLP, ainda atendia às demandas da licença pois ==esta em sua segunda versão não abrangia componentes de hardware como impeditivos da liberdade de uso do software==.

Esse caso gerou grande revolta na comunidade Open Source[^7], fazendo com que os criadores da GLP rapidamente modificassem as diretrizes de sua licença para abranger este tipo de pratica que ficou conhecida como ==**Tivolização**==.


### Referências:

[^1]: [[Placa de Captura]]

[^2]: [[HD (Hard Disk)]]

[^3]: [[Java]]

[^4]: [[Linux]]

[^5]: [[GPL (General Public License)]]

[^6]: [[Hashing]]

[^7]: [[Open Source]]

[[Entendendo Apple, GPL e Compiladores]]
