# QMLHEP2023-tasks_rohan
### Completed tasks for Quantum transformer for High Energy Physics Analysis at the LHC

This repository contains the solutions for the given tasks in these links:
- [Task-1](https://github.com/Rohan29032001/QMLHEP2023-tasks_rohan/blob/master/Task_1_ml4sci.ipynb)
- [Task-2](https://github.com/Rohan29032001/QMLHEP2023-tasks_rohan/blob/master/Task_2_QMLHEP.ipynb)
- [Task-3](https://github.com/Rohan29032001/QMLHEP2023-tasks_rohan/blob/master/Task%203%20Open%20Task.ipynb)
- [Task-8](https://github.com/Rohan29032001/QMLHEP2023-tasks_rohan/blob/master/Task_8_QMLHEP.ipynb)

Note: The idea for the Quantum Vision Transformer exists at the bottom of the same .ipynb notebook [here](https://github.com/Rohan29032001/QMLHEP2023-tasks_rohan/blob/master/Task_8_QMLHEP.ipynb)

The files named [tf_keras_model](https://github.com/Rohan29032001/QMLHEP2023-tasks_rohan/blob/master/tf_keras_model.py) and [tf_keras_L1](https://github.com/Rohan29032001/QMLHEP2023-tasks_rohan/blob/master/tf_keras_L1.py) are helper files for the Task-2 as they contain the models being implemented there. The directories [GNN_PN](https://github.com/Rohan29032001/QMLHEP2023-tasks_rohan/tree/master/GNN_PN), [GNN_PN_L1](https://github.com/Rohan29032001/QMLHEP2023-tasks_rohan/tree/master/GNN_PN_L1) contain saved weights of these models after training for 100 epochs each.

The directory [ViT60](https://github.com/Rohan29032001/QMLHEP2023-tasks_rohan/tree/master/ViT_60) contains the saved weights for the Vision Transformer trained for 64 epochs (implemented in Task 8).


### Results obtained:
The metrics used here are calculated on the test set. 

- Task 2, ParticleNetliteL1:
    - Dataset: Quark and Gluon jets
    - **Loss**: 0.4428800344467163
    - **Accuracy**:0.8027333617210388
    
    
- Task 2, ParticleNetlite:
    - Dataset: Quark and Gluon jets
    - **Loss**: 0.42622110247612
    - **Accuracy**: 0.8133999705314636

- Task 8, Vision Transformer:
    - Dataset: MNIST
    - **Loss**: 0.07690183073282242
    - **Accuracy**:  0.9825999736785889
    

