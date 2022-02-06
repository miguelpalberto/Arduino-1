# Arduino-1
Learning how to program Arduino boards with different sensors

1.1 - Aquisição de temperatura com um sensor TMP36 e montagem amplificadora

1.2 - Controlo de um servomotor e buzzer
      Programa de modo a que o buzzer emita um som com frequência de 880 Hz e de duração de 1 segundo quando atinge os 180 graus, e emita um som com 440 Hz de frequência com a mesma duração do anterior, quando o veio do servomotor atinge os 0 graus.
    
1.3 - Sensor de distância por ultrassons
      Programa que mostra no Monitor Serial a distância de um objeto ao sensor de ultrassons HC-SR04. E faça com que um ventoinha rode a 30% da sua velocidade máxima quando é detetado um objeto a uma distância inferior a 15 cm e rode à sua velocidade máxima caso contrário.

1.4 - Controlo da cancela de um parque de estacionamento
      Programa que permita controlar a cancela de um parque de estacionamento utilizando todos os sensores e atuadores considerados no âmbito deste trabalho: dois sensores de
distância HC-SR04, o servomotor que controla a cancela, o buzzer e é também usado um LED vermelho para simular uma lâmpada. A visão global deste sistema está ilustrada na Figura 17. Na ausência de qualquer veículo, a “lâmpada” LED permanece ligada com 10% do seu brilho máximo e a cancela encontra-se fechada (servomotor na posição 5 graus). Quando um veículo se aproxima, o sensor de distância 1 deteta a sua presença (se a distância for inferior a 0.5 m) e, nesta situação, a “lâmpada” LED fica com brilho máximo e a cancela deve abrir e permanecer aberta (servomotor na posição 95 graus) durante 2 segundos. Se o veículo tiver uma altura muito elevada, a distância d devolvida pelo sensor de distância 2 será inferior a 30 cm, e a cancela deverá fechar (ou permanecer fechada). Nesta situação deve ainda ser produzido um aviso sonoro com uma frequência de 440 Hz de forma a avisar o condutor que não poderá entrar por razões de segurança.
