# Identificação de Padrões de Sucesso em Vendas de Jogos — Ice

## 📋 Descrição
Análise de vendas, avaliações e classificações etárias de jogos eletrônicos para identificar padrões de sucesso por plataforma, gênero e região, apoiando o planejamento de campanhas publicitárias de uma loja de jogos.

## 🎯 Objetivo
Entender quais plataformas e gêneros têm maior potencial de vendas, como o ciclo de vida das plataformas se comporta, e se existem diferenças relevantes de comportamento entre regiões (América do Norte, Europa e Japão).

## 🗂️ Dados
Base histórica de jogos com informações de plataforma, gênero, ano de lançamento, vendas por região (América do Norte, Europa, Japão e outros), nota de crítica, nota de usuários e classificação etária (ESRB).

## 🛠️ Tecnologias
- Python (Pandas)
- Matplotlib
- SciPy (teste de hipótese — teste t)

## 🔍 Etapas da análise
1. Tratamento de tipos de dados e valores ausentes
2. Cálculo de vendas totais por jogo e análise do ciclo de vida das plataformas
3. Definição do período mais relevante para análise de tendências (a partir de 2012)
4. Análise de distribuição de vendas por plataforma e correlação entre avaliações e vendas
5. Comparação de vendas por gênero, plataforma e classificação etária entre regiões
6. Teste de hipótese comparando avaliações médias entre plataformas e entre gêneros

## 📊 Principais resultados
- O ciclo de vida médio de uma plataforma é de aproximadamente 7 anos, com pico de vendas cerca de 3 anos após o lançamento
- A correlação entre nota de usuário e vendas é fraca (≈ 0,17), indicando que outros fatores (marketing, franquia) pesam mais
- Preferências de plataforma variam por região: Xbox lidera na América do Norte, PlayStation na Europa, e consoles portáteis no Japão
- Gêneros Action e Shooter dominam no Ocidente, enquanto Role-Playing se destaca no Japão
- Teste de hipótese confirmou diferença significativa nas avaliações entre Xbox One e PC, mas não entre os gêneros Action e Sports

## 🚀 Como executar
```bash
git clone https://github.com/steffanycardoso/padroes-vendas-jogos-ice.git
cd padroes-vendas-jogos-ice
pip install pandas matplotlib scipy
jupyter notebook
```

## 📁 Estrutura do repositório
```
├── padroes-vendas-jogos-ice.ipynb
└── README.md
```
