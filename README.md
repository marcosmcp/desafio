### Desafio SRE

![Desafio](site/digitando.gif)


### How to Build Local

```bash
docker build -t desafio .
docker run -p 8000:80 -it desafio
```


```bash
docker pull marcosluv/desafio:v0
docker run -p 8000:80 -it marcosluv/desafio:v0
```