# FIAP Fase 5 - Previsão de Produtividade Agrícola com Machine Learning

## 📌 Sobre o projeto

Projeto desenvolvido para a Fase 5 do curso de Inteligência Artificial da FIAP.

O objetivo é aplicar técnicas de Machine Learning para analisar dados relacionados à produtividade agrícola e desenvolver modelos capazes de realizar previsões de produtividade (Yield) a partir de variáveis climáticas.

O projeto também contempla uma análise de infraestrutura em nuvem utilizando a AWS, comparando alternativas de processamento e seus respectivos custos.

## 📊 Dataset

O conjunto de dados utilizado está disponível neste repositório no arquivo:

`crop_yield.csv`

A base possui 156 registros e contém informações como:

- Cultura agrícola (Crop)
- Precipitação
- Umidade específica
- Umidade relativa
- Temperatura
- Produtividade agrícola (Yield)

## 🤖 Machine Learning

O desenvolvimento do modelo foi realizado em Python utilizando o Google Colab.

Durante o projeto foram realizadas etapas de:

- Carregamento e exploração dos dados
- Análise das características do dataset
- Preparação dos dados
- Separação entre dados de treino e teste
- Treinamento de modelos de Machine Learning
- Avaliação dos resultados
- Comparação entre os modelos

O notebook completo está disponível em:

`Fase_5_FIAP_Crop_Yield.ipynb`

## ☁️ Análise de custos na AWS

Além do desenvolvimento do modelo de Machine Learning, foi realizada uma análise de custos de infraestrutura utilizando o AWS Pricing Calculator.

A análise considera recursos computacionais adequados ao cenário proposto, permitindo avaliar o custo estimado da execução da solução em nuvem.

## 🛠️ Tecnologias utilizadas

- Python
- Pandas
- Scikit-learn
- Google Colab
- Machine Learning
- AWS
- GitHub

## 📁 Estrutura do repositório

- `Fase_5_FIAP_Crop_Yield.ipynb` — notebook com a análise e os modelos de Machine Learning
- `crop_yield.csv` — conjunto de dados utilizado no projeto
- `README.md` — documentação do projeto

## 🎓 Instituição

FIAP — Faculdade de Informática e Administração Paulista

Curso: Tecnólogo em Inteligência Artificial

## 👤 Autor

Willians Roberto da Silva

## ☁️ Análise de custos na AWS

Para a execução da solução em nuvem, foi realizada uma comparação de custos utilizando a AWS Pricing Calculator em duas regiões diferentes.

### Comparação de custos

| Região AWS | Custo mensal estimado |
|---|---:|
| América do Sul (São Paulo) | US$ 17,38 |
| Leste dos EUA (N. da Virgínia) | US$ 10,13 |

A região Leste dos EUA (N. da Virgínia) apresentou o menor custo, com uma economia estimada de US$ 7,25 por mês em relação à região de São Paulo, aproximadamente 41,7%.

Com base na análise de custos, a região N. da Virgínia apresenta a alternativa mais econômica para o cenário avaliado.

### Justificativa da escolha da região

Embora a região Leste dos EUA (N. da Virgínia) apresente o menor custo mensal, para este projeto a região escolhida seria a América do Sul (São Paulo).

A escolha de São Paulo se justifica pela necessidade de acesso rápido aos dados coletados pelos sensores da fazenda, reduzindo a latência por estar geograficamente mais próxima da origem dos dados. Além disso, considerando a existência de restrições legais para o armazenamento de dados no exterior, manter a infraestrutura na região de São Paulo permite que os dados permaneçam armazenados no Brasil.

Portanto, mesmo apresentando um custo mensal superior, a região de São Paulo é a opção mais adequada para o cenário proposto, conciliando desempenho, menor latência e atendimento às restrições de armazenamento dos dados.

<img width="1920" height="1080" alt="Captura AWS" src="https://github.com/user-attachments/assets/34f976ba-a222-4cc9-978b-36365c946c4d" />


## 🎥 Vídeo Demonstrativo – Entrega 1

Vídeo demonstrativo da Entrega 1 – Machine Learning:

[▶️ Assistir ao vídeo no YouTube](https://youtu.be/E4BoE-xwCW0)


## 🎥 Vídeo Demonstrativo – Entrega 2

Vídeo demonstrativo da Entrega 2 – Computação em Nuvem AWS:

[▶️ Assistir ao vídeo no YouTube](https://youtu.be/lCIoKgJg3go)
