# case-ton

### Execução:
Para simplificar a execução do código e pelas características do problema a análise foi feita em um notebook ipynb no google colab.
Formas de execução:
1) Direto pelo google colab -> forma mais simples, necessário apenas uma conta google.
2) Clonar o repositório em seu ambiente de preferência que suporte formato ipynb.

### Estrutura:
O projeto segue a seguinte estrutura:

```
case-ton/
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
|   ├── Desenvolvimento
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
└──────────────────
```
Detalhe das pastas (ou das seções por ser um formato ipynb):
- 'Bibliotecas' serve para importar e instalar as bibliotecas necessárias ao projeto.
- 'Pré-processamento' contém o scrip de tratamento de dados feito antes de iniciar as análises.
- As pastas Q1, Q2 (...) Q5, seguem uma estrutura de subpastas:
  
  &nbsp;&nbsp;&nbsp;&nbsp;* 'Desenvolvimento' -> contendo os scripts com o raciocínio passo a passo para resolução do problema; se necessário o 'Desenvolvimento' pode ter subpastas para modular os algoritmos desenvolvidos dentro dele.
  
  &nbsp;&nbsp;&nbsp;&nbsp;* 'Conclusão' -> apenas a resposta da pergunta feita e uma breve lógica do que foi feito no 'Desenvolvimento'; se pertinente a questão pode conter gráficos ou tabelas.




