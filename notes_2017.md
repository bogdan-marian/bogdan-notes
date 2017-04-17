## docker
pull carnd-term1-starter-kit immage
```
docker pull udacity/carnd-term1-starter-kit
```

start carnd-term1-starter-kit and share the current folder as a volume using 'pwd'
```
docker run -it --rm -p 8888:8888 -v `pwd`:/src udacity/carnd-term1-starter-kit
```

Anaconda and jupyter on windows
```
activate carnd-term1
jupyter notebook
```
