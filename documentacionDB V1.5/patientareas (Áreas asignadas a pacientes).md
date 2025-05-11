
| Campo                          | Tipo de dato                         | Traducción español                          |
|--------------------------------|--------------------------------------|---------------------------------------------|
| id_patientarea                 | INT UNSIGNED AUTO_INCREMENT PRIMARY KEY | ID del registro área-paciente           |
| id_patient_patientarea         | INT UNSIGNED                         | ID del paciente                             |
| id_area_patientarea            | INT UNSIGNED                         | ID del área asignada                        |
| idcreate_user_patientarea      | INT UNSIGNED                         | ID del usuario que creó el registro         |
| createdate_patientarea         | DATETIME DEFAULT CURRENT_TIMESTAMP   | Fecha de creación del registro              |
| idupdater_user_patientarea     | INT UNSIGNED NOT NULL                | ID del usuario que realizó la última modificación |
| updatedate_patientarea         | DATETIME DEFAULT CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP | Fecha de actualización del registro |
