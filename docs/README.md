```
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
├── 06-Stream JSON File Reader (stream-json-file-reader-connector)
│   ├── onException
│   │   └── 00-File Writer (file-writer-connector)
│   └── onProcess
│       └── 00-Excel (excel-connector)
├── 07-Stream XML File Reader (stream-xml-file-reader-connector)
│   ├── onException
│   │   └── 00-XML Schema Validator (xml-validator-connector)
│   └── onProcess
│       └── 00-File Writer (file-writer-connector)
├── 08-Do While (do-while-connector)
│   ├── onException
│   │   └── 00-Log (log-connector)
│   └── onProcess
│       └── 00-ZIP File (zip-file-connector)
├── 09-Retry (retry-connector)
│   └── onProcess
│       └── 00-Delayer (delayer)
└── 10-Choice (choice)
    ├── when-condition-7
    │   ├── 00-Log (log-connector)
    │   ├── 01-Stream Excel (stream-excel-connector)
    │   │   ├── onException
    │   │   │   └── 00-Log (log-connector)
    │   │   └── onProcess
    │   │       └── 00-Log (log-connector)
    │   └── 02-Parallel Execution (parallel-execution-connector)
    │       ├── execution-execution-sem-medo-de-ser-feliz
    │       │   ├── 00-Log (log-connector)
    │       │   ├── 01-Stream File Reader (stream-file-reader-connector)
    │       │   │   ├── onException
    │       │   │   │   └── 00-CSV to Excel (csv-to-excel-connector)
    │       │   │   └── onProcess
    │       │   │       └── 00-Excel (excel-connector)
    │       │   ├── 02-Another Transformer (JOLT) (transformer)
    │       │   ├── 03-Digibee Storage (digibee-storage-connector)
    │       │   ├── 04-Blob Storage (Azure) (Azure-Blob-Storage-Connector)
    │       │   ├── 05-Dropbox (dropbox-connector)
    │       │   └── 06-SAP (IDoc and RFC) (sap-connector)
    │       ├── execution-execution-3
    │       │   ├── 00-Log (log-connector)
    │       │   └── 01-Choice (choice)
    │       │       ├── when-condition-3
    │       │       │   └── 00-Log (log-connector)
    │       │       └── otherwise-condition-4
    │       │           └── 00-Log (log-connector)
    │       └── execution-execution-naturalmente-nova
    │           ├── 00-Log (log-connector)
    │           └── 01-Decidir se Funciona (choice)
    │               ├── otherwise-se funcionar
    │               │   └── 00-Log (log-connector)
    │               ├── when-se funcionar parcialmente
    │               │   └── 00-Log (log-connector)
    │               └── when-se nao funcionar
    │                   └── 00-Log (log-connector)
    └── otherwise-condition-8
        ├── 00-Log (log-connector)
        └── 01-Quando Azedou de vez (choice)
            ├── otherwise-condition-2
            │   └── 00-Log (log-connector)
            └── when-condition-1
                └── 00-Log (log-connector)

```
