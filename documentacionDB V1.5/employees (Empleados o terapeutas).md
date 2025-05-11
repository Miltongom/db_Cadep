

| Campo                         | Tipo de dato                                                   | Traducción español                       |
| ----------------------------- | -------------------------------------------------------------- | ---------------------------------------- |
| id_employee                   | INT UNSIGNED AUTO_INCREMENT PRIMARY KEY                        | ID del empleado o terapeuta              |
| cui_employee                  | VARCHAR(15)                                                    | CUI del empleado (documento)             |
| firstname_employee            | VARCHAR(30)                                                    | Primer nombre                            |
| middlename_employee           | VARCHAR(30)                                                    | Segundo nombre                           |
| thirdname_employee            | VARCHAR(30)                                                    | Tercer nombre                            |
| lastname_employee             | VARCHAR(30)                                                    | Primer apellido                          |
| secondlastname_employee       | VARCHAR(30)                                                    | Segundo apellido                         |
| thirdlastname_employee        | VARCHAR(30)                                                    | Tercer apellido                          |
| profession_employee           | TEXT                                                           | Profesión o especialidad del terapeuta   |
| phone_employee                | VARCHAR(25)                                                    | Teléfono de contacto                     |
| id_user_employee              | BIGINT UNSIGNED                                                | ID de usuario del sistema asociado       |
| birthdate_employee            | DATE                                                           | Fecha de nacimiento                      |
| idbirth_department_employee   | BIGINT UNSIGNED                                                | ID del departamento de nacimiento        |
| idbirth_municipality_employee | BIGINT UNSIGNED                                                | ID del municipio de nacimiento           |
| age_employee                  | INT(3)                                                         | Edad del empleado                        |
| id_department_employee        | INT UNSIGNED                                                   | ID del departamento de residencia        |
| id_municipality_employee      | INT UNSIGNED                                                   | ID del municipio de residencia           |
| address_employee              | TEXT                                                           | Dirección completa                       |
| gender_employee               | VARCHAR(10)                                                    | Género                                   |
| maritalstatus_employee        | VARCHAR(20)                                                    | Estado civil                             |
| id_area_employee              | INT UNSIGNED                                                   | Área de atención donde trabaja           |
| id_branch_employee            | INT UNSIGNED                                                   | Sede donde trabaja                       |
| id_state_employee             | INT UNSIGNED                                                   | Estado del empleado                      |
| idcreate_user_employee        | INT UNSIGNED                                                   | ID del usuario que creó el registro      |
| createdate_employee           | DATETIME DEFAULT CURRENT_TIMESTAMP                             | Fecha de creación                        |
| idupdater_user_employee       | BIGINT UNSIGNED                                                | ID del usuario que actualizó el registro |
| updatedate_employee           | DATETIME DEFAULT CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP | Fecha de actualización                   |
