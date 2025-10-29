## Machine learning
For this project, simulated data from [openml](https://www.openml.org/search?type=data&sort=runs&id=4532&status=active) is considered.
The data for each event contains 28 kinematical features and a binary tag, denoting if a Higgs boson (an elementary particle) was involved or not. \
First, the data is examined. It is cleaned, summarized and preprocessed. 
Afterwards, a deep neural network is constructed, trained and tested on the data. 
Finally, the robustness of the network is tested using adversarial samples.
