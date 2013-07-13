socketclient
============

# Socket TCP Client Class developed in Python

* This is an useful client tcp socket class with a few lines of code you can connect to whatever server/port you want.


# Usage:

```python
x = TCPClient('127.0.0.1',80)
if x.connect():
    data = """GET / HTTP/1.1\r\nHost:localhost\r\n\r\n"""
    send(data)
    data_returned = recv()
    print data_returned
    close()
```

* The above code tries to connect to localhost:80 and makes a request for index and wait until data is returned.

* Simple and easy! you can also code an smtp client or whatever your mind can imagine!.

