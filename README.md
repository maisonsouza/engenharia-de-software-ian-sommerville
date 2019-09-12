# Anotações do Curso de Engenharia de Software

## Capítulo 1 - Introdução
### Desenvolvimento profissional de software
### Ética na engenharia de software.
### Estudo de caso


## Capítulo 2 - Processos de Software
Um processo de software é um conjunto de atividades relacionadas que levam à produção de um produto de software.
### Atividades fundamentais para a engenharia de software.
* Especificação de sofwate, Projeto e implementação de software, Validação de software, Evolução de software.

## Modelo de processo de software
Um modelo de processo de software é uma representação simplificada de um processo de software. São abstrações que podem ser utilizadas para explicar diferentes abordagens de desenvolvimento de software.Um modelo possui fases.

### Modelo em Cascata (Processo dirigido a planos)
Principais estágios do modelo em cascata = Análise e definição de requisitos, Projeto de sistema e software, Implementação e teste unitário, integração e teste de sistema, Operação e manutenção(fase mais longa).
Atividades fundamentais = Processo de especificação, desenvolvimento, validação e evolução.
Fases = Especificação de requisitos, projeto de software, implementação, teste.
O planejamento e a programação das atividades do processo começam antes.
O estaǵio seguinte só inicia com a conclusão do estágio atual.

### Desenvolvimento Incremental
Essa abordagem intercala as atividades de modo que cada versão adiciona funcionalidade à anterior.No desenvolvimento incremental, o sistema é dividido em subsistemas ou módulos, tomando por base a funcionalidade.
Os incrementos (ou versões) são definidos, começando com um pequeno subsistema funcional que, a cada ciclo, é acrescido de novas funcionalidades.

### Engenharia de Software Orientado a Reuso.
Essa abordagem é baseada na existência de um número significativo de componentes reusáveis.


#### Estudar Lean

#### Scrum
```
Scrum é um framework leve, simples de entender e extremamente difícil de dominar, para desenvolver e manter produtos complexos e adaptativos.
```

```
ele é composto por três papeis (Product Owner, Scrum Master e Development Team); por quatro eventos (Sprint Planning, Daily Meeting, Sprint Review e Sprint Retrospective); por três artefatos (Product Backlog, Sprint Backlog e Product Increment); e por um fluxo (chamado Sprint).
```

O Scrum prega que, ao fim de cada sprint, deve-se entregar um incremento potencialmente funcional do produto ao cliente

O nome desses ciclos de desenvolvimento é Sprint!

RESPONSABILIDADES E CARACTERÍSTICAS: PRODUCT OWNER (PO)
Ele é responsável pela macro-gestão e pela gestão do produto.

RESPONSABILIDADES E CARACTERÍSTICAS: DEVELOPMENT TEAM (DT)
Responsável pela micro-gestão e pela criação do produto.

RESPONSABILIDADES E CARACTERÍSTICAS: SCRUM MASTER (SM)
Responsável pela gestão de pessoas e gestão do processo.

Product Backlog:
Antes de tudo, o que é um backlog? O backlog é uma lista, um resumo histórico, de
acumulação de trabalho num determinado período de tempo, pode ser uma pilha
de pedidos que devem ser produzidos

Sprint Backlog:

O Sprint Backlog é o conjunto de itens selecionados para serem implementados
durante a sprint mais o plano para transformá-los em um incremento

Product Increment
Ao final de cada sprint, a equipe de desenvolvimento entrega um incremento do
produto, resultado do que foi produzido durante a sprint

Definição da Reunião Diária

A Reunião Diária do Scrum é um evento time-boxed de 15 minutos para o Time de Desenvolvimento. A
Reunião Diária é realizada em todos os dias da Sprint. Nela o Time de Desenvolvimento planeja o
trabalho para as próximas 24 horas. Isso otimiza a colaboração e a performance do time através da
inspeção do trabalho desde a última Reunião Diária, e da previsão do próximo trabalho da Sprint. A
Reunião Diária é mantida no mesmo horário e local todo dia para reduzir a complexidade.

Histórias do usuário são descrições curtas e simples de um
recurso/objetivo contado a partir da perspectiva da pessoa que o
deseja, geralmente, um usuário ou cliente.

Sendo
<persona>
Quero/Gostaria
<O que>
Para / Para que
<Motivo/Resultado>
  
  SENDO um usuário on-line GOSTARIA de ser capaz de
simular um empréstimo pessoal em qualquer
dispositivo móvel PARA encontrar e contratar um
empréstimo de forma rápida e on-line.

São histórias de usuário grandes e não refinadas

Os critérios de aceitação fornecem clareza para o time sobre o
que se espera de uma história do usuário, remove ambiguidades
dos requisitos e contribui no alinhamento de expectativas


BDD (Behavior Driven Development)
§ Serve para criar testes e integrar regras de negócios com a linguagem
de programação, focando no comportamento do software.
§ Melhorar a comunicação entre as equipes de desenvolvimento e testes,
aumentando o compartilhamento de conhecimento entre elas.


Cenário: título
Dado que [cenário atual]
Quando [ação do usuário]
Então [como o software vai reagir]

Cenário 2: Estoque indisponível
Dado que o estoque da coca-cola é de 50 unidades
Quando informo uma venda de 60 unidades
Então a venda não é registrada



