# Deep Surveillance

Surveillance systems, mainly composed of cameras, are today widespread in both indoor and outdoor environments.

- Video surveillance involves the act of observing a scene or scenes and looking for specific behaviors that are improper or that may indicate the emergence or existence of improper behavior.

- Common uses of video surveillance include observing the public at the entry to sports events, public transportation (train platforms, airports, etc.), and around the perimeter of secure facilities, especially those that are directly bounded by community spaces.

In this project, convolutional neural networks using image recognition and their combination with recurrent neural networks temporal information is extracted using which an intelligent surveillance system is made.The LSTM Encoder-Decoder framework is used to learn representation of video sequences and applied for detect abnormal event in complex environment.The abnormal events are identified by computing the reconstruction loss using Euclidean distance between original and reconstructed batch.

Our training dataset contains 16 training and 21 testing video clips. The videos are captured in CUHK campus avenue with 30652 (15328 training, 15324 testing) frames in total.

This dataset accompanies paper "Abnormal Event Detection at 150 FPS in Matlab, Cewu Lu, Jianping Shi, Jiaya Jia, International Conference on Computer Vision, (ICCV), 2013".

The training videos capture normal situations. Testing videos include both normal and abnormal events. Three abnormal activities as follows:

- Strange action	
- Wrong direction	
- Abnormal object