## deploy mongoDB

```shell
docker-compose -f mongoDB.yaml up -d
```

you can view the web page via

http://localhost:8081/

## guide to run project

- Put dataset car_prices.csv at project root directory
- Run preprocess.ipynb first
- Run data_process.ipynb, you can adjust the process of data etl and model in this file

