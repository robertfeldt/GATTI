# [cryptography](https://github.com/pyca/cryptography)


## Target platform and dependencies
 It supports Python 2.7, Python 3.4+, and PyPy 5.4+.

## What is the purpose of the sw/lib, i.e. what does it aim to do for users/developers?
cryptography is a python library which provides cryptoraphic recipes and primitives.
cryptography includes both high level recipes and low level interfaces to common cryptographic algorithms such as symmetric ciphers, message digests, and key derivation functions. [see](https://github.com/pyca/cryptography/blob/master/README.rst) 

## What are the key technologies used to develop the lib?
  - Python
  - OpenSSL
  - C
  - clang and gcc compiler
  - documetation written in reStructured Text and rendered with Sphinx

## What kind of automated testing tools are used to test the sw/lib (including but possible more than YTT) and what are their key features?
  - Hypthesis is used to test the functionality of the Fernet encoding and decoding.
      https://github.com/pyca/cryptography/blob/master/tests/hypothesis/test_fernet.py
  - Hypthesis is used to test the functionality of the padding algorithms PKCS7 and ANSIx923.
      https://github.com/pyca/cryptography/blob/master/tests/hypothesis/test_padding.py
  - Pytest is also used to test parts of the lib
  - keyfeatures of pytest: (Detailed info on failing assert statements, Modular fixtures, can run [unittest](https://docs.python.org/3/library/unittest.html) and [nose](https://nose.readthedocs.io/en/latest/)) 

## Which features of the automated testing tools are currently used by the test suite?
    It uses the features of Hypothesis as descibed it the Hypothesis tool description.
    e.g.it uses the health check to avoid to slow tests and it uses for shure random test case generation. 
    In other test, where pytest is used, they use a feature that skips marked program parts depending on which python interpreter is used. 
    
## Which features of the automated testing tools are NOT used by the test suite?
    For example they don't use the feature of Hypothesis to create test case examples manually.

## Updates

**Latest update:** 2.6.1 - 2019-02-28
**First release date:** 2014-01-09

## Licensing / Cost

This software is made available under the terms of *either* of the licenses
found in LICENSE.APACHE or LICENSE.BSD. Contributions to cryptography are made
under the terms of *both* these licenses.

The code used in the OpenSSL locking callback and OS random engine is derived
from CPython, and is licensed under the terms of the PSF License Agreement.
Link: https://github.com/pyca/cryptography/blob/master/LICENSE

## Tutorials and documentation

  - Documentation and tutorials can be found [here](https://cryptography.io/en/latest/)

  - Code can be found on [GitHub repository](https://github.com/pyca/cryptography)


#Part 3 (didn't receive an answer yet) 
