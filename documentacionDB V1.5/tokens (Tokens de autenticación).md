
| Campo                 | Tipo de dato                          | Traducción español                          |
|------------------------|---------------------------------------|---------------------------------------------|
| id_token               | INT UNSIGNED AUTO_INCREMENT PRIMARY KEY | ID del token                           |
| id_user_token          | INT UNSIGNED NOT NULL                 | ID del usuario propietario del token        |
| token_token            | VARCHAR(255) NOT NULL                 | Valor del token generado                   |
| created_token          | TIMESTAMP DEFAULT CURRENT_TIMESTAMP   | Fecha de creación del token                |
| expires_token          | TIMESTAMP NOT NULL                    | Fecha de expiración del token              |
| active_token           | TINYINT(1) DEFAULT 1                  | Token activo (1) o inactivo (0)             |
| ip_token               | VARCHAR(45) NULL                      | Dirección IP desde donde se generó el token |
| idcreate_user_token    | INT UNSIGNED                          | ID del usuario que creó el registro         |
| idupdater_user_token   | INT UNSIGNED                          | ID del usuario que actualizó el registro    |
