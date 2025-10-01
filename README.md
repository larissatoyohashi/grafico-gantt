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

```mermaid
graph TD
  subgraph Matriz
A1[" Agendamento lento - C10"]:::branco
A2[" E-commerce fora de ar - E50"]:::laranja
A3[" Sistema hospitalar com falhas - V50"]:::laranja
A4[" Delivery sem atualização de status - C8"]:::branco
A5[" Registro de ponto do RH - D20"]:::amarelo
A6[" Email corporativo fora do ar - E20"]:::amarelo
A7[" Falha de segurança na fintech - E100"]:::vermelho
A8[" Sistema de controle de tráfego aéreo - V100"]:::vermelho



 
end

classDef branco fill: #fff, stroke: #000, strike-width: 1px;
classDef amarelo fill: #FFD8D, stroke: #000, strike-width: 1px;
classDef laranja fill: #FFA233, stroke: #000, strike-width: 1px;
classDef vermelho fill: #E64C3C, stroke: #000, strike-width: 1px;

```


# Gráfico Gantt - Reposição FETEPS

```mermaid
gantt
title Sistema de Biblioteca Online
dateFormat YYYY-MM-DD
section Planejamento

1ª Etapa - Definição de requisitos:done, 2025-01-01, 10d
1ª Etapa - Design :done, 2025-01-10, 10d

section Desenvolvimento
2ª Etapa - Módulo de Usuário:active pa, 2025-01-20, 15d
2ª Etapa - Módulo de Acervo:active pa, 2025-02-04, 15d

section Teste
3ª Etapa - Teste de autenticação: pt, 2025-02-19, 10d
3ª Etapa - Teste de integração: pt, 2025-02-29, 10d

section Implantação
4ª Etapa - Preparação do Ambiente de Produção: pt, 2025-03-09, 10d
4ª Etapa - Implementação: pt, 2025-03-19, 10d

```

# Atividade Grafico Crystal - Gantt

```mermaid
gantt
    title Cronograma - Sistema de Cadastro de Empresas Parceiras
    dateFormat  YYYY-MM-DD
    axisFormat  %Y-%m
    
    section Planejamento
    Levantamento de Requisitos :done, p1, 2025-10-01, 2w
    Documentação Funcional     :done, p2, after p1, 2w
    Design de Interface (UI/UX): p3, after p2, 4w

    section Desenvolvimento
    Configuração do Ambiente e BD  :active, d1, after p2, 1w
    Módulo de Login (Entrega 1)    :d2, after d1, 2w
    CRUD de Empresas (Entrega 2)   :d3, after d2, 3w
    Upload de Logotipo (Entrega 3) :d4, after d3, 2w
    Módulo de Relatórios (Entrega 4) :d5, after d4, 2w
    Painel Admin (Entrega 5)     :d6, after d5, 2w

    section Testes e Validação
    Testes Unitários e Integração : t1, after d2, 16w
    Testes de Usabilidade         :t2, after d6, 2w
    Correções e Ajustes Finais    :t3, after t2, 2w
    
    section Implantação
    Preparação do Servidor      :f1, after t3, 1w
    Implantação e Entrega Final :f2, after f1, 1w
```
# Atividade Grafico Crystal - Crystal

```mermaid
graph TD
  subgraph Matriz
A1[" Entrega 1 - D8"]:::branco
A2[" Entrega 2 - D20"]:::amarelo
A3[" Entrega 3 - C8"]:::branco
A4[" Entrega 4 - E8"]:::amarelo
A5[" Entrega 5 - E20"]:::amarelo
A6[" Entrega final - E8"]:::laranja
end
classDef branco fill: #fff, stroke: #000, strike-width: 1px;
classDef amarelo fill: #FFFF00, stroke: #000, strike-width: 1px;
classDef laranja fill: #FFA233, stroke: #000, strike-width: 1px;
classDef vermelho fill: #E64C3C, stroke: #000, strike-width: 1px;

```
