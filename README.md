#  Danika

Bienvenido a **Danika**, un gestor y creador de modificaciones visuales y sonoras para Dota 2 construido completamente desde cero. 

El objetivo de este proyecto es darte el control total sobre la apariencia de tus héroes, efectos de habilidades, mapas, interfaces, disparos y música dentro del juego, todo desde una interfaz moderna, rápida y sin complicaciones técnicas.

---

##  ¿Cómo se instala y usa?

**No necesitas instalar Python, ni librerías, ni compilar código.**

El programa ya viene completamente **precompilado y optimizado con Nuitka** en un archivo ejecutable nativo de alto rendimiento:

1. Ve a la pestaña de **Releases** en este repositorio de GitHub.
2. Descarga la última versión empaquetada.
3. Descomprime la carpeta en el lugar que prefieras de tu PC.
4. Ejecuta `Danika.exe` y listo. El asistente de inicio te guiará en los primeros pasos.

---

##  ¿Qué puedes hacer con Danika?

* **Gestión Inteligente de Mods en Segundos:** Danika divide las modificaciones en paquetes separados (`pak01` para scripts, `pak02` para héroes y `pak03` para mundo). De esta forma, si solo cambias un ítem, el programa no reconstruye todo el juego, sino únicamente la parte que tocaste en milisegundos.
* **Mods Oficiales y Desbloqueo Visual:** Explora la base de datos completa de ítems de Dota 2, viste a tus héroes con sets completos, arcanas o personas, y aplícalos al juego con un solo clic.
* **Inyector y Editor de Partículas:** ¿Quieres el efecto de una arcana o de un courier en un arma común? Puedes extraer, aislar y transferir partículas y efectos ambientales entre ítems fácilmente.
* **Modificador de Disparos (Proyectiles):** Cambia el ataque básico a distancia de tus héroes por efectos de eventos, estelas personalizadas o proyectiles exclusivos con compilación automática.
* **Creador de Combinaciones:** Mezcla piezas de diferentes skins en un solo slot para crear combinaciones únicas que no existen en el juego base.
* **Locutora y Music Packs:** Crea tus propios paquetes de música o locutores de racha. Incluye un reproductor doble para preescuchar antes de reemplazar, ecualización y nivelación automática de volumen al 159%.
* **Recreador de Arcanas y Modo Avanzado:** Automatización que conecta con *Dota 2 Workshop Tools* y *Blender* para fusionar mallas 3D, corregir esqueletos `.dmx` y transferir secuencias de animación sin romper el modelo en el juego.
* **Seguridad y Firmas Valve:** El programa calcula y digitaliza automáticamente los hashes `SHA1` y `CRC32` en el archivo de firmas de Dota 2, evitando que el juego detecte los archivos como dañados o corruptos.

---

##  Puntos Fuertes

* **Todo en uno:** Ya no necesitas 5 herramientas distintas (un visor VPK, un decompilador, editores de texto y compiladores por consola); Danika reúne todo el flujo de trabajo en una sola aplicación.
* **Rendimiento Ultrarrápido:** Procesamiento paralelo en varios hilos de CPU para copiar, extraer imágenes y compilar paquetes VPK a máxima velocidad.
* **Cero configuración tediosa:** Detecta automáticamente tu ruta de Steam y Dota 2. No requiere modificar archivos del sistema a mano.
* **Interfaz Personalizable:** Incluye temas visuales modernos (Danika, Diamante, Jade, Dorada, Melisa), soporte para modo claro/oscuro y efectos fluidos pensados para el usuario.
* **Guardián de Integridad:** Cuenta con filtros activos para limpiar scripts no autorizados y evitar conflictos entre mods viejos o carpetas residuales.

---

##  Puntos a tener en cuenta (Limitaciones)

* **Uso de mods en juegos online:** Todas las modificaciones son **100% locales** (solo tú las ves en tu pantalla y no alteran mecánicas de ventaja). Sin embargo, cualquier uso de mods en juegos de Valve siempre opera bajo el criterio y las políticas futuras de la empresa.
* **Herramientas de desarrollo adicionales:** Funciones muy avanzadas como la reconstrucción de esqueletos 3D complejos o compilaciones de modelos crudos requieren tener instalado el DLC gratuito *Dota 2 Workshop Tools* desde Steam o tener *Blender* en el sistema.
* **Carga masiva:** Si decides generar disparos o paquetes de efectos para más de 50 héroes al mismo tiempo, el proceso de compilación puede tardar un par de minutos dependiendo de la potencia de tu procesador.

---

##  Créditos y Autoría

Este proyecto fue ideado, diseñado y programado desde cero.

* **Desarrollador principal:** Shordy
* **Marca / Sello:** LyCodeLife
