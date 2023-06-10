# Credit-Card-Fraud-Detection

### Abstract
Due to a rapid advancement in the electronic commerce technology, the use of credit cards has dramatically increased. As credit card becomes the most popular mode of payment for both online as well as regular purchase, cases of fraud associated with it are also rising. This body of work models the sequence of operations in credit card transaction processing using a hidden Markov model (HMM) and show how it can be used for the detection of frauds. An HMM is initially trained with the normal behavior of a cardholder. If an incoming credit card transaction is not accepted by the trained HMM with sufficiently high probability, it is considered to be fraudulent. At the same time, we try to ensure that genuine transactions are not rejected. This project is an implementation of the HMM technique.

#### To use this work on your researches or projects you need:
* Python 3.7.0
* Python packages:
	* hidden_markov
	* numpy
	* pandas
	* scikit_learn

#

#### To install Python:
_First, check if you already have it installed or not_.
~~~~
python3 --version
~~~~
_If you don't have python 3 in your computer you can use the code below_:
~~~~
sudo apt-get update
sudo apt-get install python3
~~~~
#

#### To install packages via pip install:
~~~~
sudo pip3 install hidden_markov numpy pandas scikit_learn
~~~~
_If you haven't installed pip, you can use the codes below in your terminal_:
~~~~
sudo apt-get update
sudo apt install python3-pip
~~~~
_You should check and update your pip_:
~~~~
pip3 install --upgrade pip
~~~~
#
