# terraserv
Docker compose file to ease setup with ryansheehan/terraria 

Before running `docker-compose up -d` :

```bash
docker-compose pull
docker run -it -p 7777:7777 --rm -v $PWD/terraria/world:/root/.local/share/Terraria/Worlds ryshe/terraria:tshock-latest
```

