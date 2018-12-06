## Web Crawler / 网络爬虫  
一个网络爬虫框架的学习  
##### 目录树  
```
.
├── errors
│   └── errors.go
├── examples
│   └── finder
│       ├── finder.go
│       ├── internal
│       │   ├── client.go
│       │   ├── helper.go
│       │   ├── module.go
│       │   ├── parser.go
│       │   └── processor.go
│       └── monitor
│           └── monitor.go
├── module
│   ├── base.go
│   ├── data.go
│   ├── data_test.go
│   ├── errors.go
│   ├── fake_test.go
│   ├── local
│   │   ├── analyzer
│   │   │   ├── analyzer.go
│   │   │   ├── analyzer_test.go
│   │   │   ├── errors.go
│   │   │   └── errors_test.go
│   │   ├── downloader
│   │   │   ├── downloader.go
│   │   │   ├── downloader_test.go
│   │   │   ├── errors.go
│   │   │   └── errors_test.go
│   │   └── pipeline
│   │       ├── errors.go
│   │       ├── errors_test.go
│   │       ├── pipeline.go
│   │       └── pipeline_test.go
│   ├── maddr.go
│   ├── maddr_test.go
│   ├── mid.go
│   ├── mid_test.go
│   ├── mtype.go
│   ├── mtype_test.go
│   ├── registrar.go
│   ├── registrar_test.go
│   ├── score.go
│   ├── score_test.go
│   ├── sn.go
│   ├── sn_test.go
│   └── stub
│       ├── base.go
│       ├── stub.go
│       └── stub_test.go
├── README.md
├── scheduler
│   ├── args.go
│   ├── args_test.go
│   ├── domain.go
│   ├── domain_test.go
│   ├── errors.go
│   ├── errors_test.go
│   ├── scheduler.go
│   ├── scheduler_test.go
│   ├── status.go
│   ├── status_test.go
│   ├── summary.go
│   └── summary_test.go
└── toolkit
    ├── buffer
    │   ├── buffer.go
    │   ├── buffer_test.go
    │   ├── errors.go
    │   ├── pool.go
    │   └── pool_test.go
    ├── cookie
    │   ├── cookiejar.go
    │   └── cookiejar_test.go
    └── reader
        ├── reader.go
        └── reader_test.go

16 directories, 62 files
```
