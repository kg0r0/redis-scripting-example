# redis-scripting-example 

# Usage
```
$ docker run -d redis
$ docker ps -a 
$ docker cp hello.lua [CONTAINER ID]:/data 
$ docker exec -it [CONTAINER ID] sh 
# redis-cli EVAL "$(cat hello.lua)" 0
"Hello, world!"
```
# References
https://gist.github.com/bpo/5157860
