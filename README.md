# Projeto de Limpeza de Dados com KNIME

##  Visão Geral
Este é um projeto simples de limpeza e preparação de dados desenvolvido na plataforma **KNIME**. O fluxo realiza as seguintes etapas:

1. Carregamento do CSV original  
2. Remoção de substrings indesejadas  
3. Conversão de colunas de data e hora para o tipo **Date&Time**  
4. Redução de dimensionalidade  
5. Tratamento de valores ausentes (substituição e exclusão)  
6. Geração de um arquivo CSV limpo  

Este projeto serve como base para automatizar a limpeza e padronização de dados, facilitando análises subsequentes.

---

##  Estrutura do Repositório

├── projeto_knime/
│ └── fluxo.knwf # Arquivo do workflow do KNIME
├── dataset_original/
│ └── dados_brutos.csv # CSV com dados brutos
├── dataset_limpo/
│ └── dados_limpos.csv # CSV gerado após o processamento
├── imagem/
│ └── diagrama_fluxo.png # (Opcional) Diagrama ilustrativo do fluxo
├── README.md # Este arquivo
└── LICENSE # Licença do projeto (ex: MIT)

---

## Imagem do fluxo de limpeza
<img href="imagem/diagrama_fluxo.png" alt="Imagem-fluxo-Knime" />

