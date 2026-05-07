# Tarefa: Algoritmo Aproximativo para TSP
# Andriei Roshild Da Silva e Lincon Thiel Retzlaff

# Passo a passo para execução
1. Abra o arquivo Algoritmo Aproximativo para TSP.slnx no Microsoft Visual Studio.
2. Compila e execute o programa
3. Essa tela aparecerá
   <img width="321" height="161" alt="image" src="https://github.com/user-attachments/assets/74bcdbcf-6bd5-4683-a3e2-22bb0e3be9ed" />
4. Carregue a TSP digitando "2"
   <img width="318" height="318" alt="image" src="https://github.com/user-attachments/assets/2bac90f1-37b5-4be4-a399-d47f51837101" />
5. Escolha o arquivo para ser carregado
   <img width="322" height="532" alt="image" src="https://github.com/user-attachments/assets/a3b8e12e-fb9b-44a2-9211-93492b5a89ad" />
6. Agora é possivel verificar se a matriz foi corretamente carregada com "print", utilizar o algoritmo para a TSP aproximada com o "Execute TSP Aproximated", utilizar o algoritmo de força bruta com "Execute TSP Brute Force", ou sair da execução com "Exit Program"

# Resultados
# tsp1_253.txt
<img width="1022" height="954" alt="image" src="https://github.com/user-attachments/assets/ffabd736-70e2-4074-b4cd-14d91af7df83" />
O resultado do algoritmo aproximativo chegou a um custo de 281, o que é um resultado excelente que está extremamente próximo do resultado ideal de 253 que levou 5 segundos para rodar em meu computador, apresentando um valor aproximadamente 1,11 vezes pior em relação ao resultado ideal de 1.

# tsp2_1248.txt
<img width="620" height="841" alt="image" src="https://github.com/user-attachments/assets/c351a21d-42e2-4926-bf0c-a00a2b68a8df" />
O custo dessa vez foi de 1272 do algoritmo aproximativo que comparado a solução ideal de 1248 apresenta uma grande aproximação comparado ao teste anterior visto que é apenas 1,02 vezes pior que o ideal, mas que ainda não explora tanto a capacidade total dos algoritmos aproximativos visto que a solução força bruta foi solucionada quase que instantaneamente.

# tsp3_1194.txt
<img width="1416" height="961" alt="image" src="https://github.com/user-attachments/assets/9f4f72fa-d198-4296-b67a-3eee86c63fe0" />
O resultado aproximado chegou a 1519, o que é aproximadamente 1,27 vezes pior que o ideal de 1194, esse exemplo apresenta uma clara limitação quando comparada aos exemplos anteriores, mostrando uma significativa diferença de aproximação.
Porém quando olhamos ao algoritmo de força bruta e considerado a mesma máquina e a matriz tsp1_253 que é uma matriz 11x11, de maneira simples descobrimos que o tempo necessário para a execução é cerca de 32.760 vezes mais (15! / 11!), portanto o tempo necessário de 5 segundos para a matriz de 11x11 se tornaria um tempo de 163.800 segundos, ou aproximadamente 45,5 horas para ser solucionado considerando que o código de força bruta não tenha otimizações. Portanto, aqui começamos a perceber o verdadeiro potencial dos algoritmos aproximativos.
No entanto com otimizações no algoritmo de força bruta, somos capazes de reduzir esse tempo para algo mais eficaz, reduzindo o tempo estimado de 45 horas para aproximadamente 9 minutos, mostrando uma melhoria de 303x em relação ao tempo estimado anteriormente.
<img width="1068" height="82" alt="image" src="https://github.com/user-attachments/assets/f8d3fbb4-901b-48ce-ae7a-773c2f5cc79f" />

# tsp4_7013.txt
<img width="1761" height="720" alt="image" src="https://github.com/user-attachments/assets/a4b65a9b-5e98-4165-b40f-702780d4cd92" />
O resultado do algoritmo aproximativo chegou a 10526 que é cerca de 1,5 vezes pior que o valor ideal de 7013, já se tornando um valor não tão próximo do ideal, mas ainda satisfazendo a ideia de se ter um valor que ainda é melhor do que duas vezes o ideal
O resultado de força bruta nesse caso já é basicamente impossível de se esperar, dado que o tempo sobe de maneira fatorial, portanto considerando essa matriz de 44x44 em relação ao que já fizemos anteriormente de 15x15 que levou 9 minutos, utilizando um algoritmo extremamente simples para calcular a divisão dos fatoriais (44! / 15!), chegamos a um valor de 2.032824e+042, se fossemos transformar isso em tempo utilizando os algoritmos anteriores como base, isso se torna uma quantidade de tempo infinitamente maior do que o tempo de existência do universo, o que torna essa aproximação de 0,67 muito bem-vinda.

# tsp5_27603.txt
<img width="1919" height="835" alt="image" src="https://github.com/user-attachments/assets/3b62fd04-6bdd-4363-a503-c7f973d52551" />
O resultado do algoritmo aproximativo chegou a 35019, sendo aproximadamente 1,27 vezes pior que o valor ideal de 27603, o que comparado ao exemplo anterior é uma aproximação muito eficiente e que apesar de ser uma matriz muito menor (29x29), ela ainda é (29! / 15!) 6.761440e+018 vezes mais demorada do que a matriz de 15x15 vista anteriormente, também sendo muito mais tempo do que a idade do universo e ainda demonstrando uma boa qualidade nos resultados, se tornando o melhor exemplo de até quando um algoritmo aproximativo consegue ter um resultado satisfatório o suficiente antes de começar a perder qualidade de maneira brusca.

# Conclusão
Foi possível perceber a real importância dos algoritmos aproximativos, que mesmo utilizando uma versão otimizada do algoritmo de força bruta, ainda foi inviável de utilizá-lo, o algoritmo se mostrou um excelente algoritmo de aproximação, mantendo uma alta qualidade até uma matriz de 29x29 e ainda sendo viável mesmo em uma matriz muito maior de 44x44, perdendo pouca qualidade apesar da diferença de tamanho.
