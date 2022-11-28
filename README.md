<a href="https://github.com/trhacknon/CRLFsuite"><p align="center"><img src="https://github.com/trhacknon/CRLFsuite/blob/main/static/CRLFsuite_logo2.0.png" height="150" width="150"></p></a>
<h2 align="center">CRLFsuite - CRLF injection scanner</h2>

[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)
[![GitHub release](https://img.shields.io/github/release/trhacknon/CRLFsuite)](https://gitHub.com/trhacknon/CRLFsuite/releases/)
[![PyPI license](https://img.shields.io/pypi/l/ansicolortags.svg)](https://pypi.python.org/pypi/ansicolortags/)
[![GitHub forks](https://badgen.net/github/forks/trhacknon/CRLFsuite/)](https://gitHub.com/trhacknon/CRLFsuite/network/)
[![GitHub contributors](https://img.shields.io/github/contributors/trhacknon/CRLFsuite)](https://GitHub.com/trhacknon/CRLFsuite/graphs/contributors/)

<img src="https://github.com/Nefcore/CRLFsuite/blob/main/static/crlfsuitev2.0.svg">

<hr>

CRLFsuite is a powerful tool for `CRLF injection` detection and exploitation. Want to know how it works. <a href="https://github.com/Nefcore/CRLFsuite/wiki/How-CRLFsuite-works%3F">Here's how</a>
## Installation

You can install CRLFsuite using `pip` as given below:

```
pip3 install crlfsuite
```

or download this repository and run the following command:

```
sudo python3 setup.py install
```

## Features

* Single URL scanning

* Multiple URL scanning

* Stdin supported

* WAF detection

* Powerful payload generator

* CRLF Injection to XSS Chaining feature 

* GET & POST method supported

* Concurrency

* Fast and efficient scanning with negligible false-positive

### Newly added in v2.5.1:

* Json & Text ouput supported

* Multiple headers supported

* Verbose output supported

* Scan can be resumed after CTRL^C is pressed

* Added heuristic (basic) scanner

* Compatibility with windows


### credits

* <a href="https://github.com/trhacknon/CRLFsuite/blob/main/crlfsuite/core/prompt.py">prompt.py</a> is taken from <a href="https://github.com/trhacknon/Arjun/blob/master/arjun/core/prompt.py">Arjun</a>
* WAF Detection methodology is taken from <a href="https://github.com/trhacknon/XSStrike/blob/master/core/wafDetector.py">XSStrike</a>
* User-Agent list is taken from <a href="https://github.com/trhacknon/ParamSpider/blob/master/core/requester.py">ParamSpider</a>
* WAF signatures is taken from <a https://github.com/trhacknon/wafw00f/tree/master/wafw00f/plugins">wafw00f</a>
ref="https://github.com/trhacknon/XSStrike/blob/master/db/wafSignatures.json">XSStrike</a> and <a href="
