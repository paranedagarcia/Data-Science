
# Ciclo de Vida de un Proyecto de Data Science

El ciclo de vida de un proyecto de Data Science describe las etapas clave desde la concepción del problema hasta la entrega de soluciones accionables basadas en datos.

---

## 🧭 Etapas Generales

1. **Definición del Problema**
2. **Recolección de Datos**
3. **Preparación y Limpieza de Datos**
4. **Análisis Exploratorio (EDA)**
5. **Modelado**
6. **Evaluación del Modelo**
7. **Despliegue**
8. **Comunicación de Resultados**
9. **Mantenimiento**

---

## 🔁 Comparativa entre CRISP-DM y OSEMN

| Aspecto                    | CRISP-DM                                              | OSEMN                                                   |
|----------------------------|--------------------------------------------------------|----------------------------------------------------------|
| Acrónimo                   | Cross-Industry Standard Process for Data Mining        | Obtain, Scrub, Explore, Model, iNterpret                |
| Enfoque principal          | Minería de datos, empresarial                         | Práctico y técnico                                       |
| Etapas                     | 6: Business Understanding, Data Understanding, etc.    | 5: Obtain, Scrub, Explore, Model, Interpret              |
| Inclusión de negocio       | Explícita                                              | Implícita                                                |
| Nivel de formalización     | Alto                                                   | Medio-bajo                                               |

---

## 📊 Comparativa Extendida: CRISP-DM, OSEMN, TDSP, AWS

| Característica                       | CRISP-DM                    | OSEMN                       | TDSP (Microsoft)              | AWS Data Science Lifecycle       |
|-------------------------------------|-----------------------------|-----------------------------|-------------------------------|----------------------------------|
| Origen                              | IBM                         | Mason & Wiggins (~2010)     | Microsoft Azure               | Amazon Web Services              |
| Foco                                | Negocio y minería de datos | Práctico-técnico            | Gestión colaborativa          | Escalabilidad en la nube         |
| Etapas                              | 6                           | 5                           | 5                              | 6                                |
| Gestión de proyectos                | Media                       | Baja                        | Alta                           | Alta                             |
| Colaboración equipo                 | Limitada                    | Individual                  | Fuerte                         | Fuerte                           |
| Despliegue/Mantenimiento            | Débil                       | No considerado              | Formal con DevOps             | Automatizado con AWS             |
| Uso en industria                    | Consultorías, banca         | Startups, bootcamps         | Organizaciones Azure           | Organizaciones con AWS           |

---

## 🧠 Recomendación de Uso

| Escenario                                     | Metodología sugerida |
|----------------------------------------------|----------------------|
| Proyectos estructurados                      | CRISP-DM             |
| Startups o prototipos rápidos                | OSEMN                |
| Equipos corporativos con Azure               | TDSP                 |
| Proyectos cloud con MLOps                    | AWS Lifecycle        |

---

## 📚 Referencias

- CRISP-DM: https://www.the-modeling-agency.com/crisp-dm.pdf
- OSEMN: *Doing Data Science* (O'Reilly)
- TDSP: https://docs.microsoft.com/en-us/azure/architecture/data-science-process/
- AWS: https://docs.aws.amazon.com/sagemaker/latest/dg/data-science-process.html
