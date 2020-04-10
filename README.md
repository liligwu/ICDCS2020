# ICDCS2020_CAA_Classification

This dataset contains the state transition sequences of the nodes of Net-A and Net-B in the experiments of the paper Classification of Channel Access Attacks in Wireless Networks: A Deep Learning Approach.

The folders Net_A and Net_B contain the data of nodes of Net-A and B respectively.

The numbers of the nodes are in the file names. NOTE: The indices of nodes in the file name is one smaller than in the paper, because the node index starts with zero in the simulator. E.g. the corresponding file of Net-B node #12 in the paper is /data/Net_B/net-b_node_11_data_[0-1-5-6-7-8].pickle.

Each pickle file contains "train", "val", and "test" keywords; they include "data" and "label" of training, validation, and test dataset.

The training set has 51840 state transition sequences and their labels (attack scenarios in TABLE I of the paper). Validation and test set have 6480 samples respectively. The partition of the "train", "val", and "test" is described in Section VI-A of the paper.

Each sample is the state transition sequence of 10ms of the nodes, i.e., 500 states.
