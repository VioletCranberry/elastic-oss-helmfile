
One way to deploy Elasticsearch cluster of OSS flavour with `helmfile`.


```
├── elasticsearch-helmfile
│   ├── config
│   │   └── releases
│   │       ├── elasticsearch-client
│   │       │   └── values.yaml.gotmpl
│   │       ├── elasticsearch-data
│   │       │   └── values.yaml.gotmpl
│   │       └── elasticsearch-master
│   │           └── values.yaml.gotmpl
│   ├── templates
│   │   └── release.yaml
│   └── values
│       └── common.yaml
└── helmfile.yaml
```
