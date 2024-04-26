# Relational Database (RDBMS)

No coração de um RDBMS está o conceito de tabelas relacionais, onde os dados são organizados em linhas e colunas. Cada tabela representa uma entidade no mundo real, e as relações entre essas entidades são expressas por meio de chaves primárias e estrangeiras. Isso permite que os dados sejam armazenados de forma estruturada e consistente, facilitando consultas e análises.

Além disso, os RDBMS oferecem um conjunto robusto de operações para manipular dados, como inserção, atualização, exclusão e consulta, utilizando a linguagem SQL (Structured Query Language). O SQL fornece uma maneira padronizada de interagir com o banco de dados, permitindo que os usuários executem consultas poderosas e recuperem informações precisas de maneira eficiente.

## Vantagens e Desvantagens

### Vantagens
- Estrutura organizada
- Integridade dos dados
- Concorrencia e controle de transação
- Transações ACID

### Desvantagens
- Modelo rigido
- Desempenho
- Custo
- Limitação de escalabilidade

Nota! **ACID** é um acrônimo que representa as características chave de uma transação em um sistema de banco de dados relacional:

- **Atomicidade**: Uma transação é atomicamente executada, o que significa que é tratada como uma única unidade de trabalho indivisível. Isso implica que todas as operações dentro da transação são executadas com sucesso ou todas são revertidas se ocorrer algum erro, garantindo que o banco de dados permaneça em um estado consistente.
- **Consistência**: Após a conclusão de uma transação, o banco de dados deve permanecer em um estado consistente, ou seja, todas as restrições de integridade e regras de negócio devem ser mantidas. Isso garante que o banco de dados não entre em um estado inválido ou inconsistente após a execução de uma transação.
- **Isolamento**: As transações devem ser isoladas umas das outras, o que significa que as operações de uma transação não devem interferir nas operações de outras transações em execução simultaneamente. Isso garante que o banco de dados mantenha sua consistência mesmo em ambientes de concorrência, evitando problemas como leituras sujas, leituras não repetíveis e escritas fantasmas.
- **Durabilidade**: Uma vez que uma transação é confirmada (commit), suas mudanças devem ser permanentemente registradas no banco de dados, mesmo em caso de falha do sistema. Isso garante que as alterações feitas por transações confirmadas sejam preservadas e não sejam perdidas devido a falhas de hardware ou software.

## Casos de Uso
- Aplicações de Negócios e Transacionais: RDBMS são frequentemente utilizados em aplicações de negócios e sistemas transacionais, onde a integridade dos dados, a consistência e a confiabilidade são essenciais. Isso inclui sistemas de gestão de pedidos, sistemas bancários, sistemas de gestão de inventário, sistemas de CRM (Customer Relationship Management) e sistemas de gerenciamento de recursos humanos.
- Aplicações de Análise e Relatórios: Embora os RDBMS possam não ser tão eficientes quanto algumas soluções NoSQL para certos tipos de análise de big data, eles ainda são amplamente utilizados em aplicações de análise e geração de relatórios. Isso inclui painéis de controle empresariais, ferramentas de Business Intelligence (BI), sistemas de apoio à decisão e aplicações de mineração de dados.
- Sistemas de Gerenciamento de Conteúdo: Muitos sistemas de gerenciamento de conteúdo, como sistemas de gerenciamento de conteúdo web (CMS) e sistemas de gerenciamento de documentos, utilizam RDBMS para armazenar e gerenciar conteúdo estruturado, metadados e relacionamentos entre conteúdos.
- Sistemas de Suporte a Transações Online (OLTP): Os RDBMS são particularmente adequados para sistemas OLTP, nos quais as transações de curta duração e alto volume são realizadas, como processamento de pedidos em tempo real, reservas de passagens aéreas e reservas de hotéis.
- Sistemas de Gerenciamento de Dados Empresariais (EDM): RDBMS desempenham um papel fundamental em sistemas de gerenciamento de dados empresariais, nos quais dados críticos para o negócio são armazenados, gerenciados e compartilhados entre diferentes departamentos e aplicativos dentro de uma organização.

## Referencias
- E.F. Codd, "A Relational Model of Data for Large Shared Data Banks"
- C.J. Date, "An Introduction to Database Systems"