# 🚀 Projeto de análise exploratória de dados utilizando Python e Pandas.

Olá! Este é um projeto de análise de dados que desenvolvi em aula para explorar como funciona o ecossistema de uma empresa de aluguel de carros, olhando não só para o lucro, mas também para o rastro de carbono que deixamos no caminho.

---

### 💡 O Desafio
Trabalhar com dados reais é, na maioria das vezes, lidar com a "bagunça". Recebi quatro bases de dados diferentes (CSV e JSON) que continham erros comuns do dia a dia: datas mal formatadas, valores negativos onde não deveriam existir e informações faltantes.

Meu objetivo principal foi **limpar, organizar e conectar esses pontos** para entender a saúde do negócio e seu impacto ambiental.

---

### 🔍 O que eu fiz (e o que aprendi no processo)

#### 1. Faxina nos Dados (Data Cleaning)
Ninguém toma boas decisões com dados errados. Eu foquei em:
* **Resolver o mistério dos dados ausentes:** Clientes e veículos sem informações completas (como idade ou emissão de CO2) foram ajustados usando médias estatísticas para manter a integridade da análise.
* **Corrigir o financeiro:** Ajustei tarifas que estavam negativas (erros de sistema) e transformei textos em números reais para cálculos precisos.
* **Padronizar o calendário:** Tratei datas com formatos diferentes e limpei entradas inválidas para conseguir calcular a duração real de cada locação.

#### 2. Criando Novas Visões (Feature Engineering)
Com os dados limpos, comecei a fazer as perguntas certas:
* *Quanto cada locação rendeu de verdade?* (Cálculo de Receita Total).
* *Qual o impacto ambiental de cada viagem?* (Cálculo de emissão de CO2 com base na distância e modelo).
* *Quando as coisas acontecem?* Extraí mês, ano e dia da semana para entender o comportamento das locações no tempo.

#### 3. O "Grande Encontro" (Merge)
O momento mais importante foi consolidar tudo em uma única tabela master. Juntei os dados do **Veículo**, do **Cliente** e da **Locação**. Agora, o projeto permite ver, por exemplo, se clientes de certas cidades preferem categorias específicas de carros ou quem são os locatários com maior pontuação de fidelidade.

---

### 🛠️ Minha Caixa de Ferramentas
* **Python**: Linguagem base.
* **Pandas**: Minha principal ferramenta para manipular e limpar as tabelas.
* **Numpy**: Suporte para operações matemáticas.
* **Google Colab**: Ambiente onde desenvolvi e testei o código.

---

### 🤝 Vamos conversar!
Estou sempre em busca de aprender novas formas de tratar dados e gerar insights. Se você tiver alguma sugestão ou quiser trocar uma ideia sobre o projeto, sinta-se à vontade para entrar em contato!
