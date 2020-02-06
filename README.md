# Randomized_benchmarking
Randomized benchmarking of quantum error channels

The goal of this code is to get a better grasp at randomized benchmarking (RB), a state-of-the art way of characterizing 
the digital noise of a quantum computer. In the simplest case, a quantum circuit is composed of successive unitary gates that
act on a single qubit. However, interaction with the environment can also act in an unwanted way on the qubit (this is what
we call the "noise"). Quite naturally we therefore wish to characterize such noise and many methods have been proposed. To our
knowledge, RB seems to be the most pertinent. 

Kisqit proposes a notebook where one can manipulate the parameters of RB, but trying to dig through the details of the code 
becomes quite difficult. Here we propose a construction from scratch, using classical libraries from Python and only showing
key aspects.

The code is definitely not perfect and details are missing, but I will try to make the notebook as readable as possible.


Feel free to add or optimize the code !

