## BIPI - FRONT
Deberá crear un proyecto nuevo en Vue.js + SASS haciendo uso de los datos dentro del fichero `vehicles.json` y usando como guía de estilo las pantallas según los mockups proporcionados [Desktop](https://projects.invisionapp.com/prototype/Prueba-desktop-ck7khwo340051ey01mra7vqef) y [Mobile](https://projects.invisionapp.com/prototype/Prueba-mobile-ck7khxvl4004ofk012gmeoqpt). El proyecto tiene que incluir:

- Una vista catálogo donde se mostrarán todos los vehículos disponibles.
- Al pulsar sobre cada vehículo llevará a la vista de detalle.
- Último coche visitado. Esta vista será igual que la vista de detalle pero haciendo referencia al último vehículo que se ha visitado.

Como se puede ver en los diseños las páginas deben ser responsive.
Se tendrá en cuenta:
- Arquitectura del proyecto.
- Ajuste del desarrollo con el diseño proporcionado.
- Aplicación de store(Vuex) para la gestión del estado y su planteamiento pensando en la escalabilidad (¿Y si además del fichero tuvieramos otro origen de datos? Patrón `repository`).
- El empleo de SASS y su estructura

### EXTRA 1:
- Añadir filtro/s de vehículos en el catálogo en base a los campos que parezcan óptimos para ello

### EXTRA 2 - PARA NOTA:
- Crear una API en NODE + EXPRESSJS que devuelva los datos del fichero y haga uso de ella el front.

### EXTRA 3 - SOBRESALIENTE:
- Una vez teniendo el EXTRA 2, hacer que se conecte a una base de datos en MONGODB haciendo uso de MONGOOSE y ese sea el origen de datos de los vehículos, es decir, la base da datos deberá contener el listado de los vehículos, la api accederá a ellos y los devolverá al front.

