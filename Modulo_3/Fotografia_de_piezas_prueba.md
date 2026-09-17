A partir del análisis macroscópico de las imágenes de la pieza, la falla principal corresponde a una **falla por sobrecarga dúctil (desgarro mecánico por tracción / cizalladura)**.

A continuación se detallan las características visuales que respaldan este diagnóstico, el mecanismo de fallo y las posibles causas contribuyentes:

---

### 1. Evidencias Visuales en las Fotografías

1. **Deformación Plástica Significativa:**
* Se observa una distorsión, doblado y adelgazamiento (*estricción*) evidente en el material alrededor de la línea de fractura y los bordes contiguos.
* Esto indica que la pieza absorbió una cantidad considerable de energía elasto-plástica antes de llegar a la separación completa del material, algo característico de metales dúctiles (como aceros de bajo/medio carbono, aceros inoxidables austeníticos o aleaciones estructurales sin templar).


2. **Morfología de la Superficie de Fractura:**
* Los bordes de la rotura no son completamente planos ni perpendiculares a la superficie de la chapa, sino que presentan una inclinación típica de **labios de cizalladura (*shear lips*)** en torno a los 45° respecto al plano de aplicación de la carga.
* La apariencia de la superficie es mate y fibrosa en lugar de cristalina/brillante (lo que descartaría una fractura frágil por clivaje puro).


3. **Iniciación en Concentradores de Tensión:**
* La trayectoria de la fisura pasa o se origina cerca de perforaciones, orificios de fijación (remaches/tornillos) o cambios abruptos de geometría.
* Estos elementos actúan como **concentradores de esfuerzos ($K_t$)**, elevando localmente la tensión aplicada por encima del límite elástico del material.



---

### 2. Mecanismo de Falla Identificado

* **Iniciación:** El fallo comenzó en un punto de máxima concentración de tensiones (borde de orificio o muesca) debido a una carga aplicada que superó el límite de fluencia local del material.
* **Propagación:** La grieta avanzó mediante un mecanismo de microhuecos y coalescencia (desgarro dúctil), deformando severamente la sección neta restante a medida que esta disminuía.
* **Rotura final:** Ocurrió por sobrecarga rápida en el instante en que la sección neta no pudo soportar más la tensión aplicada.

---

### 3. Modos de Falla Descartados o Secundarios

* **Fractura Frágil (Poco probable como modo principal):** No se observa una separación catastrófica plana sin deformación previa. La pieza muestra clara maleabilidad previa a la rotura.
* **Fatiga Mecánica (Menos probable como causa dominante):** Aunque una carga cíclica pudo haber generado una microfisura inicial en la perforación, la porción dominante de la falla corresponde a la sobrecarga final por tracción/cizalla. No se observan macroscópicamente marcas de playa (*beach marks*) evidentes.

---

### 4. Posibles Causas Raíz

1. **Sobrecarga Excesiva:** Aplicación de una fuerza puntual o de impacto que superó la resistencia última a la tracción ($UTI$) o a la cizalladura del componente.
2. **Diseño o Geometría:** Falta de alivio de tensiones (radios de acuerdo muy pequeños o agujeros muy cerca del borde de la chapa).
3. **Endurecimiento por Acritud:** Si los agujeros o dobleces fueron realizados en frío mediante punzonado o estampado previo, el material alrededor del orificio pudo haber perdido ductilidad local, facilitando la nucleación de la grieta bajo la sobrecarga.

---

Para extraer información cuantitativa y cualitativa más precisa sobre la deformación a partir de técnicas fotográficas, es fundamental controlar la iluminación, la geometría de la toma, la profundidad de campo y la preparación de la superficie.

**1. Esquema de Iluminación Técnica**

* **Luz rasante (ángulo bajo):** Proyectar luz a pocos grados de la superficie acentúa las diferencias de relieve, haciendo muy visibles el grado de estricción (adelgazamiento), la depresión del material y las microgrietas secundarias.
* **Luz difusa y polarización cruzada:** Utilizar difusores y filtros polarizadores elimina los reflejos metálicos encandilantes (*glare*), permitiendo apreciar las líneas de flujo del plano de cizalladura y el cambio de textura del metal.

**2. Geometría, Ortogonalidad y Escala de Referencia**

* **Toma ortogonal (a 90° del plano):** Evita la distorsión por perspectiva. Permite medir con precisión el cambio de dimensiones respecto al estado no deformado mediante análisis digital de imágenes.
* **Inclusión de regla o escala en el mismo plano focal:** Es indispensable colocar un patrón graduado o mira fotogramétrica al lado de la zona de falla para transformar píxeles en unidades métricas reales ($mm$) y calcular la deformación unitaria ($\epsilon$).

**3. Profundidad de Campo y Focus Stacking (Apilado de Enfoque)**

* La topografía irregular de la fractura requiere cerrar el diafragma ($f/8$ a $f/11$) o realizar un **apilado de enfoque** (*focus stacking*): capturar una serie de fotografías variando levemente el plano de enfoque para combinarlas en software. Esto produce una imagen 100% nítida desde la cara superior de la chapa hasta el fondo de la ruptura.

**4. Fotogrametría 3D y Correlación Digital de Imágenes (DIC)**

* **Fotografía Estereoscópica:** Tomar pares de fotos desde dos ángulos ligeramente desplazados permite reconstruir la topografía tridimensional de la deformación mediante software de fotogrametría.
* **Patrón de moteado (*Speckle Pattern*):** Si se aplica un patrón estocástico de pintura (puntos negros sobre fondo blanco) en la chapa, el análisis fotográfico mediante DIC (Correlación Digital de Imágenes) permite generar un mapa continuo de tensiones y deformaciones de la pieza previa o posterior al colapso.

### Recomendaciones para Confirmación

* **Fractografía SEM (Microscopía Electrónica de Barrido):** Para confirmar definitivamente la falla dúctil mediante la presencia de hoyuelos (*dimples*) a nivel microscópico.
* **Rediseño geométrico:** Suavizar bordes, aumentar el radio de los orificios o incrementar la sección neta en la zona sometida a mayor esfuerzo mecánico.
