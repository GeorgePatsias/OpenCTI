# 🧬OpenCTI

Custom project with free connectors using the docker-compose stack.

## 🏭 Deployment

```bash
docker-compose up -d
```
#### Check container logs
```bash
docker-compose logs --tail=200 -f
```
## ⚙️ Configurations
All configurations and API keys for the connectors are under ```.env```

#### Additional connectors can be found here [https://github.com/OpenCTI-Platform/connectors](https://github.com/OpenCTI-Platform/connectors)

## 🔮 Usage
After deployment visit ```http://opencti:8080``` for the OpenCTI page.

## 📃 License
[MIT](https://choosealicense.com/licenses/mit/)
