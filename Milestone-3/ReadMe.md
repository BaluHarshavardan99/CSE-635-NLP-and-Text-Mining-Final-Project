This repository conatins code for the final course project - "Faithful Benchmark for Information-Seeking Dialogue - Fact Hallucinations Detection and Prevention" and detailed instructions to run the code 

Instructions to run the code:
1) For task-1: "python task1.py" - it will train and test the model. And after training, it will save the generated model as task1_model.pth. If we want to just test the model, we can comment out trainer.fit and torch.save lines from the code.
2) For task-2: BEGIN and VRM Classification: "python task2.py" - it will train and test the model. And after training, it will save the generated model as task21_model.pth and task22_model.pth respectively. If we want to just test the model, we can comment out trainer.fit and torch.save lines from the code.
3) For task-3: "python task3.py" - we need to run task-1 before we run task-3 so that the task1_model.pth is genrated which will then be used to classify whtehr the geneated responses are hallucinated or not.
