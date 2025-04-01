# Atividade-Kaggle

# 1. Base de Dados Escolhida: Depressão de Estudantes

# 2.1 Característica:
Este conjunto de dados compila uma ampla gama de informações voltadas para a compreensão, análise e previsão de níveis de depressão entre estudantes. Ele é projetado para pesquisa em psicologia, ciência de dados e educação, fornecendo insights sobre fatores que contribuem para os desafios de saúde mental dos estudantes e auxiliando no design de estratégias de intervenção precoce.

# 2.2 Variáveis:
ID: Identificador exclusivo para cada aluno

Demografia: Idade, Gênero, Cidade

Indicadores Acadêmicos: CGPA, Pressão Acadêmica, Satisfação com os Estudos

Estilo de Vida e Bem-Estar: Duração do Sono, Hábitos Alimentares, Pressão no Trabalho, Satisfação no Trabalho, Horas de Trabalho/Estudo

Fatores Adicionais: Profissão, Grau, Estresse Financeiro, Histórico Familiar de Doença Mental e se o aluno já teve pensamentos suicidas

# Variável Alvo:

Depression_Status: Um indicador binário (0/1 ou Sim/Não) que denota se um aluno está passando por depressão

# 2.3 Objetivos:

Pesquisa acadêmica: Explorar correlações entre pressões acadêmicas e tendências de saúde mental.

Projetos de ciência de dados: Criar modelos preditivos para identificar alunos em risco com base em vários indicadores.

Elaboração de políticas: Informar o desenvolvimento de programas de suporte à saúde mental direcionados dentro de instituições acadêmicas.

# 3.1 Descrição da base de dados:

A base de dados escolhida contém informações sobre estudantes e fatores associados à depressão, como idade, gênero, histórico familiar de transtornos mentais, nível de estresse acadêmico, qualidade do sono, suporte social e outras variáveis psicológicas e comportamentais. Além disso, a base inclui um indicador da presença ou não de sintomas depressivos, que pode ser uma pontuação em uma escala clínica padronizada (como o BDI - Beck Depression Inventory).

# 3.2 Justificativa da escolha do Machine Learning:

Para essa análise, a técnica de classificação é a mais adequada, pois o objetivo principal é prever se um estudante tem ou não depressão com base nos atributos disponíveis. Algoritmos como Random Forest, Support Vector Machine (SVM) ou Redes Neurais Artificiais podem ser utilizados para essa tarefa, pois possuem boa capacidade de lidar com dados complexos e não lineares. Além disso, a técnica permite identificar os fatores mais relevantes para a previsão da condição de depressão nos estudantes, contribuindo para futuras intervenções.

# 3.3 Objetivos:

Os principais objetivos dessa análise são:

Desenvolver um modelo preditivo capaz de classificar estudantes entre "com depressão" e "sem depressão" com alta precisão.

Identificar os fatores mais influentes na classificação dos estudantes, ajudando profissionais da área da saúde e educação a entender melhor os principais gatilhos para o desenvolvimento da depressão.

Explorar padrões ocultos nos dados, que podem indicar subgrupos de estudantes mais vulneráveis.

Fornecer recomendações para instituições de ensino baseadas nos resultados do modelo, ajudando na elaboração de políticas de suporte psicológico para os alunos.
