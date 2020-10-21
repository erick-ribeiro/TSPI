# Testes em diferentes contextos

Para que uma aplicação seja desenvolvida, ela passa por um processo composto por atividades. Há dois modelos de processos bastante populares, o Tradicional e o Ágil.
 1. Com base na leitura do requisito e criado o **caso de teste**  e **plano de teste**. 
 2. Com a aplicação em mãos são testados os cenários que contam no caso de testes sempre respeitando o plano de teste. 
 3. As inconsistências que surgirem devem ser evidenciadas contendo qual o
    resultado esperado do que encontramos.
 4. Devem ser sempre evidenciados os logs fornecidos pelos caso de teste.

## Tradicional
O processo Tradicional é faseado e de escopo fechado.

Preciso colocar todo o meu foco no cumprimento de minha atividade primária, **que é produzir artefatos e testar aplicações, baseando-se nas documentações e requisitos fornecidos por fases anteriores**.

No processo tradicional definimos primeiramente o escopo e as fases.

1. Produzindo Documentação (Requisitos e documentação)
Atividades: Revisar Documentação.
Artefatos: Plano de Teste e Casos de Testes.

2. Codificação (Aplicação e serviços)
Atividades: Revisando código fonte.
Artefatos: Testes de unidade e testes de integração.

3. Testando (Resultados dos testes)
Atividades: Executando os casos de testes já criados, Automatizando testes e Gerindo inconsistências e retestando.
Artefatos: Log de testes, Reporte de inconsistências e Sripts de teste automatizado.

4. Homologando (Opinião dos usuários)
Atividades: Auxiliando os usuários nos testes de aceitação.
Artefatos: Reporte de inconsistências.

5. Entrega (Sistema em produção)
Atividades: Versionando o testware, Emitindo relatórios de fechamento dos testes e Monitorando a aplicação em produção.
Artefatos: Reporte de inconsistências e Relatórios de resumo dos testes.

## Ágil
Não sou o guardião da qualidade do produto. **Eu compartilho as responsabilidades de teste com o time de desenvolvimento e os mentoro na aplicação de testes desde a concepção** a entrega em produção. Todos precisam automatizar testes, por isso eu crio e ajudo meu time a codificar esses testes.

1. Desenho(Estórias, diagramas, UX, etc).
Atividades: Discussões quanto a viabilidade, Revisão de artefatos e Levantamento de Riscos.
Artefatos: Mapas mentais.

2. Refinamento(Critérios de Aceitação).
Atividades: Colaborando na definição de critérios de aceitação, revisão de artefatos, estimativas de esforço em teste, levantamento de riscos e atualização do plano de testes.
Artefatos: Mapas mentais

3. Planejamento(Escopo de construção).
Atividades: Estimativas de esforço em teste.
Artefatos: Tarefa de teste.

4. Codificação e Testes(Aplicação e serviços).
Atividades: Executando tarefas de teste, executando testes exploratórios, automatizando testes, suportando desenvolvedores na escrita de testes, gerindo inconsistências e retestando.
Artefatos: Reporte de inconsistências, scripts de testes automatizado, testes de unidades e integração.

5. Entrega(Sistema em produção).
Atividades: Colaborando para qualidade dos processos de entrega, monitorando a aplicação em produção e monitorando execução dos scripts de testes automatizados.
Artefatos: Reporte de inconsistências.


# O que é?
Exemplos de **artefatos** parciais segundo o IEEE 829-1998

## Plano de Teste

## Caso de Teste

## MindMaps

# Exercícios
Perguntas

 10. Apenas o modelo tradicional exige que atividades de teste sejam executados?
 11. O modelo Ágil possui escopo fechado, por isso o testador tem muito tempo para produzir artefatos como caso de testes e plano de testes?
 12. No modelo tradicional, é bem comum terem atrasos nas fases finais do projeto, impactando diretamente as atividades de teste?
 13. A mentalidade de quem testa no modelo tradicional é voltada a testar as aplicações baseando-se nas documentações e requisitos fornecidos por fases anteriores?
 14. O reporte de inconsistências é um documento utilizado no modelo Tradicional e Ágil?
 15. Não é necessário utilizar mindmaps no modelo Ágil, visto que o foco não é produzir documentação adicional.
 16. No modelo Ágil é bem comum vermos testadores e desenvolvedores atuando juntos na descoberta de o que testar?

<hr> 
Respostas

 10. Falso, em ambos modelos devem ser executados as atividades de teste, o que difere mais nos modelos é a necessidade de fazer artefatos.
 11. Falso, no modelo ágil tem escopo aberto além do testador participar ativamente de todas as ações da equipe, por isso tem pouco tempo para construir tais artefatos.
 12. Verdadeiro, as fases anteriores a fase de teste tem um tempo determinado, caso alguma fase anterior exceda o tempo estimado, ira impactar o tempo estimado para teste oque ira implicar diretamente nas atividades de teste.
 13. Verdadeiro, no modelo tradicional todas as atividades de teste baseiam se em documentações elaboradas anteriormente.
 14. Verdadeiro, independente do modelo escolhido as inconsistências devem ser reportadas de maneira assertiva e clara.
 15. Falso, os mindmaps são utilizados no modelo ágil por demonstrar maior clareza e facilidade de assimilação diferente dos artefatos que são produzidos nos modelos tradicionais.
 16. Verdadeiro, no modelo ágil o testador tende a participar ativamente de todas as ações da equipe, além do time precisa ter claramente o saber da importância dos testes executados na aplicação.

# Conclusão

-   O que eu aprendi de mais importante durante o estudo desse capítulo?
>Independente da metodologia escolhida devemos ter claramente quais etapas são executadas e estabelecer em cima dessas etapas executadas quais atividades e artefatos iremos desenvolver para garantir a qualidade de nossa aplicação. Aprendi também as principais diferenças entre a metodologia ágil e a tradicional. Além de aprender sobre a maravilhosa ferramenta Steps Recorder que me forneceu ótimas ideias para implementar na empresa.
-   O que posso usar imediatamente na empresa onde trabalho?
>São todas coisas que pretendo usar imediatamente na empresa onde trabalho que aprendi neste capitulo mas posso citar como a principal, é estabelecer estratégias das atividades e artefatos que serão desenvolvidos em cada etapa da construção da aplicação da empresa. .
-   O que eu deveria se dedicar a fixar melhor?
> O que é e como elaborar, plano de testes, casos de testes e mindmaps e aprender mais sobre a IEEE 829.
