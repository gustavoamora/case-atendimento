# case atendimento

### Overview:
Este projeto tem como objetivo abordar o uso de I.A e a criação de KPIs para a área de relacionamento com o cliente.

Questões a serem respondidas:
1. Foi implementada no dia 1 de agosto uma funcionalidade nova no site que acreditam que irá diminuir a quantidade de chamados recebidos relacionados ao nosso produto. Avalie se a implementação teve um impacto estatisticamente relevante.
2. Foi notado por alguns agentes do Relacionamento com o Cliente que clientes mais recentes possuem um comportamento específico em relação à quantidade de chamados realizados logo após seu credenciamento. Prepare alguma forma de visualizar essa diferença notada pelos agentes.
3. Para conseguir melhorar a qualidade do atendimento ao cliente, foi proposto que a fila de espera para atendimento contemple prioridade para certos casos de atendimento. Proponha uma clusterização da base de clientes que julgue atender da melhor forma a necessidade apresentada.
4. Usando as tabelas disponibilizadas, faça um query que retorne o volume de chamados por semana dos últimos três meses para cada cluster de clientes proposto na questão 3.
5. Para melhorar o direcionamento da área de Relacionamento com o Cliente, a gestão precisa do insumo necessário para entender como se comportam nossos clientes e assim melhorar a tomada de decisão. Apresente pelo menos 3 KPIs que julgue relevantes para acompanhamento diário da operação do Relacionamento com oCliente.

### Execução:
Para simplificar a execução do código e pelas características do problema a análise foi feita em um notebook ipynb no google colab.

Formas de execução:

1) Direto pelo google colab -> [LINK](https://colab.research.google.com/github/gustavoamora/case-ton/blob/main/case_ton.ipynb)
   
   &nbsp;&nbsp;&nbsp;&nbsp;- Para visualizar os scripts e seus outputs é simples, basta apenas acessar o link.
   
   &nbsp;&nbsp;&nbsp;&nbsp;- Para executar os scripts é necessário logar em conta google e adicionar os arquivos case.csv e creds.csv (disponíveis na pasta data) dentro do ambiente de 'Arquivos' do colab. Basta baixar os                               arquivos para sua máquina          local e arrastá-los, desta maneira:
   ![Add base de dados](https://github.com/gustavoamora/case-ton/blob/main/images/colab.png)
   Após o carregamento, deve ficar assim:
   ![Add base de dados](https://github.com/gustavoamora/case-ton/blob/main/images/colab2.png)

   Com estes passos é possível executar os códigos.
   
3) Outra opção de execução seria clonar o repositório em seu ambiente de preferência que suporte formato ipynb.

### Estrutura:
O projeto segue a seguinte estrutura:

```
case-ton.ipynb/
├── Bibliotecas/
│   ├── Instalações 
│   └── Import
├── Pré-processamento/
|   ├── Tabela 'cases'
│   └── Tabela 'creds'   
├── Q1/
|   ├── Desenvolvimento
│   └── Conclusão
├── Q2/
|   ├── Desenvolvimento
│   └── Conclusão
├── Q3/
|   ├── Desenvolvimento/
│   │   └── Volume por categoria e subcategorias
│   │   └── Regras de associação
│   │   └── Cadeia de Markov
│   └── Conclusão
├── Q4/
|   ├── Desenvolvimento
│   └── Conclusão
├── Q5/
|   ├── Desenvolvimento
│   └── Conclusão
│
data/
├── case.csv
├── creds.csv
└── CASE TON.pdf
images/
├── colab.png
└── colab2.png
requirements.txt
└──────────────────────────

```
Detalhe das pastas/seções do arquivo principal 'case-ton.ipnb':
- 'Bibliotecas' serve para importar e instalar as bibliotecas necessárias ao projeto.
- 'Pré-processamento' contém os scripts de tratamento dos dados feito antes de iniciar as análises.
- As pastas Q1, Q2 (...) Q5, seguem uma estrutura de subpastas:
  
  &nbsp;&nbsp;&nbsp;&nbsp;* 'Desenvolvimento' -> contendo os scripts com o raciocínio passo a passo para resolução do problema; se necessário o 'Desenvolvimento' pode ter subpastas para modular os algoritmos desenvolvidos dentro dele.
  
  &nbsp;&nbsp;&nbsp;&nbsp;* 'Conclusão' -> apenas a resposta da pergunta feita e uma breve lógica do que foi feito no 'Desenvolvimento'; se pertinente a questão pode conter gráficos ou tabelas.

### Dados:
<img width="284" alt="image" src="https://github.com/gustavoamora/case-atendimento/assets/99370492/21c34ad1-f1f7-4b4d-9a67-8c3030d25447">


###### Dúvidas favor contactar pelo email: gustavoamora@gmail.com


