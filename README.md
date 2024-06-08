<a href="https://www.cqtech.org/">
    <img align="middle" src="logos/logo blue+blue.png" width="25%"/>
</a>
<a href="https://www.univ-setif.dz/">
    <img align="right" src="logos/University-Ferhat-Abbas.png" width="25%"/>
</a>

# Quantum Key Distribution Workshop | CQTraining-2
## Ferhat Abbas Sétif-1 University, June 2024
<hr>
Welcome to the second edition of the CQTraining workshop! We are excited to have you join us at the University of Sétif 1 on June 10th, 2024. This workshop is designed to review and deepen your knowledge of Quantum Key Distribution(QKD).
## Installation

To ensure you have all the necessary tools and packages installed, please follow the instructions below:

### Using Conda
To create the environment with all required dependencies, run:
```bash
conda env create -f cqtr2.yml
```

### Directly from PyPi
Alternatively, you can install the necessary packages directly using pip:

```bash
pip install qiskit[visualization] qiskit-aer qiskit-ibm-runtime --upgrade
```

### Check Installation
Check that you have everything correctly installed by running:
```bash
python -c "import qiskit; import qiskit_aer; import qiskit_ibm_runtime; print(qiskit.__version__); print(qiskit_aer.__version__); print(qiskit_ibm_runtime.__version__)"
``` 

You should get an output that ressembles (with potentially slighly different versions):
```
1.1.0
0.14.2
0.23.0
```
