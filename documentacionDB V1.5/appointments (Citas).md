
| Campo                          | Tipo de dato                          | Traducción español                          |
|-------------------------------|---------------------------------------|---------------------------------------------|
| id_appointment                 | INT UNSIGNED AUTO_INCREMENT PRIMARY KEY | ID de la cita                           |
| id_employee_appointment        | INT UNSIGNED                          | ID del terapeuta asignado                   |
| date_appointment               | VARCHAR(100)                          | Fecha y hora de la cita (formato texto)     |
| id_state_appointment           | BIGINT UNSIGNED NOT NULL               | Estado actual de la cita                    |
| idcreate_user_appointment      | INT UNSIGNED                          | ID del usuario que creó la cita              |
| createdate_appointment         | DATETIME DEFAULT CURRENT_TIMESTAMP    | Fecha de creación de la cita                |
| idupdater_user_appointment     | INT UNSIGNED NOT NULL                  | ID del usuario que actualizó la cita        |
| updatedate_appointment         | DATETIME DEFAULT CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP | Fecha de actualización |
