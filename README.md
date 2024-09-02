### Prerequisites

1. Docker
2. [Taskfile](https://taskfile.dev/)
3. Python 3.11+ for development. The FastAPI project was initiated with Python 3.12.5

### Task Commands

See [Taskfile.yml](./Taskfile.yml)

Start Docker Compose in detached mode

```shell
task up
```

Stop and remove Docker Compose containers

```shell
task down
```

View Docker Compose logs in real-time

```shell
task logs
```

View FastAPI logs in real-time

```shell
task logs:api
```

View PostgresSQL logs in real-time

```shell
task logs:db
```