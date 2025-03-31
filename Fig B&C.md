![parameters change cnn](https://github.com/user-attachments/assets/89723aee-83f0-4f3f-aea7-d74e6ab1ee35)

**Figure B. Variation in parameters throughout the training process.** The family of CNN models are trained on the non-IID mini-CIFAR-10 dataset using gradient descent. Each global round consists of $\tau=5$ local rounds. $\eta_0 = 0.001, \sigma_W=1.5, \sigma_b = 0.1$.  

![Loss_cnn+sgd+cifar10](https://github.com/user-attachments/assets/897d25ae-7368-49f8-b158-1f360cd78a35) ![Acc_cnn+sgd+cifar10](https://github.com/user-attachments/assets/2dd937d9-0dda-49dc-943c-c3aa6a7b19d7)

**Figure C. Test loss and accuracy of FedAvg and centralized learning for CNN32 trained on the non-IID CIFAR-10 dataset.** $\eta_0 = 0.001$, $\sigma_{W} = 1.5$, $\sigma_{b}=0.1$. SGD is employed for both centralized learning and FedAvg. Each global round of FedAvg consists of $\tau = 5$ SGD iterations.
