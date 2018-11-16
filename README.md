# APLICACIÓN: TUS FINANZAS  💳

Proyecto realizado por UX LAB.

**TABLA DE CONTENIDO**

1. Objetivos iniciales del proyecto.
2. Problemas a nivel de negocio y usuario.
3. Recomendaciones:
    * Modificaciones a realizar
    * Próximos desarrollos
    * Presupuesto de marketing
4. Prototipos
    * Landing page
    * Sketch
    * MVP de android
    * Conclusiones
5. Chatbox
6. Zeplin
7. Medium
8. Video
9. Google Drive

***

## INTRODUCCIÓN / CONTEXTO

El banco más importante del Perú nos ha encargado hacer un rediseño de su aplicación ‘Tus finanzas’, un MVP desarrollado como app para iOS (adicional a la app nativa del banco) que busca promover el ahorro en sus usuarios, incentivándolos a crear nuevas metas de ahorro a futuro.

* **MVP IOS**
![MVP IOS](https://lh3.googleusercontent.com/WyfUPurRuoXyyeZScQtdLhk063ZozToVlujoljul3TDwJW5KZy3Om_LvuB-TB9IcG2r_BCSpoXtXL-bZjIeGBFxQmL4GYEM2QXnQovq6EvixYaO_Z5-gFMvljM9jye7bVofendMteBI)

* **LANDING PAGE**
![LP](https://user-images.githubusercontent.com/34355830/46640889-2be58480-cb34-11e8-8f13-8bf6b885e4b2.jpg)

Según el Global Findex Report 2017, sólo el 43% de los peruanos mayores de 15 años tiene una cuenta bancaria, es decir, unas 10.9 millones de personas; un 34% ha hecho pagos digitales y apenas un 8% ha utilizado una entidad financiera para ahorrar.

Para iniciar, un overview de nuestro trabajo:
* **REDISEÑO UX**
![proceso rediseno github-01](https://user-images.githubusercontent.com/38727384/48632721-a2756d80-e98f-11e8-9cce-d8c25f9ad7f8.jpg)

## 1. OBJETIVOS INICIALES DEL PROYECTO

* Definir la dirección y evolución del MVP ‘Tus finanzas app’.
* Validar los user persona actuales.
* Analizar la efectividad de la publicidad en Facebook y la landing page asociada.
* Optimizar el flujo de los usuarios.

## 2. PROBLEMAS A NIVEL DE NEGOCIO Y USUARIO

### **Entendimiento del Problema**

Para conocer el problema de la aplicación Tus Finanzas nos dieron acceso a la data y documentación de su proceso de investigación, y además los resultados que generaron el MVP de la aplicación.

Para comenzar, decidimos concretar una reunión con la product manager del banco, Gabriela, para conocer un poco más el estado y las proyecciones que tienen sobre su aplicación.

**A) Problemas Nivel Negocio**

## Análisis de la data y guerrilla testing:
Lo primero que hicimos como UX Designers en nuestra fase de descubrimiento fue analizar la data que nos ofreció el banco tras 6 meses de uso de su MVP, y que, además, contaba con una landing page y una campaña activa de Facebook ADS. Así como un testing de guerrilla con 5 usuarios.

### En su funnel de conversiones encontramos que:

* Apenas un promedio de **2,39%** de las impresiones en Facebook se dirigen al **Landing Page**.
* No hay **relación efectiva (incremento)** entre el aumento de impresiones y la cantidad de visitas a la LP.
* Aún cuando aumentan las visitas a la LP **no hay aumento proporcional de visitas a la APP Store** en el tiempo.
* Sólo un **11%** en promedio de quienes visitan la App Store, **instalan la app**.
* Hay un **leve incremento en el último trimestre** , que no parece significativo.
* De los usuarios que descargan la aplicación, sólo un **10%** en promedio **se registra**, aún cuando las impresiones aumentan.
* Aún cuando hay varios picos de impresiones, **no existe un aumento proporcional de descargas en la app store**.
* Sólo un 0,003% de los usuarios que veían la publicidad en Facebook se registraban en el app

* Otros datos interesantes que resumimos en el siguiente gráfico:

![1_dhgsiujijhah17ghlmjdvg](https://user-images.githubusercontent.com/38727384/48633393-385dc800-e991-11e8-9212-5268453a2f12.jpeg)

## Entrevista con el cliente:

Para la Product owner es importante entender por qué, a pesar de la inversión realizada en las campañas de ADS, no se están obteniendo los resultados esperados.

“No sabemos si deberíamos invertir más en publicidad. Nos preocupa que no está dando los resultados que esperábamos” 
— Gabriela Segura (Product owner)

Respecto a los hallazgos obtenidos en el análisis de la data sobre el Sistema Operativo desde el cual los usuarios entran a la landing page (89% desde Android), el banco está dispuesto dar un giro y crear un nuevo MVP para Android.

“Queremos posicionarnos como un banco que piensa en sus clientes y brinda un servicio adicional: un app de ahorros que permita mejorar la cultura financiera del público jóven” 
— Gabriela Segura (Product owner).

**B) Problemas Nivel Usuario**

## Entrevistas con usuarios:
Realizamos entrevistas con 5 usuarios entre 19 y 35 años, y descubrimos que:

* Todos son usuarios de telefonía móvil y tienen al menos 1 app de banca instalado. La mayoría usa el SO Android.
* El mayor uso que dan a su dispositivo es para aplicaciones de mensajería instantánea (WhatsApp) y algunas apps de banca como Yape, que fue app la favorita para ellos en el tema financiero.

“Tengo cuentas en 3 bancos, pero me gusta el app del BCP (Yape) porque es fácil, seguro y rápido” 
— José Antonio (25 años)

* 3/5 han ahorrado al menos una vez, sin embargo todos manifiestan el deseo de aprender u optimizar su forma de ahorrar.

“ En mi plan de ahorro anoto mis gastos y consumos para revisarlo a fin de mes” 
— Diego (35 años)

##Insights

Los insights que obtuvimos están resumidos en el siguiente gráfico:
![1_pvun0tedxvwimhhmmwjdxg](https://user-images.githubusercontent.com/38727384/48633591-a86c4e00-e991-11e8-91df-0e5e33f10891.jpeg)



## 3. RECOMENDACIONES

### **Modificaciones a realizar**

> Antes de comenzar, realizamos un Benchmark e hicimos un User flow para saber de qué forma los usuarios iban a interactuar con la aplicación. Considerando que al diseñar la aplicación para dispositivos Android no todos iban a poder acceder con la huella digital, por eso, incluimos la opción de solicitar contraseña.
Con el inventario de contenidos, revisamos de qué forma iterar en cada área de la aplicación incluyendo iconos, texto más descriptivo y colores.

Según el análisis del testing al prototipo actual, propusimos las siguientes mejoras:

* **Rediseñar la Landing page**,presentando los detalles y uso de la app, considerando la instalación para los sistemas operativos habilitados.
* **Diseñar una interfaz amigable e interactiva** para que al usuario le sea más facil de utilizarlo y con las carácteristicas detalladas.
* **Diseñar la aplicación para Android**, ya que la mayoría de usuarios visitan el landing page desde ese sistema operativo.
* Se incluyó la **opción de solicitar contraseña** ya que al estar habilitada para S.O Android, no todos los usuarios cuentan con la opción de huella digital.
* Realizar un **cambio en el logo de la aplicación** para que sea más explicativo y no confundiese a los usuarios con la aplicación que ya existe del banco.
* Se agregó la **opción de cerrar sesión** por seguridad para el usuario.
* Se agregó el **menu hamburguesa** en todas las pantallas.

### **Próximos desarrollos**

Con respecto a los próximos desarrollos, se propone lo siguiente:

* **Nueva propuesta de guía de estilo** para que la aplicación sea más atractiva al usuario.
* **Rediseñar la MVP de iOS**.
* **Sistema de notificación por mensajes** para que el usuario esté al día sobre las operaciones que realice.

### **Presupuesto de marketing**

Con respecto al presupuesto de marketing, se propone lo siguiente:

* Realizar una **campaña de remarketing en Facebook ADS**, ya que la tasa de visualización es alta y para ello proponemos presentar las mejoras de la aplicación segmentando a las personas que visitaron la landing page al menos una vez desde dispositivos Android, así esto se incrementará de manera exponencial.
* Realizar la **campaña de Marketing con emails a los clientes del banco**, informandoles el re-lanzamiento de la aplicacion a la que podrán acceder, dirigiéndolos hacia el landing page.
* **Invertir en SEO (Search Engine Optimization)** para aparecer primero en el ranking de Google, sin hacer publicidad. Mejorar la configuración del sitio, colocar contenidos que detallen la app y cómo se distingue entre otra aplicaciones.

## 4. PROTOTIPOS

### **Landing Page**

[Prototipo del Landing Page](https://www.figma.com/file/BxazJo86RBZqx2d9i58KwrMc/Flok-App-Landing-Page-Freebie-by-Panoply-Store "Prototipo Landing Page")

### **Sketch**

[Prototipo en Sketch](https://drive.google.com/drive/folders/1UH6I5lgS31MfWvOzehh-CxOPjSI0_oR0?usp=sharing "Sketch")

### **Prototipo Alta Fidelidad MVP**

[Prototipo de Alta Fidelidad en Figma](https://www.figma.com/file/dcXYC6zHatZEzdBxMSpLsgbb/Android?node-id=0%3A1 "Prototipo Figma")

[Prototipo Navegable en Marvel](https://marvelapp.com/36eiffe "Prototipo Marvel")

### **Conclusiones de Iteración**

* La mayoría de usuarios desean saber que cuentas están asociadas y poder cambiarlas.

* Los usuarios no diferencian cuál es el motivo de la imagen principal en la aplicación, no les orienta que es una app de finanzas y no genera impacto al momento de la instalarla.

* Mejorar el tamaño de algunos textos y color de los botones que no logran ver y diferenciarlos.

* Modificar en la pantalla de ahorro, las secciones de cuenta a debitar, la periodicidad y el tipo de moneda ya que es una parte principal y lo desean ver primero.

* En la pantalla de gastos no logran diferenciarlo de la pantalla de movimientos ya que no encuentran ningún gráfico que los motive a observar sus gastos, aparte que lo ven innecesario ya que la misma información lo da movimientos.

![pantaias-01](https://user-images.githubusercontent.com/38727384/48636770-d190dc80-e999-11e8-8775-4029ceb5bb4f.jpg)

## 5. CHATBOX

### **Beneficios**

Un chatbox nos permite:

* Captar clientes indecisos brindándoles la respuesta que necesitan en el momento justo.
* Ofrecer atención básica sin necesidad de pagar a una persona para que cumpla ese rol.
* Brindar atención personalizada a los clientes en tiempo real, en cualquier momento del día.
* Fidelizar a los usuarios contestando sus consultas o inquietudes de forma inmediata.
* Configurar las respuestas programadas, de acuerdo a los diferentes objetivos comerciales.

### **Conclusión**

Es un punto muy importante considerar el desarrollo de un chatbox en la aplicación, ya que es de suma importancia la atención y la rapidez que brinda información al usuario para que puedan solucionar sus problemas o inquietudes ya que prefieren que sean solucionados a través de un chat más que por teléfono.

La mayoría de las veces cuando no se soluciona a tiempo un inconveniente, se va perdiendo la fidelización y va aumentando la tasa de abandono de sus cuentas de los clientes en los bancos, ya que no hay una preocupación por sus clientes, esto se dio a entender, a través de un insight realizado con nuestros usuarios. 
> " Ellos sienten y creen que cuando no se les ayuda y asesora, es por que para el banco no son más que un 20% del dinero que ellos ganan."

Es por eso que para ayudar y ser un diferenciador importante, se necesita crear confianza en los usuarios y sería de mucha utilidad contar con este servicio.

[ChatBox](https://app.botsociety.io/s/5bb6db758fc7d0c625abeffc?p=fa76ccbf0eb902a863e711236c76a12c8cbd3e9a "ChatBox")

![financial bot](https://user-images.githubusercontent.com/34355830/46649149-8810ce80-cb5d-11e8-8c92-76c5bb64e729.jpg)


## 6. ZEPLIN

[Zeplin para desarrolladores](https://zpl.io/a8Nmw36 "Zeplin")

![zeplin](https://user-images.githubusercontent.com/34355830/46651966-4dac2f00-cb67-11e8-8393-d4c24b5c069f.jpg)

## 7. MEDIUM

Post en [Medium](https://medium.com/@estefaniatelis/tus-finanzas-proceso-de-redise%C3%B1o-ux-18ff80bf3d15 "Medium") contando el proceso de investigacion de la app Tus Finanzas.

## 8. VIDEOS

* La documentación y el demo de la aplicación realizado en [Loom](https://www.useloom.com/share/ac1237ee9822430f9d671965bd67ff3d "Loom")

## 9. GOOGLE DRIVE

Toda la documentación de este proyecto se encuentra en
[Google Drive](https://drive.google.com/open?id=1W6P2BFLqbShTRRhkJ_BELuzVr-O2C_-i "Google DRive")
