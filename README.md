# SCRBM

## This code is for the Sequence Classification Restricted Boltzmann Machine

Prerequisites:

+ Python 3.5+

+ Tensorflow 1.8+

+ Scikitlearn 0.20+

Run code:

python orc_example.py <cell> <learning rate> <max iter> <optimiser> <objective func>

where
+ cell: [RNN, GRU, LSTM, AE, AESoft, AELSTM, DRBM, RDRBM,LSTMDRBM,LSTMDRBMSoft]
+ learning rate
+ max iter: maximum iteration
+ optimiser: [sgd, adam, rmsprop, nadam, adadelta, adagrad]
+ objective func: objective functions (xen: cross-entropy, llh: (negative) log-likelihood)
