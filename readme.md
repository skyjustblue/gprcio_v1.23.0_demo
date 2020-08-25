pip3 install grpcio==1.23.0 grpcio-tools==1.23.0 protobuf==3.9.1

PS E:\web\grpc_demo>  python3 -m grpc_tools.protoc -I. --python_out=. --grpc_python_out=. ./helloworld.proto

python3 server.py

python3 client.py