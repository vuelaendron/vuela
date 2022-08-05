![imagen](https://user-images.githubusercontent.com/8480839/182930659-e23dcc4a-0738-4035-a775-a137cd8d06e0.png)


The open-source application **Bitácora** (“logbook” in Spanish), developed especially for the <a href="https://vuela.cc/en/toolkit">OSDT</a>, helps in visualizing and organizing all the files, images and metadata generated before, during, and after a drone flight, for archiving, sharing or further processing. The user only needs to save all the files (survey area polygon, flight plan, captured images, mosaic, elevation model, etc.) in a folder, and the program will automatically generate a map visualizing the files, and a table with flight information (flight date and time, location, altitude, speed, names of relevant files). This information is also saved in open formats compatible with other software (flight information table in csv format, flight map in png and kml formats).

![imagen](https://user-images.githubusercontent.com/8480839/182968311-0f0eec55-caf1-4851-a0e6-109839bbb077.png)

&nbsp;
## Installation

1. Download the zip file from <a href="https://github.com/gpereyrairujo/bitacora/releases/download/v0.6.0-alpha/bitacora.0.6.win.zip">https://github.com/gpereyrairujo/bitacora/releases/download/v0.6.0-alpha/bitacora.0.6.win.zip</a> (or the latest version published at <a href="https://github.com/gpereyrairujo/bitacora/releases">https://github.com/gpereyrairujo/bitacora/releases</a>)

2. Extract the files from the zip, and copy the `bitacora` folder to the `C:/Program Files` folder or any other location

3. To open Bitácora, double-click the executable file `bitacora.exe` (for convenience, you can create a shortcut, or drag the file to the taskbar to pin it)


&nbsp;
## Usage

### Step 1
Put all the files from a flight in the same folder: images, flight plan, mosaic, elevation model, etc. (it can also be a folder with subfolders)

![image](https://user-images.githubusercontent.com/8480839/182928249-f728c5a9-82f0-4356-b61e-5d0704d9db0f.png)

### Step 2
With the "New flight" function, Bitácora ask you to select the folder, it will read all the information contained in the images and other files (dates and times, coordinates, flight altitude, camera used, etc.), and then it will ask for a name to identify the flight and an optional description

![image](https://user-images.githubusercontent.com/8480839/182928563-ec6c487a-ee30-4be4-84b3-818b6ce51b30.png)

Once the files in the folder are processed, all flight information is displayed in one window, as a map and and data table

![image](https://user-images.githubusercontent.com/8480839/182928763-0b5480fc-c143-4648-9526-4fcc92c76e75.png)

### Step 3
If the data is correct, with the "Save flight" function the flight can be added to the list of flights in the main window (from where it can then be displayed again with the "Open flight" function).

![image](https://user-images.githubusercontent.com/8480839/182928889-5b3bff65-734e-494a-8c38-6b689ee3147f.png)

The flight data is also saved in the original folder, in formats compatible with other programs (the data table in csv format, the geographical data in kml format and the map image in png format)

![image](https://user-images.githubusercontent.com/8480839/182929040-6a582e9e-3ed1-43d8-a9f2-803f5c862a73.png)


&nbsp;
## Supported files and extracted/visualized information

### Images (.jpg or .jpeg files)
- Number of images
- Name of the first and last image
- Camera model
- Shutter speed
- ISO sensitivity
- GPS coordinates (longitude, latitude and altitude)
- Area covered by images
- Visualization of the position of each image and the path of the drone

![image](https://user-images.githubusercontent.com/8480839/182951201-ea2ff746-1542-4dc9-ab27-d515c94b3778.png)

### Flight plan (.waypoint files)
- Flight speed
- Flight height
- Flight plan coordinates
- Visualization of the path of the drone

![image](https://user-images.githubusercontent.com/8480839/182951704-6c7b4e2f-b3b6-4134-ba78-5b7c0894eee0.png)

### Surveyed area polygon (.poly files)
- Coordinates of the surveyed area
- Visualization of the surveyed area

![image](https://user-images.githubusercontent.com/8480839/182951952-d5e80f94-ad6f-40d1-88a8-18fa49ac2c71.png)

### Mosaic (.tif files)
- Thumbnail of the image

![image](https://user-images.githubusercontent.com/8480839/182952271-ddcb92b7-df7f-4828-bd03-2c6d24232e67.png)

### Elevation model (.tif files)
- Thumbnail of the image

![image](https://user-images.githubusercontent.com/8480839/182954453-90254f60-abba-4280-9947-500465756835.png)


&nbsp;
