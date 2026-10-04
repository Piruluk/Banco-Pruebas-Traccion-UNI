# Banco de Pruebas de Tracción de Bajo Costo :hammer_and_wrench:
This repository is developed to document the design, construction, and validation of a low-cost electromechanical tensile testing machine for educational and rapid prototyping applications.
---
## Problem 
¿Es posible caracterizar mecánicamente materiales de impresión 3D y plásticos de baja resistencia utilizando una máquina de ensayo de tracción de bajo costo basada en componentes de hardware abierto y piezas impresas en 3D, manteniendo una precisión aceptable para fines educativos?
---
## Theoretical framework :memo:
El diseño de la máquina de ensayo de tracción se fundamenta en principios de mecánica de materiales, cinemática y adquisición de datos electrónicos. Los componentes clave del sistema interactúan para medir el esfuerzo y la deformación durante el ensayo:
Key principles:
- **Ensayo de Tracción Uniaxial:** Determinación de propiedades mecánicas (módulo de Young, límite elástico, resistencia última a la tracción - UTS).
- **Relación Esfuerzo-Deformación:** Adquisición sincronizada de fuerza (mediante celda de carga) y desplazamiento.
- **Transmisión de Potencia Mecánica:** Conversión de movimiento rotatorio a lineal utilizando un motor paso a paso y un husillo de bolas.
- **Acondicionamiento de Señal y Control Digital:** Uso de la plataforma Arduino para procesar las señales de la celda de carga (vía HX711) y controlar la velocidad de deformación.
---
## Members and roles :bowtie:
| Photo | Name | Role |
| :---: | :---: | :---: |
| <img width="180" height="250" alt="Felix Ramirez" src="" /> | Felix Ramirez | Responsable del diseño mecánico, ensamblaje y calibración del desplazamiento. |
| <img width="180" height="250" alt="Gianpiero Ramirez" src="" /> | Gianpiero Ramirez | Responsable de la instrumentación electrónica, desarrollo de firmware y adquisición de datos. |

**UNI 2026**

---
## References :link:

[1] Wiranata, A., et al. (2024). Economically viable electromechanical tensile testing equipment for stretchable sensor assessment. HardwareX, 19, e00546.
[2] Saavedra Ravier, D. V. (2025). Open hardware tensile testing machine for plastics (ASTM D638).
[3] Arrizabalaga, J. H., Simmons, A. D., & Nollert, M. U. (2017). Fabrication of an economical Arduino-based uniaxial tensile tester. Journal of Chemical Education, 94(4), 530-533.
