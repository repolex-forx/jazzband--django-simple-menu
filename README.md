# Repolex Knowledge Graph of jazzband/django-simple-menu

RDF knowledge graph data for [jazzband/django-simple-menu](https://github.com/jazzband/django-simple-menu), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download jazzband/django-simple-menu
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── beb79553331e12fac2dabdff2504c46ff36fb091
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── beb79553331e12fac2dabdff2504c46ff36fb091
│           └── chunk-001.nq.gz
├── blob
│   ├── 099cf398a45d6c415e03d5fd97e57594d2dbfa5d.nq.gz
│   ├── 0a6adf708119692011a8974b9e32b3f72f2df484.nq.gz
│   ├── 1297a81eab9f5a608ca65a0e4a0fac6cc55314c0.nq.gz
│   ├── 1b8af823af1319056c7db12a4d68a70f1bb74132.nq.gz
│   ├── 1c59ba98b64fe73b4a7228b2c505549de458ccf4.nq.gz
│   ├── 26e356e7e39d70683653ca81c5434eb8dc5f27c5.nq.gz
│   ├── 3826e33a50e8ea0dd4ec754743afd07d5dc3d815.nq.gz
│   ├── 3e3c76595bcab116bb99a1722e542e07cdd23c71.nq.gz
│   ├── 41cdcb3ed955efc55e6ddcda31c17bad278e36b0.nq.gz
│   ├── 46d23167ca08c469bf5ae2d77065f82ccda62c68.nq.gz
│   ├── 51a6ef2355fcc65d9f272386147851bd08f344ed.nq.gz
│   ├── 520ec6550c704d1051f266d8816062c8d7f04055.nq.gz
│   ├── 522792e6f8a1ecd0ba82e047e04d3644c925da06.nq.gz
│   ├── 598c5ae8043ae94aa5048586066d9378b1d479bc.nq.gz
│   ├── 5a02cee7876f0b1e51a870f26e687008fd6c9425.nq.gz
│   ├── 5f3c144c7490930c00ae90083319a0840551167e.nq.gz
│   ├── 5f62d0e8da6dae3e2bbba5c082b32dee0d3405ad.nq.gz
│   ├── 625a05a98703d9b82750cb6eaa7f16a9671c83f4.nq.gz
│   ├── 670009d6c5346b30f2a6df008ca1ce3116a66d4a.nq.gz
│   ├── 6a8db1953e7eb59fdfe446c68c85707b6291dc14.nq.gz
│   ├── 6aa7f6eecef1e9ec1651b12f45de35c2a825bf63.nq.gz
│   ├── 6f42f78b0704aa7f584bbe9e1b17253c828df21e.nq.gz
│   ├── 787853c499185a6ccc07bc42847498b7ed87a343.nq.gz
│   ├── 79f5683f3f0bcc3df520967bf418a6051f1cf4ba.nq.gz
│   ├── 7a541a9c4e646d7f4fed5fa1e6eaeb79d077cdba.nq.gz
│   ├── 89e17096442ded30065f950a797576bb0614ed4b.nq.gz
│   ├── 8c7f86539cb654cf2ef66b2b604b9b009bbd14e2.nq.gz
│   ├── 8f606f8acc7252fdefa85a941198e80c2a317a97.nq.gz
│   ├── 90cc91eb3a4a23d5393a643abb0e876dffe92b1d.nq.gz
│   ├── 97009ca95977109b0139203199e2fd291a660b05.nq.gz
│   ├── 9cae10f58149c1bbef4befd0ed12706383318f78.nq.gz
│   ├── a5813f304e2e3d023c485a3f41dde48b6318b8cd.nq.gz
│   ├── ad78220bf6ae7568b9e1aff6428f7851beaa7865.nq.gz
│   ├── b740b86705b0a372e581abde76cd635d9fa2db85.nq.gz
│   ├── b8aa540c0d2ee76a2393c5085c994a04938e394f.nq.gz
│   ├── d30f8df8eae753d46b6d84a6872494367774c6d2.nq.gz
│   ├── d717186226f5cfc8afc751c2c3ab0880e7b18821.nq.gz
│   ├── d82d80070c84a6982117d7608b8f7969bae4c26a.nq.gz
│   ├── e0d5efab56fb94577e7804603eb6f21f36977cb2.nq.gz
│   ├── e2e22f5ae12f4227a7164423bc3a971ea11e73b0.nq.gz
│   ├── e326307964ef4fb92e8d1b951b465aa7b713b9b2.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8e31adb07bf0940e79f49263ff1814bfb279dc7.nq.gz
│   ├── eb55d6334ac29338488c5a9852238e4584638ad7.nq.gz
│   ├── efbba46ffaa2bd450f979349bc527600824b5b08.nq.gz
│   ├── f60ee02c9562f6872caf59ce46cc3cf74c24fcbb.nq.gz
│   └── f835790fa603bb6d8ecbfeca7a9b83d1f2baab40.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── beb79553331e12fac2dabdff2504c46ff36fb091.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 55 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[jazzband/django-simple-menu](https://github.com/jazzband/django-simple-menu)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
