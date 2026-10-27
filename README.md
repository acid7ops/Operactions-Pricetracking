# Centro de Reportes · Mercaderistas (servidor interno)

Abrir `index.html` desde la raíz del servidor web.

```
index.html
1_Ejecucion_PDV/
    1_Visualizador_Escritorio.html   Visualizador de Exhibiciones (versión escritorio)
    1_Visualizador_Telefono.html     Visualizador de Exhibiciones (versión teléfono)
    (2 · Exhibiciones Adicionales: formulario en línea, sin archivo local)
    3_SecondaryShelf.html            Secondary Shelf · Visibility
2_Herramientas/
    1_GeneradorINNO.html             Generador INNO · GAPS
    2_GuiaMSL.html                   Guía MSL · Punto de Venta
```

Convención de nombres: número de orden (el mismo que en pantalla) + nombre en
PascalCase, sin espacios ni tildes. Al subir una versión nueva de un reporte,
mantener el mismo nombre de archivo para que el index siga funcionando.

Nota: Exhibiciones Adicionales abre un formulario de Google Apps Script, y las
páginas cargan librerías, fuentes y fotos desde internet (cdnjs, jsDelivr,
Google Fonts, Google Drive). Los usuarios necesitan salida a internet.
