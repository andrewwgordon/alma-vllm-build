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

