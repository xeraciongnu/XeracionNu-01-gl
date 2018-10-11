---
description: Laboratorio Android
---

# root ou non root? Esa é a cuestión…

![](.gitbook/assets/image%20%2849%29.png)

## root ou non root? Esa é a cuestión…

**\(parafraseando a Hamlet, -acto terceiro, escena primeira- de W. Shakespeare\)**

É de sobras coñecido que Android, o sistema operativo móbil\* máis utilizado do mundo \(desenvolvido e mantido por Google\) está baseado no kernel \(núcleo\) de GNU/Linux e, por iso, herda moitas das súas características.

\*Entendamos aquí por “móbil” calquera smartphone, tablet, wareable, IoT ou dispositivo encaixado que porte Android.

![](.gitbook/assets/image%20%2835%29.png)

fonte da imaxe: [https://pixabay.com/es/android-sistema-operativo-reinicio-2995824/](https://pixabay.com/es/android-sistema-operativo-reinicio-2995824/)

Unha desas características é o control de acceso ao sistema en base a perfís/permisos de usuario, como calquera sistema operativo Unix ou derivado \(entre outros\). Unha gran diferenza respecto dos seus irmáns maiores é que, por defecto, Android non nos ofrece a posibilidade de acceder ao sistema como administradores \( admin ou root, en linguaxe linuxero\). Unha decisión encomiada e criticada a partes iguais que condiciona claramente a maneira na que interactuamos cos nosos dispositivos.  
Google xustifica a súa decisión en base a que, como usuarios, podemos manexar perfectamente o noso dispositivo móbil\* sen ter acceso a partes importantes \(e/ou imprescindibles\) do sistema e sen a capacidade de poder modificalas.  
Permítenos instalar aplicacións e modificar a configuración básica do sistema para personalizala ao gusto do usuario \(cores, fondos, iconas, …\). Claramente unha decisión que simplifica a xestión da seguridade do dispositivo e que lle aforra ao usuario inexperto “dores de cabeza”.

![](.gitbook/assets/tablet-1442900_640.jpg)

fonte da imaxe: [https://pixabay.com/es/comprimido-pantalla-apps-android-1442900/](https://pixabay.com/es/comprimido-pantalla-apps-android-1442900/)

Esta actitude paternalista aseméllase perigosamente ao “despotismo ilustrado” tan de moda na Europa de finais do Século XVIII. “Todo para o pobo, pero sen o pobo”. É dicir, démosle o mellor sistema operativo aos usuarios pero impidamos que poidan tomar as súas propias decisións \(pola súa seguridade\). Quen mellor que Google ou o fabricante do hardware para dicirnos que é o mellor para nós?

![](.gitbook/assets/image%20%2842%29.png)

fonte da imaxe: [https://pixabay.com/es/seguridad-protecci%C3%B3n-antivirus-265130/](https://pixabay.com/es/seguridad-protecci%C3%B3n-antivirus-265130/)

Ata aquí parece que simplemente esteamos a expor problemas metafísicos sobre se é conveniente unha ou outra “filosofía de uso” dos nosos dispositivos. Pero nada máis lonxe da realidade. Cando compramos un destes equipos non estamos a adquirir o dereito de poder usalo libremente. Só temos o dereito para usalo.  
E esa diferenza é fundamental. A propia Google ou o fabricante do dispositivo poden decidir que o noso sistema operativo debe conter unha aplicación \(preinstalada e que non se pode desinstalar\) de calquera índole. Un antivirus, un xogo, unha app de control da saúde, un sistema de pago contactless, unha configuración predeterminada, …

Ao non ser root non poderemos modificar certas partes do sistema \(unha delas é o control sobre as aplicacións precargadas\) e non poderemos desinstalalas ou, por poñer outro exemplo, parar certos servizos que non sexan do noso interese. Pero non acaba aí a cousa.  
Aínda que Android permítenos \(con certo reparo\) instalar aplicacións que non proveñan da súa propia tenda de software, algunhas destas aplicacións non poderemos instalalas sen ter privilexios de administrador.  
Non hai que pensar en pretender instalar escuras aplicacións para fins escuros: sirva como exemplo uno dos mellores programas de copias de seguridade que existen. Estamos a falar de Titanium Backup.

![](.gitbook/assets/image%20%2878%29.png)

fonte da imaxe: [https://play.google.com/store/apps/details?id=com.keramidas.TitaniumBackup](https://play.google.com/store/apps/details?id=com.keramidas.TitaniumBackup)

Paradóxicamente, podemos atopalo en Google Play \(ver a ligazón da anterior imaxe\), ten máis de 10 millóns de descargas e unha puntuación de 4’6 sobre 5 \(con máis de 350.000 valoracións\) pero, loxicamente, necesita de permisos root para poder funcionar \(para poder copiar ou restaurar partes do sistema é imprescindible ter acceso de admin\).  
Volta ao despotismo ilustrado. Con todo isto non estamos a dicir que sexa conveniente que o dispositivo veña desprotexido \(rooteado\) por defecto pero si que sería recomendable que un usuario con coñecementos avanzados tivese a oportunidade de desbloquealo, de maneira oficial, para poder acceder completamente ao seu sistema.

Ollo! Non falamos de cambiar a versión do sistema operativo \(ou substituílo por outro distinto\), simplemente pretendemos dispoñer dunha conta nel \(na versión oficial que vén co equipo\) con permisos de administrador. Algo que parece trivial noutros sistemas operativos, é unha utopía en Android.

Isto significa que non podemos desbloquear o noso móbil ou tablet? Non, non significa iso. Se dispoñemos dos coñecementos técnicos suficientes poderemos desbloquealo para conseguir ser administradores \( rootearlo\).  
Cal é o problema, pois? O problema é que, se facemos iso, lanzamos unha serie de catastróficas desdichas na nosa contra… podemos perder a garantía do dispositivo \(cláusula que se me antolla, cando menos, abusiva\), perdemos as actualizacións oficiais de Android e, mesmo, hai certas aplicacións que non se poderán utilizar \(sobre todo apps de xestión de contidos, streamming de tv/vídeo, apps de pagos NFC, …\).

Ás veces compensa rootear o noso sistema, outras non. O certo é que existe unha gran cantidade de usuarios, sobre todo cun nivel avanzado de coñecementos, que se lanzan a rootear os seus dispositivos porque as vantaxes de ter control total sobre a configuración do equipo son evidentes \(instalación de terminais de comandos, posibilidade de reaxustar a configuración de parámetros de rede, desinstalar aplicacións preinstaladas non desexadas, cambiar a frecuencia do microprocesador, … as opcións son infinitas\). Iso xa é decisión de cada cal; o que si está claro é que non o facilitan.

![](.gitbook/assets/image%20%2872%29.png)

fonte da imaxe: [https://pixabay.com/es/configuraci%C3%B3n-opciones-software-265131/](https://pixabay.com/es/configuraci%C3%B3n-opciones-software-265131/)

Que como rooteamos un dispositivo Android?

Ben... esa é outra historia…

## [Seguinte artigo](o-ecosistema-de-openstreetmap.md)

