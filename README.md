📊 Estudo de Estatística Aplicada com Python e Pandas
Este repositório contém estudos e exercícios práticos de Estatística aplicados com a linguagem Python. O foco é a Análise de Dados, a criação de gráficos informativos e a interpretação robusta de informações utilizando bibliotecas essenciais do ecossistema de Data Science.

O objetivo principal é consolidar conceitos estatísticos e aplicar técnicas modernas de Análise Exploratória de Dados (EDA) em projetos reais, preparando-o para desafios complexos de Data Science e Análise de Dados.

🔧 Tecnologias Utilizadas
A seguir, estão as principais ferramentas e bibliotecas utilizadas neste projeto, gerenciadas de forma eficiente para garantir a reprodutibilidade do ambiente:

Tecnologia	Função Principal
Python 3.11	Linguagem de programação principal.
Pandas	Manipulação, limpeza e análise de dados (estruturas DataFrames).
NumPy	Suporte a operações matemáticas avançadas e arrays de alto desempenho.
Matplotlib	Criação de gráficos e visualização estática de dados.
Jupyter Notebook	Ambiente interativo para experimentação de código, documentação e visualização imediata de resultados.
pyenv	Gerenciamento de múltiplas versões do Python.
pipenv	Gerenciamento de ambientes virtuais e dependências do projeto.


📚 Tópicos de Estudo em Estatística
Este projeto abrange uma variedade de tópicos fundamentais em Estatística e Análise de Dados:

Estatística Descritiva: Cálculo e interpretação de métricas centrais (média, mediana, moda) e de dispersão (desvio padrão, variância, quartis).

Análise Exploratória de Dados (EDA): Técnicas e metodologias para inspecionar e resumir os principais recursos de um dataset, utilizando as poderosas funcionalidades do Pandas.

Visualização de Dados: Criação de gráficos informativos (histogramas, box plots, gráficos de dispersão, etc.) com Matplotlib para identificar padrões e outliers.

Manipulação de Datasets Reais: Trabalho prático com dados reais para simular cenários de mercado e interpretar resultados no contexto de negócios.

Conceitos Teóricos: Aplicação prática de conceitos de probabilidade e estudo de distribuições estatísticas.

⚙️ Pré-requisitos
Para rodar o projeto localmente, você precisará ter instalado:

Git (Opcional, mas recomendado para clonar o repositório).

pyenv (Para gerenciar a versão correta do Python).

pipenv (Para isolar e gerenciar as dependências do projeto).

🚀 Guia de Configuração e Execução
Siga os passos abaixo para configurar o ambiente e começar a explorar os notebooks.

1. Clonar o Repositório (Opcional)

git clone <URL_DO_SEU_REPOSITORIO>
cd <NOME_DO_REPOSITORIO>

2. Instalar e Configurar Python 3.11 com pyenv
Certifique-se de que a versão correta do Python está instalada e definida para este projeto.


# Instalar Python 3.11 (caso ainda não esteja instalado)
pyenv install 3.11.0

# Definir Python 3.11 como versão local para o projeto
pyenv local 3.11.0
Isso criará um arquivo .python-version no diretório, garantindo que o pipenv utilize esta versão.

3. Criar e Ativar o Ambiente Virtual com pipenv
Use o pipenv para criar um ambiente isolado para o projeto e ativá-lo:



# Criar ambiente virtual usando Python 3.11 (detectado pelo pyenv)
pipenv --python 3.11

# Ativar o ambiente virtual
pipenv shell

4. Instalar Dependências
Com o ambiente virtual ativo, instale todas as bibliotecas necessárias:



pipenv install pandas numpy matplotlib jupyter
Os arquivos Pipfile e Pipfile.lock serão criados/atualizados, controlando as dependências.

5. Executar o Jupyter Notebook
Para iniciar a interface do Jupyter e interagir com os notebooks de estudo:


pipenv run jupyter notebook
Isso abrirá o seu navegador padrão na interface do Jupyter, onde você poderá navegar até a pasta notebooks/ e começar seus estudos.

📂 Estrutura do Repositório
Diretório/Arquivo	Descrição
notebooks/	Contém todos os arquivos .ipynb com os estudos e exercícios de Estatística.
data/	Local para armazenar os arquivos de dados (CSV, Excel, etc.) utilizados nas análises.
README.md	Este arquivo de documentação.
Pipfile	Define as dependências do projeto.
Pipfile.lock	Garante a reprodutibilidade, travando as versões das dependências.
.python-version	Arquivo do pyenv que define a versão local do Python (3.11.0).


💡 Dicas e Comandos Úteis
Comando	Descrição
pipenv shell	Sempre use este comando para entrar no ambiente virtual antes de trabalhar.
exit	Sai do ambiente virtual do pipenv.
pipenv update	Atualiza todas as dependências do Pipfile.
pipenv install <pacote>	Instala um novo pacote no ambiente virtual.
pipenv install --dev	Instala as dependências em outro computador que já possui o Pipfile.lock.


Contribuições: Se você planeja transformar isso em um repositório colaborativo, adicione uma seção de Contribuições e licença. Caso contrário, mantenha-o como seu repositório pessoal de estudo!
