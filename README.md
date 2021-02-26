# shinyproxy
Docker file and application yml for Shiny Proxy

<h4> Must run the shiny proxy container with these args </h4>

```
sudo docker run -d -v /var/run/docker.sock:/var/run/docker.sock --net shiny_net -p 8080:8080 img_nm
```
