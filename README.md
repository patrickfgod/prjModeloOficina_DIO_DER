# prjModeloOficina_DIO_DER

Repositório para o Desafio de Projeto DIO

### 📝 Descrição do Desafio
Este repositório foi criado como parte de um desafio de projeto. O objetivo é criar o esquema conceitual para o contexto de oficina com base na narrativa fornecida.

O esquema do modelo foi adicionado ao repositório para análise e documentação. Este arquivo fornece o contexto necessário para compreender o esquema desenvolvido.

### 🎯 Objetivo do Projeto
O modelo inicial deve ser refinado com base nos seguintes requisitos:

- [x] Sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica
- [x] Clientes levam veículos à oficina mecânica para serem consertados ou para passarem por revisões  periódicas
- [x] Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega.
- [x] A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra
- [x] O valor de cada peça também irá compor a OSO cliente autoriza a execução dos serviços
- [x] A mesma equipe avalia e executa os serviços
- [x] Os mecânicos possuem código, nome, endereço e especialidade
- [x] Cada OS possui: n°, data de emissão, um valor, status e uma data para conclusão dos trabalhos.

### 🛠️ Detalhamento dos Campos ENUM
Alguns campos do modelo utilizam o tipo ENUM para garantir consistência e limitar os valores permitidos. Abaixo estão listados os campos e suas respectivas opções:

**Tabela Servico**\
tipo_servico:
ENUM('revisao', 'conserto')

**Ordem_Servico**\
status:
ENUM('Aberta', 'Em Execução', 'Concluída')

![Diagrama](https://github.com/patrickfgod/prjModeloOficina_DIO_DER/raw/main/Desafio%20DIO_DER%2002.png)
