# Actividad-7

 # 📌 Descripción

 Este repositorio contiene el desarrollo de la **Actividad 7**, cuyo objetivo es comprender los conceptos fundamentales relacionados con las bases de datos, los tipos de datos, el manejo de información mediante Excel, el lenguaje de programación Python y el sistema gestor de bases de datos MySQL.

 Durante la actividad se desarrollan ejercicios prácticos relacionados con:

 - Tipos de datos en bases de datos.
- Manejo de información en Excel.
- Comparación entre Excel y una base de datos.
- El concepto de "No hay sistema".
- Procesos antes y después de las computadoras.
- Filosofía y Zen de Python.
- Librerías Pandas, Polars y SciPy.
- Integración de Python con MySQL.
- Uso de MySQL en Google Colab y Visual Studio Code.
- Diseño de una base de datos.
- Requerimientos funcionales y no funcionales.

 # 🗃️ PUNTO 1 — Tipos de datos y bases de datos

 ## 1\. Tipos de datos

 Los tipos de datos permiten definir qué clase de información puede almacenarse en una columna de una base de datos.

 | Tipo | Descripción | Ejemplos |
| --- | --- | --- |
| `INT` | Números enteros | Edad, cantidad, documento |
| `VARCHAR` | Texto de longitud variable | Nombre, ciudad, correo |
| `CHAR` | Texto de longitud fija | Código, país, estado |
| `TEXT` | Texto largo | Descripción, observaciones |
| `DATE` | Fecha | Fecha de nacimiento |
| `DATETIME` | Fecha y hora | Fecha de una cita |
| `TIME` | Hora | Hora de atención |
| `DECIMAL` | Número decimal exacto | Precio, salario |
| `FLOAT` | Número decimal | Temperatura, mediciones |
| `BOOLEAN` | Verdadero o falso | Activo/inactivo |
| `BIGINT` | Entero de gran tamaño | Identificadores grandes |

### Ejemplos

 #### INT

```
Edad: 20
Cantidad: 150
Documento: 1001234567
```

 #### VARCHAR

```
Nombre: "Juan Pérez"
Ciudad: "Bogotá"
Correo: "juan@gmail.com"
```

 #### DATE

```
2004-05-20
2026-09-30
2026-10-01
```

 #### DECIMAL

```
3500000.00
2500000.50
159900.00
```

 # 💻 2. ¿Qué significa "No hay sistema"?

 Cuando escucho la frase **"No hay sistema"**, pienso en una situación en la que una organización no puede utilizar temporalmente sus sistemas informáticos.

 Esto puede generar diferentes problemas:

 - Pérdida o inaccesibilidad de información.
- Retrasos en la atención.
- Errores al registrar datos manualmente.
- Dificultad para consultar información.
- Pérdidas económicas.
- Interrupción de servicios.
- Problemas de comunicación entre áreas.

 Por ejemplo, si un banco presenta una falla en sus sistemas, los clientes podrían tener dificultades para consultar saldos, realizar transferencias o utilizar determinados servicios.

 # 🏦🏥🛒 3. Impacto en diferentes sectores

 ## 🏦 Banca

 Los bancos utilizan sistemas informáticos para administrar cuentas, transferencias, pagos, préstamos y movimientos financieros.

 Una falla puede impedir temporalmente que los usuarios realicen determinadas operaciones.

 ## 🏥 Salud

 Los hospitales utilizan sistemas para gestionar pacientes, citas, historias clínicas, medicamentos y resultados.

 Una interrupción puede provocar retrasos y obligar al personal a utilizar procesos manuales.

 ## 🛒 Comercio

 Los comercios utilizan sistemas para administrar inventarios, precios, ventas y pagos.

 Una falla puede impedir registrar correctamente las compras y actualizar el inventario.

 ### Ejemplos de situaciones

 1. Fallas en sistemas bancarios que interrumpen temporalmente servicios digitales.
2. Incidentes tecnológicos en instituciones de salud que obligan a utilizar procesos manuales.
3. Interrupciones en sistemas de ventas o pagos de establecimientos comerciales.

 # 📝 4. Antes de las computadoras

 Antes de la utilización generalizada de sistemas informáticos, muchas actividades se realizaban mediante documentos físicos.

 ### 🏦 Bancos

 Las operaciones se registraban en libros y documentos físicos. Los clientes tenían que acudir personalmente a las sucursales para realizar muchas operaciones.

 ### 🏥 Salud

 Las historias clínicas se almacenaban en carpetas físicas y las citas podían solicitarse personalmente o mediante llamadas telefónicas.

 ### 🛒 Comercio

 Los inventarios se registraban manualmente y los empleados realizaban muchos cálculos utilizando documentos y calculadoras.

 # 📊 5. Comparación

 | Proceso | Antes | Actualmente |
| --- | --- | --- |
| Banco | Libros y documentos físicos | Banca digital |
| Historia clínica | Carpetas | Sistemas digitales |
| Citas médicas | Presencial/teléfono | Aplicaciones y páginas web |
| Inventarios | Registros manuales | Sistemas digitales |
| Ventas | Caja y cálculos manuales | Sistemas POS |
| Facturación | Documentos físicos | Facturación electrónica |
| Comunicación | Cartas y llamadas | Correo y mensajería |

 # 📗 6. Tablas en Excel

 ## 🚗 Automóvil

 | Modelo | Marca |
| --- | --- |
| GR Supra | Toyota |
| Mustang GT | Ford |
| M4 | BMW |

> El Toyota GR Supra representa el automóvil que me gustaría tener.

 ## 🏥 Paciente

 > Los datos de esta tabla son ejemplos. Para la entrega final se deben reemplazar por los datos de un compañero.

 | Nombre | Edad |
| --- | --- |
| Juan Pérez | 20 |
| Laura Gómez | 22 |
| Andrés Martínez | 21 |

## 🛍️ Producto

 | Nombre | Precio |
| --- | --- |
| Computador portátil | $3.500.000 |
| Smartphone | $2.500.000 |
| Consola de videojuegos | $2.800.000 |

### Operaciones realizadas

 En Excel se deben realizar:

 - Filtrado de información.
- Ordenamiento ascendente y descendente.
- Modificación de registros.
- Eliminación de registros.

 # 📋 7. Excel vs. Base de datos

 | Excel | Base de datos |
| --- | --- |
| Hoja de cálculo | Sistema especializado |
| Fácil de utilizar | Requiere mayor conocimiento técnico |
| Adecuado para cantidades moderadas | Adecuado para grandes volúmenes |
| Utiliza fórmulas y filtros | Utiliza consultas SQL |
| Puede utilizarse individualmente | Diseñada para múltiples usuarios |
| Relaciones limitadas | Relaciones entre tablas |
| Control de datos más limitado | Mayor control de integridad |

### Reflexión

 Excel es una excelente herramienta para organizar y analizar información de manera sencilla. Sin embargo, cuando aumenta la cantidad de información y se necesitan relaciones entre diferentes conjuntos de datos, una base de datos como MySQL ofrece mayores posibilidades de organización, seguridad, integridad y consulta.

 # 🐍 PUNTO 2 — Python y Zen de Python

 ## 1\. Zen de Python

 El Zen de Python es una colección de principios que representan ideas relacionadas con el diseño y la filosofía del lenguaje Python.

 Para visualizarlo se puede ejecutar:

```
import this
```

 Algunos principios importantes son:

 - Lo bello es mejor que lo feo.
- Lo explícito es mejor que lo implícito.
- Lo simple es mejor que lo complejo.
- La legibilidad cuenta.
- Debería existir una forma clara de hacer las cosas.

 ### ⭐ Principio favorito

 El principio que más me gusta es:

 > **"Readability counts"**

 En español:

 > **"La legibilidad cuenta".**

 Elegí este principio porque considero importante que un programa no solamente funcione, sino que también sea fácil de leer y comprender.

 # 🐍 2. Ejemplo en Python

```
import this
```

 También podemos utilizar Python para trabajar con datos:

```
import pandas as pd

datos = {
    "Nombre": ["Juan", "Laura", "Andrés"],
    "Edad": [20, 22, 21],
    "Ciudad": ["Bogotá", "Medellín", "Cali"]
}

df = pd.DataFrame(datos)

print(df)

print("\nEdad promedio:")
print(df["Edad"].mean())

print("\nPersonas mayores de 20 años:")
print(df[df["Edad"] > 20])
```

 Este código permite crear un conjunto de datos, convertirlo en un `DataFrame`, calcular un promedio y filtrar información.


 # 📊 3. Librerías Python

 ## Pandas

 Pandas es una biblioteca utilizada para manipular y analizar datos.

```
import pandas as pd

datos = {
    "Producto": ["Computador", "Celular", "Tablet"],
    "Precio": [3500000, 2500000, 1500000]
}

df = pd.DataFrame(datos)

print(df)
```

 Se utiliza principalmente para:

 - Análisis de datos.
- Limpieza de información.
- Archivos CSV.
- Excel.
- Transformación de datos.

 ## ⚡ Polars

 Polars es una biblioteca para trabajar con datos tabulares de forma eficiente.

```
import polars as pl

df = pl.DataFrame({
    "Producto": ["Computador", "Celular", "Tablet"],
    "Precio": [3500000, 2500000, 1500000]
})

print(df)

resultado = df.filter(
    pl.col("Precio") > 2000000
)

print(resultado)
```

 Puede resultar especialmente útil cuando se manejan grandes cantidades de datos.

 ## 🔬 SciPy

 SciPy es una biblioteca orientada al cálculo científico y técnico.

 Puede utilizarse para:

 - Estadística.
- Optimización.
- Álgebra lineal.
- Procesamiento de señales.
- Cálculos científicos.

 Ejemplo:

```
from scipy import stats

datos = [10, 12, 15, 20, 25]

print(stats.tmean(datos))
```

 # 🗄️ 4. MySQL + Python

 MySQL es un sistema gestor de bases de datos relacionales.

 Python puede conectarse a MySQL mediante diferentes conectores.

 Instalación:

```
pip install mysql-connector-python
```

 Conexión:

```
import mysql.connector

conexion = mysql.connector.connect(
    host="localhost",
    user="root",
    password="123456",
    database="actividad7"
)

print("Conexión exitosa")

conexion.close()
```

 > Para un proyecto real, las contraseñas no deberían almacenarse directamente en el código. Se recomienda utilizar variables de entorno o un sistema de gestión de secretos.

 # 🔎 5. Consulta desde Python

```
cursor = conexion.cursor()

cursor.execute("SELECT * FROM producto")

resultados = cursor.fetchall()

for producto in resultados:
    print(producto)
```

 Python puede utilizarse para realizar las operaciones **CRUD**:

```
C → Create   → Crear
R → Read     → Consultar
U → Update   → Actualizar
D → Delete   → Eliminar
```

 # ☁️ 6. MySQL en Google Colab

 Para instalar el conector:

```
!pip install mysql-connector-python
```

 Después:

```
import mysql.connector
```

 La conexión depende de dónde esté alojado el servidor MySQL. Debido a que Google Colab ejecuta el código en un entorno remoto, un servidor MySQL instalado únicamente en el computador local no será accesible directamente mediante `localhost`.

 # 💻 7. MySQL en Visual Studio Code

 Para trabajar con MySQL y Python en Visual Studio Code se necesita:

 - Python.
- Visual Studio Code.
- Extensión de Python.
- MySQL Server.
- MySQL Connector.

 Instalación del conector:

```
pip install mysql-connector-python
```

 La ventaja de Visual Studio Code es que permite organizar el proyecto en diferentes archivos y trabajar directamente con el código fuente y los scripts SQL.

 # 📈 8. MySQL + Python: aplicaciones

 La combinación de Python y MySQL puede utilizarse en:

 - 🏥 Sistemas hospitalarios.
- 🏦 Sistemas financieros.
- 🛒 Tiendas virtuales.
- 📦 Sistemas de inventarios.
- 🎓 Plataformas educativas.
- 👥 Sistemas de usuarios.
- 📊 Análisis de datos.
- 🌐 Aplicaciones web.
- 🏢 Sistemas empresariales.

 ### Flujo básico

```
             USUARIO
                ↓
         APLICACIÓN PYTHON
                ↓
       CONECTOR MYSQL
                ↓
          BASE DE DATOS
                ↓
        INFORMACIÓN
```

 # 🗃️ PUNTO 3 — Propuesta de base de datos

 ## 🏥 Sistema de gestión de citas médicas

 Para este punto se propone desarrollar un aplicativo para administrar pacientes, médicos y citas médicas.

 El sistema permitirá registrar información, consultar datos y administrar las citas de una institución médica.

 # 👥 Usuarios

 El sistema tendrá cuatro tipos de usuarios:

 - Administrador.
- Médico.
- Paciente.
- Recepcionista.

 # 🧱 Tablas de la base de datos

 ## Tabla `paciente`

 | Campo | Tipo | Descripción |
| --- | --- | --- |
| id\_paciente | INT | Identificador |
| nombre | VARCHAR(100) | Nombre completo |
| documento | VARCHAR(20) | Documento |
| fecha\_nacimiento | DATE | Fecha de nacimiento |
| telefono | VARCHAR(20) | Teléfono |
| correo | VARCHAR(100) | Correo |
| activo | BOOLEAN | Estado |

## Tabla `medico`

 | Campo | Tipo | Descripción |
| --- | --- | --- |
| id\_medico | INT | Identificador |
| nombre | VARCHAR(100) | Nombre |
| especialidad | VARCHAR(100) | Especialidad |
| telefono | VARCHAR(20) | Teléfono |
| correo | VARCHAR(100) | Correo |

## Tabla `cita`

 | Campo | Tipo | Descripción |
| --- | --- | --- |
| id\_cita | INT | Identificador |
| id\_paciente | INT | Paciente |
| id\_medico | INT | Médico |
| fecha | DATE | Fecha |
| hora | TIME | Hora |
| estado | VARCHAR(30) | Estado |
| motivo | TEXT | Motivo |

 # 🔗 Relaciones

```
PACIENTE
   │
   │ 1
   │
   │ N
   ▼
 CITA
   ▲
   │ N
   │
   │ 1
   │
 MÉDICO
```

 Un paciente puede tener múltiples citas.

 Un médico puede atender múltiples citas.

 Cada cita pertenece a un paciente y a un médico.

 # 🛠️ Modelo SQL

```
CREATE DATABASE actividad7;

USE actividad7;

CREATE TABLE paciente (
    id_paciente INT AUTO_INCREMENT PRIMARY KEY,
    nombre VARCHAR(100) NOT NULL,
    documento VARCHAR(20) NOT NULL UNIQUE,
    fecha_nacimiento DATE,
    telefono VARCHAR(20),
    correo VARCHAR(100),
    activo BOOLEAN DEFAULT TRUE
);

CREATE TABLE medico (
    id_medico INT AUTO_INCREMENT PRIMARY KEY,
    nombre VARCHAR(100) NOT NULL,
    especialidad VARCHAR(100) NOT NULL,
    telefono VARCHAR(20),
    correo VARCHAR(100)
);

CREATE TABLE cita (
    id_cita INT AUTO_INCREMENT PRIMARY KEY,
    id_paciente INT NOT NULL,
    id_medico INT NOT NULL,
    fecha DATE NOT NULL,
    hora TIME NOT NULL,
    estado VARCHAR(30) DEFAULT 'Pendiente',
    motivo TEXT,

    FOREIGN KEY (id_paciente)
        REFERENCES paciente(id_paciente),

    FOREIGN KEY (id_medico)
        REFERENCES medico(id_medico)
);
```

 # 📝 Requerimientos funcionales

 Los requerimientos funcionales indican las acciones que el sistema debe realizar.

 | Código | Requerimiento |
| --- | --- |
| RF01 | Registrar pacientes. |
| RF02 | Modificar pacientes. |
| RF03 | Consultar pacientes. |
| RF04 | Registrar médicos. |
| RF05 | Consultar médicos. |
| RF06 | Registrar citas. |
| RF07 | Consultar citas. |
| RF08 | Modificar citas. |
| RF09 | Cancelar citas. |
| RF10 | Consultar citas por paciente. |
| RF11 | Consultar citas por médico. |
| RF12 | Cambiar el estado de una cita. |

 # ⚙️ Requerimientos no funcionales

 | Código | Requerimiento |
| --- | --- |
| RNF01 | El sistema debe proteger la información almacenada. |
| RNF02 | Las contraseñas deben almacenarse de forma segura. |
| RNF03 | El sistema debe contar con control de acceso. |
| RNF04 | Las consultas deben responder rápidamente. |
| RNF05 | La interfaz debe ser sencilla de utilizar. |
| RNF06 | Se deben realizar copias de seguridad. |
| RNF07 | La información debe mantener su integridad. |
| RNF08 | El sistema debe permitir mantenimiento y actualización. |
| RNF09 | El sistema debe evitar datos duplicados cuando corresponda. |
| RNF10 | El sistema debe mantener disponibilidad durante el horario de servicio. |

 # 🧩 Tecnologías utilizadas

 | Tecnología | Uso |
| --- | --- |
| 🐍 Python | Desarrollo y programación |
| 🗄️ MySQL | Base de datos |
| 📊 Pandas | Análisis de datos |
| ⚡ Polars | Procesamiento de datos |
| 🔬 SciPy | Cálculos científicos |
| 📗 Excel | Manejo inicial de información |
| 💻 Visual Studio Code | Desarrollo |
| ☁️ Google Colab | Ejecución de Python |
| 🐙 GitHub | Control y almacenamiento del proyecto |

 # 🎯 Conclusiones

 El desarrollo de esta actividad permitió comprender la importancia de las bases de datos en los sistemas informáticos actuales.

 Se estudiaron diferentes tipos de datos como `INT`, `VARCHAR`, `DATE` y `DECIMAL`, comprendiendo su utilización en situaciones reales.

 También se analizó la diferencia entre trabajar con información en Excel y utilizar una base de datos relacional. Excel resulta útil para tareas de análisis y organización de datos, mientras que sistemas como MySQL permiten trabajar con información estructurada, relaciones entre tablas y aplicaciones que requieren una gestión más robusta.

 Python permite complementar las bases de datos mediante la creación de aplicaciones, automatización y análisis de información. Las bibliotecas Pandas, Polars y SciPy amplían las posibilidades de procesamiento y análisis de datos.

 Finalmente, se diseñó una propuesta de sistema de gestión de citas médicas, identificando sus tablas, campos, relaciones y requerimientos funcionales y no funcionales.

 # 📎 Evidencias

 En este repositorio se incluyen las siguientes evidencias:

 - [x] Investigación sobre tipos de datos.
- [x] Reflexión sobre "No hay sistema".
- [x] Comparación antes/después de las computadoras.
- [x] Tablas de Excel.
- [x] Operaciones de filtrado y ordenamiento.
- [x] Zen de Python.
- [x] Ejercicios en Python.
- [x] Análisis de Pandas.
- [x] Análisis de Polars.
- [x] Análisis de SciPy.
- [x] Conexión Python + MySQL.
- [x] Aplicación de MySQL.
- [x] Infografía.
- [x] Propuesta de base de datos.
- [x] Modelo de tablas.
- [x] Requerimientos funcionales.
- [x] Requerimientos no funcionales.
- [x] Script SQL.

 ## 👨‍💻 Autor

 **Nombre:** Annaela Marquez, Camilo Cuadrado.

Tienes razón. En la conversación aparecen **29 preguntas**. Aquí están todas, resumidas y numeradas:

 29 preguntas y respuestas — Resumen

# 29 preguntas y respuestas

 1. **¿Qué nivel Tier tendría un centro de datos que se cae 22 horas al año?**\
    Aproximadamente **Tier II**, con 99,75 % de disponibilidad.
2. **¿Por qué un técnico de climatización no debería entrar libremente a la sala de servidores?**\
    Por **seguridad, protección de equipos, información y control de acceso**.
3. **¿Qué pasa si se rompe el único cable de fibra de una empresa?**\
    Se pierde la conectividad hasta reparar la fibra. Es un **punto único de falla**.
4. **¿Por qué los servidores no tienen pantalla ni teclado?**\
    Porque normalmente se **administran remotamente**, ahorrando espacio y costos.
5. **¿Qué evita perder las notas si se daña un disco?**\
    **RAID, copias de seguridad y replicación** protegen los datos.
6. **¿Para qué sirven las baterías si ya hay generadores?**\
    La **UPS** mantiene los equipos funcionando mientras arranca el generador.
7. **¿En qué se gastan los 50 W adicionales con un PUE de 1,5?**\
    En **refrigeración, UPS, distribución eléctrica, iluminación y sistemas auxiliares**.
8. **¿Por qué no se usan rociadores de agua comunes en la sala de servidores?**\
    Porque el agua puede dañar los equipos; se emplean sistemas de extinción adecuados.
9. **¿Qué dato del edificio guardarías cada minuto para detectar un problema?**\
    Principalmente **temperatura**, además de humedad.
10. **¿Por qué es útil separar un problema grande en capas?**\
     Facilita **localizar el problema y diagnosticarlo más rápidamente**.
11. **Nombra tres aplicaciones y su protocolo de capa 7.**\
     Chrome → **HTTP/HTTPS**; Gmail → **SMTP/IMAP**; Google Drive → **HTTP/HTTPS**.
12. **¿Qué pasa si el servidor olvida tu sesión en cada clic?**\
     Tendrías que **autenticarte continuamente**. Se utilizan cookies o tokens de sesión.
13. **¿Qué preguntas de un rector se responden mejor con este modelo?**\
     Preguntas sobre **disponibilidad, riesgos, seguridad, continuidad, costos y capacidad**.
14. **¿Cómo dibujarías como grafo la topología de red del centro de datos?**\
     Los **equipos son nodos** y las **conexiones son aristas**.
15. **Si a las 10:04 sube la temperatura, ¿qué equipo revisarías primero?**\
     El **sistema de climatización HVAC/CRAC/CRAH**.
16. **¿Diferencia entre buscar «router» por palabra exacta o por significado?**\
     Exacta → busca el **texto**; semántica → busca el **concepto**.
17. **Para una transferencia bancaria, ¿ACID o BASE? ¿Y para «me gusta»?**\
     Transferencia → **ACID** por consistencia. «Me gusta» → **BASE** por disponibilidad y escalabilidad.
18. **¿Qué base de datos usarías para catálogo, carrito y pagos?**\
     Catálogo → **SQL o NoSQL**; carrito → **Redis/NoSQL**; pagos → **SQL con ACID**.
19. **¿Por qué una videollamada prefiere UDP y una transferencia bancaria TCP?**\
     La videollamada prioriza **baja latencia**; la transferencia necesita **fiabilidad y orden de los datos**.
20. **¿Por qué se agotaron las direcciones IPv4 y qué resuelve IPv6?**\
     IPv4 tiene direcciones de **32 bits** y su espacio se agotó. IPv6 usa **128 bits**, proporcionando muchas más direcciones.
21. **Si la IP es la dirección de tu casa, ¿qué sería la MAC?**\
     La **MAC identifica la interfaz de red**, mientras la IP identifica su ubicación lógica en la red.
22. **¿Qué ventajas tiene la fibra óptica frente al cobre?**\
     Mayor **velocidad, distancia y capacidad**, además de menor interferencia electromagnética.
23. **Si la página no carga, ¿por cuál capa empezarías a revisar?**\
     Por las **capas inferiores**, empezando por física y red, y luego subiendo hasta aplicación.
24. **¿Qué problemas tendría la universidad guardando las notas en hojas de cálculo sueltas?**\
     **Inconsistencias, pérdida de datos, problemas de seguridad, duplicación y dificultad para hacer copias de seguridad**.
25. **¿Qué columna une la tabla de estudiantes con la tabla de notas?**\
     El **ID del estudiante**, que es clave primaria en estudiantes y clave foránea en notas.
26. **Si las notas van dentro del estudiante, ¿qué ventaja y riesgo trae?**\
     Ventaja: **simplicidad**. Riesgo: **dificultad de mantenimiento y posibles inconsistencias**.
27. **¿Por qué guardar la sesión del usuario en memoria y no en disco?**\
     Porque la **memoria es mucho más rápida**, aunque es volátil.
28. **¿Qué pasa con una empresa si su único cable de fibra se rompe en una obra?**\
     Puede perder todos los servicios de red hasta la reparación. La solución es tener **redundancia y rutas independientes**.
29. **¿Qué pasa si el servidor olvida tu sesión en cada clic?**\
     La aplicación no podría mantener al usuario identificado entre solicitudes; habría que **iniciar sesión repetidamente**.
