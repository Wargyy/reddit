## Next Delivery: Part 3, 8 November

#### 1. Software Process
- Try to find the approximate development process used by analysing the repository/code.

#### 2. Requirement Elicitation and Domain/Use-Cases Diagram
- Rewrite the Requirement part with the following guidelines

```
Requisitos

- Aceitam as pull requests, desde que estas obedeçam, aos standards de codigo deles.

- Em relação as issues/bugs, utilizam o git apenas para bugs confirmados, 
e tem uma pagina/subreddit propria para sugestões, feature requests.

- Por questões de segurança, pedem para nunca alertar para bugs por meios publicos, em vez disso pedem paraenviar os bugs para um email 
dedicado para isso.
```

- Make the domain and use-case diagrams

#### 3. Software Design: Architecture, frameworks, etc

Software:
http://staruml.io/ <-- Mentioned in email by the Prof.
Enterprise Architect, Anything that makes Standard UML diagramas.

Create the following Diagrams:
- Logic (Packages) -> Pedro A
- Components (Something that is higher level than classes) -> Daniel
- Deployment (Linked to Hardware) -> Pedro F
- Process (Activity Diagrams) -> Diogo

#### 4. Report of software Test - To delivery till 22.
Sugestion for the Report:

1) Degree of Testability of the software program
Topics: Discuss how 'testable' is the program. Discuss how to improve the testability of software components.

The testability of software components (modules, classes) is determined by factors such as:
- Controllability: The degree to which it is possible to control the state of the component under test (CUT) as required for testing.
- Observability: The degree to which it is possible to observe (intermediate and final) test results.
- Isolateability: The degree to which the component under test (CUT) can be tested in isolation.
- Separation of concerns: The degree to which the component under test has a single, well defined responsibility.
- Understandability: The degree to which the component under test is documented or self-explaining.
- Heterogeneity: The degree to which the use of diverse technologies requires to use diverse test methods and tools in parallel.

2) Test Statistics
  Number of tests (# tests unitários; # tests de sistema, # tests de desempenho, ...)
  % coverage (given by tools like EclEmma)
  Code coverage: is it any good? (see http://avandeursen.com/2013/11/19/test-coverage-not-for-managers/)

3) [Opcional] Take a bug report, create test cases to reproduce it, and fix it, eventually using automated software fault diagnosis techniques. (grade >18)

#### 5.
Boa tarde,

Após a entrega do trabalho prático ontem, resta apenas mais um trabalho prático (e apresentação). Para este último trabalho, talvez o mais trabalhoso, o que vos é pedido é o seguinte:

- Identificar uma feature que deva ser evoluida
- Identificar componentes que implementam essa feature
- Evoluir a feature, verificando que as restantes funcionalidades não são quebradas
- Submeter um patch

Continuação de bom trabalho.
Cumprimentos,
Rui Maranhão.
