# Theorem10 [A Theorem on Numbers of the Form 10<sup>x</sup>]
This repository includes a computer program for a mathematical theorem paper titled "A Theorem on Numbers of the Form 10<sup>x</sup>", in Pure Mathematics.

#### Paper Title: A Theorem on Numbers of the Form 10<sup>x</sup>

#### Author: [Ravin Kumar](https://mr-ravin.github.io)

#### Publication: 5<sup>th</sup> October, 2021.

#### Publication Journal: [International Journal of Pure and Applied Mathematics Research](https://www.svedbergopen.com/journals/International-Journal-of-Pure-and-Applied-Mathematics-Research/About-the-Journal/)

#### Publication House: [SvedbergOpen](https://www.svedbergopen.com/)

#### Publication Link: https://www.svedbergopen.com/files/1635526259_(5)_IJPAMR28112020MTN001_(p_55-57).pdf

#### Publication Copy: https://mr-ravin.github.io/mathematician/static/media/A_Theorem_on_Numbers_of_the_Form_10%5Ex.6ce02303.pdf

#### Cite as: 

Ravin Kumar (2021). A Theorem on Numbers of the Form 10X
. International Journal of Pure and
Applied Mathematics Research, 1(1), 55-57. doi: 10.51483/IJPAMR.1.1.2021.55-57.


#### Doi: [10.51483/IJPAMR.1.1.2021.55-57](https://doi.org/10.51483/IJPAMR.1.1.2021.55-57)

#### Earlier Preprints:

- OSF.io: [https://osf.io/ku45y/](https://osf.io/ku45y/)
- Elsevier-SSRN, Computation Theory eJournal 11th Oct'2019: [https://ssrn.com/abstract=3460506](https://ssrn.com/abstract=3460506)

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
