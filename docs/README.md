```
├── 00-Git Config (capsule-v1-demo-devops-commit-message-2.0)
├── 01-JSON Generations Super (json-generator-connector)
├── Git Config-c8ae5
├── 02-Transformer (JOLTA) (transformer)
├── JSON Generations Super-01965
├── Transformer (JOLTA)-58fe8
├── 03-Template Transformer (template-transformer)
├── 04-JSON Generator (json-generator-connector)
├── JSON Generator-78007
├── Template Transformer-88e12
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
│   ├── onProcess
│   │   └── 00-File Writer (file-writer-connector)
│   └── onException
│       └── 00-XML Schema Validator (xml-validator-connector)
├── 08-Do While (do-while-connector)
│   ├── onException
│   │   └── 00-Log (log-connector)
│   └── onProcess
│       └── 00-ZIP File (zip-file-connector)
├── 09-Retry (retry-connector)
│   └── onProcess
│       └── 00-Delayer (delayer)
├── Another Transformer (JOLT)-ad605
└── 10-Choice (choice)
    ├── when-condition-7
    │   ├── 00-Log (log-connector)
    │   ├── 01-Stream Excel (stream-excel-connector)
    │   │   ├── onException
    │   │   │   └── 00-Log (log-connector)
    │   │   └── onProcess
    │   │       └── 00-Log (log-connector)
    │   └── 02-Parallel Execution (parallel-execution-connector)
    │       ├── execution-execution-naturalmente-nova
    │       │   ├── 00-Log (log-connector)
    │       │   └── 01-Decidir se Funciona (choice)
    │       │       ├── otherwise-se funcionar
    │       │       │   └── 00-Log (log-connector)
    │       │       ├── when-se funcionar parcialmente
    │       │       │   └── 00-Log (log-connector)
    │       │       └── when-se nao funcionar
    │       │           └── 00-Log (log-connector)
    │       ├── execution-execution-sem-medo-de-ser-feliz
    │       │   ├── 00-Log (log-connector)
    │       │   ├── 01-Stream File Reader (stream-file-reader-connector)
    │       │   │   ├── onException
    │       │   │   │   └── 00-CSV to Excel (csv-to-excel-connector)
    │       │   │   └── onProcess
    │       │   │       └── 00-Excel (excel-connector)
    │       │   ├── 02-Another Transformer (JOLT) (transformer)
    │       │   └── 03-Digibee Storage (digibee-storage-connector)
    │       └── execution-execution-3
    │           ├── 00-Log (log-connector)
    │           └── 01-Choice (choice)
    │               ├── otherwise-condition-4
    │               │   └── 00-Log (log-connector)
    │               └── when-condition-3
    │                   └── 00-Log (log-connector)
    └── otherwise-condition-8
        ├── 00-Log (log-connector)
        └── 01-Quando Azedou de vez (choice)
            ├── otherwise-condition-2
            │   ├── 00-Log (log-connector)
            │   └── 01-Quando Azedou de vez (choice)
            │       ├── when-se o bicho não pegar
            │       │   ├── 00-Log de dois (log-connector)
            │       │   └── 01-Choice (choice)
            │       │       ├── when-condition-5
            │       │       │   └── 00-Logs (log-connector)
            │       │       ├── when-condition-9ssss
            │       │       │   ├── 00-Log-eterno (log-connector)
            │       │       │   └── 01-Bloco de Validação Inicial (block-execution-connector)
            │       │       │       ├── onException
            │       │       │       │   └── 00-Log - onException (log-connector)
            │       │       │       └── onProcess
            │       │       │           └── 00-Log de Validação Inicial (log-connector)
            │       │       ├── when-condition-10 com pão
            │       │       │   ├── 00-Log (log-connector)
            │       │       │   ├── 01-SAP (IDoc and RFC) (sap-connector)
            │       │       │   └── 02-Stream JSON File Reader (stream-json-file-reader-connector)
            │       │       │       └── onProcess
            │       │       │           ├── 00-File Reader (file-reader-connector)
            │       │       │           └── 01-GZIP V2 (Compress and Decompress) (gzip-connector-v2)
            │       │       ├── when-condition-9
            │       │       │   ├── 00-Log (log-connector)
            │       │       │   └── 01-Do While (do-while-connector)
            │       │       │       └── onProcess
            │       │       │           └── 00-HL7 (hl7v2-mllp-connector)
            │       │       └── otherwise-condition-6
            │       │           ├── 00-Log - OTHERWISE (log-connector)
            │       │           └── 01-Parallel Execution (parallel-execution-connector)
            │       │               ├── execution-execution-1
            │       │               │   ├── 00-Log-1s (log-connector)
            │       │               │   └── 01-Stream DB V3 (stream-db-connector-v3)
            │       │               │       └── onProcess
            │       │               │           └── 00-Relationship (relation-connector)
            │       │               └── execution-execution-2
            │       │                   ├── 00-Log-2s (log-connector)
            │       │                   └── 01-For Each 0 (for-each-connector)
            │       │                       ├── onProcess
            │       │                       │   ├── 00-JSON Transformer (json-transformer-connector)
            │       │                       │   └── 01-Block do For-Each 1 (block-execution-connector)
            │       │                       │       ├── onProcess
            │       │                       │       │   ├── 00-Log do Block do For-Each (log-connector)
            │       │                       │       │   └── 01-Block-Execution 2 (block-execution-connector)
            │       │                       │       │       ├── onProcess
            │       │                       │       │       │   ├── 00-Log (log-connector)
            │       │                       │       │       │   └── 01-SAP (IDoc and RFC) (sap-connector)
            │       │                       │       │       └── onException
            │       │                       │       │           ├── 00-Event Publisher (event-publisher-connector)
            │       │                       │       │           └── 01-Throw Error (throw-error-connector)
            │       │                       │       └── onException
            │       │                       │           └── 00-Throw Error do Block do For-Each (throw-error-connector)
            │       │                       └── onException
            │       │                           └── 00-Throw Error do For-Each (throw-error-connector)
            │       └── otherwise-se o bicho pegar
            │           └── 00-Log de nada (log-connector)
            └── when-condition-1
                └── 00-Log (log-connector)

```
