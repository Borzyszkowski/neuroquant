<p align="center"><img src="http://i.imgur.com/fcot8Jw.png" width="800" align="middle"></p>

Implementation of a Topological Quantum Processor on [Intel Loihi chip](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8259423&tag=1), a dedicated neuromorphic hardware for training and inference of Spiking Neural Networks.


Built using : https://www.nengo.ai/nengo-loihi/

### How to run?
>~~~~
>pip install -r requirements.txt
>~~~~

To execute code on the remote Loihi Superhost refer to Intel Labs for an access and configure your machine using the following [instruction](https://www.nengo.ai/nengo-loihi/installation.html) and add `SLURM=1` to the command below. Otherwise, the project will be executed by default in a simulation mode.

>~~~~
>python Neuromorphic_TQP.py
>~~~~
