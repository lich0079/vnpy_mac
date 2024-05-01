
## MAC


```
git clone --depth=1   https://github.com/vnpy/vnpy.git

cd vnpy

/opt/homebrew/bin/python3.10 -m venv  .
bin/python3 -m pip install numpy --index=https://pypi.doubanio.com/simple
bin/python3 -m pip install ta-lib==0.4.24 --index=https://pypi.doubanio.com/simple

bin/python3 -m pip install rqdatac
bin/python3 -m pip install vnpy --index=https://pypi.doubanio.com/simple
bin/python3 -m pip install vnpy_ctastrategy vnpy_ctabacktester vnpy_datamanager vnpy_sqlite vnpy_rqdata --index=https://pypi.doubanio.com/simple


bin/python3 examples/veighna_trader/run.py


```
