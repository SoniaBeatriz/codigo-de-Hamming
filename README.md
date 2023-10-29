# codigo-de-Hamming
Implementação do código corretor de erros Hamming em uma simulação de envio com ruído gaussiano

O projeto tem como objetivo corrigir os erros em uma imagem que foi adicionada ruidos usando um código de bloco do tipo Hamming(7, 4, 3) e apresentar curvas de crescimento em que o eixo x representa a intensidade do ruído e o eixo y a razão quantidade de bits originais/quantidade de bits com erro.

O cálculo da matriz de verificação foi feita de duas formas diferentes (cada uma em um dos arquivos anexados), com o método original que é uma adição modulo 2 e com um operador lógico XOR visto que o resultado é o mesmo.
