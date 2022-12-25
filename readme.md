# Golden master project to write ci compliant diploma thesis documents

## Introduction

Documents should be placed into `src/main/asciidoc`.

## Necessary adaption steps

- configure filename in pom.xml
- build via invocation of maven wrapper (`./mvnw`), no goal needed, because of default configuration
- generated document(s) will be available in `target/asciidoc/pdf`
