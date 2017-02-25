#APIRest HTTP client/server for asyncio 
- No database config
- Tutorial http://aiohttp.readthedocs.io/en/stable/ 

##INSTALL
with python3.5 / pip3.5

cd poolls
pip3 install -e .

or

python3.5 setup.y install

##RUN
python -m aiohttpdemo_polls


- TEST:
ab -n 7000 -c 100 http://127.0.0.1:9009/
