
| Campo                  | Tipo de dato                         | Traducción español                   |
|------------------------|--------------------------------------|--------------------------------------|
| id_branch              | INT UNSIGNED AUTO_INCREMENT PRIMARY KEY | ID de la sede                    |
| name_branch            | VARCHAR(50)                          | Nombre de la sede                    |
| phone_branch           | VARCHAR(25)                          | Teléfono de la sede                  |
| id_municipality_branch | INT UNSIGNED                         | ID del municipio                     |
| id_department_branch   | INT UNSIGNED                         | ID del departamento                  |
| id_state_branch        | BIGINT UNSIGNED                      | ID del estado                        |
| idcreate_user_branch   | INT UNSIGNED                         | ID del usuario que creó              |
| createdate_branch      | DATETIME DEFAULT CURRENT_TIMESTAMP   | Fecha de creación                    |
| idupdater_user_branch  | INT UNSIGNED NOT NULL                | ID del usuario que actualizó         |
| updatedate_branch      | DATETIME DEFAULT CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP | Fecha de actualización |
