# deep_learning

**Task 1:**
create a NumPy Program which applies the gradient descent algorithm
to minimise the given error function. Initialise the algorithm with the following values: 
𝑟 = 8, 𝑠 = 1, 𝑡 = 4.
𝑦 = 𝑓(𝑟, 𝑠, 𝑡) = (𝑟 − 7)3 + (4𝑠 − 20)2 + (2𝑠 − 10)2 + (4 𝑡2/𝑡− 12)2
𝐸 = 𝑦2
Hence find the values of 𝑢, 𝑣 & 𝑤 where the function (and thus the Error) is equal to zero

**Task 2:**
Using PyTorch without helper functions (without using torch.nn or torch.optim), calculate
the values of 𝑎 & 𝑏 that best fit the model 𝑓(𝑥) using the gradient descent algorithms with
the following:
𝑓(𝑥) = 𝑒−𝑎𝑥 + 2𝑎𝑥 + 𝑏
𝑋 and 𝑦0 values are given.

**Task 3 – Neural Networks**
**Part 1:**
The dataset contains images of MRI scans from patients diagnosed with Alzheimer's, separated into four classes; 
0: Mild Demented, 1: Moderate Demented, 2:NonDemented, 3: Very Mild Demented.
Using the datasets provided:
1. Create two basic* Neural Networks. The first should be a Simple Neural Network.
The second, a Convolutional Neural Network.
2. Create two improved* Neural Networks. The first should be a Simple Neural
Network. The second, a Convolutional Neural Network.
You should then conduct a comparative analysis of the two improved models, discussing
the changes you made and how they’ve improved on the basic models.
• A “basic” neural network is “A functional neural network, that contains the
necessary features to constitute as that type of neural network, however may
not produce the best results.”.
• An “improved” neural network is “A neural network where changes/adaptations
have been made to the model structure, or training algorithm, to improve the
results delivered by the model.”.
**Part 2:**
1. Using only your optimized Convolutional Neural Network you’ve created. Test a
learning rate of 0.00000001 vs a learning rate of 10 (using the SGD optimizer from
the learning material & keeping all other parameters in your model the same).
Discuss what happens when these values are used and why. Furthermore, discuss in
detail, the advantages and disadvantages of a higher & lower learning rate, and its
impact.
2. Secondly, discuss in detail, the advantages and disadvantages of a higher & lower
batch size.
