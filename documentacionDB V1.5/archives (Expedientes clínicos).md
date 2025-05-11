
| Campo                         | Tipo de dato                          | Traducción español                          |
|-------------------------------|---------------------------------------|---------------------------------------------|
| id_archive                    | INT UNSIGNED AUTO_INCREMENT PRIMARY KEY | ID del expediente clínico                |
| id_patient_archive            | INT UNSIGNED                          | ID del paciente asociado                    |
| idcreate_user_archive         | INT UNSIGNED                          | ID del usuario que creó el expediente       |
| createdate_archive            | DATETIME DEFAULT CURRENT_TIMESTAMP    | Fecha de creación del expediente            |
| idupdater_user_archive        | INT UNSIGNED NOT NULL                  | ID del usuario que actualizó                |
| updatedate_archive            | DATETIME DEFAULT CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP | Fecha de actualización |
