# 🧠 Cómo entrenar a tu perceptrón  
### Proyecto interactivo de Métodos Numéricos & Redes Neuronales

Este repositorio contiene una versión web totalmente interactiva de nuestro proyecto sobre el **entrenamiento de un perceptrón** para resolver las puertas lógicas **AND** y **OR**, junto con la presentación teórica completa y el PDF original del informe.

El objetivo es ofrecer una explicación clara, visual e intuitiva del funcionamiento del perceptrón, su frontera de decisión y el efecto que tienen los parámetros `b`, `w₁`, `w₂` y el umbral `τ` sobre la clasificación.

---

## 🚀 Demo en vivo (GitHub Pages)

👉 **[Ver proyecto en línea](https://TU_USUARIO.github.io/NOMBRE_DEL_REPO/)**  
*(Recuerda actualizar esta URL cuando subas el repo)*

---

## 📁 Contenido del repositorio

El proyecto está organizado en varias páginas:

### **`index.html`**
Página de inicio con presentación del proyecto y navegación.

### **`teoria.html`**
Contiene **todo el desarrollo teórico del informe**, pasado a HTML/LaTeX y estructurado:

- Definición del perceptrón  
- Función de nivel  
- Función de activación  
- Frontera de decisión  
- Función de pérdida  
- Gradiente  
- Descenso por gradiente  
- Interpretación geométrica  

### **`interactivo.html`**
Una demo interactiva donde puedes:

- Seleccionar **AND** o **OR**  
- Cambiar entre parámetros **entrenados** o **manuales**  
- Ajustar sliders para `b`, `w₁`, `w₂`  
- Cambiar el umbral `τ`  
- Ver la frontera de decisión en tiempo real  
- Observar cómo el modelo clasifica los 4 puntos `{0,1}²`  
- Revisar la tabla con valores de `F(x)` y clase predicha `ŷ`  

*(El módulo XOR ha sido eliminado para evitar confusión y mantener el enfoque en perceptrones lineales.)*

### **`pdf.html`**
Permite visualizar directamente el PDF original del informe, sin recuadros ni cajas.

### **Otros recursos**
- Carpeta `/img` *(opcional)*  
- Carpeta `/docs` para PDF *(si la usas)*  

---

## 🎯 Objetivo del proyecto

El propósito principal era:

1. **Implementar y explicar** cómo se entrena un perceptrón mediante descenso de gradiente.  
2. **Visualizar** la frontera de decisión y su relación con los parámetros.  
3. **Mostrar** por qué algunas puertas (AND/OR) son linealmente separables y otras (como XOR) no.  
4. **Crear una herramienta interactiva** para experimentar con los parámetros y la clasificación.  
5. Convertir el informe en **una web clara, estética y totalmente navegable**.

---

## 🧩 Tecnologías usadas

- **HTML5 + CSS3**  
- **JavaScript vanilla**  
- **SVG dinámico para la frontera de decisión**  
- **GitHub Pages** para hosting  
- Diseño responsive y moderno, inspirado en dashboards UI  

---

## 📸 Capturas (opcional)

> Añádelas cuando tengas el repo subido  
> por ejemplo:  
> `![Demo](img/demo.png)`  
> `![Interactivo](img/interactivo.png)`

---

## 🧭 Navegación

La barra superior incluye acceso directo a:

- Teoría  
- Demo interactiva  
- PDF original  
- Inicio  

Cada página mantiene el mismo estilo visual para una experiencia coherente.

---

## 👥 Autores

Proyecto desarrollado por:

- **Nombre 1**  
- **Nombre 2**  
- **Nombre 3 (si aplica)**  
- Asignatura: *Métodos Numéricos / Redes Neuronales*  
- Universidad / Curso (opcional)

---

## 📄 Licencia

Este proyecto puede usarse libremente con fines académicos.  
Si deseas reutilizar el código interactivo en otros proyectos, se agradece la atribución.

---

## 📝 Notas finales

Si más adelante quieres añadir:

- descarga del código,
- una versión oscura/clara,
- animaciones,
- o una extensión para perceptrones multicapa (XOR),

puedo ayudarte a integrarlo fácilmente.

---

¿Quieres que prepare también un **banner bonito para poner arriba del README**, o un **GIF de la demo interactiva**?
