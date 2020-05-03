# MPI_map_reduce
Project to make log analyzer utilizing MPI parallel for analysis

# Usage
```
./binary –(addr|stat|time) path/to/logfile
```

Log example:
```
2013-03-27 21:47:14,021 83.6.229.4 “POST /result HTTP/1.1” 500
2013-03-27 21:47:20,035 83.6.229.4 “GET /favicon.ico HTTP/1.1” 404
2013-03-27 23:27:25,299 107.21.253.204 “POST /result HTTP/1.1” 200
2013-03-27 23:27:25,373 107.21.253.204 “GET /favicon.ico HTTP/1.1” 404
2013-03-27 23:47:35,052 194.29.146.3 “GET /favicon.ico HTTP/1.1” 404
2013-03-27 23:47:35,330 194.29.146.3 “POST /result HTTP/1.1” 200
2013-03-27 23:48:46,443 91.231.138.27 “GET /favicon.ico HTTP/1.1” 404
```
