# docker-laravel-vue
- **nginx** - `:80`
- **mysql** - `:3306`
- **php** - `:9000`
- **redis** - `:6379`
- **mailhog** - `:8025` 

## Run docker
```bash
docker-compose up -d --build site
 ```

## Using BrowserSync

```bash
docker-compose run --rm --service-ports npm run watch
```
