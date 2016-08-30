## Microprocessadores ARM

A Arquitetura ARM foi introduzida no mercado em 1985 e concebido com base na Arquitetura RISC. Este padrão usa códigos condicionais na ramificação. Existem várias arquiteturas ARM, como Arquiteturas de 64/32 bit, arquiteturas de 32 bits (córtex) e arquiteturas de 32 bits (legados). 

ARM é o conjunto de instruções mais amplamente usado em todo o mundo. O conjunto de instruções pode ser dividida em seis grandes classes de instruções como:

* instruções de ramificação, 
* instruções de processamento de dados, 
* Instruções de carga e instrução de armazenamento, 
* instruções de co-processador 
* instruções de geração de exceção. 

Diferentes tipos de instruções de reamificação podem ser identificados utilizando o código de operação e os sinalizadores condicionais.

Existem 16 registos de uso geral chamados R0 a R15 na ISA ARM e cada um tem um tamanho de 32-bits.
 
R13 registo é chamado Stack Pointer (SP), R14 é chamado link Register (LR) e R15 é chamado Programa Counter (PC). ARM ISA apoia muitas operações aritméticas, como adição, subtração, e multiplicação. núcleos ARM tem um barramento de endereços de 32 bits, o que proporciona uma 4GB espaço de endereço linear plana. A memória é abordada em bytes e pode ser acessado como palavras duplas (8 bytes), palavras (4 bytes), ou meias palavras (2-bytes).


## Microprocessadores MIPS

MIPS foi projetado e introduzido no mercado pela MIPS Technologies em 1981. 

Esta ISA também é baseado em  conjunto de instruções RISC e tem um sistema de codificação fixa.

Registros de condição são utilizados para a ramificação e MDMX, MIPS-3D são utilizados como extensões. 

Existem três tipos de instruções MIPS e são R, I e J. Cada instrução começa com um código de operação 6 bits. Em instruções tipo R, existem três registos, um campo para elevação e montagem e um campo de função. 

Em  instruções do tipo I, há dois registros e um valor imediato de 16 bits.

Enquanto instruções tipo J siga opcode com um salto alvo de 26 bits. MIPS tem 32 registos inteiros, a fim de realizar operações aritméticas. O registo $0 prende 0 e registrar $1 é normalmente reservado para o Assembler.