# README-tests

*README file to test proper display on github, before commiting.*


## Details

<details>

<summary>Click to expand</summary>

```json
[
  {
    "works?": 123,
    "hello": "yes",
  }
]
```

</details>


## Shell color + long request

```sh
curl -X POST http://localhost:5050/classify \
  -H 'Content-Type:application/json' \
  -d '{"service":"hwrt", "mapping":"similar-0", "bound":0, "pretty":true, "strokes":[[{"x":50,"y":60,"time":0},{"x":55,"y":65,"time":10}],[{"x":60,"y":70,"time":80}]]}'
```


## File tree

```bash
something
├── app
│   ├── data
│   │   └── some-nice-file.bin
│   ├── main.c
│   ├── LICENSE
│   ├── Makefile
│   └── manifest.json
├── Dockerfile
├── best-script-ever.sh
└── README.md
```
