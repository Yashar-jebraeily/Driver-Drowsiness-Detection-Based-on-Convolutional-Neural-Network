Driver Drowsiness Detection Based on Convolutional Neural Network Architecture Optimization Using Genetic Algorithm
this code is the first step of the algorithm used in the paper 
you can train the model and use transfer learning or finetune on your own dataset, i used Drowsy Detection Dataset that was collected by myself and it is available on my Kaggle account.10.34740/kaggle/dsv/8311245
please don't forget to cite our paper:
@ARTICLE{10479511,

  author={Jebraeily, Yashar and Sharafi, Yousef and Teshnehlab, Mohammad},

  journal={IEEE Access}, 

  title={Driver Drowsiness Detection Based on Convolutional Neural Network Architecture Optimization Using Genetic Algorithm}, 

  year={2024},

  volume={12},

  number={},

  pages={45709-45726},

  keywords={Vehicles;Brain modeling;Accidents;Convolutional neural networks;Feature extraction;Fatigue;Genetic algorithms;Accidents;Vehicle driving;Vehicle safety;Driver drowsiness detection;convolutional neural network (CNN);neural architecture search;genetic algorithm},

  doi={10.1109/ACCESS.2024.3381999}}




Designing and selecting an appropriate structure for a convolutional neural network always comes with challenges that must be carefully managed. Several influential factors in the design of CNNs can directly impact their performance, including the number of layers, filter sizes, the number of neurons in each layer, the amount of training data, and hardware settings. Inappropriate choices for these factors can lead to overfitting, reduced performance, or other issues. In recent research, various methods have been used to obtain the structure of convolutional neural networks, one of which is evolutionary optimization algorithms. In this study, as depicted in Figure 6, the genetic optimization algorithm has been utilized to obtain an appropriate structure for convolutional neural networks. 

   
![shara6-3381999-large](https://github.com/Yashar-jebraeily/Driver-Drowsiness-Detection-Based-on-Convolutional-Neural-Network/assets/165891529/ebc20ba8-a376-46a4-8928-41cbd3d64308)
                                         Figure6



To determine the appropriate number of layers and the structure of a convolutional neural network (CNN) for detecting driver drowsiness, we first obtain the optimal CNN structure using a genetic algorithm in an evolutionary approach based on the FER-2013 dataset. The FER-2013 dataset consists of 35887 images categorized into six classes. To better understand the optimization process in the genetic algorithm for obtaining the optimal CNN structure, as depicted in Figure 7, a chromosome in the genetic algorithm is defined as the parameters of a convolutional layer and a fully connected layer. As seen in Figure 7, these parameters include the number of filters in the convolutional layer (F1), kernel size (K), dropout rate (D1), the activation function of the convolutional layer (A1), the number of neurons in the dense layer (N), the activation function of the dense layer (A2), dropout rate (D2), and the number of epochs for network training (Ep). Together, these parameters form the chromosome and the genetic algorithm is used to optimize them. A CNN with one convolutional layer and one fully connected layer is initially designed based on the FER-2013 dataset using the genetic algorithm to obtain its optimal structure. Subsequently, as shown in Figure 8, while keeping the structure of the first convolutional layer fixed, a second convolutional layer is added along with another fully connected layer. Again, the optimal structure is determined using the genetic algorithm with the FER-2013 dataset. As illustrated in Figure 8, this process continues until no improvement in the performance of the CNN is observed by adding a convolutional layer. 



![shara7-3381999-small](https://github.com/Yashar-jebraeily/Driver-Drowsiness-Detection-Based-on-Convolutional-Neural-Network/assets/165891529/bb3844d1-8f27-4420-ab0f-996b6e896264)
                              Figure7







   

  ![Graphical-abstract](https://github.com/Yashar-jebraeily/Driver-Drowsiness-Detection-Based-on-Convolutional-Neural-Network/assets/165891529/679db7a7-42bd-4bc7-bd85-5f4bc44f06a7) 
                                Figure8
  
