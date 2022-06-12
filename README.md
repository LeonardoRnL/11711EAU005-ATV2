Aluno: Leonardo Rangel de Lima   nºmat: 11711EAU005

Atividade 1 - Sistemas Embarcados 1

Na ativade anterior, foi programado um firmware que inicializa o controlador e configura o pino PC13 como saída, o qual está conectado a um LED na placa de desenvolvimento, para fazer que o LED fique piscando com um certo intervalo de tempo. Agora, na atividade presente, utilizando-se o desenvolvimento passado, foi configurado o botão KEY presente na placa, este que está conectado ao pino PA0, para que se possa alterar a frequência com que o LED fique piscando.

Para isso, primeiramente foi habilitado o clock na porta A usando o registardor AHB1ENR, depois com registradores MODER, OTYPER e PUPDR foi configurado o pino PA0 como entrada, com pull-up ligado e pull-down desligado e por fim foi utilizado o registrador IDR, que quando lido retorna o estado do pino, para assim alterar a frequência com que o LED pisca dependendo do estado do pino.
