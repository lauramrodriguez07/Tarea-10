# Tarea-10
## Dockerización
Primero se inicia crando una carpeta para dejar los tres archivos organizados en un mismo lugar
<img width="1647" height="207" alt="image" src="https://github.com/user-attachments/assets/e37f872d-7604-4922-b52e-c2b3b3833a2b" />

Luego creamos los archivos de Python, en donde pegamos los codigos de cada uno de los ejemplos (Bipedo, Brazo y Carro):
<img width="1690" height="98" alt="image" src="https://github.com/user-attachments/assets/85144994-e496-4d51-8049-7129ee4c970d" />

+ Se crea una carpeta especial para el Bipedo, es decir un archivo URDF, el cual nos ayudara a que se definan las propiedades fisicas, visuales y cinematicas del robot, es decir, interpretar y modelar al robot en un entorno de 3D:
<img width="1690" height="101" alt="image" src="https://github.com/user-attachments/assets/97144292-1461-41a8-bb24-5f5b0db54fc9" />

Ahora, se creo un archivo de Dockerfile para todos los archivos:
<img width="1690" height="101" alt="image" src="https://github.com/user-attachments/assets/0bf15acd-2744-434d-9fa9-d550bea91fae" />

Seguimos al paso de contruir la imagen Docker:
<img width="1690" height="327" alt="image" src="https://github.com/user-attachments/assets/fb37aa94-a2b6-49f7-ac3c-215ddb8b2ff6" />
<img width="1690" height="327" alt="image" src="https://github.com/user-attachments/assets/99a787b3-c74e-423a-8ae3-7bd2e77ef45a" />

A continuación iniciamos ejecutando cada uno de los ejemplos en docker:
+ Bipedo:
<img width="1214" height="890" alt="image" src="https://github.com/user-attachments/assets/86bcfb9a-fac0-4dbd-9ce3-812b122f04a7" />
<img width="1013" height="786" alt="image" src="https://github.com/user-attachments/assets/cfd43fcf-88d7-4e5b-bb24-b25cd1155d01" />

+ Brazo:
<img width="1690" height="1025" alt="image" src="https://github.com/user-attachments/assets/26c2f6b0-c73a-4c55-915d-959337270ee6" />

+ Carro:
<img width="1690" height="1025" alt="image" src="https://github.com/user-attachments/assets/a373b4ed-5598-4230-8e12-f511d8bda253" />
