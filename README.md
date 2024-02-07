# case-ton

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
   
3) Clonar o repositório em seu ambiente de preferência que suporte formato ipynb.

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

###### Dúvidas favor contactar pelo email: gustavoamora@gmail.com


