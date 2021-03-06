# Theorem10 [A theorem in Mathematics]
This repository includes a computer program for a mathematical theorem paper titled "A theorem on numbers of the form 10^x"

#### Author: [Ravin Kumar](https://mr-ravin.github.io)

#### Publication: 8th October 2019

#### Publication Link: https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3460506

#### Doi: http://dx.doi.org/10.2139/ssrn.3460506

#### Publication Details:

- #### Elsevier-SSRN, Computation Theory eJournal 11th Oct'2019: [https://ssrn.com/abstract=3460506](https://ssrn.com/abstract=3460506)

#### Cite as:

```
Kumar, Ravin, A Theorem on Numbers of the Form 10^x (September 16, 2019). DOI: 10.31219/osf.io/ku45y,
(2019). Available at SSRN: https://ssrn.com/abstract=3460506 or http://dx.doi.org/10.2139/ssrn.3460506 
```

#### Earlier Preprints:

- Osf.io: [https://osf.io/ku45y/](https://osf.io/ku45y/)

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

```python
Copyright (c) 2019 Ravin Kumar
Website: https://mr-ravin.github.io

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation 
files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, 
modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the 
Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the 
Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE 
WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR 
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, 
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```
