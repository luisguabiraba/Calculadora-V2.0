# Calculadora-V2.0 🧮
Calculadora Científica em C para realizar 20 operações matemáticas. Conta com **tratamento de erros**, **histórico de operações** e uso de **estruturas de controle** como *switch, while, e if*. 
##  Como usar:
Compile o programa no terminal com o comando:
   bash
   ````gcc main.c -o calculadora -lm````
(Usa -lm é necessário para linkar a biblioteca matemática math.h.)

# Funcionalidades 💻
Operações básicas: *soma, subtração, multiplicação e divisão*

Operações científicas: *potenciação, radiciação e funções trigonométricas (seno, cosseno e tangente)*

Outras funções: *logaritmos, exponencial, porcentagem, valor absoluto, módulo e raiz cúbica*

Cálculos especiais: *fatorial, hipotenusa, delta e determinante 2x2*

Histórico de operações: *registra todas as operações realizadas durante a execução (máximo de 100 antes de precisar executar novamente)*

Validação de entradas: *impede divisões por zero e outros erros de cálculo*

# Estrutura do Código 🆒
funcoes.c → contém todas as funções matemáticas separadas da main, garantindo melhor organização.

main.c → gerencia o menu, o fluxo principal e o histórico das operações.

Uso de structs para armazenar o histórico (Operacao), com campos para tipo da operação, valores e resultado.

# Autores 👥
YAN GUTTO, LUIZ GUSTAVO, DANILO, RICARDO MISAEL GOMES e ELÍDIO DUTRA JÚNIOR.
