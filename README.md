# HCRN
PyTorch implementation of Hourglass-shaped Convolutional Recurrent Network (HCRN) described in our paper "Towards Modeling Auditory Restoration in Noisy Environments"

# Requirements
Pytorch＝0.4.1  
resampy  
soundfile   
pysepq  
librosa  
pystoi  
lera

# Data Preparation
Use the scripts in preprocess to process the WSJ, ESC-50 and Audioset datasets. Please modify the dataset paths in the scripts.

# Train and test
For training:  python3 Train.py

For testing:  python3 Test.py

Please modify specify processed dataset paths in config.yaml.

# Contact
If you have any questions, please feel free to contact me at huangyating2016@ia.ac.cn

# Citations
If you find this repo helpful, please consider citing:    
```
@inproceedings{huang2021towards,    
  title={Towards Modeling Auditory Restoration in Noisy Environments},    
  author={Huang, Yating and Hao, Yunzhe and Xu, Jiaming and Xu, Bo},    
  booktitle={In Proceedings of the 33th International Joint Conference on Neural Network (IJCNN)},    
  year={2021},    
  organization={IEEE}    
}  
```
