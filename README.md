# Repolex Knowledge Graph of jaraco/jaraco.develop

RDF knowledge graph data for [jaraco/jaraco.develop](https://github.com/jaraco/jaraco.develop), parsed by [repolex](https://repolex.ai).

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
rlex download jaraco/jaraco.develop
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ceeeeeb31bf5b9b77272e6d6c42032a49952b4ae
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ceeeeeb31bf5b9b77272e6d6c42032a49952b4ae
│           └── chunk-001.nq.gz
├── blob
│   ├── 0edad868f9af58823fc511ffa52bce7702ff4ccd.nq.gz
│   ├── 10d412f406891b9683f832fcbc134c9bdf4f916e.nq.gz
│   ├── 114e10fd2af79ce0d2a8f535a7115dc5ed9c45fc.nq.gz
│   ├── 19e341abea2aaa779ed3bb01460de2510e48f392.nq.gz
│   ├── 1f2aa7533b0423a8eb943f6f4ec02498e39581a0.nq.gz
│   ├── 240329c3604d8ead4c10aa8c88352caa8e4ce7b2.nq.gz
│   ├── 247b10241bd117f8a1c37ef4d8c64267e542b52e.nq.gz
│   ├── 2e3b9a5b2e02d8623057eea489da2adc4db808cd.nq.gz
│   ├── 2e3f4dd791a6372b427d618eb0baa8c4dc58e5f0.nq.gz
│   ├── 304196f81e11a168c9894f966e4a617ebf4ed53c.nq.gz
│   ├── 52c14f9e5c755fe67a668d31a972708f935f0d60.nq.gz
│   ├── 549e324cb718199b65aad571a1e26bd1d87747ed.nq.gz
│   ├── 54c9000ec94341dd65c2053251b85b124017b9b5.nq.gz
│   ├── 54cc8303b22089e12053e552d4e6cb852a865b8a.nq.gz
│   ├── 577e87a793a20e413f7321f4f17ec1eba2ea1962.nq.gz
│   ├── 5a4957b39315415bafacb64709fc991c55d51fa9.nq.gz
│   ├── 5bdc232005af9be104a00437ae9bc64417a4c1cc.nq.gz
│   ├── 606db2e03a664ced1c9a1c84418d36fcbe02f779.nq.gz
│   ├── 700235be57c1b2872455c0be5333f59cf568e252.nq.gz
│   ├── 724370638fc188317bbc7dc868f1a571995fd796.nq.gz
│   ├── 75aea34d0b61cf9162a1ed66fae00b383bd017b2.nq.gz
│   ├── 7773505d7ac874893dffb9422265769b33d68ef3.nq.gz
│   ├── 86496e4bf694ec54f43d094b861168b3e4d14c8b.nq.gz
│   ├── 8684e1eff4094f60ff20408cc6cf3240c0c6c76a.nq.gz
│   ├── 8ab58175e542346cb5b11b1cab6bdcef63e2cd26.nq.gz
│   ├── 8d9b39df8288a2d23f4dff190aacc82d8f73cfbb.nq.gz
│   ├── 9a0f3bce1395ae3819030b822e5d9076c85068ea.nq.gz
│   ├── 9b8903399126b7490e60bda0769eba1436a586b0.nq.gz
│   ├── 9e9bafa064ffd9f5da3f6904a52e1355e72ba6e3.nq.gz
│   ├── a0036392922a599d9faf26ee5134165124243bd0.nq.gz
│   ├── af472a1f834ff7b3d9e5ac9fbb44862e12b5ebc1.nq.gz
│   ├── afd8fdb8e766ba23f86c3e1669babbf0949240cf.nq.gz
│   ├── b06cc2cadd0a24992318e7108eb297d4c2fe274a.nq.gz
│   ├── c791c1f4d511ee1c40a85f1b42d369d1506cc4b6.nq.gz
│   ├── c7c5fde38ff839dad632b2bfd1139a71276861f9.nq.gz
│   ├── ca2db348e9dec565166b1e798881cfcc499caa7b.nq.gz
│   ├── ced5ba0664589a73b3d63d528b9aa934a2c6e04b.nq.gz
│   ├── d50a4c89a0369ebc7157adc7090e8d4999f5ab96.nq.gz
│   ├── ddf4852d012ff93b07aba8ad5c7f47f75b69059f.nq.gz
│   ├── df0be5fe90dfcba0f95126e3bb5da5d34e1a3780.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e792e572e36b5a88c735cdb0484dbbd1289f5825.nq.gz
│   ├── eb3bd8770bd160b82dd3437d61e5a20ad25f2ab8.nq.gz
│   ├── ed440fc2241e0338e58bca24828e00decddf7b6a.nq.gz
│   ├── ee2af54823f062ac734bb1329d1c92c0cbd616de.nq.gz
│   ├── f94dd11a2d9eb7b942191a307d8b58669f7ec8db.nq.gz
│   ├── f9ac950897f9d756e8f334ea795dcf9d7f80c96c.nq.gz
│   └── fc557806d24e038c74d45a12a7baa500c45079ff.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── ceeeeeb31bf5b9b77272e6d6c42032a49952b4ae.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 56 files
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

[jaraco/jaraco.develop](https://github.com/jaraco/jaraco.develop)

---
*Parsed on 2026-10-20 by [repolex](https://repolex.ai)*
