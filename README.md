# DesarrolloPruebas

la parte frontend puede ser ejecutada desde consola ejecutando los siguientes comandos
1) npm install --force
2) npm install axios
3) node index.js (ejecutar desde consola cmd windows en la raiz del proyecto)
4) acceder a http://localhost:3000/index


la parte backend puede ser abierta en el IDE de prefencia (IntelliJ) es un proyecto gradle unicamente se debe ejecutar la clase main
y luego se pueden consumir los endpoints que este expone, sea desde cualquier app, browser o en su defecto postman, una vez se haya ejecutado el proyecto 
se puede accceder a:

localhost:8080/thService/employees/findAll
localhost:8080/thService/employees/findById/{cualquier ID}

estos son 2 endpoints que se exponen desde la API desarrollada
