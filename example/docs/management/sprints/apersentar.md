
# APRESENTAR AUTORIZACAO
Apresentar a autorização

## Dados do Sprint
* **Goal**:  Apresentar a autorização
* **Data Início**: 30/11/2024
* **Data Fim**: 31/11/2024

## Sprint Backlog

|ID |Nome |Resposável |Data de Inicío | Data Planejada | Status|
|:----    |:----|:--------  |:-------:       | :----------:  | :---: |
|spike.epic1.story1.estudar|Estudar sobre OPA|João Marcos ||30/11/2024|TODO|
|spike.epic1.story1.apresentar|Apresentar o estudo OPA|João Marcos |20/11/2024|30/11/2024|DONE|
|spike.epic1.story2.apresentar|Apresentar o estudo OpenFGA|João Marcos |20/11/2024|30/11/2024|DOING|

# Análise de Dependências do Sprint

Análise gerada em: 25/11/2024, 10:38:11

## 🔍 Grafo de Dependências

```mermaid
graph BT
    classDef sprint fill:#a8e6cf,stroke:#333,stroke-width:2px;
    classDef done fill:#98fb98,stroke:#333,stroke-width:2px;
    classDef external fill:#ffd3b6,stroke:#333,stroke-width:1px;
    spike.epic1.story2.estudar["🔍 spike.epic1.story2.estudar<br>⚠️ Dependência Externa"]:::external
    spike.epic1.story1.estudar["🔍 Identificador: spike.epic1.story1.estudar<br>📝 Tarefa: Estudar sobre OPA<br>📊 Estado: TODO<br>👤 Responsável: João Marcos "]:::sprint
    spike.epic1.story1.apresentar["🔍 Identificador: spike.epic1.story1.apresentar<br>📝 Tarefa: Apresentar o estudo OPA<br>📊 Estado: DONE<br>👤 Responsável: João Marcos "]:::done
    spike.epic1.story2.apresentar["🔍 Identificador: spike.epic1.story2.apresentar<br>📝 Tarefa: Apresentar o estudo OpenFGA<br>📊 Estado: DOING<br>👤 Responsável: João Marcos "]:::sprint
    spike.epic1.story1.apresentar -.-> spike.epic1.story2.estudar
    spike.epic1.story1.apresentar --> spike.epic1.story1.estudar
    spike.epic1.story2.apresentar -.-> spike.epic1.story2.estudar
    spike.epic1.story2.apresentar --> spike.epic1.story1.estudar
```

**Legenda:**
- 🟢 Verde Claro: Issues no sprint
- 🟢 Verde Escuro: Issues concluídas
- 🟡 Laranja: Dependências externas ao sprint
- ➡️ Linha sólida: Dependência no sprint
- ➡️ Linha pontilhada: Dependência externa

## 📋 Sugestão de Execução das Issues

| # | Issue | Título | Status | Responsável | Dependências |
|---|-------|--------|--------|-------------|---------------|
| 1 | spike.epic1.story1.estudar | Estudar sobre OPA | TODO | João Marcos  | 🆓 |
| 2 | spike.epic1.story1.apresentar | Apresentar o estudo OPA | DONE | João Marcos  | spike.epic1.story2.estudar⚠️, spike.epic1.story1.estudar |
| 3 | spike.epic1.story2.apresentar | Apresentar o estudo OpenFGA | DOING | João Marcos  | spike.epic1.story2.estudar⚠️, spike.epic1.story1.estudar |

**Legenda das Dependências:**
- 🆓 Sem dependências
- ✅ Issue concluída
- ⚠️ Dependência externa ao sprint



## Cumulative Flow
![ Cumulative Flow](./charts/cfd-apersentar.svg)


