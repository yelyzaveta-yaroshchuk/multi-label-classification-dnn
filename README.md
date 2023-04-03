# multi-label-classification-dnn

An irrigation machine
We're going to automate the watering of farm parcels by making an intelligent irrigation machine. So classes/labels are not mutually exclusive, you could water all, none or any combination of farm parcels based on the inputs.

An output of your multi-label model could look like this: [0.76 , 0.99 , 0.66 ]. If we round up probabilities higher than 0.5, this observation will be classified as containing all 3 possible labels [1,1,1]. For this particular problem, this would mean watering all 3 parcels in your farm is the right thing to do, according to the network, given the input sensor measurements.

Today we will use DNN and will try to find the best activation function for the dealing with an intelligent irrigation machine problem.

The data contains information from 20 sencorces and 3 parcels, overall 2000 observation.

![image](https://user-images.githubusercontent.com/129201759/229486772-65e12d23-3d90-417b-a4c6-794f2ae61c55.png)

