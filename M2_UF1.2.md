Instalaciones de captación y distribución de señales de radiodifusión sonora y televisión.
========================================================================

Identificación de los tipos de complementos utilizados en las instalaciones de captación y distribución de señales de radiodifusión sonora y televisión
------------------------------------------------------------------------

Para dar uniformidad y normalización existe la normativa e ICT 
(Infraestructura Común de Telecomunicación), aprobada por
[RD 346/2011](https://www.boe.es/buscar/act.php?id=BOE-A-2011-5834),
en ella está detallada el diámetro de los tubos, formas de 
distribuirlos, elementos de cabecera, captación, numero de PAUs, tomas, 
etc.

### Canalizaciones

#### Tipos de canalizaciones

En RTV se utilizan 3 tipos de canalizaciones:

- **Tubo corrugado:** Es un tubo flexible destinado a ser empotrado y la
instalación por defecto (siempre que sea posible).
- **Tubo rígido:** Para la instalación superficial.
- **Canaletas:** Para la instalación superficial. Preferido en instalaciones de oficinas, en las que no sea posible empotrar.

<p>
<img src="img/t-corrugado.png" width="30%">
<img src="img/t-rigido.png" width="30%">
<img src="img/canaleta.png" width="30%">
</p>

#### Zonas de canalización en edificios

Si nos fijamos en la siguiente imagen, podremos distinguir varias zonas

<p align="center"><img src="img/esq-gen-telecos.jpg"></p>

##### Canalización de enlace

En este caso la superior parte del RE (Registro de enlace) y llega al 
RITS (recinto de instalaciones...). Es una canalización muy expuesta al 
exterior, por lo que se prefiere tubos empotrados.

Las condiciones son:

- 4 tubos de 40mm de diámetro
- Canaletas de 6.000mm² con 4 compartimentos.

Se necesitan 4 tubos o 4 compartimentos para 1 cable de TDT, 2 de TV sat
y 1 reserva.

##### Canalización principal

Une los RITS y RITI y se distribuye en 
vertical por la vertical del edificio (normalmente por el hueco de 
escalera). Si por ejemplo se hace por tubos el reglamento indica:

<p align="center"><img src="img/tubos-can-ppal.png"></p>

##### Canalización secundaria

Une los registros de la canalización principal con los PAU (Punto Acceso 
Usuario) de cada vivienda. Por lo general está compuesta de 4 tubos:

- Cable de par o par trenzado
- Cables coaxiales de TBA (telecomunicaciones de banda ancha)
- Cables coaxiales RTV
- Cables de fibra óptica

El diámetro de los tubos dependerá de los cables a aloja y numero de
PAU que alimenten.

##### Canalización interior o de usuario

Parte del PAU y termina en las diferentes tomas (TV, Radio, teléfono).
La distribución es con tubos de 20mm (o canales).

##### Redes de canalización

Finalmente se habla de redes de canalización al conjunto de las 
canalizaciones:

- Red de alimentación: la compuesta por tos tubos que llegan hasta el
RITI o RITS.
- Red de distribución: La compuesta por las canalizaciones principales
- Red de dispersión: la compuesta por las canalizaciones secundarias
- Red interior: los tubos que discurren por un local o vivienda.


### Conductores

Para los servicios de RTV. El cableado de referencia es el cable coaxial 
de 75Ω de impedancia (la impedancia es constante ya que no depende de
la resistencia, sino de su inductancia y capacitancia).

Su estructura se compone de 4 capas:

- Nucleo central de cobre (llamado vivo)
- un primer aislante
- Una malla metálica conductora
- Una cubierta protectora también aislante.

<p align="center"><img src="img/estruct-coaxial.png"></p>

**NOTA IMPORTANTE:** Aunque el coaxial es la elección de preferencia,
se deben tener en cuenta algunas consideraciones:

- Su avería es relativamente sencilla de producirse y difícil de 
detectar.
- No se debe deformar la distancia entre malla y vivo (con bridas muy
apretadas por ejemplo).
- No empalmar los cables. Siempre un único cable sin empalmes o en caso
extremo utilizar conectores.


### Armarios

En edificios de hasta 10 viviendas se puede sustituir el RITI o RITS
de obra por un armario modular metálico con cerradura, conectado a 
tierra, con IP 55 (exteriores) e IP33 (interiores) y con ventilación.

<p align="center"><img src="img/armario-telecos.png"></p>


### Racks

Armarios o cajas, destinadas a alojar dispositivo electrónico con medida
normalizada de 10 o 19 pulgadas (donde cada pulgada son 25,4mm). De esta 
manera todos los fabricantes pueden amoldarse a esas medidas.

Cada 3 agujeros frontales fijadores se los denomina U y miden 44,45mm.

<p align="center"><img src="img/rackU.png"></p>

Suelen instalarse en el RITI, aunque también se dispone de ellos en
oficinas de cierto tamaño o instalaciones con un mínimo de complejidad.

### Complementos auxiliares

#### Registros secundarios
Son los que enlazan la canalización principal con las secundarias de
cada planta.

<p align="center"><img src="img/registros-secundarios.png"></p>

Ubicados en zonas comunitarias y con cerradura. Normalmente de 
450x450x150mm para hasta 20 viviendas por planta

<p align="center">
<img src="img/caja-registro-secundario.png" width="45%">
<img src="img/interior-registro-secundario.png" width="45%">
</p>

### Registros de enlace

Se instalan cuando la distancia entre las antenas y el RITS es grande,
suelen medir 360x360x120mm

<p align="center"><img src="img/registro-enlace.png"></p>