## Descrição do Projeto

Este notebook contém exemplos práticos e implementações de modelos de tradução automática, incluindo abordagens utilizando Seq2Seq com LSTM e arquiteturas baseadas em Transformer, implementadas com TensorFlow.

## Estrutura do Notebook

1. **Preparação de Dados**
   - Criação de um dicionário de tradução simplificado.
   - Exemplo de código utilizado:
     ```python
     translation_dict = {
         'is': 'é',
         'house': 'casa',
         'small': 'pequena',
         'The':'a',
     }
     ```

2. **Implementação de Modelos Seq2Seq**
   - Exemplo de modelo Seq2Seq utilizando LSTM.
   - Exemplo de código utilizado:
     ```python
     import tensorflow as tf
     from tensorflow.keras.layers import Input, Embedding, LSTM, Dense
     from tensorflow.keras.models import Model
     ```

3. **Implementação de Modelos Transformer**
   - Introdução ao uso de modelos Transformer para tradução automática.
   - Exemplo de código utilizado:
     ```python
     # Exemplo de um modelo NMT que usa arquitetura Transformer
     ```

## Como Executar

1. Certifique-se de que todas as dependências necessárias estão instaladas, como TensorFlow.
2. Execute cada célula do notebook sequencialmente, começando pela preparação dos dados e seguindo pelas implementações dos modelos Seq2Seq e Transformer.

---

Este README oferece uma visão geral do conteúdo do notebook, destacando as implementações e as etapas principais do projeto. Se houver algo específico que você gostaria de adicionar ou ajustar, estou à disposição para ajudar!
