### Projeto SQL: Análise de Dados de Leitura Durante a Pandemia
Este projeto foi desenvolvido para explorar e analisar um banco de dados fornecido por um serviço concorrente no mercado de leitura. O objetivo foi gerar insights para o desenvolvimento de um novo produto voltado para os amantes de livros.

#### 📋 Descrição do Projeto
Com a pandemia de coronavírus, o comportamento das pessoas mudou drasticamente. Muitos passaram a dedicar mais tempo à leitura, criando oportunidades para startups inovarem neste mercado. O banco de dados analisado contém informações sobre livros, autores, editoras, classificações e avaliações de usuários. Este projeto utiliza SQL para explorar esses dados e responder a perguntas de negócio que auxiliam na proposição de um produto voltado para este público.

#### 🗂️ Estrutura do Banco de Dados
O banco de dados é composto por cinco tabelas principais:

Tabela: books (Livros)
Coluna	Descrição
book_id	Identificador do livro
author_id	Identificador do autor
title	Título do livro
num_pages	Número de páginas
publication_date	Data de publicação
publisher_id	Identificador da editora
Tabela: authors (Autores)
Coluna	Descrição
author_id	Identificador do autor
author	Nome do autor
Tabela: publishers (Editoras)
Coluna	Descrição
publisher_id	Identificador da editora
publisher	Nome da editora
Tabela: ratings (Classificações)
Coluna	Descrição
rating_id	Identificador da classificação
book_id	Identificador do livro
username	Usuário que avaliou o livro
rating	Classificação dada pelo usuário
Tabela: reviews (Avaliações)
Coluna	Descrição
review_id	Identificador da revisão
book_id	Identificador do livro
username	Usuário que revisou o livro
text	Texto da revisão
🔍 Metodologia
Todas as análises foram realizadas utilizando SQL, com foco em responder questões relevantes para o desenvolvimento do produto, tais como:

Quais são os autores mais populares?
Quais livros possuem as melhores avaliações?
Quais editoras publicam os livros mais lidos?
Existe alguma correlação entre o número de páginas e a classificação dos livros?
📊 Resultados
As consultas SQL realizadas forneceram insights valiosos, incluindo:

Identificação dos livros mais bem avaliados e revisados.
Análise das editoras que dominam o mercado.
Perfis de leitores com maior engajamento (em termos de classificações e avaliações).
Essas informações foram fundamentais para formular uma proposta de produto focado em maximizar a experiência de leitura dos usuários.

🛠️ Ferramentas Utilizadas
SQL: Linguagem principal para consultas e manipulação de dados.
DBeaver/MySQL Workbench: Ferramentas para execução das consultas e visualização do banco de dados.
✅ Conclusão
O projeto demonstrou a importância da análise de dados para a criação de produtos alinhados às necessidades do público-alvo. Todas as pesquisas e análises foram realizadas exclusivamente com SQL, destacando sua eficiência e versatilidade na manipulação e exploração de dados.

📂 Repositório
Explore os arquivos e scripts SQL no repositório deste projeto para entender como cada insight foi gerado.

