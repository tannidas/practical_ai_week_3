# practical_ai_week_3
Week 3 Assignment

**Task-1**:


Inside the "Centralized_to_Federated" folder run "client.py" in one terminal and run "server.py" in different terminal. This task is for "CIFAR-10 Dataset".

**Task-2**:

Inside the "Femnist" folder run "client.py" in one terminal and run "server.py" in different terminal. This task is for "FEMNIST Dataset". Test was done for num_of_rounds = 100 and epochs = 30. 

**Result**:

Inside the "Femnist folder":

server.out --> output from server.py
client.out --> output from client.py


Notes:

1. Following arguments inside the **flower.server.strategy.FedAvg** function have to be changed according to the number of clients

   min_available_clients = 1,
   min_fit_clients = 1, 
   min_evaluate_clients = 1

