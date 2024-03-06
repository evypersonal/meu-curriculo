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

