# Image-to-Text Converter

## Descripción
Herramienta que convierte texto contenido en imágenes o archivos PDF con imágenes en texto editable en documentos Word (.docx). Utiliza tecnología de reconocimiento óptico de caracteres (OCR) para extraer el texto con precisión, permitiendo así reutilizar y filtrar información de manera eficiente.

## Características
- **Conversión de imágenes a texto:** Extrae texto de archivos de imagen como JPEG, PNG, etc.
- **Conversión de PDF a texto:** Extrae texto de PDFs que contienen imágenes.
- **Exportación a Word:** Guarda el texto extraído en documentos Word (.docx) para una fácil edición y filtrado.

## Tecnologías Utilizadas
- **Lenguaje de Programación:** Python
- **Bibliotecas Principales:**
  - `pytesseract` para OCR
  - `poppler` para manipulación de archivos PDF
  - `python-docx` para la generación de documentos Word
  - `PyPDF2` para manejo de archivos PDF

## Requisitos
- Windows 7 o superior
- Tesseract-OCR (incluido en el ejecutable)

## Instalación
1. Descarga el archivo ejecutable (`ocr_to_word.exe`) desde la página de releases.
2. Coloca el ejecutable en cualquier carpeta de tu preferencia.

## Uso
1. Coloca los documentos de imagen o PDF en la carpeta `Documentos` que se encuentra en el mismo directorio que el ejecutable.
2. Ejecuta el programa haciendo doble clic en `ocr_to_word.exe`.
3. El programa procesará los archivos que están en la carpeta `Documentos` y generará los documentos Word correspondientes en la misma carpeta.

## Contribución
Las contribuciones son bienvenidas. Por favor, sigue estos pasos:
1. Haz un fork del repositorio.
2. Crea una rama para tu función (`git checkout -b feature/nueva-funcion`).
3. Realiza tus cambios y haz commit (`git commit -m 'Añadir nueva función'`).
4. Sube tus cambios a tu fork (`git push origin feature/nueva-funcion`).
5. Abre un Pull Request.

## Licencia
Este proyecto está licenciado bajo la [Licencia MIT](LICENSE).





