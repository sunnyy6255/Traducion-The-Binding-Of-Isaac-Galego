# Traducion-The-Binding-Of-Isaac-Galego

Ola, graciñas por ler isto.
Son Sunnyy, persoa que fixo este mod. De momento non teño muito feito, quizais logo esquézaseme
actualizar o README. 

==========================================
# Árbore de Directorios
==========================================

Nesta sección explico para min de dentro duns meses cando non me lembre de que carallo estou a facer
e a ti como están ordenados os ficheiros e por que.

/TTBOIG
    /content 
    {Neste outro están os elementos estáticos e gráficos, que non van en /content non sei moi ben por que.
    Entendo que se referencian cousas lóxicas e estas remplázannas}
    /resources
    {Neste directorio almacenamos ficheiros de configuracións e lóxicos, cando se abre o xogo con mods
    entendo que ten este cartafol prioridade}
    metadata.xml {información sobre o mod}
    README.md {Estás a leelo :D}

Agora mesmo en resources non hai nada, porque son tódolos elementos gráficos que non podo cambiar nun IDE,
teño que usar eu algunha ferramenta de deseño gráfico.
Pero básicamente é copiar o /resources/gfx e ver cousas de aí

20/10/26
Maldicións rematadas, 7 liñas lol
Engadido txt de rules e xmls de stages, bossportraits, minibosses, players.
O txt é polo texto que sae ao usar a carta de reglas entendo e os outros son para cando aparecen textos ao
enfrentarte un miniboss estilo: Blue baby vs Sloth ou cando entras a un piso: Basement I

22/10/26
Traducidos minibosses.xml :D
Traducidos stages, engadidos repentance(a ver si van).

Tiven que cambiar tódolos archivos porque equivoqueime de directorio ao extaer T-T
Curses traducido, traducido minibosses, traducido stages

23/10/26
Traducidos nomes do tarot normal
Traducidos nomes e descricións de tarot normal e inverso
quedan => baralla francesa, runas, cartas misceláneas, almas e pilulas
francesa, runas, cartas misceláneas e runas acabadas

25/10/26
Traducidos players quedan pilulas

26/10/26

Traducindo Playerforms: quedan Fun guy, Bookworm, Stompy. Non lles atopo tradución directa.

Quero investigar que é o ficheiro de translationsstrings e bossportraits. 
Achievements cambiará a pestana de achievements ou será gui?
fortunes e rules seguen funcionando aínda que non estivesen nos novos extraídos?: probar a borrar todos menos un e ver que pasa.
Personaxes traducidos: sempre referencias aos mesmos nomes en players.xml -> facer un índice

27/10/26 
creado o índice
playerforms: Guppy: mantense; é o nome dun becho
             Fun Guy: 
             Bob: debería mantelo?
             Bookworm: rata de biblioteca?
             Stompy: martillo pilón? pisón?
teño que traducir as pilulas -> gardar stats no índice
    vida, sorte, bágoas
    + / -, máis / menos

30/10/26
    Traducidas stats de pilulas, quedan algunhas específicas que quero atopar 
    significado específico.
    Vou aproveitar o tren e revisar o que fixen por erros.

    Falta descrición soul of the keeper


==============
# POR TRADUCIR
==============

- Achievements -> ver se é gráfico ou código
- Boss -> Bossportraits non sei que modifica, son gráficos: están en ./resources/ui
- Challenges -> Quizais sexa gráfico tamén, non o sei
- Fortunes? e Rules? non sei como funciona coa nova extracción
- Items :thousand_yard:
- pocketitems

- Descubrir que editar en UI, cando todo o texto esté rematado

======================
# ÍNDICE DE REFERENCIA
======================

Nomes de personaxes:
    - Isaac
    - Magdalena
    - Caín
    - Xudas
    - Bebé Azul
    - Eva
    - Sansón
    - Azazel
    - Lázaro
    - Edén
    - O Perdido
    - Lázaro (Lazarus2 "volto á vida")
    - Xudas escuro (Judas' shadow)
    - Lilit
    - O Tendeiro
    - Apolión
    - O Esquecido
    - A Alma (Alma de Forgotten)
    - Betania
    - Xacobo 
    - Esaú
Personaxes B son os Tainted

Nomes de estadísticas:
    - HP / Vida
    - Tears / Bágoas
    - Speed / Velocidade
    - Shot speed / Velocidade de bágoa
    - Luck / Sorte
    - Range / Rango
