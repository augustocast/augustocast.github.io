---
layout: post
title: "El 'Meat Proxy'. ¿Por qué copiar y pegar respuestas de la IA te está haciendo peor profesional?"
author: "Augusto"
date: 2026-08-20 00:52:27 -0300
tags: [ai, coding, learning, llm]
description: "Qué tareas no es conveniente delegar?"
sticky: true
translation_url: /en/2026-08-20-meat-proxy/
---


Tuve un problema de credenciales, con la cuenta de mail que uso para desarrollar para un cliente. Cargué un ticket al agente de soporte y me respondió una IA. La respuesta no me ayudó a resolver el problema por lo que escalé el ticket, al supervisor *humano* del agente. Me contestó rápido y, muy amablemente, me sugirió algunos pasos para resolver mi problema: un copy-paste de lo que me respondió la IA en el primer ticket. Perdí dos días. Algo está mal con esto, y [este](https://gruhn.me/blog/2026-08-03/) post de Niklas Gruhn me ayudó a pensarlo.

El argumento central de Gruhn es que responder a una pregunta con "El chat dijo: ..." no agrega valor. Llama al individuo que implementa eso un "Meat Proxy". O sea, una extensión que reproduce lo que dice el chat. Lo interesante acá es que este comportamiento no solo no agrega valor, porque uno podría ir directamente a preguntarle al chat, sino que es incluso peor que el chat, porque no se le puede repreguntar.

Todos caemos en esta tentación y delegarle las respuestas a un LLM está siempre al alcance de la mano. En muchos casos, sirve como un acelerador y potenciador de nuestro trabajo pero a veces tiene costos encubiertos. ¿Qué costos esconde y por qué hay tareas que es mejor no delegar?
## Pan para hoy, hambre para mañana
Desde el punto de vista del desarrollador, recibir una consulta, preguntarle la respuesta a un LLM y responder con copy-paste se siente tentador. Pareciera que uno hace [trampa](https://cenital.com/usar-ia-se-siente-como-hacer-trampa/), y tiene en segundos lo que debería tardar un buen rato. Los costos ocultos: desperdiciar una oportunidad para aprender, ser menos valioso en el futuro y volverse reemplazable. 

Uno no puede saber todo (y le puede preguntar al chat lo que no sabe), pero sí puede aprender a saber lo que sabe, lo que no, a quién, cuándo y cómo preguntar. Es decir, tener (buen) criterio. Gran parte de ser un buen desarrollador de software no está asociado a escribir buen código sino a *entregar valor con criterio*. Y el buen criterio se gana con experiencia, enfrentándose a situaciones difíciles y aprendiendo de ellas. Un desarrollador con criterio vale más que uno que no lo tiene, por lo cual hacer outsourcing de las tareas que ayudan a formar criterio pareciera ser una mala inversión. 
## Dificultad deseable
¿Cómo se forja un buen criterio? No hay atajos ni recetas mágicas, o por lo menos yo no las conozco. La industria funciona muy parecido a un [taller medieval](https://smarthistory.org/workshop-northern-europe/).  
De forma muy simplificada, existen:
1. desarrolladores Senior, que "saben" resolver problemas, porque ya resolvieron muchos problemas.  
2. desarrolladores Junior que quieren aprender a resolver problemas, para ser Senior. 

 Al Junior le lleva más tiempo que al Senior resolver los problemas, y tiene menos autonomía. En un proceso de mentoría, el Senior guía al Junior para que resuelva el problema, aunque le lleve más tiempo que a él, delegando parte de sus tareas, y mostrándole cómo las realiza. Si uno usa el "modo fácil" y delega la capacidad de filtrar, jerarquizar y comunicar, puede resolver tareas pero no aprender a resolver problemas.
 
Esto puede verse como un quick-win pero, a la larga, es una [mala decisión](https://en.wikipedia.org/wiki/Hyperbolic_discounting). Enfrentarnos a procesos costosos y tener que [esforzarnos](https://en.wikipedia.org/wiki/Desirable_difficulty) es clave en el proceso de aprendizaje. Si hacés literalmente lo mismo que el ChatGPT podrías ser literalmente reemplazado por el ChatGPT. Y, lamentablemente, el criterio no es algo que se aprende una vez y dura para siempre. Se oxida, por lo que hay que ejercitarlo.
## Delegá la ejecución, no el juicio
Responder un mensaje de trabajo tiene dos aristas: por un lado, cumplir con la tarea en sí. Por otro, el trabajo que uno debe hacer para sintetizar, jerarquizar, priorizar y darnos cuenta de que lo que estamos diciendo no es una estupidez.

Delegá la ejecución, pero no delegues el juicio. ¿Buscar la sintaxis de un `git rebase`? Ejecución: delegá. ¿Decidir si el bug se arregla ahora o se documenta? Juicio: no lo delegues.
Y hay un costo que se paga hoy, no en el futuro: los LLM generan mucho texto, chato y sin jerarquía. Un mensaje así es más costoso de leer que uno pensado, priorizado y escrito por una persona. Cada vez que delegás la síntesis, no ahorrás trabajo: se lo pasás al que te lee. Y tus compañeros lo notan, aunque nadie te lo diga. 

Por más que te lleve un poquito más de tiempo, es una buena idea pensar por vos mismo en el contenido de tus mensajes de Slack, tus tarjetas de Jira o tus reportes.

No dejes que un LLM piense por vos, o vas a terminar siendo un Meat Proxy: el supervisor que copia y pega sin criterio y le hace perder dos días de trabajo a un desarrollador.
