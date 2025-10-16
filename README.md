# Análise de Indicadores para Implementação Uber

## Objetivo do Projeto
Definir as métricas que podem ser usadas **para indicar "sucesso"** na implementação da Uber em uma cidade-alvo de 100.000 habitantes, na região Nordeste. Foram utilizados dados de cidades-proxy com perfis demográficos e econômicos variados. O projeto também visa estabelecer **boas práticas de marketing** durante a implementação do projeto piloto.

## Resultado-Chave (Perfil de sucesso)
O perfil de sucesso desejável para a cidade-alvo é que, durante o projeto piloto, a cidade possua uma **média aproximada de 2,90 viagens diárias**, **valor médio por corrida de R$55,80** e **receita em horário de pico de R$56,01**. A análise identificou que o maior valor por corrida está associado a bairros de classe baixa (Cidade 9), sugerindo um **uso mais estratégico e de longa distância** do serviço.
A maior receita em horários de pico está associada a cidades de classe média (Cidade 6), indicando um maior potencial de demanda em horários de pico (18h-20h).

---

## Metodologia e Documentação do Processo

### 1. Fonte de Dados e Considerações

* **Problema:** A base inicial de dados seria obtida via Kaggle. No entando, devido à ausência de base de dados abertas e segmentadas de corridas da Uber em cidades brasileiras foi necessário **alterar a fonte de dados**.
* **Solução:** Para simular o cenário de análise e garantir a viabilidade do projeto, foi gerada uma **base de dados sintética (fictícia)** com o auxílio de inteligência artificial.
* **Transparência:** Os dados numéricos usados neste projeto **não são reais**, mas as relações e os padrões criados entre as variáveis são **analiticamente consistentes** para refletir cenários de negócio plausíveis.

### 2. Preparação de Dados e Criação de Métricas (Power Query e Excel)

* **O que eu fiz:** Usei o Power Query para importar e limpar os dados e, em seguida, criei as métricas-chave dos indicadores de sucesso que serão usados na implementação do projeto piloto.
* **Passos de como eu fiz:**
  * Criei as colunas de métricas.
  * Filtrei as tabelas de métricas para mostrar apenas os dados das cidades **3,6 e 9** (cidades-proxy).
* **Por que eu fiz**: O tratamento e a criação de métricas são essenciais para traduzir dados brutos em informações de negócio acionáveis.

### 3. Visualização e Criação do Dashboard

* **O que eu fiz**: Criei um dashboard claro e profissional para apresentar os resultados.
* **Passos de como eu fiz:**
   * Criei **tabelas dinâmicas** para cada métrica.
   * Criei **gráficos dinâmicos** (barras para métricas, rosca para faixa etária) a partir das tabelas dinâmicas.
   * **Formatei os números** para duas casas decimais (diretamente na tabela dinâmica).
   * **Adicionei títulos e rótulos** aos gráficos e ajustei o **eixo vertical para iniciar em zero**.
   * Adicionei uma **tabela de contexto** com PIB per capita, custo e qualidade de vida.
   * **Removi as linhas de grade** da planilha para um visual profissional.
* **Por que eu fiz:** Usar um dashboard profissional e bem formatado garante que toda a equipe e os Stakeholders **entenda** as conclusões de forma rápida e sem distrações.
