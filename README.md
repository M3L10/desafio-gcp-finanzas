# Desafío Académico: Método de Gradientes Conjugados Precondicionado (GCP) en Finanzas

**Estudiante:** Ronal Limachi Mamani  
**Universidad:** Universidad Mayor de San Andrés (UMSA)  
**Facultad:** Ciencias Puras y Naturales - Carrera de Informática  
**Asignatura:** Métodos Numéricos  
**Mención:** Ingeniería de Sistemas  

---

## 📌 Descripción del Proyecto
Este repositorio contiene la solución completa al **Desafío Académico de Métodos Numéricos**, consistente en el desarrollo y despliegue de una aplicación web interactiva que modela y resuelve problemas de optimización y distribución presupuestaria financiera interdepartamental ($n \ge 4$) mediante el **Método de Gradientes Conjugados Precondicionado (GCP)**, fundamentado en el artículo científico del **Lic. Porfirio Suñagua S. (Revista Boliviana de Matemática UMSA, 2020)**.

---

## 🛠️ Tecnologías Utilizadas
- **HTML5 & Tailwind CSS:** Estructura semántica y diseño moderno reactivo.
- **JavaScript Vanila (ES6+):** Solvers numéricos integrados directamente en el frontend.
- **Chart.js:** Visualización interactiva de curvas de convergencia en escala logarítmica.
- **KaTeX:** Renderizado matemático riguroso en formato LaTeX.

---

## 📁 Arquitectura del Proyecto

```text
.
├── index.html       # Estructura de la aplicación web y los 10 módulos interactivos
├── styles.css       # Estilos personalizados de la interfaz
├── solvers.js      # Solvers numéricos (Cholesky, GC, GCP, Sylvester, Condicionamiento)
├── app.js          # Control de eventos de la UI, gráficos dinámicos y módulo QA
└── README.md        # Documentación del proyecto y guía de ejecución
```

---

## 🚀 Instrucciones de Ejecución Local

No requiere la instalación de dependencias pesadas ni servidores complejos. Para ejecutar localmente:

1. Clona este repositorio:
   ```bash
   git clone https://github.com/M3L10/desafio-gcp-finanzas.git
   ```
   
2. Navega al directorio del proyecto:
   ```bash
   cd desafio-gcp-finanzas
   ```
3. Abre el archivo `index.html` directamente en tu navegador web preferido (Chrome, Firefox, Edge, Brave).

---

## 📚 Referencias
- **Suñagua S., P. (2020).** *Método de Gradientes Conjugados Precondicionado*. Revista Boliviana de Matemática UMSA, 04, 2-7.
- **Golub, G. H., & Van Loan, C. F. (2013).** *Matrix Computations* (4th ed.). Johns Hopkins University Press.
- **Saad, Y. (2003).** *Iterative Methods for Sparse Linear Systems* (2nd ed.). SIAM.
