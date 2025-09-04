📚 Projeto Asimov – WebApp Interativo de Livros e Reviews
O Projeto Asimov é um aplicativo web desenvolvido em Python com Streamlit que permite explorar os livros mais populares e suas avaliações, de forma interativa e visual. Com filtros dinâmicos e gráficos, o usuário pode analisar tendências, preços e notas dadas por leitores.

🚀 Objetivo
Criar uma aplicação prática e intuitiva que:

Liste os livros mais bem avaliados.

Exiba reviews reais de leitores.

Permita filtrar por preço máximo.

Mostre gráficos interativos sobre anos de publicação e distribuição de preços.

🛠️ Tecnologias Utilizadas
Python 3.x

Streamlit – Criação do webapp

Pandas – Manipulação de dados

Plotly Express – Visualizações interativas

CSV – Fonte de dados (Top 100 livros e reviews)

📂 Estrutura do Projeto
Código
Projeto_Asimov/
│
├── app.py                      # Código principal do Streamlit
├── datasets/
│   ├── customer reviews.csv    # Reviews dos leitores
│   └── Top-100 Trending Books.csv  # Lista dos livros mais populares
└── README.md                   # Documentação do projeto
⚙️ Como Executar
Clonar o repositório

bash
git clone https://github.com/Rob77719/Projeto_Asimov.git
cd Projeto_Asimov
Criar ambiente virtual e instalar dependências

bash
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows
pip install -r requirements.txt
Executar o Streamlit

bash
streamlit run app.py
Acessar no navegador

Código
http://localhost:8501
📊 Funcionalidades
Tabela de reviews com notas e comentários.

Filtro de preço via slider.

Gráfico de barras com quantidade de livros por ano de publicação.

Histograma com distribuição de preços.

Layout responsivo com colunas lado a lado.

🔮 Melhorias Futuras
Adicionar busca por título ou autor.

Criar sistema de login e favoritos.

Integrar API para dados em tempo real.

Adicionar gráficos de análise de avaliações.

👨‍💻 Autor
Desenvolvido por Roberto como parte do aprendizado em Python, unindo tecnologia e literatura.
