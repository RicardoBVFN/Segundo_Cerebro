
09-09-2025 19:56

Tags: [[Web]], [[Informática]], [[Tratamento de Dados]]
Status: #Maduro 


### Definição

Um bloco de dados consiste na menor partição de dados existente, tanto para a transmissão de dados[^1] quanto no armazenamento de dados[^2].

### Relevância

O domínio do conceito de blocos de dados é fundamental para se ter um conhecimento refinado a respeito do tratamento de informações em sistemas digitais.

Compreender que um arquivo em um computador é composto por um conjunto de blocos de dados te torna capaz de decidir, por exemplo, se você irá optar por uma configuração de armazenamento focada em desempenho (Raid 0[^3]) ou segurança das informações (Raid 1[^4]) para os Block Devices[^5] da máquina.

Paralelamente, arquivos transferidos via rede, tanto em WAN[^6] quanto em LAN[^7], são transmitidos na forma de blocos de bits chamados pacotes que, essencialmente, representam a mesma sub unidade do exemplo anterior. Sabendo disso, torna-se mais claro o porquê dos protocolos de endereçamento, identificação e autenticação serem voltados para pacotes e não para arquivos.

### Referências:

[^1]: [[Introdução à Infraestrutura de Comunicação]]

[^2]: [[Armazenamento]]

[^3]: [[Raid 0 (Stripe)]]

[^4]: [[Raid 1]]

[^5]: [[Block Devices (Armazenamento)]]

[^6]: [[WAN]]

[^7]: [[LAN]]
