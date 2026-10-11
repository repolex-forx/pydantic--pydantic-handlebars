# Repolex Knowledge Graph of pydantic/pydantic-handlebars

RDF knowledge graph data for [pydantic/pydantic-handlebars](https://github.com/pydantic/pydantic-handlebars), parsed by [repolex](https://repolex.ai).

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
rlex download pydantic/pydantic-handlebars
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9812951da4fcb56d6beb1c04512e77fe392ac2e4
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9812951da4fcb56d6beb1c04512e77fe392ac2e4
│           └── chunk-001.nq.gz
├── blob
│   ├── 0086358db1eb971c0cfa8739c27518bbc18a5ff4.nq.gz
│   ├── 0f4fd84209b55118096f548f7779e27b548ab586.nq.gz
│   ├── 10714470e38ef069b9303184fbf0230b52f33d2d.nq.gz
│   ├── 1508141132f2bc78108ba9b456b6dd85f14fbe3d.nq.gz
│   ├── 1558cfe5700fe0c80d595a7080b878e474d177f3.nq.gz
│   ├── 1bc1c46e238169322dd16bb917f33d6338958d02.nq.gz
│   ├── 24ee5b1be9961e38a503c8e764b7385dbb6ba124.nq.gz
│   ├── 2d78e1531d2486ba278639aef25837674f491d35.nq.gz
│   ├── 2e7c92adc06ef77c4a6af2e0131fdb4a59759bde.nq.gz
│   ├── 2f70d05e79861245d980b7deb45085e5014c18c6.nq.gz
│   ├── 399842dea15d75168b18d6a0fe601955b8ef9a09.nq.gz
│   ├── 3c4de836d5eede2e17848571d41633e4604c5621.nq.gz
│   ├── 479aae6497d92928113cc91c9ef644dd54e61644.nq.gz
│   ├── 4d2d201d8a448fbed69972a304c8c86a42545666.nq.gz
│   ├── 4ed062c14a2eaadf9bbaf92ebc3ca85e795461f3.nq.gz
│   ├── 567f457d04dba509a91041d2b82eed8e6773650e.nq.gz
│   ├── 5c17d24c669882e5a450d7ba954dc392e24c4b1d.nq.gz
│   ├── 619b2e9a792404c0033003f2695df2c08f2f8bb0.nq.gz
│   ├── 63499eb6dbb9886dabd02df8bc5f03aa69ee4d4c.nq.gz
│   ├── 64d2e7c6d18dc73fea366e68ba333e319c28668f.nq.gz
│   ├── 69b5f30d39aa8c06cf150582efa474087cbd6c0e.nq.gz
│   ├── 6c7cdf90fdd15a32c4d7a9209850cba914e381e5.nq.gz
│   ├── 6f64e970ffd734d1d961fb5e6f939c0dd4700913.nq.gz
│   ├── 72828be8a89a5a5f9cfef7d131cba7aa275c75b3.nq.gz
│   ├── 7ef3e1ee28baf1e02ef037b6b7550f7edd3dea30.nq.gz
│   ├── 8fd04fc31e1fc23d8eff50f2bdbe5a64511dd478.nq.gz
│   ├── 92de4b168a13a622cb3d863217feb42001550b22.nq.gz
│   ├── 952b186d4cb4d4f9889385de8047007688245cd5.nq.gz
│   ├── 95ea60f1962e06c7673b4bd248924c466a1d540f.nq.gz
│   ├── 96c8bd4f6bdd1973ce9ec6f7aad38f0fd2ba032e.nq.gz
│   ├── 9bebfe5b3c235f7e844e74959ae2b0302466ffac.nq.gz
│   ├── 9f167e91d96cfe8d72536d51ddbef2c5677dbe1b.nq.gz
│   ├── a7df22d23df2dc8fd3ba7b19b6d6ddde5ec8f18f.nq.gz
│   ├── b19d08eedfff52395b0d770d32f11b1d58a616b4.nq.gz
│   ├── b5e1dad4f381da58f764c9ea8e8180d181e33404.nq.gz
│   ├── b958fcae610491522b1e823d9e916b133684f50a.nq.gz
│   ├── bb06fc4d0b668b4d6561e068685602447790b019.nq.gz
│   ├── bbac7844b73b1d8d342d72a08d1cb56d0d92ada8.nq.gz
│   ├── c279b56b0d63300c96cec414a33459027a7e9a5e.nq.gz
│   ├── c4e7e30197c10d1aad494c6301283a065d34924f.nq.gz
│   ├── c7075ff22affafc3feb95e4b3eec19bc3583bed6.nq.gz
│   ├── c82e2013c83dd953e0f90e253179e917c8f05dd5.nq.gz
│   ├── d5d3a5dd6b0f9c12ca2632c39fc35ae52541cb3b.nq.gz
│   ├── d77b91b0198fbf363f88c98b8039e65b8e46f4bc.nq.gz
│   ├── d80fe76718bc8ab8d21563ebbf6b0b9872e6c706.nq.gz
│   ├── d8463bade24274f049e69aa57723efe5e4ca0a86.nq.gz
│   ├── d84f27583201fd6596f6e4ad895abcfe95beb9a9.nq.gz
│   ├── e01fe816aa4e1040f7bc5a45641522912e4dbd44.nq.gz
│   ├── e660e51bbeb8efee6a7e2413991d91fe040394b7.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea62ac6bfd3e4d87f4e83882d72945981269120e.nq.gz
│   ├── eaa908bf197b08430733869c5428d2f665967c72.nq.gz
│   ├── ed9ac1adf2bb829616fff8351d6e5b59b4940eb2.nq.gz
│   ├── f14dc1f85825ac5d4f4fae2a6301dd7193639c73.nq.gz
│   ├── f7e0062d38cf349b791f938aea10ca7ac1d9ed47.nq.gz
│   └── fa0c55d6603d96496ae8858926d3f0885c8be20a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 9812951da4fcb56d6beb1c04512e77fe392ac2e4.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 64 files
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

[pydantic/pydantic-handlebars](https://github.com/pydantic/pydantic-handlebars)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
