# Rotación de imágenes

Repositorio de apoyo para el ejercicio de rotación de imágenes en el curso de Visión por Computador.

## Descripción

Este proyecto contiene un cuaderno de Jupyter (`rotacion.ipynb`) en el que se describe paso a paso el proceso matemático para rotar una imagen un ángulo θ alrededor de su centro, así como la implementación de cada etapa usando operaciones de NumPy (sin recurrir a librerías que apliquen la rotación automáticamente).

El objetivo es que los estudiantes:

1. Comprendan y expliquen cada uno de los pasos matemáticos involucrados.
2. Apliquen dichos pasos sobre una imagen de ejemplo usando únicamente NumPy.
3. Visualicen y comparen el resultado con la imagen original.

## Estructura del repositorio

```bash
vc_rotar_imagen/
├── rotacion.ipynb       # Cuaderno de Jupyter con la descripción y espacio para su implementación
└── README.md            # Este archivo de descripción
```

## Ejercicio

1. Abre el cuaderno `rotacion.ipynb` en Jupyter Lab o Notebook.
2. Lee la sección **Descripción matemática** donde se detallan los pasos:
   - Conversión de grados a radianes.
   - Cálculo del centro de la imagen.
   - Traslación al origen, aplicación de la matriz de rotación y traslación inversa.
   - Mapeo inverso para evitar huecos y técnicas de interpolación.
3. Crea nuevas celdas y escribe el código que:
   - Cargue una imagen de ejemplo.
   - Aplique paso a paso las transformaciones matemáticas con operaciones de NumPy.
   - Interpole valores cuando corresponda (p. ej. bilineal).
   - Genere y muestre la imagen rotada.
4. Añade comentarios en Markdown explicando lo que hace cada bloque de código.

## Ejecución

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu_usuario/vc_rotar_imagen.git
   ```
2. Navega al directorio:
   ```bash
   cd vc_rotar_imagen
   ```
3. Instala los requisitos (solo NumPy y Matplotlib):
   ```bash
   pip install numpy matplotlib
   ```
4. Ejecuta Jupyter Lab o Notebook:
   ```bash
   jupyter lab
   ```
5. Abre `rotacion.ipynb` y comienza el ejercicio.

## Contribuciones

Si encuentras errores o deseas mejorar la guía, abre un _issue_ o envía un _pull request_.

## Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.

