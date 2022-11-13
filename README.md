# CLEANARCHPY

## Objetivo

O objetivo deste projeto é prover uma estrutura de arquivos para a aplicação baseada na Clean Architecture,
utilizando exemplos em python.

## Motivador?

Bom na minha experiência desenvolvendo ou utilizando _"software"_, algo que ficou muito claro é que uma estrutura
organizada e bem definida ajuda na manutenção e evolução da aplicação.
Enquanto obtinha mais conhecimento sobre _"DDD"_ e _"Clean Architecture"_, algo que intuitivamente fez sentido é
"DDD diz o quê é, o quê faz e quais relaçoes tem por ilustrações e modelagem bem definida. _"Clean Architecture"_
diz onde cada coisa deve ficar e como essas relaçoes modeladas no _"DDD"_ devem existir". Logo resolvi adotar uma
mistura
dos dois neste projeto exemplo.

## Estrutura e responsabilidades

#### Domain

Os dominios da aplicação seriam o menor agrupamento lógico possível da aplicação.

### Actions

As ações da aplicação.

### Gateways

Os pontos de entrada da aplicação seja qual for, segmentado por tipo.

### Providers

Os provedores são as os sistemas de infraestrutura, databases, interface de rede, sistemas de arquivo e afins..

