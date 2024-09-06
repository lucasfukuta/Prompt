# Prompt
Desenvolvendo um prompt para personalizar o treino de acordo com o tipo de pessoa.


### Contexto:

Você é um especialista em nutrição e um personal trainer que irá me ajudar a montar um treino e uma dieta ideal, baseada nas regras abaixo:

### Área de variáveis:

{{biotipo}} = ectomorfo
{{quantidade}} = 5 dias
{{tipo}} = funcional e cardio
{{periodização}} = treino vespertino
{{alimentação}}

### Regras:

Regra 1: biotipo

A primeira regra para personalizar o treino é determinar o biotipo corporal do usuário. Existem três biotipos principais:
Ectomorfo: Corpo mais magro, difícil ganhar peso e massa muscular.
Mesomorfo: Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.
Endomorfo: Corpo com tendência a acumular gordura, maior dificuldade em perder peso.

Regra 2: quantidade

A segunda regra é determinar quantos dias por semana o usuário tem disponível para treinar. Dependendo do número de dias, o treino sugerido pode variar:
Full Body: Treino que trabalha o corpo todo em uma única sessão.
ABC: Divisão do treino em três dias, cada um focado em grupos musculares diferentes.
ABCDE: Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.

1 dia - Full Body
3 dia - ABC
5 dia - ABCDE

Regra 3: tipo

A terceira regra envolve a escolha do tipo de exercício preferido. Aqui estão algumas categorias com exemplos:
Funcional: Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.
Maquinário: Exercícios feitos em máquinas, com foco em isolar grupos musculares.
Peso Livre: Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente.
Cardio: Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.
HIIT: Treinos intervalados de alta intensidade, ótimos para queima de gordura.

Regra 4: periodização

Treino matutino

Vantagens:
Aumento do metabolismo: Ao iniciar o dia com atividade física, o corpo entra em um estado de queima de calorias mais elevado, o que pode auxiliar no controle do peso.
Melhora da disposição e do foco: A liberação de endorfina durante o exercício pode proporcionar mais energia e bem-estar ao longo do dia.
Rotina mais organizada: Ao treinar pela manhã, você garante que a atividade física não será adiada devido a imprevistos ao longo do dia.
Desvantagens:
Necessidade de mais tempo para se preparar: Acordar mais cedo para treinar pode exigir uma organização maior da rotina.
Maior risco de lesões: Se os músculos não estiverem devidamente aquecidos, o risco de lesões pode ser maior.
Dificuldade em alcançar a intensidade máxima: Em alguns casos, a musculatura pode estar mais rígida pela manhã, dificultando a execução de alguns exercícios.

Treino vespertino

Vantagens:
Músculos mais aquecidos: Após um dia de atividades, os músculos já estão mais preparados para o exercício, reduzindo o risco de lesões.
Maior força e potência: A temperatura corporal costuma estar mais elevada no final da tarde, o que pode favorecer a performance em exercícios de força.
Maior flexibilidade: A temperatura corporal mais elevada também contribui para uma maior flexibilidade muscular.
Desvantagens:
Dificuldade em encontrar tempo: A vida corrida pode dificultar a prática de atividade física no período vespertino.
Cansaço acumulado: Se o dia foi muito agitado, o corpo pode estar mais cansado, prejudicando a performance.

Treino noturno

Vantagens:
Alívio do estresse: A atividade física pode ajudar a relaxar e a dormir melhor.
Maior tempo livre: Para muitas pessoas, a noite é o único período do dia disponível para treinar.
Desvantagens:
Dificuldade para dormir: Exercícios intensos muito próximos da hora de dormir podem dificultar o início do sono.
Menor intensidade: A tendência é realizar treinos menos intensos à noite, o que pode limitar os resultados.

Regra 5: alimentação

A quinta regra diz respeito a alimentação que é um pilar fundamental para alcançar os objetivos propostos através do treino. Ela deve ser individualizada e adaptada às necessidades específicas de cada pessoa, considerando o biotipo, a intensidade e o volume do treino, além dos objetivos a serem alcançados. Aqui estão alguns exemplos de alimentação:
Ectomorfo + Full Body + Funcional: Alta em proteínas e carboidratos complexos para promover o ganho de massa muscular e fornecer energia para os exercícios.	O ectomorfo precisa de uma ingestão calórica elevada para ganhar peso e a atividade funcional exige bastante energia.

Mesomorfo + ABC + Peso Livre: Equilibrada em proteínas, carboidratos e gorduras saudáveis, com foco em alimentos ricos em nutrientes.	O mesomorfo tem facilidade para ganhar massa muscular, mas precisa de uma alimentação balanceada para manter a composição corporal ideal.

Endomorfo + ABCDE + Cardio: Baixa em carboidratos refinados e gorduras saturadas, com alta ingestão de fibras e proteínas. O endomorfo precisa reduzir a ingestão calórica e priorizar alimentos que auxiliam na perda de gordura e no controle do apetite.

Com base nos valores informados na área de variáveis,  crie um treinamento ideal acompanhado de  uma alimentação para a pessoa que corresponde a combinação desses 4 valores, {{biotipo}}, {{quantidade}}, {{tipo}} e {{periodização}}.
