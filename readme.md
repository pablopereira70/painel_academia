# Desafio Módulo 6 — DataViz & Storytelling

**Sobre o projeto**

Projeto desenvolvido como parte do desafio do Módulo 6 da formação de Analista de Dados do bootcamp [EducaDados](https://www.linkedin.com/company/educadadostech/home/).

O desafio consiste em analisar os dados de uma rede de academias, buscando compreender o comportamento dos alunos, a frequência de treinos, a receita e identificar possíveis riscos de cancelamento.

A solução proposta é um dashboard interativo de página única, desenvolvido no Power BI, seguindo boas práticas de Data Visualization.

## Objetivos

- Analisar a quantidade e o comportamento dos alunos.
- Acompanhar a frequência de treinos ao longo do tempo.
- Analisar a receita por plano.
- Identificar alunos ativos, inativos e em risco.
- Facilitar a exploração dos dados por período e unidade.

## Escopo do dashboard

O dashboard deverá contemplar os seguintes indicadores:

**KPIs**
- Total de alunos;
- Receita total;
- Média de frequência por aluno;
- Percentual de alunos ativos.

**Visualizações**
- Frequência ao longo do tempo;
- Receita por plano;
- Alunos por status;
- Alunos mais frequentes;
- Heatmap de dia da semana e horário.

**Filtros**
- Período;
- Unidade.

Também será desenvolvida uma lógica para identificar alunos em risco, considerando a ausência de treinos por mais de 10 dias.

## Tecnologias e ferramentas

- **Power BI:** tratamento, modelagem, análise e visualização dos dados.
- **Power Query:** extração e transformação dos dados.
- **DAX:** criação de medidas e regras de negócio.
- **Figma:** planejamento do layout e definição da identidade visual.
- **Excel:** armazenamento da base de dados original.

## Organização do projeto

```text
.
├── README.md
├── docs/
│   ├── capturas/
│   ├── instrucoes.docx
│   ├── etl.md
│   ├── modelagem.md
│   ├── medidas.md
│   └── dashboard.md
├── dados/
│   └── base_academia.xlsx
├── design/
│   └── fundo.png
└── dashboard/
    └── desafio_dataviz.pbip
```

### Documentação

A pasta `docs/` reúne a documentação técnica das etapas de desenvolvimento:

| Arquivo | Conteúdo |
|---|---|
| `etl.md` | Extração, transformação e carga dos dados. |
| `modelagem.md` | Estrutura do modelo e relacionamentos. |
| `medidas.md` | Medidas DAX e regras de negócio. |
| `dashboard.md` | Construção e decisões de Data Visualization. |
| `capturas/` | Contém capturas de tela do projeto. |

## Progresso do desenvolvimento

- [X] Entendimento e exploração dos dados.
- [X] ETL e tratamento dos dados.
- [ ] Modelagem dos dados.
- [ ] Desenvolvimento e validação das medidas.
- [ ] Elaboração do layout no Figma.
- [ ] Construção do dashboard no Power BI.
- [ ] Validação dos requisitos e resultados.
- [ ] Documentação final e instruções de execução.

## Execução local

*As instruções para configuração do ambiente e execução do projeto serão adicionadas após a conclusão do desenvolvimento.*

## Resultado

*Imagens e apresentação do dashboard serão adicionadas após a finalização do projeto.*

---

Desenvolvido por Pablo Pereira 🧑‍💻