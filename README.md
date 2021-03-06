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


## Capítulo 8 -Testes de software

### Objetivos

```
Os testes pretendem mostrar que um programa faz o que foi destinado a fazer 
e descobrir defeitos do programa antes que ele seja colocado para uso.
```

* O Processo de teste tem dois objetivos: 
  
  *1 - Demonstrar ao desenvolvedor e ao cliente que o software atende aos requisitos.*
  
  *2 - Descobrir situações em que o software se comporta de maneira incorreta, indesejável ou de forma diferente 
  das especificações.*
  
* O primeiro objetivo leva a **testes de validação**, nos quais você espera que o sistema execute corretamente usando 
determinado conjunto de casos de teste que refletem o uso esperado do sistema.
* O segundo objetivo leva a **testes de defeito**, nos quais os casos de teste são projetados para expor os defeitos.

**Os testes não podem demonstrar se o software é livre de defeitos.(DIJKSTRA)**

Os testes fazem parte processo mais amplo de verificação e validação.(V&V)
* **Validação** - estamos construindo o produto certo? (Produto)
* **Verificação** - estamos construindo o produto corretamente?(Processo)

O objetivo da *verificação* é o processo de conferir se o software cumpre seus requisitos funcionais e não funcionais.
O objetivo da *validação* é garantir que o software atenda as expectativas do cliente.

A *validação* é essencial porque nem sempre a especificação de requsitos reflete o desejo do cliente e usuários do sistema.
O teste é uma verificação dinâmica de *Validação e Verificação* (V&V)
* O objetivo final dos processos de verificação e validação é estabelecer a confiança de que o software está pronto,
para seu propósito. Isso significa que o sistema deve ser bom o suficiente para seu intuito.

Atvidades estáticas de V&V
- Inspeção e Revisão (código fonte)

* Vantagens da inspeção de software:
1 - Durante o teste, erros podem esconder outros erros. Como a inspeção é um processo estático, você não precisa se preocu
par com as interações entre os erros.
2 - Podemos inspecionar sistemas incompletos sem custos adicionais.
3 - Podem revelar outros problemas que impactam na qualidade como: ineficiências, algoritmos inadequados, estilo pobre
de programação que dificultará a manutenção e atualização.

As inspeções de programa são uma idéia antiga e vários estudos e experimentos demonstraram que as inspeções são mais 
eficazes na descoberta de defeitos do que os teste de programa.

Engano  -> Defeito -> Erro  -> Falha.
Mistake -> Bug     -> Error -> Failure

Geralmente o sistema de software comercial passa por três estágios:
1 - Testes em desenvolvimento, em que o sistema é testado durante o desenvolvimento para descobrir bugs e defeitos
Projetistas de sistemas e programadores podem estar envolvidos no processo.
2 - Testes de lançamento (release) em que uma equipe de teste independente testa uma versão completa do sistema antes que ele seja 
liberado para os usuários. O objetivo dos testes de release é verificar se os sistema atende aos requisitos dos stakeholders
3 - Testes de usuário, em que os usuários ou potenciais usuários de um sistema testam o sistema em seu próprio ambiente.
O teste de aceitação é um exemplo de teste de usuário em que o cliente testa formalmente o sistema para decidir se aceita ou se
mais desenvolvimento será necessário.



Teste manual - um testador executa o programa com alguns dados de teste e compara os resultados com suas expectativas, ele 
anota e passa as discrepâncias aos desenvolvedores so programa.
Teste automatizados - Os testes são codificados em um programa que é executado cada vez que o sistema em desenvolvimento é testado.

Testes de regressão - reexecução de testes anteriores para verificar se as alterações no programa não introduziram novos bugs.


### Testes de desenvolvimento
```
Inclui todas as atividades de teste executadas pela equipe responsável pelo sistema.
```
* O testador do software geralmente é o programador que o desenvolveu.
* Alguns processos de desenvolvimento usam pares programador-testador.

* Existem três estágios de testes em desenvolvimento
```
1 - Teste de unidade - em que são testadas unidades do programa ou classes individuais. Esse tipo de teste deve se 
concentrar em testar a funcionalidade dos objetos e seus métodos.(Desenvolvedor)
2 - Teste de componentes - em que várias unidades são integradas, criando componentes compostos. Esse teste deve se concentrar
em testar as interfaces dos componentes que promovem acesso as funções.()
3 - Teste de sistema - em que alguns ou todos os componentes em um sistema são integrados e o sistema é testado como um todo
O teste de sistema deve se concentrar em testar as interações dos componentes. 
```
* O teste de desenvolvimento é basicamente um processo de teste dos defeitos cujo objetivo é descobrir bugs de software.
Geralmente ele é intercalado com a depuração, processo de localizar problemas no código e alterar o programa para consertá-los.

**Depuração**
```
É o processo de consertar erros e problemas que foram descobertos por meio de testes.
Usando as informações dos testes de programa, os depuradores, aplicam seu conhecimento de linguagem de programação e o resultado
esperado do teste para localizar e consertar o erro do programa.
```

#### Teste de unidade
```
É o processo de testar os componentes de programa, como os métodos ou as classes.
```
* As funções ou métodos são o tipo de componente mais simples.
Esse teste consiste em chamadas para essas rotinas com diferentes parâmetros de entrada.
* Sempre que possível o teste de software deve ser automatizado.
* Um framework de automação de teste como o **JUnit** pode ser usado para escrever e executar testes do programa. Os fra
meworks de teste de unidade fornecem cem classes de teste genéricas que podem ser estendidas para criar casos de teste
específicos.
* Um teste automatizado tem três partes:
```
1 - Uma parte de configuração, em que o sistema é iniciado com o caso de teste ou seja as entradas e saídas esperadas.
2 - Uma parte da chamada, em que se chama o objeto ou o método a ser testado.
3 - Uma parte de asserção, em que o resultado da chamada é comparado com o resultado previsto.
```
**Mock objects** são objetos com as mesma interface dos objetos externos que estão sendo utilizados, simulando sua funci
onalidade.

#### Escolhendo casos de teste de unidade
```
Testar é caro e demorado, então é importante escolher casos de teste de unidade eficazes. A eficácia, neste caso, signi
fica duas coisas:
1 - Os casos de testes devem mostrar que, quando utilizado conforme o esperado, o componente que está sendo testado faz
o que deveria fazer;
2 - Se houver defeitos no componente, eles devem ser revelados pelos casos de teste.
```
* Portanto, devem ser projetados dois tipos de teste:
```
Teste de partição - São identificadops grupos de entrada com características comuns que devem ser processadas da mesma
maniera.Deve se escolher testes de dentro de cada um desses grupos.
Teste baseado em diretriz - Nesse tipo de teste, diretrizes que refletem a experiência prévia com os tipos de erros que
os programadores costumam cometer quando desenvolvem componentes são usadas para escolher ows casos de teste.
```
 

### Desenvolvimento dirigido por testes.

### Teste de lançamento.

### Teste de usuário.





