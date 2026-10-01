# Sistema MediSalud

Sistema de gestión para una empresa de servicios médicos.

## Módulos principales

- Gestión de usuarios
- Gestión de pacientes
- Gestión de médicos
- Gestión de especialidades
- Gestión de citas
- Historias clínicas
- Consultas médicas
- Recetas
- Medicamentos
- Pagos
- Reportes

## Entidades principales

- USUARIO
- PACIENTE
- MEDICO
- ESPECIALIDAD
- CITA
- HISTORIA_CLINICA
- CONSULTA
- RECETA
- MEDICAMENTO
- PAGO

## Relaciones principales

Un paciente puede tener muchas citas.
Un médico puede atender muchas citas.
Un paciente posee una historia clínica.
Una cita puede generar una consulta.
Una consulta puede generar recetas.
Una receta contiene medicamentos.
Una cita puede generar un pago.
