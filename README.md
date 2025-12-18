DS-matrix_multiplication
This project performs distributed matrix multiplication using two different virtual machines (VMs). They have different IP addresses. One VM runs the master.py file and the other VM (a clone) runs worker.py.

How it works:

Master: Generates matrices, splits the work, computes part locally, and sends the rest to the worker.
Worker: Receives matrix rows, multiplies them, and sends the result back.
How to run:

First on the worker VM, run python3 worker.py
Then on the master VM, run python3 master.py
Make sure both VMs use the same port.
