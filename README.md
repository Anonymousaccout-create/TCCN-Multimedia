This is a multimedia material for a paper titled "A Novel Tensor Causal Convolution Network Model for Highly-Accurate Representation to Spatio-Temporal Data” including the dataset". It contains the code for the TCCN model and the ten datasets used in this paper.

The file TCCN_DATA\D{number}\D{number}.txt contains one of the datasets used in the paper. Each row consists of four numerical values in the format (i::j::k::value), where (i, j, k) denotes the index in a third-order tensor, and value indicates the corresponding entry at that index.

The file scr\TCCN, scr\InitTensor, and scr\TensorTuple contain the implementation of the TCCN model, and they are written in Java. It can be executed on any machine with a Java Development Kit (JDK) environment installed.

Before running the TCCN model, the file TCCN_DATA\D{number}\D{number}.txt must be split into training, validation, and test sets.
