# O Papel dos Bancos de Dados SQL e NoSQL na Engenharia de Dados

**Banco de dados** é uma coleção de dados podendo ser estruturada ou não estruturada.

**Os bancos de dados relacionais** (SQL) se baseiam no fato de que todos os dados sejam guardados em tabelas. São adequados para solucionar problemas que se colocam no nível da concepção e normalmente o uso mais comum deste tipo 
de banco é para implementar funcionalidades do tipo CRUD (do inglês Create, Read, Update e Delete), ou seja, criar ou inserir, ler ou selecionar, alterar e excluir um dado. Numa determinada funcionalidade pode envolver múltiplas operações, assim temos o conceito de transação em um SGBD. Uma transação é uma sequência de operações executadas como uma única unidade lógica de trabalho 
De modos a garantir a integridade das transações, os SGBDs relacionais implemntam as propriedades ACID:
* Atomicidade
* Consistência, 
* Isolamento
* Durabilidade


**Banco de dados Não-relacional (NoSQL)** não se aplica o conceito de schema: uma chave de valor é que é utilizada para recuperar valores, conjunto de colunas ou documentos. visa atender aos requisitos de gerenciamento de dados, semiestruturados ou não estruturados, garantindo alta disponibilidade e escalabilidade, suas propriedades básicas são:
* Basically Available (Basicamente Disponível)
* Soft state (em um estado flexível)
* Eventual consistency (Eventualmente Consistente)

Uma das diferenças nos bancos de dados NoSQL é que toda a informação é agrupada e guardada no mesmo registro. Já no SQL você precisa ter o relacionamento entre várias tabelas para ter a informação, informação esta disposta no modelo entidade e relacionamento.

O NoSQL não veio para substituir o SQL, mas sim para oferecer mais uma alternativa de um banco de dados mais flexível no suporte de dados, assim sendo, o mais comum em soluções escalares de sucesso é a utilização de uma arquitetura híbrida, aproveitando o melhor dois dois modelos.

**A Engenharia de Dados** é a área responsável por planejar, criar, manter e evoluir toda a estrutura de dados de uma organização (NASCIMENTO, 2017)

O Engenheiro de Dados transforma dados em um formato útil para análise. Este profissional deve:
* Entender a origem e natureza dos dados.
* Lidar o planejamento e desenvolvimento do esquema de dados.
* Definir estruturas confiáveis para suportar todo o fluxo de dados e 
* Implementar a coleta, preparação e armazenamento.
* Propor e implementar a estrutura de armazenamento e soluções de Data Warehouse.
* Entender a necessidade de integração de dados.
* Propor e implementar a estrutura de integração e rotinas de ETL.
