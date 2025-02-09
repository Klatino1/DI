<p align="right">
  <img src="https://cpilosenlaces.com/wp-content/uploads/2023/03/cpifp-los-enlaces-2x.png" alt="Descripción de la imagen" width="175"/>
</p>


# :package: Inventario y Gestión de Personal
## :sparkles: Descripción del Proyecto

*Este proyecto está diseñado para centralizar la gestión de altas y bajas de usuarios, inventarios de dispositivos y accesorios, así como las asignaciones de dispositivos para cada persona.*

---

## :dart: Objetivos

- Centralizar la gestión de altas y bajas de los usuarios de una empresa.
- Centralizar el inventario de dispositivos y accesorios.
- Gestionar las asignaciones de dispositivos para cada persona.

---

## :no_entry_sign: Vinculación a empresa

- **No**

---

## :hammer_and_wrench: Actividades a realizar

- Análisis del modelo de datos.
- Análisis y desarrollo de casos de uso.
- Desarrollo de la aplicación.
- Pruebas del entorno.

---

## :toolbox: Recursos necesarios para la ejecución

1. **Figma**
2. **Android Studio** ![Android Studio](https://img.shields.io/badge/Android%20Studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=white)
3. **Kotlin/Java** ![Kotlin](https://img.shields.io/badge/Kotlin-0095D5?style=for-the-badge&logo=kotlin&logoColor=white)

---

## :bar_chart: Imágenes y diagramas

### Posible modelo de datos

```mermaid
erDiagram
    USUARIO {
        int id
        string nombre
        string email
        string rol
        string departamento
        string localizacion
    }
    DISPOSITIVO {
        int id
        string marca
        int precio
        date fecha_alta
        string estado
    }
    DEPARTAMENTO {
        int id
        int id_lider
        int presupuesto_disponible
        int presupuesto_total
    }
    USUARIO ||--o{ DISPOSITIVO : asigna
    USUARIO ||--o{ DEPARTAMENTO : lidera
    DEPARTAMENTO ||--o{ DISPOSITIVO : administra
```

### Estimación de dispositivos

```mermaid
pie
    title Distribución de Categorías
    "PC Sobremesa" : 40
    "PC Portátil" : 30
    "Periféricos" : 20
    "Móviles" : 10
```

### Planificación

```mermaid
gantt
    title Planificación del Proyecto
    section Documentación
    Documentación de la memoria       :active, doc1, 2025-03-01, 3mo
    section Análisis
    Análisis del modelo de datos      :done,   an1, 2025-03-01, 3w
    Investigación de tecnologías      :done,   an2, 2025-03-22, 1w
    section Desarrollo
    Desarrollo de la aplicación       :active, dev1, 2025-04-01, 5w
    section Pruebas
    Pruebas del entorno               :         test1, 2025-05-06, 1w
    Corrección de errores             :         test2, 2025-05-13, 2w
    section Presentación
    Preparación de la presentación    :         pres1, 2025-06-01, 1w
    Presentación del proyecto         :crit,    pres2, 2025-06-09, 1w
```

---


## :clipboard: Hacks y Tips

- Usar **Figma** para diseñar las interfaces del usuario.
- Prueba el entorno en dispositivos reales para evitar errores de compatibilidad.

---

## :tv: Vídeos relacionados

[![Video Demo](https://img.youtube.com/vi/vJapzH_46a8/0.jpg)](https://youtu.be/vJapzH_46a8?si=DBOZ8nRyrrGp1ynN)

---

## :memo: Tabla de funcionalidades

| Función               | Descripción                           | Estado       |
|-----------------------|---------------------------------------|--------------|
| Gestión de usuarios   | Altas y bajas de usuarios             | Pendiente      |
| Inventario de equipos | Control y registro de dispositivos    | Pendiente  |
| Asignaciones          | Asignación de dispositivos a personas | Pendiente    |

:tada: ¡Una vez se acabe esto si todo va bien tendremos el título!
