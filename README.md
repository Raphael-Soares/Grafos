# vue-docker

## Project setup

```
npm install
```

### Compiles and hot-reloads for development

```
npm run serve
```

### Compiles and minifies for production

```
npm run build
```

### Lints and fixes files

```
npm run lint
```

### Compila a imagem docker

```
docker build -t lexinode .
```

### executa a imagem docker

```
docker run -it -p 8080:8080 --rm --name dockerize-vuejs-app-1 lexinode
```
