## Projektio

## Running
### Cloning <br/>
```
git clone https://github.com/stannisl/projektio.git
cd projektio
git submodule update --init --recursive
```

### Building Docker Images
Requirements: docker.

Backend image
```
docker build -t projectio-backend ./backend
```
Frontend image
```
# To do
```

### Running Docker Images
Running Backend image at port 8080
```
docker run -p 8080:8080 projektio-backend
```

Running Frontend Image
```
# To do
```
## Tests

### Backend

Postman коллекция в ./external_tests/backend/

### Frontend

Пока нету

## Developing Instruction

Хочешь получить новейший репозиторий?

```
git pull origin main
git submodule sync
git submodule update --remote
```