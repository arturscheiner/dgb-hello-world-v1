## This is the pipeline dgb-hello-world README:
## This is the pipeline components tree:
```bash
├── 00-Git Config (capsule-v1-demo-devops-commit-message-2.0)
├── 01-JSON Generations Super (json-generator-connector)
├── 02-Transformer (JOLTA) (transformer)
├── 03-Template Transformer (template-transformer)
├── 04-JSON Generator (json-generator-connector)
├── 05-Stream File Reader Pattern (stream-file-reader-pattern-connector)
│   ├── onException
│   │   └── 00-CSV to Excel (csv-to-excel-connector)
│   └── onProcess
│       ├── 00-CSV to Excel (csv-to-excel-connector)
│       ├── 01-Log (log-connector)
│       └── 02-Log (log-connector)
└── 06-Stream JSON File Reader (stream-json-file-reader-connector)
    ├── onException
    │   └── 00-File Writer (file-writer-connector)
    └── onProcess
        └── 00-Excel (excel-connector)

```
