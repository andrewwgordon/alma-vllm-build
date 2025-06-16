# alma-vllm-build
## Overview
Build of vLLM for Alma Linux 8.10
## Installation
```bash
dnf install python3.12
dnf install python3.12-pip
alias python=/usr/bin/python3.12
cd /home
mkdir vllm
cd vllm
python -m venv venv
source venv/bin/activate
python -m pip install vllm --extra-index-url https://download.pytorch.org/whl/cu124
```
## vLLM SCA
```text
NAME   INSTALLED  FIXED-IN   TYPE    VULNERABILITY        SEVERITY  EPSS%  RISK  
pip    23.2.1     23.3       python  GHSA-mq26-g339-26xf  Medium    11.67  < 0.1  
torch  2.7.0                 python  GHSA-887c-mr87-cxwp  Medium     4.49  < 0.1  
torch  2.7.0      2.7.1-rc1  python  GHSA-3749-ghw9-m3mg  Low        5.64  < 0.1
```

