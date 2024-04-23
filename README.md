## deploy mongoDB

```shell
docker-compose -f mongoDB.yaml up -d
```

you can view the web page via

http://localhost:8081/

## guide to run project

- 并不需要使用上课演示的通过pyspark命令启动一个jupyter server再拉起notebook的形式来运行，直接使用带有pyspark库的python环境即可
- Put dataset car_prices.csv at project root directory
- Run data_process.ipynb

