

| Campo                         | Tipo de dato                                                   | Traducción español                             |
| ----------------------------- | -------------------------------------------------------------- | ---------------------------------------------- |
| id_patient                    | INT UNSIGNED PRIMARY KEY                                       | ID del paciente                                |
| cui_patient                   | VARCHAR(15)                                                    | CUI (Documento de identificación)              |
| firstname_patient             | VARCHAR(30)                                                    | Primer nombre                                  |
| middlename_patient            | VARCHAR(30)                                                    | Segundo nombre                                 |
| thirdname_patient             | VARCHAR(30)                                                    | Tercer nombre                                  |
| lastname_patient              | VARCHAR(30)                                                    | Primer apellido                                |
| secondlastname_patient        | VARCHAR(30)                                                    | Segundo apellido                               |
| thirdlastname_patient         | VARCHAR(30)                                                    | Tercer apellido                                |
| birthdate_patient             | DATE                                                           | Fecha de nacimiento                            |
| idbirth_department_patient    | BIGINT UNSIGNED                                                | Departamento de nacimiento                     |
| idbirth_municipality_patient  | BIGINT UNSIGNED                                                | Municipio de nacimiento                        |
| age_patient                   | INT(3)                                                         | Edad del paciente                              |
| weight_patient                | DECIMAL(5,2)                                                   | Peso (kg)                                      |
| schooling_patient             | VARCHAR(30)                                                    | Nivel de escolaridad                           |
| phone_patient                 | VARCHAR(25)                                                    | Teléfono de contacto                           |
| id_department_patient         | INT UNSIGNED                                                   | Departamento de residencia                     |
| id_municipality_patient       | INT UNSIGNED                                                   | Municipio de residencia                        |
| address_patient               | TEXT                                                           | Dirección                                      |
| gender_patient                | VARCHAR(10)                                                    | Género                                         |
| religion_patient              | VARCHAR(25)                                                    | Religión                                       |
| maritalstatus_patient         | VARCHAR(20)                                                    | Estado civil                                   |
| dependentfamily_patient       | BOOLEAN                                                        | Tiene familiares a cargo (sí/no)               |
| reasonforconsultation_patient | TEXT                                                           | Motivo de la consulta                          |
| referreddoctor_patient        | VARCHAR(60)                                                    | Referido por (nombre del médico o institución) |
| idcreate_user_patient         | INT UNSIGNED                                                   | ID del usuario que registró                    |
| id_branch_patient             | INT UNSIGNED                                                   | ID de la sede donde recibe atención            |
| id_state_patient              | INT UNSIGNED                                                   | ID del estado del paciente                     |
| createdate_patient            | DATETIME DEFAULT CURRENT_TIMESTAMP                             | Fecha de creación                              |
| idupdater_user_patient        | BIGINT UNSIGNED                                                | ID del usuario que actualizó                   |
| updatedate_patient            | DATETIME DEFAULT CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP | Fecha de actualización                         |
