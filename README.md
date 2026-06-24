# dio-bootcamp-fundamentos-cloud-aws

Este repositório tem como principal objetivo relatar um pouco do aprendizado adquirido durante o **Bootcamp Fundamentos Cloud AWS**, oferecido pela **Digital Innovation One (DIO)**.

## Desafios

### Desafio 01 - Primeira Arquitetura

* [Acessar desafio](desafio1/)

Neste primeiro desafio, foi necessário criar duas arquiteturas, ambas localizadas na pasta `desafio1`.

As imagens apresentadas correspondem ao primeiro desafio do bootcamp e demonstram a arquitetura de dois projetos distintos: um utilizando **EC2** e outro utilizando **AWS Lambda**.

Apesar de ambos possuírem uma proposta inicial semelhante — um usuário enviando um arquivo para a nuvem — o processamento ocorre de formas diferentes.

#### Arquitetura utilizando EC2

Nesta arquitetura, o arquivo enviado passa por uma instância responsável por realizar algumas validações. Em seguida, outra instância EC2 captura esse arquivo e o encaminha para uma nova etapa do fluxo, onde ele poderá ser consumido ou processado conforme a necessidade da aplicação.

#### Arquitetura utilizando AWS Lambda

Na arquitetura baseada em Lambda, o arquivo é enviado inicialmente para um bucket **Amazon S3**. Após isso, uma função **AWS Lambda** é acionada para processar os dados e, posteriormente, enviá-los para um banco de dados.

Essa abordagem demonstra um modelo mais orientado a eventos e sem a necessidade de gerenciamento direto de servidores.
