#Documentation
Use futures to call multiple gRPC services and process returned results with
callbacks.

#Install
pip install -r requirements.txt

#Run
python greeter_server.py 50051 3

python greeter_server.py 50052 10

python greeter_client.py
