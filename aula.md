@TODO --> anotação de tarefa (a fazer)
@FIX --> anotação de problema para resolver

# Unidades de Medidas Absolutas

**px:** Píxel
**pt:** Pontos
**em:** Tamanho texto elemento **pai** <!--normalmente utilizado em Textos e imagens-->
**rem:** Tamanho texto elemnto **raiz**

# Unidades Relativas (propocionais)

**%:** pai
**vw:** viewport width
**vh:** viewport height

# Reset <!--mini reset-->

* {
    margin: 0;
    padding: 0;
    border: none;
    box-sizing: border-box; <!-- box-sizing: como o CSS calcula o tamanho doselementos-->
}

# Unidades que não possuem medida

<!-- Alguns valores não tem unidades de medidas -->
**line-height;**
**aspect-ratio;**
**font-weight;**

# Displays

<!--faz com que os elementos se comportem como "blocos cheios,ocupando 100% da largura disponivel do elemento pai-->
<!--Alguns elementos tem display: inline (a, img, spam)-->
**blockquote** -> display : **block** (até o fim da linha)
**q** -> display : **inline** (tamanho do conteúdo)
**section** -> display : **flex** (exibe como caixa flexivel (Flexbox)) <!--aplicado sempre ao elemento pai-->
<!-- Flexbox tem várias propriedades que trabalham junto -->
**justify-content** -> alinhamento do artigo

# Combinadores

<!-- Especificar seletores (chamar a tag), sem a necessidade de class -->
article h1{
    font-weight: 600; <!--Demi-bold (quase negrito) -->
    font-weight: 700/bold; <!--bold (negrito) -->
}
<!-- h1 descendente do article (através do espaço "article/ /h1")-->

# HEXADECIMAL

Hexadecimal (base-númerica 16) -> base númerica de 16 algarimos
0...9 A B C D E F -> #AA33FF (vermelho, verde, azul)
cores básicas: vermelho,....(depende)
cores básicas de mayteriais físicos: amarelo, azul e vermelho;
cores básicas de luzes (RGB): vermelho, verde, azul;
cores básicas de materiais/luzes (CMYK): ciano, magenta, amareo, preto.

#AA         33          FF
vermelho    verde       azul

rgb(0...255, 0...255, 0...255) -> valores vão de 0...à 255. (decimal tem que usar vírgula e espaços.Ex : rgb(170, 51, 255))
No hexadecimal #00...FF 00...FF 00...FF (no Hexadecimal não utiliza virgula e nem espaço. Ex : #AA33FF)

# Unificação de padding nas sessões

Unificamos o padding em uma só estilização;

# Overflow

definir o tamanho de height no paragrafo do article;
hidden (para esconder o texto do article);

# Criar variavel no CSS

no root-> --cor-primaria-texto: red;

no corpo-> color: var(--cor-primaria-texto).

# Class
"."

# Id
"#"

# Lógica de Programação (Ebook I)

## Algoritmo

### Descrição narrativa
Descrever passo a passo a resolução;

### Fluxograma
Ilustação do passo a passo;

### Pseudocódigo
Portugol;

@TODO
Exercício de lógica: utilize a descrição narrativa e o fluxograma para descrever o algoritmo do processo de "Fritar um ovo".
Para fluxograma: https://app.diagrams.net/
Para descrição narrativa: Bloco de notas.

## Linguagem de programação

### Baixo Nível
- Linguagens mais próximas do nivel da máquina;
- Mais complexas;
- Melhor performance

### Alto Nível
- Linguagens mais próximas do nível humano;


### Formas de execução do algoritmo
**Existem 2 formas:**
- Compilada : Ex (C# / Java) Primeiro traduz o código, para depois executar.
- Interpretada: Ex (JavaScript/Python) Executam diretamento o código.
Amabas fazem a interpretação do código para o nível da máquina.

### Tipos de linguagem
**Existem 2 tipos:**
- Estruturadas: Trabalha com apenas um arquivo, codificando o algo-ritmo linha após linha seguindo uma sequência lógica de evento;
- Orientadas a objetos: Reusabilidade de código com o objetivo de simplificar a manutenção de um programa.

## Variáveis(Const/Let)

**Possuem Tipos de dados:**
- String (Cadeia de caracteres / Texto)
- Number (Números)
- Boolean (Verdadeiro,Falso)
- Objeto;

**Identificador:**
- camelCase
- snake_case
- PascalCase


**Valor:**
- True/False;
- 'texto';
- 32;
- 21.09;
- {id: 1, nome: 'Evy', instrutor: true};

**Escopo:**
- Variável com Escopo global: Válida em toda parte do programa;
- Variável com Escopo local: Válida em determinado parte do código;

## Operadores de Atribuição

=       -> valor é atribuido à variável;
+=      -> atribui somando o novo valor;
-=      -> atribui subtraindo o novo valor;
*=      -> atribui multiplicando o novo valor;
/=      -> atribui dividindo o novo valor;

## Operadores Aritméticos

+       -> Soma
-       -> Subtração
*       -> Multiplicação
/       -> Divisão
%       -> Resto da divisão (módulo)

## Operadores de Incremento e Decremento

++      -> Incrementa 1;
--      -> Decrementa 1;
Pré incremento      -> incrementa antes da variavel;
Pós incremento      -> incrementa após a variável;

## Operadores de comparação

===      -> Igualdade; 
!=      -> Diferença;
>       -> Maior;
<       -> Menor;
<=      -> Menor ou Igual;
>=      -> Maior ou Igual;
