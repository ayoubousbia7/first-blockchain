# The zypherchain blockchain 

## Overview
Implementation of a functional blockchain in python

## To run the server
```
flask --app src/zyphercoin run
```

## Simulate transaction between nodes
start first node on port 5001

```
flask --app src/node_5001.py
```
start second node on port 5002

```
flask --app src/node_5002.py
```
start third node on port 5003

```
flask --app src/node_5002.py
```

## 


