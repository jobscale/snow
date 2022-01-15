# Snow is beautiful

## CodePen
```
https://codepen.io/yuanchuan/pen/dyPXRXB
```

## Run
```
npm i -g serve
npm start
```

## Container
```
{
  docker build . -t local/snow
  docker run --rm --name snow -p 3000:80 -it local/snow
}
xdg-open http://127.0.0.1:3000
```
