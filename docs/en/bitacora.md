![imagen](https://user-images.githubusercontent.com/8480839/182930659-e23dcc4a-0738-4035-a775-a137cd8d06e0.png)


**Bitácora** es una herramienta para ayudar a organizar la información generada con drones. Permite visualizar y organizar la información generada antes, durante y después de los vuelos.

---

## Instalación

1. Descargar el archivo zip desde <a href="https://github.com/gpereyrairujo/bitacora/releases/download/v0.6.0-alpha/bitacora.0.6.win.zip">https://github.com/gpereyrairujo/bitacora/releases/download/v0.6.0-alpha/bitacora.0.6.win.zip</a> (o la última versión publicada en <a href="https://github.com/gpereyrairujo/bitacora/releases">https://github.com/gpereyrairujo/bitacora/releases</a>)

2. Extraer los archivos del zip, y copiar la carpeta `bitacora` a la carpeta `C:/Archivos de programa` o a cualquier otra ubicación

3. Para abrir Bitácora, hacer doble clic en el archivo ejecutable `bitacora.exe` (para más comodidad, se puede crear un acceso directo, o arrastrar el archivo a la barra de tareas para fijarlo)

---

## Utilización

### Paso 1
Colocar todos los archivos de un vuelo en una misma carpeta: imágenes, plan de vuelo, mosaico, modelo de elevación, etc. (también puede ser una carpeta con subcarpetas)

![imagen](https://user-images.githubusercontent.com/8480839/182928249-f728c5a9-82f0-4356-b61e-5d0704d9db0f.png)

### Paso 2
Con la función "Nuevo vuelo", Bitácora solicitará que seleccionemos la carpeta, leerá toda la información contenida en las imágenes y demás archivos (fechas y horarios, coordenadas, altura de vuelo, cámara utilizada, etc.), y luego nos solicitará un nombre para identificar el vuelo y una descripción opcional

![imagen](https://user-images.githubusercontent.com/8480839/182928563-ec6c487a-ee30-4be4-84b3-818b6ce51b30.png)

Una vez procesados los archivos de la carpeta, toda la información del vuelo se muestra en una ventana, en formato de mapa y de tabla

![imagen](https://user-images.githubusercontent.com/8480839/182928763-0b5480fc-c143-4648-9526-4fcc92c76e75.png)

### Paso 3
Si los datos son correctos, con la función "Guardar vuelo" se incorpora el vuelo a la lista de vuelos de la ventana principal (desde donde luego se puede visualizar nuevamente con la función "Abrir vuelo")

![imagen](https://user-images.githubusercontent.com/8480839/182928889-5b3bff65-734e-494a-8c38-6b689ee3147f.png)

También se guardan los datos del vuelo en la carpeta original, en formatos compatibles con otros programas (la tabla de datos en formato csv, los datos geográficos en formato kml y la imagen del mapa en formato png)

![imagen](https://user-images.githubusercontent.com/8480839/182929040-6a582e9e-3ed1-43d8-a9f2-803f5c862a73.png)

---

## Archivos compatibles e información extraída/visualizada

### Imágenes (archivos .jpg o .jpeg)
- Cantidad de imágenes
- Nombre de la primera y la última imagen
- Nombre de la cámara utilizada
- Velocidad de obturación
- Sensibilidad ISO
- Coordenadas GPS (longitud, latitud y altitud)
- Superficie cubierta por las imágenes
- Visualización de la posición de cada imagen y del recorrido del dron

![imagen](https://user-images.githubusercontent.com/8480839/182951201-ea2ff746-1542-4dc9-ab27-d515c94b3778.png)

### Plan de vuelo (archivos .waypoint)
- Velocidad de vuelo
- Altura de vuelo
- Coordenadas del plan de vuelo
- Visualización del recorrido del dron

![imagen](https://user-images.githubusercontent.com/8480839/182951704-6c7b4e2f-b3b6-4134-ba78-5b7c0894eee0.png)

### Polígono del área de estudio (archivos .poly)
- Coordenadas del área de estudio
- Visualización del área de estudio

![imagen](https://user-images.githubusercontent.com/8480839/182951952-d5e80f94-ad6f-40d1-88a8-18fa49ac2c71.png)

### Mosaico (archivos .tif)
- Visualización de una miniatura de la imagen

![imagen](https://user-images.githubusercontent.com/8480839/182952271-ddcb92b7-df7f-4828-bd03-2c6d24232e67.png)

### Modelo de elevación (archivos .tif)
- Visualización de una miniatura de la imagen

![imagen](https://user-images.githubusercontent.com/8480839/182954453-90254f60-abba-4280-9947-500465756835.png)


