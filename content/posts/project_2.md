+++
title = 'Chasqui-II'
featured_image = "/images/chasqui_2.jpg"
date = 2024-09-07T16:31:23-05:00
+++


Soy estudiante investigador voluntario en la iniciativa satelital [Chasqui-II](https://www.facebook.com/CHASQUI2UNI) de la Universidad Nacional de Ingeniería, cuyo objetivo es desarrollar el segundo nanosatelite de la universidad.

* Coordinador del Subsistema de Órbita/Atmósfera.
* Coordinador del Subsistema de Carga Útil.

En el marco de esta iniciativa he desarrollado las siguientes investigaciones (papers):

### Nanosatellite Proposal for Monitoring the South Atlantic Magnetic Anomaly (SAMA) and Plasmaspheric Hiss over the Intertropical Zone of South America in Interplanetary Shocks

El objetivo principal de esta propuesta es monitorear la desaparición del **Plasmaspheric Hiss (PH)** y el debilitamiento del **campo geomagnético** en la región **South Atlantic Magnetic Anomaly (SAMA)**, debido a tormentas geomagnéticas causadas por **Interplanetary Shocks**, utilizando dos CubeSats: **CHASQUI A** y **CHASQUI B.**

Mis contribuciones en el desarrollo de la propuesta incluyen:

* **Análisis de los fenómenos:**
    - Análisis del **PH** a través de la **Densidad Espectral de Potencia (PSD)**.
    - Desarrollo de un **mapa de la intensidad total del campo geomagnético (Modelo IGRF-13)** en la región **SAMA**.
* **Simulación orbital:**
    - Simulé las órbitas de las misiones propuestas utilizando **[Systems Tool Kit (STK)](https://www.ansys.com/products/missions/ansys-stk)**.

* **Blindaje contra radiación:**
    - Determiné los espesores mínimos de blindaje de aluminio necesarios para proteger las cargas útiles de radiación mediante **[SPENVIS](https://www.spenvis.oma.be/)**, calculando la **Dosis Total Ionizante (TID**).

Esta investigación fue presentada en el [73rd International Astronautical Congress (IAC)](https://iac2022.org/) en Paris, Francia:
 * [Paper](http://www.scopus.com/inward/record.url?eid=2-s2.0-85167584351&partnerID=MN8TOARS)
 * [Presentación Interactiva](https://iac2022-iaf.ipostersessions.com/Default.aspx?s=E4-0C-0D-A3-DB-8D-96-4A-A6-B7-A2-A5-13-25-69-4B)

{{< figure src="/images/chasqui1.png" >}}
{{< youtube id="zmycXLVhT-s" >}}

   


### Computational tools for modeling the Chasqui A and Chasqui B nanosatellite missions in space weather study 

Los objetivos de este estudio fueron simular la interacción física de los proyectos nanosatélites **(Chasqui A y B)** con el **Plasmaspheric Hiss (PH)** y la **South Atlantic Magnetic Anomaly (SAMA)** respectivamente.

Mis principales contribuciones incluyeron la **simulación del entorno de radiación** al que estarían expuestos los nanosatélites, utilizando **SPENVIS** para calcular la deposición de radiación mediante el modelo **SHIELDOSE-2Q**, y determinar los materiales óptimos para el blindaje de los satélites. Para esto, llevé a cabo las siguiente simulaciones:

* **Espectros de protones y electrones atrapados:** Simulado con los modelos **AP-8** y **AE-8**.
* **Espectros de partículas solares:** Simulado con el modelo **SAPPHIRE**.
* **Espectros de partículas cósmicas:** Simulado con el modelo **ISO-15390**.

Esta investigación fue presentada en el [11th Nano-Satellite Symposium](https://nanosat11th.itu.edu.tr/) en Estambul, Turquia:
 * [Paper](https://nanosat11th.itu.edu.tr/assets/papers/Computational.pdf)