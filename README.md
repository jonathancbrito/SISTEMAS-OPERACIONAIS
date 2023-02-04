# SISTEMAS-OPERACIONAIS
Material de Avaliação Prática - Disciplina SISTEMAS OPERACIONAIS - Engenharia de Software 10/2022
##
Nesta atividade, você é convidado a realizar uma atividade para verificar como a disciplina em questão pode contribuir na sua experiência e formação profissional. Por este motivo, nesta atividade discursiva, você é instigado a solucionar um problema voltado para sua área de formação.

Agora, vejamos o contexto apresentado abaixo:

Na unidade 2 do livro, você aprendeu como os processos são executados na CPU e como o sistema operacional faz a gerência deles. Estes processos, ou programas em execução, devem estar integralmente ou parcialmente na memória principal (memória RAM) do computador.  Desde que exista apenas um programa de cada vez na memória RAM, não há conflitos entre os processos. Se a memória RAM do computador for grande o suficiente para armazenar todos os processos, não há conflitos entre os processos. Mas na prática, o montante total de RAM demandado por todos os processos em execução ao mesmo tempo em um computador é muitas vezes bem maior do que pode ser colocado na memória. Em sistemas operacionais típicos de computador como Windows, OS X ou Linux, algo como 50-100 processos ou mais podem ser iniciados tão logo o computador for ligado.

Por exemplo, quando uma aplicação do Windows é instalada, ela muitas vezes emite comandos de tal forma que em inicializações subsequentes do sistema, um processo será iniciado somente para conferir se existem atualizações para as aplicações. Um processo desses pode facilmente ocupar 5-10 MB de memória. Outros processos de segundo plano conferem se há e-mails, conexões de rede chegando e muitas outras coisas. E tudo isso antes de o primeiro programa do usuário ter sido iniciado.

Programas de aplicação do usuário, como o Photoshop, podem facilmente exigir 500 MB apenas para serem inicializados e muitos gigabytes assim que começam a processar dados. Em consequência, manter todos os processos na memória o tempo inteiro exige um montante enorme de memória e é algo que não pode ser feito se ela for insuficiente. Duas abordagens gerais para lidar com a sobrecarga de memória foram desenvolvidas ao longo dos anos: swapping (troca de processos) e memória virtual.  (Tannembaum, 2016. adaptado, p130)
 

TANENBAUM, A. S. Sistemas Operacionais Modernos. 4ª edição. [S.l.]: Pearson Education do Brasil, 2016.
 
Tendo por base o texto acima, explique:
 
1. As duas principais técnicas para tratar a sobrecarga de memória.
2. Explique com suas palavras, porque a técnica de swapping é menos usada da que a técnica de memória virtual.
3. Explique sobre as duas implementações possíveis para a memória virtual, destacando a sua principal diferença.
