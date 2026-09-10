# 🚀 Sistema de Telemetria: Relatório Operacional de Pré-Decolagem

## 📋 Explicação do Projeto

Este projeto é uma **Atividade Integradora** que simula um sistema de validação de telemetria aeroespacial. O objetivo principal é analisar um conjunto de dados críticos de uma espaçonave e executar um algoritmo de verificação rigoroso para decidir o status final da missão: **"PRONTO PARA DECOLAR"** ou **"DECOLAGEM ABORTADA"**.

O sistema avalia cinco parâmetros fundamentais em tempo real:
* **Temperatura Interna:** Mantida entre 18°C e 26°C para segurança da tripulação.
* **Integridade Estrutural:** Validação binária (1 = OK, 0 = Falha).
* **Nível de Energia:** Verificação de carga mínima exigida (85%).
* **Pressão dos Tanques:** Monitoramento de limites seguros (3000 a 4500 psi).
* **Módulos Críticos:** Status operacional de sistemas vitais de suporte.

Além do algoritmo de decisão, o projeto engloba análises matemáticas de consumo energético e uma reflexão crítica sobre o impacto socioambiental e ético da exploração espacial.

---

## ⚙️ Funcionalidades

- **Leitura de Dados:** Ingestão de dicionários de dados simulando sensores de telemetria.
- **Validação Condicional:** Funil lógico em Python para garantir que todos os parâmetros estejam dentro das faixas seguras.
- **Análise de Autonomia:** Cálculo de consumo energético considerando perdas térmicas.
- **Feedback Operacional:** Retorno imediato do status e do motivo exato em caso de aborto da missão.

---

## 💻 Instruções de Execução do Código

Para rodar o notebook Python localmente ou em nuvem, siga os passos abaixo:

### Opção 1: Via Google Colab (Recomendado)
1. Acesse o [Google Colab](https://colab.research.google.com/).
2. Faça o upload do arquivo `telemetria_pre_decolagem.ipynb` (ou cole o link deste repositório na aba GitHub).
3. Clique no botão `Play` em cada célula ou use o atalho `Shift + Enter` para executar o código passo a passo.

### Opção 2: Execução Local (Jupyter Notebook)
**Pré-requisitos:** É necessário ter o Python e o Jupyter instalados na sua máquina.
