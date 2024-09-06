### cmd
```
npm init
npm install express
rm -rf node_modules

docker build -t lexnetix-test-image .
docker run -it -p 3000:3000 --name lexnetix-test-container lexnetix-test-image

```
![Screenshot helloworld](./assets/imgs/Screenshot.png)
