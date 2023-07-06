## This is the pipeline dgb-hello-world README:
## This is the pipeline components tree:
```bash
   ├── Git Config (capsule-v1-demo-devops-commit-message-2.0)
   ├── JSON Generations Super (json-generator-connector)
   ├── Transformer (JOLTA) (transformer)
   ├── Template Transformer (template-transformer)
   ├── JSON Generator (json-generator-connector)
   ├── Stream File Reader Pattern (stream-file-reader-pattern-connector)
       │└──> onProcess
       ├── CSV to Excel (csv-to-excel-connector)
       ├── Log (log-connector)
       ├── Log (log-connector)
       │└──> onException
       ├── CSV to Excel (csv-to-excel-connector)
   ├── Stream JSON File Reader (stream-json-file-reader-connector)
       │└──> onProcess
       ├── Excel (excel-connector)
       │└──> onException
       ├── File Writer (file-writer-connector)
   ├── Stream XML File Reader (stream-xml-file-reader-connector)
       │└──> onProcess
       ├── File Writer (file-writer-connector)
       │└──> onException
       ├── XML Schema Validator (xml-validator-connector)
   ├── Do While (do-while-connector)
       │└──> onProcess
       ├── ZIP File (zip-file-connector)
       │└──> onException
       ├── Log (log-connector)
   ├── Retry (retry-connector)
       │└──> onProcess
       ├── Delayer (delayer)
       │└──> onException
   ├── Choice (choice)
         │└──) when: condition-7
           ├── Log (log-connector)
           ├── Stream Excel (stream-excel-connector)
           │└──> onProcess
           ├── Log (log-connector)
           │└──> onException
           ├── Log (log-connector)
           ├── Quando Azedou de vez (choice)
             │└──) when: se o bicho não pegar
             ├── Log de dois (log-connector)
             ├── Choice (choice)
               │└──) when: condition-5
               ├── Logs (log-connector)
               ├── Parallel Execution (parallel-execution-connector)
               │└──Ξ parallel execution-sem-medo-de-ser-feliz
               ├── Log (log-connector)
               ├── Stream File Reader (stream-file-reader-connector)
                 │└──> onProcess
                 ├── Excel (excel-connector)
                 │└──> onException
                 ├── CSV to Excel (csv-to-excel-connector)
               ├── Another Transformer (JOLT) (transformer)
               ├── Digibee Storage (digibee-storage-connector)
               ├── Blob Storage (Azure) (Azure-Blob-Storage-Connector)
               ├── Dropbox (dropbox-connector)
               ├── SAP (IDoc and RFC) (sap-connector)
               │└──Ξ parallel execution-naturalmente-nova
               ├── Log (log-connector)
               ├── Decidir se Funciona (choice)
                   │└──) when: se nao funcionar
                   ├── Log (log-connector)
                   │└──) when: se funcionar parcialmente
                   ├── Log (log-connector)
                   │└──* otherwise: se funcionar
                   ├── Log (log-connector)
               │└──Ξ parallel execution-3
               ├── Log (log-connector)
               ├── Choice (choice)
                   │└──) when: condition-3
                   ├── Log (log-connector)
                   │└──* otherwise: condition-4
                   ├── Log (log-connector)
               │└──) when: condition-9ssss
               ├── Log-eterno (log-connector)
               ├── Bloco de Validação Inicial (block-execution-connector)
               │└──> onProcess
               ├── Log de Validação Inicial (log-connector)
               │└──> onException
               ├── Log - onException (log-connector)
               │└──) when: condition-9
               ├── Log (log-connector)
               ├── Do While (do-while-connector)
               │└──> onProcess
               ├── HL7 (hl7v2-mllp-connector)
               │└──> onException
               │└──) when: condition-10 com pão
               ├── Log (log-connector)
               ├── SAP (IDoc and RFC) (sap-connector)
               ├── Dropbox (dropbox-connector)
               ├── Stream JSON File Reader (stream-json-file-reader-connector)
               │└──> onProcess
               ├── File Reader (file-reader-connector)
               ├── GZIP V2 (Compress and Decompress) (gzip-connector-v2)
               │└──> onException
               │└──* otherwise: condition-6
               ├── Log - OTHERWISE (log-connector)
               ├── Parallel Execution (parallel-execution-connector)
               │└──Ξ parallel execution-1
               ├── Log-1s (log-connector)
               ├── Stream DB V3 (stream-db-connector-v3)
                 │└──> onProcess
                 ├── Relationship (relation-connector)
                 │└──> onException
               │└──Ξ parallel execution-2
               ├── Log-2s (log-connector)
               ├── For Each 0 (for-each-connector)
                 │└──> onProcess
                 ├── JSON Transformer (json-transformer-connector)
                 ├── Block do For-Each 1 (block-execution-connector)
                   │└──> onProcess
                   ├── Log do Block do For-Each (log-connector)
                   ├── Block-Execution 2 (block-execution-connector)
                     │└──> onProcess
                     ├── Log (log-connector)
                     ├── SAP (IDoc and RFC) (sap-connector)
                     │└──> onException
                     ├── Event Publisher (event-publisher-connector)
                     ├── Throw Error (throw-error-connector)
                   │└──> onException
                   ├── Throw Error do Block do For-Each (throw-error-connector)
                 │└──> onException
                 ├── Throw Error do For-Each (throw-error-connector)
             │└──* otherwise: se o bicho pegar
             ├── Log de nada (log-connector)
         │└──* otherwise: condition-8
           ├── Log (log-connector)
           ├── Quando Azedou de vez (choice)
             │└──) when: condition-1
             ├── Log (log-connector)
             │└──* otherwise: condition-2
             ├── Log (log-connector)
```
