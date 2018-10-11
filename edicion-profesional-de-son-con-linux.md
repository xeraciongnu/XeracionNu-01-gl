---
description: Laboratorio de Música
---

# Hydrogen. Un secuenciador profesional de batería.

![](.gitbook/assets/image%20%2865%29.png)

## Hydrogen. Un secuenciador profesional de batería, multiplataforma e de licenza libre.

### Introdución: un ritmo para gobernalos a todos

Montar un grupo musical ou poñer unha base rítmica elaborada ás nosas cancións e ensaios non sempre é fácil, especialmente se non contamos cunha batería ou percusionista que nos axude coa tarefa.  
Para iso, temos as chamadas caixas de ritmos e os secuenciadores de batería, cos cales poderemos crear unha serie de patróns rítmicos con distintos sons \(por exemplo, os propios dunha batería de jazz\) que servirán de base para os nosos experimentos musicais.  
  
Con todo, o problema adoita ser o mecánico destes programas, cunha precisión tan extrema no ritmo que se perde o “factor humano”, aquilo que separa o secuenciado pola máquina do creado polo home. Como primeiro paso fronte a iso, e baixo o paraugas do software libre, chega un programa cargado de utilidade: Hydrogen.

![Logo de Hydrogen](.gitbook/assets/image%20%2829%29.png)

Hydrogen \([https://sourceforge.net/projects/hydrogen/](https://sourceforge.net/projects/hydrogen/)\) é un secuenciador de batería multiplataforma e de licenza libre desenvolvido polo programador italiano Alessandro Cominu \(aka Comix\), útil e accesible tanto pola aparente “sinxeleza” do programa como por unha contorna gráfica moi intuitiva, sendo unha ferramenta de traballo e creación tanto para percusionistas e compositores con experiencia como para aqueles máis novos na materia.

O programa baséase na creación de distintos patróns rítmicos, que serán modificados en función a diversas variables \(velocidade ou tempo, tipo de son, duración, etc...\), para ser posteriormente mesturados/producidos e enlazados uns con outros para dar lugar, finalmente, a un ficheiro de son \(. wav\). Falemos, pois, deste software.

### Achegándonos a Hydrogen: funcionamento básico

Hydrogen presenta unha interface gráfica baseado en QT, e na súa pantalla principal posúe tres xanelas fundamentais a través das cales o usuario poderá interactuar para crear os seus patróns e secuencias rítmicas: ‘ Pattern Editor’, ‘ Song Editor’ e ‘ Mixer’.  
Á marxe destas, nas que profundaremos a continuación, atoparemos unha barra de ferramentas básicas, enfocadas a reproducir o son creado e partes de este ou establecer un tempo determinado, entre outros. Con todo, interactuaremos espacialmente a través das xanelas anteriormente mencionadas.

![Arriba de todo, a barra de ferramentas. Xusto debaixo, o &apos;Song Editor&#x2019;. Abaixo &#xE1; esquerda, o &apos;Pattern Editor&apos;. Abaixo &#xE1; dereita, o &apos;Instrument Editor&apos;...](.gitbook/assets/image%20%2832%29.png)

A primeira delas, o ‘ Pattern Editor’, permítenos crear os patróns rítmicos básicos sobre os que imos traballar para dar forma ás distintas secuencias. Aquí poderemos controlar os instrumentos ou sons que formarán parte do patrón, así como a intensidade destes ou a súa aparición ao longo do propio patrón \(que admite valores de entre 1 e 32 pulsos\).  
Cada unha das notas que se aplican á secuencia poden ser introducidas mediante clicks ou a través de dispositivos MIDI. Deste xeito, a través do ‘ Pattern Editor’ entramos na primeira fase da creación da nosa secuencia rítmica, dando lugar aos elos rítmicos que, unidos, darán lugar á secuencia ou cadea. Precisamente, será co ‘Song Editor’ co que controlaremos como se enlazan estes patróns na liña do tempo. De forma intuitiva \(a través de pequenos cadrados azuis\), podemos modificar e mover no tempo os nosos patróns, ademais de crear algúns novos.  
  
Aínda que nesta xanela atoparemos outras opcións \(sen profundar especialmente nelas, animando a todos os lectores a probalo eles mesmo\), estas serán as básicas coas que poderemos controlar o noso traballo.  
  
Por último, o ‘ Mixer’. Esta é a xanela na que xorde a maxia, aquela que fai de Hydrogen un programa especial. Dividirémola en dúas seccións, sendo a primeira o mesturador como tal, aquilo co que poderemos producir e controlar con precisión o resultado sonoro de cada un dos sons, dos patróns ou da secuencia completa.  
Aquí poderemos controlar os volumes, aplicar ata catro efectos de son por sonido \(a través dunha biblioteca de complementos LADSPA [http://ladspa.org/](http://ladspa.org/)\) ou “humanizar” o son ao facer máis ou menos irregulares os pulsos rítmicos, rompendo así a precisión robótica, e facendo máis realista o resultado sonoro. Así mesmo, a segunda sección é o ‘ Instrument editor’, onde poderemos cambiar a ganancia, o ton e outras características do son \(ataque e caída, engadir un ton aleatorio, darlle unha maior resonancia,...\).  
  
Ao final, o ‘ Mixer’ serviranos para dar sentido, realismo e personalidade aos nosos pequenos experimentos rítmicos.

![... e aqu&#xED;, o &apos;Mixer&apos;.](.gitbook/assets/image%20%2821%29.png)

### Por que Hydrogen e non outro?

A pregunta é: por que Hydrogen e non calquera outro secuenciador de batería? Ben, en primeiro lugar está o feito de que é software libre, por suposto. Pero máis aló diso, Hydrogen é un programa que destaca pola súa versatilidade, en todos os sentidos.  
Apto para expertos e para novatos, para aqueles que traballen sobre sons predeterminados \(existindo a opción de descargar kits completos de batería que se axusten ás nosas necesidades\) ou aqueles que busquen o seu propio son, para aqueles que necesiten un metrónomo e para os que necesitan unha batería para as súas creacións,...  
  
Hydrogen é fácil de usar e adáptase ao que o usuario requira. Non podemos esquecer as opcións de “humanizar” o son e a de xerar un ton aleatorio para os distintos instrumentos/sons. Este apartado está especialmente coidado neste programa, e os resultados de fronte ao usuario son únicos, con infinitas posibilidades.  
Por suposto, o programa non pode substituír ao 100% a un batería humano \(tampouco temos claro que sexa iso o que queremos, non?\) e ten os seus defectos, como todo, pero desde logo é unha boa solución “en tempos de crise”. É unha máquina, si... pero unha máquina xenial. Por todo iso, e por todas esas cousas que cada un atopemos en Hydrogen... A cacharrear!

Arquivo sonoro: [https://ia801506.us.archive.org/26/items/Xeraciongnu-01/Prueba de Hydrogen.wav](https://ia801506.us.archive.org/26/items/Xeraciongnu-01/Prueba%20de%20Hydrogen.wav)

Sobre o arquivo: trátase dun son de proba, unha secuencia de catro patróns \(A, B, C e D\).  
  
O “Patrón A” repítese tres veces, sendo un ritmo base, e logo pasamos ao “Patrón B” con outros sons diferentes.  
Volvemos ao “Patrón A” ,que se repite dúas veces, e pasamos a un “Patrón C” cuxo final se "humanizou“ en exceso \(por iso o pulso soa “a destempo”\).  
Finalmente, tras pasar un par de veces polo “Patrón A”, finalizamos co “Patrón D”, que dá un peche ao noso pequeno experimento!

## [Seguinte artigo](persoas-que-difunden-a-cultura-libre-francisco-estrada.md)

