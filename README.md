# deploy the website


in folder``docs``:
```bash
sudo docker build -f Dockerfile -t cyberswatwebpage .
```
then
```bash
sudo docker run -dp 3000:3000 --name=docsify -v $(pwd):/docs cyberswatwebpage
```

# debug the website

```bash
docsify serve docs
```

