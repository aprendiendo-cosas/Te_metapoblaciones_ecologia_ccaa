# Metapoblaciones


> + **_Tipo de material_**: <span style="display: inline-block; font-size: 12px; color: white; background-color: #029BF9; border-radius: 5px; padding: 5px; font-weight: bold;"> Teoría</span> <span style="display: inline-block; font-size: 12px; color: white; background-color: #E68532; border-radius: 5px; padding: 5px; font-weight: bold;"> Aplicación</span>
> + **_Versión_**: 2026-2027
> + **_Asignatura (grado)_**: Ecología (CCAA)
> + **_Autor_**: Curro Bonet-García (fjbonet@uco.es)
> + **Duración**: Aproximadamente 2 horas.

![portada](https://raw.githubusercontent.com/aprendiendo-cosas/Te_metapoblaciones_ecologia_ccaa/refs/tags/2026-2027/imagenes/portada.png)


<span style="color:black;font-weight:700;font-size:8px">
    https://peerj.com/articles/11925/
</span>

[TOC]



## 1. Objetivos 

En esta guía se describen dos sesiones de una hora cada una. Tiene los siguientes objetivos. 

+ Entender el concepto de metapoblación. 
+ Comprender que la idea de población que describimos en el tema inicial de la asignatura puede asemejarse al concepto de subpoblación que veremos aquí.
+ Entender que la definición de población es escalo-dependiente. A las escalas más pequeñas (de tiempo y de espacio) funciona como vimos en el tema inicial, pero a escalas superiores se asemeja al concepto de sub-especie.
+ Incorporar el concepto de migración como elemento clave para entender cómo funcionan las metapoblaciones en la naturaleza.
+ Aprender el papel que tiene el concepto de metapoblación en la gestión de especies.

Este acto docente consta de dos sesiones diferentes que se describen a continuación: "Conceptos generales sobre metapoblaciones" y "El papel de las metapoblaciones en la gestión de especies". La primera se impartió en clase. La segunda debe de ser estudiada en casa por los alumnos.



## 2. Del concepto de área de distribución de una especie al individuo: necesidad de entender la escala

En la aproximación conceptual a los sistemas ecológicos, herramientas teóricas como «población» o «metapoblación» operan como constructos metodológicos diseñados para interpretar la realidad, sin que constituyan entidades discretas directamente observables de forma aislada en el medio natural. Tradicionalmente, los modelos poblacionales cerrados parten de la asunción de que los individuos no abandonan el sistema (ausencia de migración) para aislar analíticamente procesos como la competencia intraespecífica. Sin embargo, en los sistemas biológicos reales la movilidad constituye una propiedad ubicua, ya sea mediante el desplazamiento activo de organismos adultos o a través de la dispersión pasiva de fases del ciclo biológico (como polen, semillas o esporas) en organismos sésiles.   

Para comprender esta dinámica, es preciso analizar los extremos espaciales. En el límite superior se encuentra el área de distribución de una especie, entendida como el conjunto geográfico global donde esta se manifiesta (por ejemplo, la distribución mediterránea de *Quercus ilex*). En términos teóricos abstractos, cabría denominar a dicho conjunto global como «la población» de la especie.  

En el extremo opuesto se sitúa el individuo aislado, el cual resulta insuficiente por sí mismo para constituir una población al carecer de la capacidad intrínseca de reproducción y dinámica colectiva.

Entre el individuo y el área de distribución no existe una discontinuidad neta, sino un gradiente continuo que demanda establecer una jerarquía de escala espacial. Dicha jerarquía no alude a relaciones de dominancia o poder, sino a un principio de ordenación analítica de los elementos a lo largo del espacio. Así, un encinar continuo puede albergar diversas subpoblaciones locales diferenciadas por factores edáficos o topográficos (por ejemplo, suelos profundos frente a pedregosos, o exposiciones de solana frente a umbría), las cuales presentan estructuras de edades y tasas demográficas propias, pero integradas dentro de unidades mayores. La interpretación del sistema ecológico depende intrínsecamente del nivel de resolución espacial seleccionado. Este gradiente continuo es el que nos permite definir el concepto de metapoblación.



## 3. La metapoblación y la doble regulación: local y regional

La incorporación de la heterogeneidad espacial dio lugar a la teoría de metapoblaciones, que formaliza la coexistencia de subpoblaciones discretas conectadas mediante flujo genético y dispersión. En este marco, se reconocen dos escalas simultáneas de regulación demográfica:   

1. **Regulación local:** Opera en el interior de cada parche o fragmento ocupado. Cada parche ocupado recibe el nombre de supbolación. En cada una de ellas rigen las tasas de natalidad y mortalidad, el crecimiento dependiente de la densidad y la competencia intraespecífica tradicional (dinámica local intraterritorial). Aquí se incluiría todo lo que hemos estudiado hasta ahora para las poblaciones. Dicho de otra forma, lo que antes llamábamos población ahora se llama subpoblación. 
2. **Regulación regional:** Determina la proporción global de fragmentos ocupados en el paisaje y depende de los procesos de dispersión e intercambio entre subpoblaciones (tasas de inmigración y emigración).   

A escala local, el número de individuos fluctúa por la interacción demográfica interna del parche; a escala regional, la ocupación de parches en el mosaico se rige por cuántos individuos abandonan fragmentos de origen y logran colonizar fragmentos vacíos. Un análogo ilustrativo se aprecia en la transición demográfica de un país: mientras su balance dependa casi exclusivamente del saldo vegetativo de nacimientos y defunciones, el sistema opera bajo regulación local; cuando los flujos transfronterizos de migración global pasan a dominar la dinámica de adición de individuos, el régimen demográfico adquiere un carácter eminentemente regional.   

Cada subpoblación local está sujeta a una probabilidad finita de extinción ($e$) debida a estocasticidad demográfica, ambiental o perturbaciones. Para que una metapoblación persista a largo plazo, esta tasa de extinción local debe compensarse continuamente con la colonización de parches vacíos mediante migración ($m$). En este sentido, la dispersión también exhibe una dependencia de la escala: la probabilidad de intercambio entre fragmentos decrece de manera inversa a la distancia que los separa.

 

## 4. Modelización matemática de las metapoblaciones

El modelo clásico propuesto por Richard Levins formaliza la fracción de parches ocupados ($P$) en un tiempo determinado, asumiendo parches discretos de calidad y tamaño homogéneos, e independencia entre el tamaño del fragmento y su tasa de extinción. En la ecología del paisaje moderna este supuesto se rechaza categóricamente: según la teoría insular y los modelos metapoblacionales espacialmente explícitos (e.g., Hanski), la tasa de extinción es estrictamente dependiente del área del parche debido a efectos de tamaño muestral demográfico y cuello de botella.   

La tasa de extinción regional ($E$) se define como el producto entre la probabilidad de extinción individual de un parche ($e$) y la proporción de parches ocupados ($P$):   

$$E = e \cdot P$$

Dado que $e$ se asume constante, la extinción de fragmentos aumenta linealmente conforme mayor es el número de parches con presencia de la especie. Por ejemplo, en una estancia con miles de individuos la probabilidad absoluta de registrar un deceso en un intervalo de tiempo es mayor que en una habitación con pocas personas, aun cuando la probabilidad per cápita de muerte sea idéntica.   

Por su parte, la tasa de colonización regional ($C$) depende de la probabilidad de migración ($m$), de la proporción de parches emisores de propágulos ($P$) y de la proporción de parches diana disponibles y desocupados ($1 - P$):   

$$C = m \cdot P \cdot (1 - P)$$

Esta relación genera una curva cuadrática de carácter unimodal. Cuando $P$ es reducido, la colonización se halla limitada por la escasez de propágulos disponibles; a valores muy elevados de $P$, el factor $(1 - P)$ actúa como un mecanismo limitante, reduciendo la colonización a cero cuando todos los parches ya albergan a la especie.   

La variación temporal de la ocupación se formula como el balance neto entre ambos procesos:   

$$\frac{dP}{dt} = C - E = m \cdot P \cdot (1 - P) - e \cdot P$$

El sistema converge hacia un punto de equilibrio estable ($\hat{P}$) donde $C = E$. Especies con alta capacidad de vuelo (como ciertas mariposas) presentan valores elevados de $m$, desplazando el pico de colonización a valores bajos de $P$; en contraste, organismos con capacidades limitadas de desplazamiento (como anfibios de dispersión restringida) requieren coberturas espaciales mayores de parches fuentes para alcanzar tasas análogas de recolonización.   



## 5. Aplicación de las metapoblaciones al concepto de área de distribución de una especie

La extrapolación de la teoría metapoblacional al marco territorial transforma los paradigmas de conservación biológica y la delimitación del área de distribución. Tradicionalmente, la gestión se ha enfocado en proteger exclusivamente los polígonos donde una especie presenta poblaciones consolidadas. No obstante, la dinámica descrita demuestra que un sistema metapoblacional viable requiere de forma inexorable la existencia de parches temporalmente vacíos que actúen como receptores en el ciclo dinámico de extinción-recolonización.   

Si se eliminan los fragmentos desocupados dentro de una matriz de conectividad para destinarlos a usos antrópicos (como infraestructuras o urbanizaciones), se destruye el término $(1 - P)$ funcional, colapsando la tasa regional de colonización y precipitando a la metapoblación hacia la extinción estocástica regional. Por consiguiente, el área de distribución efectiva no abarca únicamente el hábitat ocupado de manera sincrónica, sino la red integral de hábitats potenciales conectados a escala de paisaje.   



## 6. Aspectos evolutivos de las metapoblaciones

En escalas temporales prolongadas, la estructura metapoblacional actúa como un motor evolutivo clave. La reducción sostenida de la tasa de migración ($m$) debido al incremento de la distancia geográfica o la fragmentación geomorfológica disminuye el flujo genético entre grupos de subpoblaciones. Cuando el aislamiento temporal es lo suficientemente prolongado, la deriva genética y la selección disruptiva local promueven la acumulación diferencial de mutaciones en los extremos geográficos de la metapoblación.   

Este fenómeno conduce a la diferenciación subespecífica. Como se evidencia en el complejo de *Quercus ilex*, la divergencia entre la subespecie *Quercus ilex rotundifolia* (dominante en gran parte de la península ibérica) y *Quercus ilex ilex* (propia de franjas más húmedas y litorales) refleja cómo una arquitectura metapoblacional fragmentada en el tiempo da origen a variantes genéticas incipientes. La subespecie constituye, por tanto, la proyección temporal de dinámicas metapoblacionales donde las restricciones a la dispersión favorecen la divergencia evolutiva sobre el mosaico regional.   



---

Los conceptos descritos anteriormente se muestran en la siguiente presentación:

+ [Visualización en línea](https://prezi.com/view/HVNUNV6AEAildf8Wawgi/).
+ Descarga de ejecutable para verla offline. Disponible para  [Mac](https://github.com/aprendiendo-cosas/Te_metapoblaciones_ecologia_ccaa/raw/2026-2027/presentacion/teoria_metapoblaciones.zip) y para [Windows](https://github.com/aprendiendo-cosas/Te_metapoblaciones_ecologia_ccaa/raw/2026-2027/presentacion/teoria_metapoblaciones.exe).
+ [Descarga en formato pdf](https://github.com/aprendiendo-cosas/Te_metapoblaciones_ecologia_ccaa/raw/2026-2027/presentacion/teoria_metapoblaciones.pdf).
+ También se puede ver incrustada a continuación:

<iframe src="https://prezi.com/p/embed/rqjOcSAhETwmd1wOYay9/" id="iframe_container" frameborder="0" webkitallowfullscreen="" mozallowfullscreen="" allowfullscreen="" allow="autoplay; fullscreen" height="915" width="560"></iframe>


## El papel de las metapoblaciones en la gestión de especies

Esta segunda parte pretende mostrar ejemplos del uso del concepto de metaboblación en la gestión de especies. Para guiar la sesión se usa [esta](https://github.com/aprendiendo-cosas/Te_metapoblaciones_ecologia_ccaa/raw/2026-2027/presentacion/aplicaciones_metapoblaciones.pptx) presentación de diapositivas:

+ Manejo de la cabra montés ibérica en Andalucía. Esta parte la comentamos explícitamente en clase.

+ Restauración de poblaciones de anfibios en la cuenca del río Guadiamar después del accidente de Aznalcollar (año 1998). 

+ Traslocación de megafauna en África. Es un ejemplo (un poco extremo) sobre cómo los humanos gestionamos las subpoblaciones de grandes herbívoros. 





---

[Aquí](https://github.com/aprendiendo-cosas/Te_metapoblaciones_ecologia_ccaa/archive/refs/tags/2026-2027.zip) puedes descargar un archivo .zip que contiene este guión en formato html y todo el material que incluye.

---
Haz click [aquí](https://github.com/aprendiendo-cosas/Te_metapoblaciones_ecologia_ccaa/releases) para ver cómo ha cambiado este guión en los distintos cursos académicos.

---

[Aquí](https://github.com/aprendiendo-cosas/Te_metapoblaciones_ecologia_ccaa/blob/2026-2027/notas_imparticion_Te_metapoblaciones_ecologia_ccaa.md) puedes ver las notas que tomó el profesor una vez que se impartió la clase.

---

 <p xmlns:cc="http://creativecommons.org/ns#" >El contenido de este repositorio se puede utilizar bajo la siguiente licencia:  <a  href="https://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1"  target="_blank" rel="license noopener noreferrer"  style="display:inline-block;">CC BY-NC-SA 4.0<img  style="height:22px!important;margin-left:3px;vertical-align:text-bottom;"   src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"  alt=""><img  style="height:22px!important;margin-left:3px;vertical-align:text-bottom;"   src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"  alt=""><img  style="height:22px!important;margin-left:3px;vertical-align:text-bottom;"   src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1"  alt=""><img  style="height:22px!important;margin-left:3px;vertical-align:text-bottom;"   src="https://mirrors.creativecommons.org/presskit/icons/sa.svg?ref=chooser-v1"  alt=""></a></p> 

<p>Esta licencia no aplica a enlaces a artículos, libros o imágenes no originales. Estos productos tienen su licencia correspondiente.</p>
