## docker
pull carnd-term1-starter-kit immage
```
docker pull udacity/carnd-term1-starter-kit
```

start carnd-term1-starter-kit and share the current folder as a volume using 'pwd'
```
docker run -it --rm -p 8888:8888 -v `pwd`:/src udacity/carnd-term1-starter-kit
```
start bash
```
docker run -it --rm  -v `pwd`:/src udacity/carnd-term1-starter-kit bash
```

Anaconda and jupyter on windows
```
activate carnd-term1
jupyter notebook
```
## run jupyter on amazon cloud
enable port forwording on the local machine with inclooded authentication
```
ssh -f -i "AmazonOhio.pem" ubuntu@ec2-18-221-253-111.us-east-2.compute.amazonaws.com -L 8889:localhost:8889 -N
```

connect
```
ssh -i "AmazonOhio.pem" ubuntu@ec2-18-221-253-111.us-east-2.compute.amazonaws.com

```
start the jupyer notebook and connect as you ould normaly woud
