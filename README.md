# lilach-rag

project structure:

project-root/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── myproject/
│   │   │           ├── Main.java
│   │   │           ├── pubmed/
│   │   │           │   └── PubMedFetcher.java
│   │   │           ├── elastic/
│   │   │           │   ├── ElasticIndexer.java
│   │   │           │   └── ElasticSearcher.java
│   │   │           └── utils/
│   │   │               └── JsonParser.java
│   │   └── resources/
│   │       └── application.properties
│   └── test/
│       └── java/
│           └── com/
│               └── myproject/
│                   └── ElasticIndexerTest.java
└── pom.xml
