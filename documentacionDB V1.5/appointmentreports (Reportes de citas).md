

| Campo                            | Tipo de dato                                                   | Traducción español                        |
| -------------------------------- | -------------------------------------------------------------- | ----------------------------------------- |
| id_appointmentreport             | INT UNSIGNED AUTO_INCREMENT PRIMARY KEY                        | ID del reporte de cita                    |
| id_archive_appointmentreport     | INT UNSIGNED                                                   | ID del expediente clínico relacionado     |
| id_appointment_appointmentreport | INT UNSIGNED                                                   | ID de la cita asociada                    |
| objective_appointmentreport      | VARCHAR(100)                                                   | Objetivo de la cita (propósito principal) |
| observations_appointmentreport   | TEXT                                                           | Observaciones de la cita                  |
| height_appointmentreport         | DECIMAL(5,2)                                                   | Estatura del paciente                     |
| weight_appointmentreport         | DECIMAL(5,2)                                                   | Peso del paciente                         |
| idcreate_user_appointmentreport  | INT UNSIGNED                                                   | ID del usuario que creó el reporte        |
| createdate_appointmentreport     | DATETIME DEFAULT CURRENT_TIMESTAMP                             | Fecha de creación del reporte             |
| idupdater_user_appointmentreport | INT UNSIGNED NOT NULL                                          | ID del usuario que actualizó el reporte   |
| updatedate_appointmentreport     | DATETIME DEFAULT CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP | Fecha de actualización del reporte        |
