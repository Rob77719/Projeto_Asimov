📚 Projeto Asimov – WebApp de Livros e Reviews
Um projeto desenvolvido em Python que cria um webapp interativo para exibir os melhores livros e suas avaliações, utilizando dados reais de tendências e reviews de leitores.

🚀 Sobre o Projeto
O Projeto Asimov foi criado como parte da conclusão do curso de Python Básico, com o objetivo de aplicar conceitos fundamentais da linguagem no desenvolvimento de uma aplicação web. A aplicação permite que o usuário:

Visualize uma lista dos livros mais bem avaliados.

Leia reviews de outros leitores.

Explore tendências literárias de forma simples e intuitiva.

🛠️ Tecnologias Utilizadas
Python 3.x

Flask – Framework web para Python

Pandas – Manipulação e análise de dados

HTML/CSS – Estrutura e estilo do front-end

Bootstrap – Layout responsivo

CSV – Fonte de dados (Top 100 livros e reviews)

📂 Estrutura do Projeto
Código
Projeto_Asimov/
│
├── app.py                  # Arquivo principal do Flask
├── runner.py               # Script para iniciar a aplicação
├── Top-100 Trending Books.csv  # Lista dos livros mais populares
├── customer reviews.csv    # Reviews dos leitores
└── README.md               # Documentação do projeto
⚙️ Como Executar
Clone o repositório

bash
git clone https://github.com/SEU_USUARIO/Projeto_Asimov.git
cd Projeto_Asimov
Crie um ambiente virtual e instale as dependências

bash
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows
pip install -r requirements.txt
Execute a aplicação

bash
python runner.py
Acesse no navegador

Código
http://127.0.0.1:5000
📊 Funcionalidades
Listagem dos Top 100 livros mais populares.

Exibição de reviews reais de leitores.

Interface responsiva e amigável.

Filtros para busca por título ou autor.

📌 Próximos Passos
Adicionar sistema de login e favoritos.

Implementar API para buscar dados em tempo real.

Criar gráficos de análise de avaliações.

👨‍💻 Autor
Desenvolvido por Roberto como parte do aprendizado em Python. Inspirado na paixão por livros e tecnologia.
