

| Campo                        | Tipo de dato    | Descripción                                       |
|-----------------------------|-----------------|---------------------------------------------------|
| id_relative                 | INT UNSIGNED    | Identificador único del familiar (PK)            |
| idprincipal_patient_relative| INT             | ID del paciente principal (FK → patients)        |
| idsecondary_patient_relative| INT             | ID del paciente secundario (FK → patients)       |
| relationship_relative       | VARCHAR(30)     | Parentesco con el paciente (padre, madre, etc.)  |
| idcreate_user_relative      | INT             | Usuario que registró al familiar (FK → users)    |
| createdate_relative         | DATETIME        | Fecha de creación del registro                   |
| idupdater_user_relative     | INT             | Usuario que actualizó el registro (FK → users)   |
| updatedate_relative         | DATETIME        | Fecha de la última actualización del registro    |
