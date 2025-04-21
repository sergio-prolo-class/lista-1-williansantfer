## Disciplina: Programação Orientada a Objetos

## Lista 1: Ambiente Java, Git e Gradle

## Alunos: Willian Ferreira dos Santos, Mônica Cancellier

### Instruções para executar as aplicações da Lista 1:

**Aplicação 1**

	Nesta aplicação, você pode imprimir no terminal uma das três formas: um triângulo retângulo, um losango ou um retângulo vazado.

    O primeiro argumento será o nome da figura. As letras devem minúsculas e sem acento.

    Se escolher o triângulo ou o losango, só será preciso de mais um argumento, um número inteiro que será a dimensão. No caso do losango, o número deve ser ímpar.

    Porém, se escolher imprimir o retângulo, será necessário adicionar mais dois argumentos (números inteiros) que serão a largura e altura da forma.

    Exemplo:

    Certifique-se de estar em lista-1-williansantfer/exercicio-1

    Após isso, no terminal, digite: gradle run --args "triangulo 5"

**Aplicação 2**

	Neste programa, é possível imprimir na tela um determinado valor de resistência, baseado em resistor de 4 faixas.

    Deve-se entrar com 4 argumentos. Todos serão cores, em letras minúsculas, sem acento e separados por um espaço. A primeira cor representa a primeira faixa do resistor, a segunda cor representa a segunda faixa do resistor e assim por diante.

    Cores disponíveis para cada faixa:

        Faixa 1 / Faixa 2: preto, marrom, vermelho, laranja, amarelo, verde, azul, violeta, cinza e branco;
        Faixa 3 (Multiplicador): preto, marrom, vermelho, laranja, amarelo, verde, azul, violeta, cinza e branco;
        Faixa 4 (Tolerância): preto, marrom, vermelho, verde, azul, violeta, cinza, ouro e prata.

    Exemplo:

    Certifique-se de estar em lista-1-williansantfer/exercicio-2

    Em seguida, no terminal, digite: gradle run --args "amarelo branco verde azul"

**Aplicação 3**

	Este aplicativo gera um tabuleiro de batalha naval, com os navios posicionados de forma aleatória.

	Para executar:

		Certifique-se de estar em lista-1-williansantfer/exercicio-3
		
		Logo após, no terminal, digite: gradle run

**Aplicação 4**

	Este programa receberá, como redirecionamento de entrada, um arquivo texto contendo um tabuleiro de batalha naval e verificará se o tabuleiro é válido.

	Para executar:

		Certifique-se de estar em lista-1-williansantfer/exercicio-4

		Depois, no terminal, digite:
        
        ```gradle run < tabuleiro.txt```