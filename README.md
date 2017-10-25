# docker-shiny-server

```sh
docker run --rm -p 7123:3838 -v $(pwd)/my-shiny-app:/srv/shiny-server/ -v $(pwd)/logs:/var/log/shiny-server fikovnik/shiny-server
```
