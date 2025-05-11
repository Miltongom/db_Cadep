| Campo                               | Tipo de dato                                                   | Traducción español                      |
| ----------------------------------- | -------------------------------------------------------------- | --------------------------------------- |
| id_structureappointment             | INT UNSIGNED AUTO_INCREMENT PRIMARY KEY                        | ID de la estructura de cita             |
| id_appointment_structureappointment | INT UNSIGNED NOT NULL                                          | ID de la cita                           |
| id_user_structureappointment        | INT UNSIGNED NOT NULL                                          | ID del usuario (empleado/terapeuta)     |
| id_patient_structureappointment     | INT UNSIGNED NOT NULL                                          | ID del paciente                         |
| id_schedule_structureappointment    | INT UNSIGNED NOT NULL                                          | ID del horario asignado                 |
| id_week_structureappointment        | INT UNSIGNED NOT NULL                                          | ID de la semana correspondiente         |
| active_structureappointment         | BOOLEAN NOT NULL DEFAULT 1                                     | Estado activo/inactivo de la estructura |
| idcreate_user_structureappointment  | INT UNSIGNED                                                   | ID del usuario que creó                 |
| createdate_structureappointment     | DATETIME DEFAULT CURRENT_TIMESTAMP                             | Fecha de creación                       |
| idupdater_user_structureappointment | INT UNSIGNED NOT NULL                                          | ID del usuario que actualizó            |
| updatedate_structureappointment     | DATETIME DEFAULT CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP | Fecha de actualización                  |
