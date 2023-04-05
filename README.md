# Pesquisa Java - PAMI
### Pedro Santos Pequini e Renan Mitsuru Nishitani Souza 2°DS
Pesquisa de PAM sobre JAVA

### Tipos de dados - Estrutura Condicional - Estrutura de Repetição - Elementos Gráficos Android Studio
## Tipos de Dados

Em Java, existem dois tipos de grupos de dados: Primitivos e Não-primitivos, que são:

### Primitivos:
1. byte;
1. short;
1. int;
1. long;
1. boolean;
1. char;
1. float; e
1. double.

### Não Primitivos:

1. classes;
1. interfaces; e
1. arrays;

## Primitivos   

Byte: tipo de dado inteiro ou negativo e precisa de 8 bits para ser implementado, seu valor máximo é 127 e o mínimo é -128.E sua maior vantagem é a economia de espaço/memória.       

Short: assim como o byte, pode ser um valor negativo ou inteiro, mas tem o dobro do tamanho byte, sendo 16 bits para sua utilização, com seu valor mínimo sendo -32.768, e seu máximo 32.767.E sua maior vantagem, assim como o byte, é a economia de memória, podendo ser utilizado em casos específicos.   

Int: é uma das variáveis mais utilizadas na linguagem Java, pois ela também pode ser negativa ou inteira, porém utiliza o dobro de bit da variável short, sendo 32 bits. Com o valor mínimo de -2.147.483.648 e o máximo de 2.147.483.647.    

Long: é uma variável circustancial, mas é utilizado em casos de consumo excessivo de memória, pois utiliza 64 bits na sua implementação.    

Booleano: é o "mais primitivo de todos", pois apenas utiliza verdadeiro e falso.   

Char: é o tipo de dados que guarda caracteres, com 16 bits único Unicode. Com seu valor mínimo de o, e seu máximo de 65.535.   

Float: é um tipo de dado de precisão simples, contendo 32 bits, que armazena valores decimais, porém utiliza menos espaço que a variável double (que também armazena dados decimais).    

Double: é um tipo de dado de dupla precisão que armazena valores decimais, mas com sua capacidade de 64 bits. A double é utilizada como padrão nos tipos de dados desta mesma espécie (decimal).  

## Não Primitivos   

Classes: uma classe em Java é a representação de uma absatração, que contém atributos e métodos, em que atributos são as características que compõem a classe, e os métodos são as tarefas e ações que a classe tem que cumprir.   

Interfaces: é utilizado para "obrigar" um grupo de classes para ter propriedades e métodos em comum para determinado contexto, podendo ser utilizade em classes com métodos diferentes. De forma mais simples, é um contrato que a classe deve ser implementado na classe de forma obrigatória.   

Array: ele é utilizado para guardar dados do mesmo tipo, de forma que seus elementos são armazenados em localizações seqênciais contínuas na sua memória.   



## Estrutura Condicional    
Estruturas Concionais são comandos utilizados quando se há um príncipio booleano, no qual uma instrução vai fazer algo se for verdadeira ou algo se for falsa.  

### If/Else  
O If e o Else é uma estrutura de condição, portanto no código será analisado uma condição e, se essa condição for verdadeira irá fazer uma instrução, caso seja falsa irá fazer outra.


## Estrutura de Repetição     
Estruturas de repetição, também conhecidas por _loop_, é um comando utilizado para executar repetidamente uma tarefa ou instrução, e na linguagem Java existem duas estruturas que são mais utilizadas, que são o _"For"_ e o _"While"_.    
### For   
O For é uma estrutura que é utilizada quando irá ser executado por um tempo e com a quantidade de vezes determinados.   
Ele tem a seguinte estrutura:   
```
for (<variável de controle>, <análise da variável de controle>, <incremento da variável de controle>) {
    // Código a ser executado
}
```   
Na utilização do For, precisamos de uma variável para contar a quantidade de repetições que deverão ser executadas, que será a variável de controle, sendo utilizada no primeiro argumento do comando. No segundo argumento, necessita definir até quando a execução deverá ser feita, que geralmente é feita com uma condição booleana. E no terceiro argumento, indicará o quanto a variável de controle irá ser modificada no final de cada execução.   
Exemplo da estrutura em funcionamento:   
```
package br.com.treinaweb;

public class Exemplo {
	
    public static void main(String[] args) {
        for (int i = 0; i <= 10; i++) {
            System.out.println(“A variável i agora vale “ + i);
        }
    }
	
}

```   
### While   
O While é parecido com o For, mas sua diferença é que deve ser utilizado em casos em que não se sabe ao certo o número de repetições que deverão ser executadas.  
Ele tem a seguinte estrutura:   
```
while (<condição>) {
    // Trecho de código a ser repetido
}

```   
Para a interrupção da execução do programa, deverá ser estabelecido um limite em condição booleana.   
Exemplo da estrutura em funcionamento:   
```
package br.com.treinaweb;

import java.util.Scanner;

public class Exemplo {
	
    public static void main(String[] args) {
        Scanner in = new Scanner(System.in);
        int numero = -1;
        while (numero != 10) { 
// enquanto a variável não for 10, o trecho de código será repetido
            System.out.println(“Digite um número: “);
            numero = in.nextInt();
            if (numero == 10) {
                System.out.println(“Você acertou!“);
            } else {
                System.out.println(“Você errou :(“);
            }
        }
    }
								   
}

```   


## Elementos Gráficos Android Studio    
























Links usados:
- https://www.javatpoint.com/pt/tipo-de-dado-em-java  
- https://pt.code-paper.com/java/examples-primitive-and-non-primitive-data-types-java
- https://www.treinaweb.com.br/blog/estruturas-condicionais-e-estruturas-de-repeticao-em-java   
- https://raullesteves.medium.com/github-como-fazer-um-readme-md-bonit%C3%A3o-c85c8f154f8   
- http://fabrica.ms.senac.br/2015/03/tipos-de-dados-em-java/#:~:text=Os%208%20tipos%20primitivos%20de,%C3%A9%20a%20economia%20de%20mem%C3%B3ria.   
- https://www.blogson.com.br/classes-objetos-atributos-e-metodos-em-java/   
- https://www.devmedia.com.br/entendendo-interfaces-em-java/25502   
- https://www.freecodecamp.org/portuguese/news/metodos-de-arrays-em-java-como-imprimir-um-array-em-java/#:~:text=Um%20array%20%C3%A9%20uma%20estrutura,ser%20invocados%20em%20um%20array.   
   


