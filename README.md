Download Link: https://assignmentchef.com/product/solved-cs260-machine-learning-algorithms
<br>
<table style="height: 110px;" width="902">

 <tbody>

  <tr>

   <td width="524"></td>

   <td width="96"> </td>

  </tr>

 </tbody>

</table>

I<strong>Problem Description.</strong>

In this homework, you are asked to implement and solve linear Logistic Regression model and Linear SVM model (without regularization term) on MNIST dataset. In this task, you only need to perform binary classification on digit 0 and 1. Details of these models could be found in lecture 2 slides. We provide a skeleton code for data loading and iterations of training data. You are asked to implement the rest of training in Pytorch code. You are required to optimize the model by using SGD and Momentum methods. Detailed submission requirements are written in the final section.

<h1>Resources</h1>

You can follow the setup instructions at <a href="https://pytorch.org/get-started/locally/">https://pytorch.org/get-started/locally/</a><a href="https://pytorch.org/get-started/locally/">.</a>

A useful tutorial on learning pytorch by examples at <a href="https://pytorch.org/tutorials/beginner/pytorch_with_examples.html">https://pytorch.org/tutorials/beginner/pytorch_ </a><a href="https://pytorch.org/tutorials/beginner/pytorch_with_examples.html">with_examples.html</a><a href="https://pytorch.org/tutorials/beginner/pytorch_with_examples.html">.</a>

More illustrations of different optimizers could be found here: <a href="http://ruder.io/optimizing-gradient-descent/">http://ruder.io/optimizing-gradient-descent/</a><a href="http://ruder.io/optimizing-gradient-descent/">.</a>

<h1>Data</h1>

We use MNIST digit classification dataset. Pytorch/torchvision has provide a useful dataloader to automatically download and load the data into batches. In this homework, we need two class, digit 0 and digit 1, for binary classification. We have written the data loader for you as follow. You can find it in the attached file.





