| Campo                   | Tipo de dato                                                   | Traducción español                 |
| ----------------------- | -------------------------------------------------------------- | ---------------------------------- |
| id_schedule             | INT UNSIGNED AUTO_INCREMENT PRIMARY KEY                        | ID del horario                     |
| hour_schedule           | TIME                                                           | Hora específica disponible         |
| idcreate_user_schedule  | INT UNSIGNED                                                   | ID del usuario que creó el horario |
| createdate_schedule     | DATETIME DEFAULT CURRENT_TIMESTAMP                             | Fecha de creación del horario      |
| idupdater_user_schedule | INT UNSIGNED NOT NULL                                          | ID del usuario que actualizó       |
| updatedate_schedule     | DATETIME DEFAULT CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP | Fecha de actualización             |
