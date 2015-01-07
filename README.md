tckfc
=====

[![Latest Version](https://pypip.in/version/tckfc/badge.svg)](https://pypi.python.org/pypi/tckfc/)
[![Downloads](https://pypip.in/download/tckfc/badge.svg)](https://pypi.python.org/pypi/tckfc/)
[![Download format](https://pypip.in/format/tckfc/badge.svg)](https://pypi.python.org/pypi/tckfc/)
[![Supported Python versions](https://pypip.in/py_versions/tckfc/badge.svg)](https://pypi.python.org/pypi/tckfc/)
[![License](https://pypip.in/license/tckfc/badge.svg)](https://pypi.python.org/pypi/tckfc/)

This tool seeks asynchronously TrueCrypt key file using combinations of provided key files with provided password.

Installation
============
    pip install tckfc

Usage
=====

``python tckfc.py [-h] [-c [COMBINATION]] keyfiles tcfile password mountpoint``

  * **keyfiles:** Possible key files directory
  * **tcfile:** TrueCrypt encrypted file
  * **password:** Password for TrueCrypt file
  * **mountpoint:** Mount point

Example
=======

    mkdir mnt
    cp a.pdf keys/
    cp b.doc keys/
    cp c.txt keys/
    cp d.jpg keys/
    cp e.gif keys/
    python tckfc.py keys/ encrypted.img 123456 mnt/

[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/Octosec/tckfc/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

