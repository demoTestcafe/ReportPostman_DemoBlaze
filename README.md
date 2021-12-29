# ReportPostman_DemoBlaze

Captura de los servicios del sistema con Postman, ejecución con Newman y reporte de preubas con HTML Extra

comandos para instalación y ejecución con Newman
- npm install -g newman (en consola ejecutar comando para instalación de newman)
- newman run "ruta"\DemoBlaze.postman_collection.json -e "ruta"\demoBlaze.postman_environment.json

comandos para instalación y ejecución con html extra
- npm install -g newman-reporter-htmlextra
- newman run "ruta"\DemoBlaze.postman_collection.json -e "ruta"\demoBlaze.postman_environment.json -r htmlextra
