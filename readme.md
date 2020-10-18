# NLW3 - Rocketseat

Aplicação desenvolvida entre os dias 11/10/2020 ao 18/10/2020.

Trata-se de uma aplicação para busca de orfanatos para visitas. A mesma foi desenvolvida em Typescript, Express, TypeORM, React, React Native, etc...

# Backend

| route      | method | auth | parmas | body                                                                                    |
| ---------- | ------ | ---- | ------ | --------------------------------------------------------------------------------------- |
| orphanages | get    | no   |        |                                                                                         |
| orphanages | get    | no   | id     |                                                                                         |
| orphanages | post   | no   |        | name, latitude, longitude, about, instructions, opening_hours, open_on_weekends, images |
