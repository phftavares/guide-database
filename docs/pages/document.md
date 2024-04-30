# Document
Um banco de dados de documentos, é um tipo de banco de dados NoSQL que armazena e manipula dados em formato de documentos, em vez de tabelas e linhas como em bancos de dados relacionais tradicionais. Cada documento é uma unidade de armazenamento de dados autocontida, que pode conter campos e valores de diferentes tipos, como texto, números, arrays e até mesmo outros documentos aninhados.

## Princípios chave
- **Modelagem Flexível**: Os bancos de dados de documentos permitem uma modelagem de dados flexível, onde cada documento pode ter sua própria estrutura, sem a necessidade de seguir um esquema rígido.
- **Escala Horizontal**: Muitos sistemas de banco de dados de documentos são projetados para escalabilidade horizontal, o que significa que podem facilmente distribuir dados em vários servidores para lidar com grandes volumes de dados e altas cargas de trabalho.
- **Consulta Poderosa**: Geralmente, esses bancos de dados oferecem suporte a consultas complexas e indexação eficiente para recuperar dados de forma rápida e eficaz, mesmo em grandes conjuntos de dados.

## Vantagens e Desvantagens

### Vantagens
- Flexibilidade
- Desempenho
- Escala

### Desvantagens
- Consistência
- Complexidade de Consulta
- Gerenciamento de Dados Aninhados

## Casos de uso
- **Aplicações Web e Móveis**: Muitas aplicações web e móveis têm modelos de dados flexíveis e evoluem rapidamente ao longo do tempo. Os bancos de dados de documentos são ideais para esses casos de uso, pois permitem que os desenvolvedores modelem os dados de acordo com as necessidades específicas da aplicação sem a necessidade de esquemas fixos.
- **Gerenciamento de Conteúdo**: Sistemas de gerenciamento de conteúdo (CMS) e plataformas de blog frequentemente lidam com uma grande variedade de tipos de conteúdo, como artigos, imagens, vídeos e comentários. Um banco de dados de documentos pode ser usado para armazenar e recuperar esses tipos de dados de forma eficiente, enquanto mantém a flexibilidade para lidar com novos tipos de conteúdo.
- **Catálogos de Produtos e E-Commerce**: Em ambientes de comércio eletrônico, onde os produtos podem ter atributos variados e podem precisar ser atualizados frequentemente, um banco de dados de documentos pode ser útil. Isso permite que os vendedores modifiquem e expandam os atributos dos produtos sem a necessidade de modificar esquemas de banco de dados complexos.
- **Análise de Logs e Eventos**: Muitas vezes, em sistemas de análise de logs e eventos, os dados podem ser semi-estruturados e volumosos. Os bancos de dados de documentos podem lidar bem com esses tipos de dados, permitindo a ingestão eficiente e a análise de grandes volumes de registros de forma escalável.
- **Gestão de Perfil e Usuário**: Plataformas que lidam com perfis de usuário e dados de preferências geralmente se beneficiam da flexibilidade oferecida por um banco de dados de documentos. Isso permite que as informações do perfil do usuário sejam facilmente estendidas e modificadas à medida que novos recursos são adicionados ao sistema.


## Referencias
- Chodorow, K. MongoDB: The Definitive Guide. O'Reilly Media, Inc.
- Hawkins, B. NoSQL for Mere Mortals. Addison-Wesley Professional.