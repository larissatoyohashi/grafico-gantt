# grafico-gantt
Material desenvolvido na disciplina de Gestão Ágil de Projetos no terceiro semestre do curso de Desenvolvimento de Software Multiplataforma da FATEC de Registro

```mermaid
gantt
title Construção de uma Casa
dateFormat YYYY-MM-DD
section Planejamento
1ºMês - Planejamento e Aprovações:active pa, 2025-01-01, 20d
2ºMês - Preparação do Terreno: pt, 2025-01-15, 10d
3ºMês - Escavação e Construção:active a3, after a2, 15d
4ºMês - Fundação: a4, after a3, 30d
5ºMês - Instalação Elétricas e Hidráulicas:a5, after a4, 20d
6ºMês - Acabamento Interno:a6, after a5, 25d
7ºMês - Acabamento Externo:a7, after a6, 15d
8ºMês - Inspeção Final:a8, after a7, 5d

```


```mermaid
gantt
title Exemplo de Gráfico de Gantt
dateFormat YYYY-MM-DD
section 1ºBimestre
1ºBimestre Finalizado:done a1, 2025-02-02, 60d
2ºBimestre Finalizado:done a2, after a1, 60d
section 2ºBimestre
3ºBimestre Em Andamento:active a3, 2025-08-01, 60d
4ºBimestre Em Andamento:crit a4, after a3, 60d
```



# crystal
```mermaid
graph TD
  subgraph Matriz
A1["C8"]:::branco-->A2["C20"]:::amarelo-->A3["V50"]:::laranja-->A4["V100"]:::vermelho
B1["C8"]:::branco-->B2["C20"]:::amarelo-->B3["V50"]:::laranja-->B4["V100"]:::vermelho
C1["C8"]:::branco-->C2["C20"]:::amarelo-->C3["V50"]:::laranja-->C4["V100"]:::vermelho
D1["C8"]:::branco-->D2["C20"]:::amarelo-->D3["V50"]:::laranja-->D4["V100"]:::vermelho


 
end

classDef branco fill: #fff, stroke: #000, strike-width: 1px;
classDef amarelo fill: #FFD8D, stroke: #000, strike-width: 1px;
classDef laranja fill: #FFA233, stroke: #000, strike-width: 1px;
classDef vermelho fill: #E64C3C, stroke: #000, strike-width: 1px;

```

# crystal - atividade 02

