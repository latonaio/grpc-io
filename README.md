# grpc-io
grpc-ioは、主にエッジコンピューティング環境において、gRPCをセットアップするためのレポジトリです。  

## 動作環境

* OS: Linux OS  
* CPU: ARM / AMD / Intel  

## How to Install
[python-base-images](https://github.com/latonaio/python-base-images)のsetup.pyに必要に応じてバージョンを指定して、使用してください。

```
setup(
    name="aion",
    version="0.0.1",
    author="XXXXXXXXXXXXXXXX",
    author_email="XXXXXXXXXXXXXXX",
    packages=find_packages(),
    install_requires=[
        "python-dateutil",
        "protobuf>=3.11.3",
        "grpcio",
        "mysqlclient",
        "pymongo",
        "retry",
    ],
)
```

## go.mod に組み込む方法
[grpc-golang](https://github.com/latonaio/grpc-golang) を参照してください。