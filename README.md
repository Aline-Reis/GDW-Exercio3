 Árvore de Nós DOM
```mermaid
graph TD
  A[Document] --> B[biblioteca]

  %% Primeiro livro
  B --> C1[livro]
  C1 --> A1["atributo: categoria='ficcao'"]

  C1 --> D1[titulo]
  D1 --> E1["O Guia do Mochileiro das Galáxias"]

  C1 --> D2[autor]
  D2 --> E2["Douglas Adams"]

  %% Segundo livro
  B --> C2[livro]
  C2 --> A2["atributo: categoria='tecnico'"]

  C2 --> D3[titulo]
  D3 --> E3["Introdução ao XML"]

  C2 --> D4[autor]
  D4 --> E4["Professor Exemplo"]
