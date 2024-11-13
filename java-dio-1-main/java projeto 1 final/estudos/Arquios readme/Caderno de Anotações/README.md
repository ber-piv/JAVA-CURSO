*04/11/2014*
# Declarar variável em java 

## estrutura 

**tipo Nome bem definio = Atribuição 9opcinal em alguns casos**
   
    exemplos
    int idade = 23;
    double altura = 1.62
    Dog spike; // obserev que ela não tem valor

**booLean** = valores lógicos  (true and false)

# Métodos

## estrutura
**TipoRetorno NomeObjetivoNoInfinitivo Parametro(s)**

observação =
**sempre infinitivo**
   
    Exemplo
    int somar (int numeroUm, int numero@)
    string formatarCep (long cep)


 **todo método tem seus parametros**
**cada parametro é separado por vígula**

# indentação
**deixar o código hierrarquico, tabulado**

    facilidade = deixa ele de fácil compreensão

# packges
Organização de arquivos .java

*05/11/2024*

# java beans

 ## o que é?

 **ela é umaespécie de "conceito" que visa deixar o código apresentavel e de fácil comprensão**

## Sugestões de nomeclatura

    variável:
        Deve ser clara e objetiva;
        sempre se escreve no simgular (exceto quando se refere á coleção ou array);
        se escreve em idioma único;
    métodos:
        serão denomidados como verbos;
        1° letra minúscula e 2 em diante 1° letra maiuscula;
        infinitivo;

*06/11/2024*

# tipos e variaveis

## tipos de dados

**são dividos em tipos primitivos (não objetos e são vaores brutos) e são armazenados diretamente na pilha de memoria**

    usamos mais o int como dado primitivo e é o recmendado;
    com parte fracionária usamos mais o double e é o recomendado;
    se não informados valor ele coloca 0 omo valor
    se comecar com 0 deve ser outro tipo (não pode ser int);

**Cuidado: java é fortimente "tipado"**

**devems estar  ciente do limite de armazenamento de cada dado**

recuso : **cast** trasforma de um  tipo mais abrangente para um mais curto e específico

*07/11/2024* 

# Constantes

**São valores que em armazenado em memória não pode serem alterados**

 em java são reprensentaods pela palavra (reservada) **final** antes do tipo

    Constantes são sempre escritas em CAIXA ALTA

# operadores 

## atribuição representado por =

**definir um valorou alterar o valor de uma variável**
  
    exemplo
        int idade = 17;
        double peso = 178.8
    
## aritimétios respresentado por =, - , *, /

    exemplo
        double soma = 10.6 + 8.2;
        int divisao = 4 / 2;

se aplcado a variavis tipo texto ele fazra a concatenação de textos (juntar os textos)

    exemplo 
        String nome = "LINGUAGEM" + "JAVA";

se usado () ele resolvera o que está emtre os () primeiro 

## unário 

são aplicados com operadors numericos e ells realzam um trabalhode incrementar

**temos**

    (+) = op. un. de valor poitivo - são positivos msm sem esse operador
    (-) = op. un. de valor negativo - nega um número ou expressao
    (++) = op. un. incremento val. - incre. val. 1 unidade
    (--) = op. un. decremento val. - dec. val. 1 unidade
    (!) = op. un. lógico de neg. - nega o valor de uma expressao boleana

*13/11/2024*

# Incrementar

incrementar valores

    exemplo
        incrementar de 1 em  1
            int numero = 5;
            numero = numero + 1;
        ou
            int numero = 5;
            numero++;
                obs: deve ser colopcando antes da ipressao
                se quiser o contrário fzaer como a seguir 
                    ++ numero;

o mesmo pode ser feito para subtrair valor (decrementar) com:

    exemplo
        numero --;

isso serve para numero 1 cremeatr ou decrementar

# bolean dicas 

se colocar um **!** antes do nome da varivel no codigode impressão ela fica o valor oposto (fale ou true)

        System.out.println(!variavel);
    ou
        variavel  = !variavel;

# Ternário

é uma forma resmida para definir uma condição e escolher dentre dois valores e estara escrita em unica linha

    simbolos
        expressao condicional = ? caso condicao seja true = : caso condição seja false 
    exemplo
        int a, b;
        a = 5;
        b = 6;
        String resultado = a == b ? "verdadeiro" : "falso";
       OU
        int a, b;
        a = 6;
        b = 6;
        String resultado = a == b ? "verdadeiro" : "falso";

pde ser usar o "formato" int no lugar de string

     exemplo
        int a, b;
        a = 5;
        b = 6;
       int resultado = a == b ? 1 :0;
       OU
        int a, b;
        a = 6;
        b = 6;
        int resultado = a == b ? 1 :2;

# Relacionais 

avaliam as relacoes entre duas variaveis ou epressãoes

       tipos
            == igauldade entre 2 valores
            != uma diferente da outra
            > uma maior que a outra
            >= uma maior ou igual a outra
            < uma menor que a outra
            <= uma menor ou igual

nos auxiliam na tomadas de decioes 

nmsempre estamos falamdo de numeros, podemos verificar conteudos como por exemplo textos 

# Lógicos

permite criar expressoes logicas  maioores apartir da juncao de 2 ou mais expressoes

    tipos
        && = operador lógico de significado "E"
        || = operador logico de significado "OU"

**obs: não precis começar sempre com uma expressão boleana**