# test_grpc_hnishi
This is a tutorial of gRPC.

## Workflow

on Anaonda environment

- install grpcio-tools

```bash
conda install -c anaconda grpcio-tools
# or you can pip
# pip install grpcio-tools
```

- generate scripts

```bash
python codegen.py
```

- start server and client

```bash
python sample_server.py
# open another console
python sample_client.py
# put your name on this console
```

## Reference

PythonでgRPCで双方向通信を試す。
@ike_dai
2018年10月30日に投稿

https://qiita.com/ike_dai/items/1a28f6a42c4a0d3a49d0
