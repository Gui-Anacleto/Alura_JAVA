# Modulo 1: O que é JAVA?

Nessa aula introdutória já aprendemos vários assuntos fundamentais sobre Java.

Falamos sobre as principais características da linguagem Java como:

    -orientado a objetos
    -parecido com C++
    -muitas bibliotecas e grande comunidade

Além disso, aprendemos:

    -a diferença entre o código fonte e o Bytecode
    -para executar o Bytecode é preciso ter a máquina virtual java
    -o Bytecode é independente do sistema operacional
  
Vimos também os principais componentes da plataforma Java que são:

    -Java Virtual Machine (JVM)
    -linguagem Java
    -Bibliotecas Java (API)
    -Na próxima aula já vamos escrever o primeiro código Java! Vamos continuar?

# Modulo 2: Instalação e primeiro comando.

Nessa aula você escreveu o seu primeiro código Java e aprendemos:

    -qual é a diferença entre JRE e JDK
    -como compilar um código fonte Java na linha de comando (javac)
    -como executar o Bytecode na linha de comando (java)
    -um programa Java deve estar escrito dentro de uma classe (class)
    -toda instrução Java deve ser finalizada com ;
    -para abrir e fechar um bloco usaremos as chaves {}
    -um programa Java possui uma entrada que é uma função (método) main
    -para imprimir algo no console usamos a instrução System.out.println()
    
# Modulo 3: Começando com eclipse


Este capítulo apresentou:

    -O papel de um IDE e sua diferença de um editor
    -Como fazer o download do Eclipse IDE
    -Para que serve um workspace
    -O conceito de perspectiva
    -Como criar um projeto Java, inclusive classes e como executá-lo.
    -Como exibir diferentes views

# Modulo 4: Tipos e variaveis

Nesta aula iniciamos nosso aprendizado com variáveis e tipos primitivos do Java. Os tipos vistos com mais detalhe foram int (inteiro) e double (decimal). Que usamos para fazer operações aritméticas e também concatenar com texto.

Durante o capítulo falamos sobre boas práticas na hora de nomear classes e também variáveis. Iniciamos as classes com letra maiúscula e as nossas funções e variáveis com letras minúsculas. Vamos falar mais sobre isto no futuro.

Foi possível entender um pouco de type casting e como podemos passar um valor de um tipo para uma variável de outro. Para alguns casos nós não precisamos fazer nada, pois o casting é implícito e em outros precisamos deixar claro para o compilador que sabemos o que estamos fazendo, mostrando entre parênteses o tipo que queremos que seja usado.

Veja como funciona o cast implícito e explícito na tabela abaixo.

        DE/PARA	byte	short	char	int	long	float	double
        byte	----	Impl.	(char)	Impl.	Impl.	Impl.	Impl.
        short	(byte)	----	(char)	Impl.	Impl.	Impl.	Impl.
        char	(byte)	(short)	----	Impl.	Impl.	Impl.	Impl.
        int	        (byte)	(short)	(char)	----	Impl.	Impl.	Impl.
        long	(byte)	(short)	(char)	(int)	----	Impl.	Impl.
        float	(byte)	(short)	(char)	(int)	(long)	----	Impl.
        double	(byte)	(short)	(char)	(int)	(long)	(float)	----
        
Para comparar cada tipo primitivo de forma mais clara, a tabela abaixo mostra qual o tamanho de cada um.

        TIPO	TAMANHO
        boolean	1 bit
        byte	1 byte
        short	2 bytes
        char	2 bytes
        int	    4 bytes
        float	4 bytes
        long	8 bytes
        double	8 bytes
