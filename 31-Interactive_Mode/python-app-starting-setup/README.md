```shell
# ERROR
$ docker run sha256:cb899bdc84d9d755b309fcc3e73aec7a38e28e465e1ee59b30de395b88a4713c
Please enter the min number: Traceback (most recent call last):
  File "/app/rng.py", line 3, in <module>
    min_number = int(input('Please enter the min number: '))
EOFError: EOF when reading a line
```

```shell
$ docker run -it sha256:cb899bdc84d9d755b309fcc3e73aec7a38e28e465e1ee59b30de395b88a4713c
Please enter the min number: 40
Please enter the max number: 50
48
```
