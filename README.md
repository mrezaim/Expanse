# EXPANSE: A Deep Continual / Progressive Learning System for Deep Transfer Learning (Submitted to NeurIPS 2022)
A new methodology for deep transfer learning, which opens the possibility of continual deep learning while tackling the catastrophic forgetting dilemma and the overly biased pre-trained model issue.

In this set of experiments we evaluate different aspects of EXPANSE system. The details of experiments and analysis of the results are available in the paper. The following notebooks are created using Google Colaboratory. 

1) EXPANSE_two_steps_training.ipynb<br>
    Evaluates the two-step training using "perfect_digits.png" as a source of perfected data on MNIST datasets.
2) EXPANSE_model_expansion.ipynb<br>
    Evaluates model expansion a long with two-step training on MNIST datasets.
3) EXPANSE_on_MNIST_to_compare_with_top_known_DNN_Model.ipynb<br>
    We applied EXPANSE on an existing best performed DNN model on MNIST to verify if it can improve it.
4) EXPANSE_on_MNIST_using_10_percent_of_first_step_training_data_on_second_step.ipynb<br>
    Evaluates the effect of redcing the amount of using source data mixed with target data in the second step of training on MNIST dataset.
5) EXPANSE_Fashion_MNIST.ipynb<br>
    Evaluates applying EXPANSE on a DNN for Fashion MNIST datasets.
6) EXPANSE_on_Fashion_MNIST_using_10_percent_of_first_step_training_data_on_second_step.ipynb<br>
    Evaluates the effect of redcing the amount of using source data mixed with target data in the second step of training on Fashion MNIST dataset.
