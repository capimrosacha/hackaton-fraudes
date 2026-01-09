# 🛡️ Caçadores de Fraudes - Detecção em Compras Públicas

Projeto desenvolvido para o **Hackathon Relâmpago** com o objetivo de automatizar a auditoria de gastos públicos e identificar possíveis irregularidades em listas de compras utilizando Python.

## 📝 Descrição do Projeto
A aplicação analisa uma base de dados de compras governamentais para detectar padrões que fujam da normalidade administrativa, auxiliando no controle de conformidade e integridade.

## 🎯 Objetivos do Desafio
O sistema foi projetado para atender aos seguintes requisitos:
* **Detecção de Duplicidade:** Identificar compras idênticas (mesmo item, valor e servidor).
* **Limite de Valor:** Listar todas as compras que excedem o teto de **R$ 1.000,00**.
* **Auditoria de Horário:** Identificar transações realizadas fora do expediente bancário/comercial (antes das **08:00** ou após as **18:00**).
* **Organização por Servidor:** Agrupamento inteligente dos dados utilizando dicionários para rastrear o histórico de cada funcionário.
* **Relatório de Severidade:** Geração de um resumo consolidado classificando a gravidade das infrações encontradas.

## 🛠️ Tecnologias e Técnicas
* **Python 3.x**: Linguagem principal.
* **Pandas**: Utilizado para manipulação eficiente de grandes volumes de dados.
* **Modularização**: Código estruturado em funções independentes para cada regra de negócio.
* **List Comprehensions**: Aplicadas para garantir um código limpo, rápido e seguindo as melhores práticas da linguagem.

## 📂 Estrutura das Funções
O script conta com as seguintes funções principais:
1. `detectar_compras_duplicadas()`
2. `verificar_valores_suspeitos()`
3. `compras_fora_de_horario()`
4. `organizar_por_servidor()`
5. `gerar_relatorio()`

## 🚀 Como Executar
1. Instale a biblioteca necessária:
   ```bash
   pip install pandas  
   
2. Execute o arquivo principal:
   ```bash
   python hackaton_fraudes.py
   ```



Equipe: Eric Rodrigues Arrais & Kenya Tyeh Kusano Santos

Data: 06/04/2025
