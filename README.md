# Una manera rapida de probar el servidor de REDIS

`npm install --global redis-cli`

`npx redis-cli -u redis://:{password}@{host}:{port} ping`

`npx redis-cli -u redis://:PasswordSecreto1111!@127.0.0.1:6379 ping`

Deberia retornar `PONG`