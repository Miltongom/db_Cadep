
| Campo                 | Tipo de dato                       | Traducción español           |
|-----------------------|------------------------------------|-------------------------------|
| id_role               | INT UNSIGNED PRIMARY KEY AUTO_INCREMENT | ID del rol             |
| name_role             | VARCHAR(15)                        | Nombre del rol               |
| description_role      | TEXT                               | Descripción del rol          |
| id_state_role         | BIGINT UNSIGNED                    | ID del estado asociado       |
| idcreate_user_role    | INT UNSIGNED                       | ID del usuario que creó       |
| createdate_role       | DATETIME DEFAULT CURRENT_TIMESTAMP | Fecha de creación            |
| idupdater_user_role   | INT UNSIGNED NOT NULL              | ID del usuario que actualizó  |
| updatedate_role       | DATETIME DEFAULT CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP | Fecha de actualización |
