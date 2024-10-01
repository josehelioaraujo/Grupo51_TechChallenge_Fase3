# **PosTech Inteligência Artificial Para Desenvolvedores - Fiap**
###  **Projeto Challenge Fase 3 - Grupo 51**

### **Objetivo**:
- Projeto de **Fine Tuning** de um Modelo Foundation LLM(**LLaMA 3 8B**), utilizando o dataset "**The AmazonTitles-1.3MM**".

### **Descrição do Arquivo**:
  - Arquivo Colab Principal do Projeto Tech Challenge Fase 3

### **Grupo 51/Alunos:**
  
| Matrícula                       | Nome do Aluno  | Email                                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| RM355027 | José Hélio Araujo Andrade  | helioandrade@hotmail.com|
| RM356210 | Bernardo Guimarães Tinti   | betinti@hotmail.com |

## **Introdução**
A implementação da solução desse projeto, foi dividida em 5 arquivos Colab,   visando dividir as funcionalidades por etapas, tais como:
   - Arquivo Principal com links para as etapas do projeto
   - Etapa de Prepação dos Dados
   - Etapa de Geração de Perguntas e Respostas - Sem Fine Tuning
   - Etapa de Geração de Perguntas e Respostas - Com Fine Tuning
   - Comparativo Avaliação do Modelo - Com X Sem Fine Tuning

# **Entregáveis**


- [Repositório no GitHub](https://github.com/josehelioaraujo/Grupo51_TechChallenge_Fase3)   
- [Video Apresentação no Youtube](https://www.youtube.com/watch?v=Tg8BMBnIWOI)  


### **Arquivos no Google Colab**

| Descrição do Arquivo Colab | Link de acesso   |
| ------------------------------------------------------------ |   ------------------------------------------------------------ |
| Colab Principal(esta página)   | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1PWEjYtJVAXYlr2zqjj3Ts8r_gW31m_cV#scrollTo=48mnS5Es6O_y) |
| Etapa de Preparação do Dados   | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1QBcfFYk8ij5GZZ8lHKjMhzXUnTgcXUQN#scrollTo=lFz7PZnJBCg) |
| Etapa de Geração de Perguntas e Respostas - Sem Fine Tuning   | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1dsZ8I_LtLQ2d6H5fmQMw9JZP8NrzZ7at#scrollTo=PFioDDNoSFUf) |
| Etapa de Treinamento do Modelo e Geração de Perguntas e Respostas    | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1C4ti87nuhmzfHzjwc-iqYitp883bZRGA) |
| Comparativo Avaliação do Modelo - Com X Sem Fine Tuning    | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1hlUUkRJZeVQoqlSzaaAxJwbBCC6cklEr?usp=sharing) |

  
  

### **Datasets no Hungging Face**

| Datasets                               | Descrição                                                  | Link de Acesso                                                  |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Dataset Original |Dataset original que será usado no Fine Tuning no treinamento do modelo  | [![Dataset on HF](https://huggingface.co/datasets/huggingface/badges/resolve/main/dataset-on-hf-sm.svg)](https://huggingface.co/datasets/helioandrade/amazon-titles-jsonl) |
| Datasets com 'Chunks'  | Datasets que foram particionados a partir do dataset original |[![Dataset on HF](https://huggingface.co/datasets/huggingface/badges/resolve/main/dataset-on-hf-sm.svg)](https://huggingface.co/datasets/helioandrade/amazon-titles) |
| Datasets com Fine Tuning  | Datasets com Fine Tuning e treinados com perguntas e respostas | [![Dataset on HF](https://huggingface.co/datasets/huggingface/badges/resolve/main/dataset-on-hf-sm.svg)](https://huggingface.co/datasets/helioandrade/amazon-titles-questions-answering/tree/main) |




### **Ferramentas utilizadas**
- [Conversor texto/audio ](https://crikk.com/text-to-speech/portuguese/)- usado na criação do audio da narração
- **OBS Studio** - usado na gravação do video de apresentação
- **DaVinci Resolve** - usado na montagem e edição do video de apresentação
