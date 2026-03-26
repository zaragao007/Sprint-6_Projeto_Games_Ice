# 🎮 Análise de Tendências e Mercado de Games - Loja Ice

## 🎯 Contexto do Projeto
A Ice, uma loja internacional de videogames, precisa planejar suas campanhas publicitárias para o ano de 2017. Para alocar o orçamento de forma eficiente, foi necessário analisar o histórico de vendas de jogos, avaliações de usuários e especialistas, gêneros e plataformas para identificar padrões de sucesso.

Neste projeto, conduzi uma análise estatística focada no ciclo de vida das plataformas e no comportamento do consumidor por região para descobrir os verdadeiros motores de venda do mercado.

## 🔗 Links Rápidos
* **[Dashboard Interativo no Tableau Public](https://public.tableau.com/app/profile/marcelo.aragao/viz/Analise_Mercado_Games_Ice_2017/Dashboard?publish=yes)**
* **[Apresentação Executiva (PDF)](Apresentacao_Executiva_Ice.pdf)**

## 🛠️ Ferramentas e Tecnologias
* **Linguagem:** Python
* **Bibliotecas:** Pandas, NumPy, Matplotlib, SciPy
* **Ambiente:** Jupyter Notebook
* **Visualização:** Tableau
* **Técnicas:** Testes de Hipóteses (Student's t-test), Análise de Ciclo de Vida de Produto, Tratamento de Dados Ausentes e Análise Exploratória de Dados (EDA).

## 📂 Estrutura do Repositório
* `Notebook_Sprint6.ipynb`: O código-fonte contendo a limpeza dos dados, testes estatísticos e as conclusões analíticas.
* `games (1).csv`: Base de dados original brutos.
* `ice_games_portfolio.csv`: Base de dados tratada e exportada para alimentar o dashboard.
* `Apresentacao_Executiva_Ice.pdf`: Relatório visual contendo a estratégia de negócios e recomendações para 2017.
* `requirements.txt`: Lista de dependências e bibliotecas utilizadas no projeto.

## 💡 Principais Insights Comerciais
1. **O Ciclo de Vida:** O tempo de vida útil de uma plataforma de sucesso é de aproximadamente 10 anos. Em 2016, gigantes como PS3 e Xbox 360 já estavam em franco declínio.
2. **O Foco de 2017:** Para o mercado ocidental (América do Norte e Europa), todo o esforço de marketing deve ser direcionado para o **PlayStation 4** e **Xbox One**, que estão no auge. No Japão, o ecossistema da **Nintendo (3DS)** domina o mercado de forma isolada.
3. **Gêneros Lucrativos:** Jogos de Ação (Action) e Tiro (Shooter) possuem a maior fatia de mercado global em volume financeiro, sendo as apostas mais seguras para o estoque principal.
4. **Impacto das Avaliações:** As notas da crítica especializada têm uma correlação positiva moderada com as vendas. Por outro lado, as notas dadas pelo público (usuários) não impactam significativamente o sucesso comercial de um título.

## 🚀 Recomendação Final
A estratégia para 2017 deve ser estritamente segmentada por região. No Ocidente, a recomendação é focar agressivamente em jogos de Ação e Tiro para PS4 e Xbox One, utilizando as notas da crítica especializada como alavanca nas campanhas. No mercado Japonês, a abordagem deve mudar totalmente para jogos de RPG no console portátil Nintendo 3DS.

---
*Desenvolvido por Marcelo - Analista de Dados*
