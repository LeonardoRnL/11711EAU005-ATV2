Aluno: Leonardo Rangel de Lima   nºmat: 11711EAU005

Atividade 1 - Sistemas Embarcados 1

Nesta atividade foi desenvolvido um programa para piscar um LED integrado no kit de desenvolvimento STM32F411, com o intuito de experenciar todo o processo de criação dos arquivos necessários para implementação do programa, além do processo de compilação para esta plataforma. Dentre os arquivos criados estão, o startup.c que prepara o sistema para a execução do programa principal, o Makefile que automatiza o processo de compilação, o main.c que contém o programa principal, e o linker que arranja todos os arquivos.

Primeiramente foi desenvolvido o arquivo de inicialização do sistema, o startup.c, nele são executadas várias tarefas que se fazem necessárias para o funcionamento da plataforma, entre eles estão a declaração e inicialização do Stack, declaração e incialização dos vetores de interrupção, assim como todo processo essencial para execução do programa principal.

Depois, criamos um arquivo que faz uso do utilitário make, especificamente o GNU make, com esse utilitário foi possível automatizar todo o processo de compilação do código. Como estamos trabalhando com a linguagem C, há grande número de parâmetros, além de que, em um projeto profissional um prorgama será composto de diversos arquivos fontes, o que tornaria o processo de compilação mais complexo e sujeito a erros.

