### tile38
--- 
https://github.com/tidwall/tile38

```
NEARBY people FENCE ROAM people * 5000

NEARBY people MATCH alice FENCE ROAM people bob 100
NEARBY people MATCH a* FENCE ROAM friends * 100

SETHOOK myhook http://10.0.1.5/hook NEARBY people FENCE ROAM people * 5000
```

```sh
telnet localhost 9851
telnet localhost 9851

docker pull tile38/tile38
docker run -p 9851:9851 tile38/tile38

brew install tile38
tile38-server

pkg install tile38
make -C /usr/ports/databases/tile38 install

tile38-server

tile38-cli
SET fleet truck1 POINT 33.5123 -112.2693
GET fleet truck1
```

```
{
  "command":"set",
  "detect":"roam",
  "hook":"",
  "key":"people",
  "id":"alice",
  "time":"2016-05-24T09:19:44.08649461-07:00",
  "object":{"type":"Point","coordinates":[-115.02,33.02]},
  "nearby":{
    "key":"people",
    "id":"bob",
    "meters":1451.138152186708
  }
}
```


