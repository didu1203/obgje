# obgje
task result type:  <class 'aiohttp.client_reqrep.ClientResponse'>
result read type:  <class 'bytes'>
result content:  b'{"delay":3}'
cost 3.991998
request 1 to http://localhost:3000/aio success
request 4 to http://localhost:3000/aio success
request 2 to http://localhost:3000/aio success
task result type:  <class 'aiohttp.client_reqrep.ClientResponse'>
result read type:  <class 'bytes'>
result content:  b'{"delay":9}'
task result type:  <class 'aiohttp.client_reqrep.ClientResponse'>
result read type:  <class 'bytes'>
result content:  b'{"delay":8}'
task result type:  <class 'aiohttp.client_reqrep.ClientResponse'>
result read type:  <class 'bytes'>
result content:  b'{"delay":3}'
timeout...
<Task pending coro=<<_RequestContextManager without __name__>()> wait_for=<Future pending cb=[<TaskWakeupMethWrapper object at 0x038F1390>()]> cb=[callback(3, 'http://localhost:3000/aio')() at .\multi_get_timeout.py:13]>
<class '_asyncio.Task'>
timeout...
<Task pending coro=<<_RequestContextManager without __name__>()> wait_for=<Future pending cb=[<TaskWakeupMethWrapper object at 0x038DF810>()]> cb=[callback(0, 'http://localhost:3000/aio')() at .\multi_get_timeout.py:13]>
<class '_asyncio.Task'>
cost 10.005833
