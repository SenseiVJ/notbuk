# notbuk:::
A manera de ejercicio fundacional, y con el objeto de aprender sobre el uso del framework, se construirá una aplicación web para el control de clases para una escuela rural, basada en la revisión periódica del cuaderno. Se entiende que el cuaderno es el instrumento en el que el docente puede revisar el avance general del estudiante, tanto en las actividades particulares asignadas, como del desarrollo del proceso de lecto-escritura

### ¿Qué gemas voy a usar?
- Device (auth)
- Sidekiq (bg job queuing)
- Pagy (pagination)
- was-sdk-s3 (active storage)
- image_process (active storage)
- inline_svg
- redis
- sendgrid-ruby
- name_of_person
- omniAuth (if you don’t have google for run suite, it’s ok. If you have a google account, then use it, idiot)
- simpleform

### Punrto de partida
Como punto de partida estoy usando el [kickoff-tailwind](https://github.com/justalever/kickoff_tailwind) de [Andy Leverenz](https://github.com/justalever), que trae incorporado devise, friendly_id, sidekiq, y name_of_person. Este template está basado a su vez en [Jumpstart](https://github.com/excid3/jumpstart) de [Chris Oliver](https://twitter.com/excid3/). Por lo que se da el crédito correspondiente a todos ellos.
