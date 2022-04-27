---
title: tipos de computadoras 
layout: post
post-image: https://www.google.com.mx/url?sa=i&url=https%3A%2F%2Fbuildersoft.com.mx%2Fmantenimiento-de-pc%2F&psig=AOvVaw1W3OFi7a8JyBzcdp4FuUz3&ust=1651106569217000&source=images&cd=vfe&ved=0CAkQjRxqFwoTCJjF5rOBs_cCFQAAAAAdAAAAABAD
description: This post will guide you to install WhatATheme on your Jekyll site, follow
  the easy steps to set up WhatATheme.
tags:
- how to
- setup
- theme
---

# ¿Qué es una computadora?
Un computador, computadora u ordenador es una máquina digital programable, de funcionamiento electrónico, capaz de procesar grandes cantidades de datos a grandes velocidades. Así obtiene información útil que luego presenta a un operador humano, o transmite a otros sistemas mediante redes informáticas de distinto tipo.
La computadora es la herramienta más versátil, potente y revolucionaria que el ser humano ha creado en su historia reciente. Representa el punto cumbre de la Revolución industrial, científica y tecnológica que presenció el siglo XX después de la Segunda Guerra Mundial.

Su presencia y popularización en nuestro tiempo no sólo cambió para siempre el modo de procesar la información en el mundo, sino también la manera de trabajar y concebir el trabajo, las formas de comunicarse a larga distancia, las formas de ocio, y muchas otras áreas de la vida cotidiana.

---

**Hardware.** La parte física y tangible del sistema, o sea, sus componentes eléctricos y electrónicos, que cumplen con diversas funciones fundamentales, como la realización de cálculos o la alimentación eléctrica del sistema. De algún modo equivaldría al “cuerpo” de la computadora.


###  Software  -
*Tipos de software por funcionalidad:Los tipos de software que existen se pueden clasificar en tres grandes grupos de acuerdo con las funciones que habilitan. De esta forma, hablamos de software de aplicación (dentro del cual encontramos, a su vez, el software de gestión), software de programación y software de sistema.
* Software de aplicación:Dentro de este tipo de software podemos encontrar diferentes herramientas que incluyen desde bases de cálculo, programas de empresa o de diseño. Su ámbito es muy amplio y abarca ofimática y editores de texto, programas que permiten realizar diversas funciones enfocadas hacía elámbito recreativo o laboral.
*Software de gestión:Los diferentes tipos de software de gestión se incluirían dentro de los denominados software de aplicación, como herramientas que facilitan todos los aspectos relacionados con la gestión integral de la empresa: desde contabilidad o la facturación a la gestión de la nómina o de los impuestos. Destacamos algunos ejemplos:  
Los programas de gestión contable permiten el seguimiento contable de la propia empresa o para un cliente de forma ágil y eficiente. Los más avanzados permiten integrar la contabilidad con la fiscalidad y presentar de forma directa a la Adminsitración los modelos fiscales. 
Además de facturar de forma ágil e intuitiva, el software de facturación contribuye a la gestión global del negocio. Además de un ahorro de tiempo, evitan errores manuales y permiten automatizar el proceso de facturación y mejorar la productividad.
Los software de gestión de nóminas son soluciones de gestión laboral y RRHH que pueden utilizar desde Despachos Profesionales a empresas. Entre otras funciones, permiten desde la gestión de nóminas con procesos masivos, hasta la gestión de los empleados y documentación de RRHH. 
El software fiscal, puesto que la normativa laboral y fiscal está en constante actualización, se ha convertido en uno de los elementos imprescindibles para la correcta presentación de los diferentes impuestos tanto de personas físicas (IRPF, Patrimonio, Sucesiones) como jurídicas (IVA e IS), de forma eficiente y segura.
Finalmente, los programas ERP están diseñados para agilizar las tareas y mejorar la productividad global del negocio. Esto las convierten en un pilar básico, puesto que cuentan con funcionalidades que abarcan 360° en la gestión empresarial: gestión comercial, stocks, nóminas, facturación, contabilidad, etc. 
`Ping on Messenger`<br>
`Send an Email`<br>
`Tweet on Twitter`<br>
The contact section will also include 10 different social media buttons for your audience to follow.<br>
`Facebook`, `Twitter`, `Instagram`, `LinkedIn`, `GitHub`, `YouTube`, `Reddit`, `Behance`, `Dribbble` & `Spotify`.

### El almacenamiento -
Hoy me he puesto a trabajar en una máquina virtual que compartiré en mi comunidad privada y no tenía espacio en los discos de virtualización, así que me he puesto a investigar máquina por máquina, hasta que una me está ocupando la friolera de 196GB!!! Una máquina virtual que utilizo para mi canal de YouTube secundario y que no tiene esta capacidad, es más, he iniciado la máquina y según Windows el espacio ocupado era de 51Gb casi 4 veces menos evidentemente esto es algo que hay que revisar de vez en cuando, ya que si disponemos de discos SSD para las máquinas virtuales por sus prestaciones, con el sobrecoste de estos debemos estar atentos a la optimización del almacenamiento.

En este caso el problema viene de atrás, y al abrir la carpeta donde se encuentra el disco puedo encontrar lo siguiente.
Aquí vemos dos tipos de archivos principalmente, los vhdx y los avhdx que están ahí supuestamente de cuando la máquina virtual se dedico a eso del internete de las cosillas.

Si has tenido experiencias con los avhdx sabrás que cuanto menos los toquemos mejor, ya que estos son archivos de diferenciación entre el vhdx y estados de la máquina virtual, me explico para personas humanas…

Cuando creas un punto de control o snapshot, el sistema genera uno de estos discos que será el que realmente guarda el estado de la máquina y seguirá trabajando en un vhdx, lo que pasa es que sin el avhdx el sistema no puede funcionar. Estos archivos son combinados por Hyper-V cuando eliminamos un punto de control.

Por esto reducir el espacio ocupado es delicado, si elimino los archivos avhdx podría ser (aunque no debería) que me quedará sin máquina virtual, y esta máquina lleva generaciones en la familia.
### Projects -
The Projects page will include all the projects from the **`projects.yml`** file which is present in the _data folder.<br>
Projects will be showcased in a card-list format where each card will contain
* An image related to the project
* A Project Title
* A Project Description of about 80 words

### Footer -
The footer includes
* A small about the author widget which show the same `Author Image` as mentioned in the about section of the Home page which includes `Name of the Author`, `Around 75 words about the author`.
* A more link widget which includes a link to any extra page that you've created and a `Subscribe via RSS` link.
* A Recent posts widget which will include latest 3 posts.

#### Extra Features -
WhatATheme comes pre installed with
* **HTML Compressor** - It'll compress all the pages by removing any extra space or blank lines.
* **Google Analytics** - A web analytics service offered by Google that tracks and reports website traffic. For more information [click here](https://analytics.google.com){:target="blank"}.
* **Disqus** - A worldwide blog comment hosting service for web sites and online communities that use a networked platform. For more information about Disqus [click here](https://help.disqus.com/en/articles/1717053-what-is-disqus){:target="blank"}

	##### For more information about WhatATheme [click here](https://github.com/thedevslot/WhatATheme/blob/gh-pages/README.md){:target="blank"}.

---

# Installation
### Step 1 - Setting up WhatATheme
> * Fork the [repository](https://github.com/thedevslot/WhatATheme/tree/master){:target="blankl"}
> * Go to repository settings and set Github Pages source as master.
> * Your new site should be ready at [https://username.github.io/WhatATheme/](#){:target="blank"}

### Step 2 - Making changes via **_config.yml**
> * Open _config.yml file
> * Fill the available details accordingly
> * Commit the changes
