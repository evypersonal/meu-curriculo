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

<!-- Especificar seletores, sem a necessidade de class -->
article h1{
    font-weight: 600; <!--Demi-bold (quase negrito) -->
    font-weight: 700/bold; <!--bold (negrito) -->
}
<!-- h1 descendente do article (através do espaço)-->