# AutomatoFinito_Maquina-de-Lavar
Trabalho de Teoria da Computação [Linguagens Regulares] implementação de Autômato Finito Determistico (AFD)


1  INTRODUÇÃO

A Máquina de Estados Finito é formada por um conjunto de estados e conjunto de regras e transições entre cada estado. Esta técnica bastante utilizada  devido a necessidade de pouco processamento e fácil compreensão.A utilização das máquinas de estado finito foi extremamente ampla, existem muitas possibilidades de implementação de máquinas de estado finito em software: desde instruções básicas de comutação, ponteiros de função (C, C++) até implementações baseadas em "padrão de estado" orientadas a objetos.
Embora ultrapassadas em relação às técnicas modernas de inteligência artificial, como agentes inteligentes, redes neurais, algoritmos genéticos, busca heurística, etc., as máquinas de estados finitos voltaram a ser usadas em larga escala em diferentes tipos de dispositivos. Esses dispositivos não suportam IA modernos pois o mesmo consome muitos recursos da máquina: CPU, memória, gráficos, som, entre outros. 

2  MÁQUINA DE LAVAR 

Para demonstração de um autômato finito utilizaremos como exemplo a implementação de uma máquina de lavar roupas, onde existem transições de estados que refletem em determinada ação.  

Para Implementação foi utilizada linguagem de programação JAVA

3 AUTÔMATO DA MÁQUINA DE LAVAR 

1 - q0 (Moeda) - Estado inicial onde deve ser inserido uma moeda, caso não seja inserida  continua no mesmo estado (espera da moeda). Após a inserção da moeda a máquina  poderá ser ligada; 

2 - q1 (Sabão) - Após ligar, deverá ser adicionado o sabão. Caso o sabão não for adicionado o estado Q1 ficará em espera até a ação ser feita;

3 - q2 (Lavar) - Após o sabão ser adicionado a Máquina realizará a função lavar;

4 - q3 (Centrifugar) - Realizar a função de Centrifugação; 

5 - qf  (Secar) - Realizar a função de Secagem e após isso, desliga;
