# Ej. - Any Company Global - Normalización de Bases de Datos

## Instrucciones:

Descarga el pdf donde encontrarás una tabla de datos sin normalizar
Normaliza la tabla (se recomienda el uso de Google Sheets)
Realiza un diagrama ER de Chen (ver recursos)
Realiza un diagrama de tipo patas de gallo (ver recursos)
Crea un repositorio con el Readme
Inserta en el Readme la descripción del ejercicio así como los diagramas creados (puedes utilizar Mermaid)

## Requisito:

Normalizar la tabla proporcionada (ver pdf)
Con diagrams.net realizar un diagrama de entidad-relación (de Chen)
Con diagrams.net realizar un diagrama UML (Database Schema - Patas de gallo) de la base de datos con sus tablas, campos y relaciones
Entregables:

Enlace del repositorio con el Readme

## Recursos:
diagrams.net

Normalización ejemplo: Freecodecamp.org

Como crear un diagrama de base de datos
Mermaid - Entity Relationship Diagrams

![Separador Animado](https://capsule-render.vercel.app/api?type=waving&color=auto&height=100&section=header)

## Paso 1:
Primero creo la Database "company".

<img width="229" height="148" alt="image" src="https://github.com/user-attachments/assets/34bae552-38f2-47f2-9f63-cb41ff5834d1" />


## Paso 2:
Importo la sentencia SQL del archivo "any_company_global_create_table_script.sql" o copio la sentencia de ese mismo archivo y la pego en el editor SQL para crear la tabla "sales_not_normalized".
<img width="632" height="494" alt="image" src="https://github.com/user-attachments/assets/b371e2b3-941b-4a4b-bef6-96aedef816b8" />

## Paso 3:
Importo la sentencia SQL del archivo "any_company_global_insert_data_script.sql" o copio la sentencia de ese mismo archivo y la pego en el editor SQL para insertar los datos en la tabla.
<img width="1279" height="451" alt="image" src="https://github.com/user-attachments/assets/58eb4818-81f1-4009-984d-452098389c29" />

## Paso 4:
Realizo la normalización de la tabla "sales_not_normalized":
<img width="561" height="394" alt="image" src="https://github.com/user-attachments/assets/120ef388-9425-4f12-b280-1e94b6b5d4fa" />

## Paso 5:
Para crear las tablas normalizadas, hago una sentencia SQL usando una nueva database (db_any_company_global_normalized):

<img width="618" height="568" alt="image" src="https://github.com/user-attachments/assets/40f2ed06-7c09-4e3f-b495-c98aafc582dd" />
<img width="440" height="349" alt="image" src="https://github.com/user-attachments/assets/2e745d8a-9940-4d0a-963a-006a7aaefb61" />

Inserto los datos de las tablas normalizadas con SQL:
<img width="375" height="62" alt="image" src="https://github.com/user-attachments/assets/ab84e0b8-85b1-45f8-a10c-a90389553b59" />
<img width="401" height="77" alt="image" src="https://github.com/user-attachments/assets/0698ae0e-300d-4730-a4be-f1fa9c1d0375" />
<img width="427" height="129" alt="image" src="https://github.com/user-attachments/assets/c7fa6392-ecaf-4e29-ba05-393971ceedfe" />
<img width="425" height="142" alt="image" src="https://github.com/user-attachments/assets/a23eeb2c-cf7d-42f4-a1e0-719c407d15ba" />
<img width="422" height="130" alt="image" src="https://github.com/user-attachments/assets/32aa6b4a-3252-4fcb-8cff-2bcc03772cf2" />
<img width="420" height="130" alt="image" src="https://github.com/user-attachments/assets/7a5630c2-2472-4b3a-b182-f0b0a525b742" />
<img width="423" height="126" alt="image" src="https://github.com/user-attachments/assets/1847a0d4-d74a-421e-87a4-dd26af5141b8" />

## Paso 6:
Realizo la consulta para saber que pais corresponde id_sales 3.
<img width="482" height="270" alt="image" src="https://github.com/user-attachments/assets/5abf2e22-c4f8-455e-a7ca-c39cd72324d7" />
