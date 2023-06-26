단순 정보 제공을 위한 score board 입니다. 참조용으로만 사용되며 실제 채점시에는 로그 파일을 직접 확인해서 채점 합니다.

# provisoned time
Mon Jun 26 04:06:34 UTC 2023

- 101
```
/v1/unicorn POST 201 0.036234
/v1/unicorn GET 200 0.029865
/v1/location POST 201 0.055023
/v1/location GET 500 0.034139
/v1/stress POST 201 0.029197
/v1/status GET 200 0.028852
```

- 102
```
/v1/unicorn POST 404 0.005016
/v1/unicorn GET 404 0.001317
/v1/location POST 404 0.002548
/v1/location GET 404 0.001161
/v1/stress POST 404 0.001618
/v1/status GET 200 0.004469
```

- 103
```
/v1/unicorn POST 409 0.007079
/v1/unicorn GET 409 0.004667
/v1/location POST 409 0.003488
/v1/location GET 409 0.004567
/v1/stress POST 409 0.003086
/v1/status GET 409 0.004369
```

- 104
```
/v1/unicorn POST 404 0.001792
/v1/unicorn GET 404 0.002639
/v1/location POST 404 0.001196
/v1/location GET 404 0.001615
/v1/stress POST 404 0.002808
/v1/status GET 200 0.002803
```

# traffic-1
### success request count
- 101: 41369
- 102: 34577
- 103: 149
- 104: 181

### instance count
- 101: 4 (last)
- 102: 2 (last)
- 103: 2 (last)
- 104: 3 (last)
