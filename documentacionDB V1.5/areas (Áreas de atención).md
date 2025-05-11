
| Campo                 | Tipo de dato                         | Traducción español                  |
|------------------------|--------------------------------------|-------------------------------------|
| id_area                | INT UNSIGNED AUTO_INCREMENT PRIMARY KEY | ID del área                     |
| name_area              | VARCHAR(30)                          | Nombre del área (Ej. Psicología)    |
| description_area       | TEXT                                 | Descripción detallada del área      |
| duration_area          | TIME                                 | Duración por sesión (Ej. 00:30:00)  |
| id_state_area          | INT UNSIGNED                         | ID del estado del área              |
| idcreate_user_area     | INT UNSIGNED                         | ID del usuario que la creó          |
| createdate_area        | DATETIME DEFAULT CURRENT_TIMESTAMP   | Fecha de creación                   |
| idupdater_user_area    | INT UNSIGNED NOT NULL                | ID del usuario que la actualizó     |
| updatedate_area        | DATETIME DEFAULT CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP | Fecha de actualización |
