Termodinâmica e Ciclos de Potência para Engenharia Mecânica
1. Contexto e Objetivos
Este caderno temático foca nos fundamentos da termodinâmica clássica e sua aplicação em ciclos de geração de potência, essenciais para a Engenharia Mecânica e frequentemente cobrados em exames de alto nível, como os da Petrobras
.
Objetivos de Estudo:
Dominar as Leis da Termodinâmica: Compreender desde o equilíbrio térmico (Lei Zero) até as restrições de direção e entropia impostas pela Segunda Lei
.
Análise de Propriedades: Fixar o uso de diagramas p-v-T, diagramas de fase e o princípio dos estados equivalentes para substâncias puras
.
Eficiência de Ciclos: Analisar e calcular o desempenho de ciclos de potência a vapor (Rankine) e a gás (Brayton, Stirling), utilizando o Ciclo de Carnot como padrão de reversibilidade
.
2. Curadoria de Fontes
Para garantir a profundidade técnica, o NotebookLM foi alimentado com materiais de referência citados na bibliografia base da área
:
Apostila de Conhecimentos Específicos (Mecânica): Material focado em concursos (Ex: Estratégia Concursos), abordando de conceitos fundamentais a questões comentadas da CESGRANRIO
.
Fundamentos da Termodinâmica (Borgnakke & Sonntag): (Referência externa base) Utilizado para aprofundar em processos isentrópicos e tabelas de propriedades
.
Princípios de Termodinâmica para Engenharia (Moran & Shapiro): (Referência externa base) Fonte para as definições mais amplas de trabalho e interações com a vizinhança
.
(Sugestão: Adicionar links para repositórios de universidades como MIT OpenCourseWare ou bibliotecas digitais de instituições como a UFSC/USP para completar as 5 fontes).
3. Engenharia de Prompts e "Cicatrizes"
A interação com a IA foi refinada através de iterações estratégicas para extrair insights precisos:
Variações de Prompts Testados:
Prompt Nível 1 (Exploratório): "Resuma os ciclos de potência."
Resultado: Resumo genérico. A IA listou os nomes, mas sem os processos específicos.
Prompt Nível 2 (Técnico): "Descreva os quatro processos do ciclo de Rankine ideal e como aumentar sua eficiência."
Resultado: Resposta detalhada citando expansão isentrópica na turbina, troca isobárica no condensador e medidas como reaquecimento e regeneração
.
Prompt Nível 3 (Resolução de Problemas): "Com base na 1ª Lei, calcule o calor fornecido se a variação de energia interna é 18J e o trabalho é 75J."
Resultado: Aplicação direta da fórmula Q=ΔU+W, resultando em 93J
.
"Cicatrizes" e Troubleshooting:
Dificuldade com Notação Matemática: A IA inicialmente teve dificuldades em ler fórmulas complexas inseridas como imagens.
Solução: Foi necessário pedir para a IA "transcrever a fórmula do balanço de energia do ciclo" antes de pedir o cálculo, garantindo que ela reconhecesse W 
ciclo
​
 =Q 
sai
​
 −Q 
entra
​
  corretamente
.
Confusão entre Ciclos Aberto e Fechado: No Ciclo Brayton, a IA misturou o modelo idealizado com motores reais.
Ajuste: Refinei o prompt para "Considerando as hipóteses do ar-padrão", o que forçou a IA a focar no ciclo fechado e na transferência de calor externa
.
Unidades de Medida: A IA ocasionalmente negligenciou a conversão de Celsius para Kelvin em cálculos de eficiência de Carnot.
Ação: Implementei a instrução sistemática: "Sempre verifique se as temperaturas estão em Kelvin antes de aplicar o rendimento térmico"
.
