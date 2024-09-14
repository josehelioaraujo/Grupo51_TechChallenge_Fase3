  
## Objetivo
 - Repositório para o Tech Challenge Fase 3 do Pós Fiap - AI para Devs
 
## Projeto
- Projeto de Fine-Tuning com Dataset LF-Amazon-1.3M e Implementação de Chatbot

## Definição do Problemas
 - A fazer

## 1. Preparação dos Dados
- Carregar o dataset LF-Amazon-1.3M (arquivo JSON)
- Verificar a estrutura dos dados

### 1.1 Limpeza de Dados
- Remover registros com campos nulos
- Imprimir estatísticas de limpeza

## 2. Pré-processamento
- Limpar o texto (remover caracteres especiais, normalizar)
- Tokenização
- Padronização do comprimento das sequências

## 3. Divisão do Dataset
- Separar os dados em conjuntos de treinamento, validação e teste

## 4. Escolha e Preparação do Modelo Base
- Selecionar um modelo base adequado (por exemplo, T5, BERT, RoBERTa)
- Carregar o modelo pré-treinado e o tokenizador

## 5. Fine-Tuning
- Definir a arquitetura do modelo para a tarefa específica
- Configurar hiperparâmetros (taxa de aprendizado, tamanho do batch, etc.)
- Treinar o modelo nos dados de treinamento
- Monitorar o desempenho usando o conjunto de validação

## 6. Avaliação do Modelo
- Avaliar o modelo no conjunto de teste
- Calcular métricas relevantes (por exemplo, perplexidade, BLEU score)

## 7. Implementação do Chatbot
- Criar uma interface para receber perguntas do usuário
- Usar o campo 'titles' do dataset como entrada para o modelo
- Gerar respostas usando o campo 'content' correspondente
