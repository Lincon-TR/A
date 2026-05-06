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
6. Agora é possivel verificar se a matriz foi corretamente carregada com "print", utilizar o algoritmo de Prim para a TSP aproximada com o "Execute TSP Aproximated", utilizar o algoritmo de força bruta com "Execute TSP Brute Force", ou sair da execução com "Exit Program"

# Resultados
# tsp1_253.txt
<img width="1022" height="954" alt="image" src="https://github.com/user-attachments/assets/ffabd736-70e2-4074-b4cd-14d91af7df83" />
O resultado do algoritmo de Prim chegou a um custo de 281, o que é um resultado excelente que está extremamente próximo do resultado ideal de 253 que levou 5 segundos para rodar em meu computador, apresentando um valor aproximadamente 0,90 em relação ao resultado ideal de 1

# tsp2_1248.txt
<img width="620" height="841" alt="image" src="https://github.com/user-attachments/assets/c351a21d-42e2-4926-bf0c-a00a2b68a8df" />
O custo dessa vez foi de 1272 do algoritmo de Prim que comparado a solução ideal de 1248 apresenta uma grande aproximação comparado ao teste anterior mas que ainda não explora tanto a capacidade total dos algoritmos aproximativos visto que a solução força bruta foi solucionada quase que instantaneamente

# data/tsp3_1194.txt
<img width="1416" height="961" alt="image" src="https://github.com/user-attachments/assets/9f4f72fa-d198-4296-b67a-3eee86c63fe0" />
Aqui é onde começamos a ver o verdadeiro potencial dos algoritmos aproximativos, o resultado aproximado chegou a 1519, o que é aproximadamente 0,80 do ideal de 1194 
No entanto o algoritmo de força bruta não conseguiu nem mesmo executar a tempo consideravel, considerado a mesma máquina e a matriz tsp1_253 que é uma matriz 11x11 que levou 5 segundos de execução, de maneira simples descobrimos que o tempo necessário para a execução é cerca de (15! / 11!
