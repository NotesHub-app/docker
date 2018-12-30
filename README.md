# NotesHub (docker-compose)

## Установка и запуск

```sh
mkdir -p /opt/noteshub && cd "$_"
git clone https://github.com/NotesHub-app/docker .

# <<< Настроить server.env по примеру server.env.example >>>

docker-compose up --build
``` 
