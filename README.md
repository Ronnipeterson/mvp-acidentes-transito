# Análise de Acidentes de Trânsito com Vítimas (Belo Horizonte - 2021)

## Descrição do Projeto

Este projeto tem como objetivo analisar dados de acidentes de trânsito com vítimas ocorridos no ano de 2021 em Belo Horizonte e regiões próximas, a fim de compreender padrões, fatores associados à ocorrência dos acidentes e aspectos relacionados à fatalidade.

O trabalho foi desenvolvido como parte de um MVP (Minimum Viable Project) na área de Ciência de Dados, contemplando desde a definição do problema até as etapas de análise exploratória e pré-processamento dos dados.

---

## Objetivo

O objetivo deste projeto é analisar dados de acidentes de trânsito com o intuito de compreender os fatores associados à ocorrência de fatalidades.

Trata-se de um problema de **classificação supervisionada**, no qual a variável de interesse é o indicador de fatalidade (`INDICADOR_FATALIDADE`).

---

## Hipóteses Investigadas

- Os acidentes se concentram em determinados horários do dia (picos de tráfego).
- Há variação na ocorrência de acidentes ao longo da semana.
- Alguns tipos de acidentes apresentam maior associação com fatalidades.
- Fatores como clima, pavimento e velocidade podem influenciar a gravidade dos acidentes.
- A distribuição espacial dos acidentes não é homogênea.

---

## Dataset

- Fonte: Portal de Dados Abertos da Prefeitura de Belo Horizonte
- Tipo: Dados reais (não curados)
- Registros: ~11.000 acidentes
- Periodicidade: Anual (2021)

### Principais variáveis:

- **Temporais:** data e hora do acidente
- **Categóricas:** tipo de acidente, clima, pavimento, região, origem do boletim
- **Numéricas:** velocidade permitida, coordenadas geográficas
- **Alvo:** indicador de fatalidade (SIM/NÃO)
