<h1> 2022 Spring/Summer [Fundamentals of Machine Learning]</h1>

---



<h2> HW2_CNN with MNIST Data_2019313561 Min Jae Jo(조민재)</h2>

<h3><strong>How to Execute: Please just click the cells in order!</strong></h3>

<h3> Explanation about model and brief composition of codes</h3>

<ol> 1. I used .ipynb file extension and seperated cells. Before each cells, there is inline markdowns, implicating the total cell's intention.</ol>

<ol> 2. In one cell, there are some comments written, to make clear among commands both to me and TAs.</ol>

<ol> 3. First 3 cells are for set-ups. 1) Importing pytorch, numpy, matplotlib and tensorflow 2) Checking device-I use cpu+gpu(M1 chip), so I had to add {if-else} to set as using CPU. If you have GPU(CUDA), I made it to use that. 3) Normalization of data 4) Data loaded </ol>

<ol> 4. [Defining Model 01~03.] :
 These 3 cells are defining 3 models as required in assignment sheet. I defined "forward" sequences as in a class.</ol>

<ol> 5. Train Setup: epoch and minibatch sized were initialized as with fixed value as required in assignment sheet.</ol>

<ol> 6. From Here, I splited cells for train-test per model and same for model 1 and 2. But for model 3(ResNet), learning rate decays for 2 times in 30 epochs total. All the results per epoch and minibatch with loss will be printed and when each epoch is finished, test result will be printed.<strong>All the models will be saved as pytorch file.</strong> </ol> 

<ol> 7. After 30 epochs, 2 figures will be plotted.(These will be First is the "Loss per epoch" and latter is the "Test Accuracy". To check all the data, you could check:

​	  e.g. For model 1: model01_loss, model01_acc = loss per epoch , test accuracy, respectively. </ol>

<ol> 8. After all the train and test, the results will appear as a table and this will also be saved. (I used Matplotlib.table())</ol>

<ol> <strong>9. When loading pytorch file, please use the command below.</strong><br>
  <code>model01= torch.load(./model1.pt)</code> <br>
  <code>model02= torch.load(./model2.pt)</code> <br>
  <code>model03= torch.load(./model3.pt)</code></ol>

 <h4> Thank you for reading  </h4>

