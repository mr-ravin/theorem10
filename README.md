# Theorem10 [A theorem in Mathematics]
This repository includes a computer program for a mathematical theorem paper titled "A theorem on numbers of the form 10^x"

#### Author: [Ravin Kumar](https://mr-ravin.github.io)

#### Publication Details:

- #### Elsevier-SSRN, Computation Theory eJournal 11th Oct'2019: [https://ssrn.com/abstract=3460506](https://ssrn.com/abstract=3460506)

- #### Preprint OSF.IO: [https://osf.io/ku45y/](https://osf.io/ku45y/)

- #### Doi: https://doi.org/10.31219/osf.io/ku45y

### Demonstration

```python
import theorem10
x=4 # we took x=4 as an example, for number of form 10^x 
num_bits=theorem10.get_bits(x)  # here, we pass x to get_bits function, and it returns number of bits 
                                # that will always represent total numbers greater than 10^x
```

### PyPi package installation

```
pip3 install theorem10
```
##### Note: This computer program is made available free to use. Please use this code at your own risk.
