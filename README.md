# dio-bootcamp-fundamentos-cloud-aws
Este repositorio tem como fundamento principal relatar um pouco do meu aprendizado obtido através do Bootcampo Fundamento Cloud da AWS oferecido pela Digital Innovation One - DIo.

- [Desafio 01 - Primeira Arquitetura](desafio1/)

Nesse primeiro desafio, precisamos criar duas arquiteturas, os quais estão localizadas na pasta desafio1. Essas imagens são referentes ao primeiro desafio do bootcampo, mostrando a arquitetura de um projeto utilizando EC2 e outro projeto utilizando Lambda. Ambos são projetos similares no inicio, sendo um usuário enviando um arquivo a nuvem, porém havendo tratamentos diferentes. Um deles vai para uma instancia onde realiza algumas validações, depois o EC2 capta esse arquivo e envia para uma outra instancia onde é possivel consumi-lo de alguma maneira. Já no projeto lambda,  o arquivo é enviado para o S3, depois ao lambda, e dai a um banco de dados.
