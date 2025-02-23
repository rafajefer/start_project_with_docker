# todo-list

### Passo a passo

Clone Repositório

```sh
git clone https://github.com/rafajefer/start_project_with_docker.git
```

```sh
cd start_project_with_docker/reactjs
```

### Criando um projeto

```sh
docker compose up -d
```

```sh
docker exec -it reactjs-container npx create-next-app@latest
```

```
✔ What is your project named? … my-app
✔ Would you like to use TypeScript? … No / Yes
✔ Would you like to use ESLint? … No / Yes
✔ Would you like to use Tailwind CSS? … No / Yes
✔ Would you like your code inside a `src/` directory? … No / Yes
✔ Would you like to use App Router? (recommended) … No / Yes
✔ Would you like to use Turbopack for `next dev`? … No / Yes
✔ Would you like to customize the import alias (`@/*` by default)? … No / Yes
Creating a new Next.js app in /app/my-app.

# output example
```

### Comandos docker

Para start o container utilizando o docker composer

```sh
docker compose up -d
```

Acesse o container

```sh
docker exec -it reactjs-container bash
```

### Para encerrar o container

```sh
docker compose down
```
