# Repolex Knowledge Graph of zopefoundation/zope.event

RDF knowledge graph data for [zopefoundation/zope.event](https://github.com/zopefoundation/zope.event), parsed by [repolex](https://repolex.ai).

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
rlex download zopefoundation/zope.event
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 2d08012c56c3ecf9b047402a294c19561a95f93f
│   │   │   └── chunk-001.nq.gz
│   │   └── 88722ea6df44e57b72d724906d43a11680193637
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 2d08012c56c3ecf9b047402a294c19561a95f93f.nq.gz
│   └── repolex
│       ├── 2d08012c56c3ecf9b047402a294c19561a95f93f
│       │   └── chunk-001.nq.gz
│       └── 88722ea6df44e57b72d724906d43a11680193637
│           └── chunk-001.nq.gz
├── blob
│   ├── 034043e1628b277e8c3805e50acd2ac1e6e85255.nq.gz
│   ├── 03d3cbf165ff47dbc61f233fb8b173196d566e69.nq.gz
│   ├── 044981d51cbd21b0f2984783c13b0f043618a501.nq.gz
│   ├── 05444bfec5e9458eef2fb65a21a603ccd442f853.nq.gz
│   ├── 07675b622d6ff2b814ee0f0798f9ebc79530f589.nq.gz
│   ├── 09c2e510b65c389d71ba0a3503648b257156b228.nq.gz
│   ├── 0ab12fe1e0c8eb6cb0d68fce1b14a2209cdb0def.nq.gz
│   ├── 0dc7df2eac8496f864e37defdeaa7152fc656fda.nq.gz
│   ├── 188120b692cc972bed5f7063baaa7ebd9dd5fcea.nq.gz
│   ├── 1f321f52abb7db6f79c285bab56e2852dc575699.nq.gz
│   ├── 2806c164989aa9137a6c1860716ae9abccef75ad.nq.gz
│   ├── 2c836f34d0e435cd07aafb4fbbadf9fab6d753fa.nq.gz
│   ├── 464572a3c5ea027110f117742884741d72e77361.nq.gz
│   ├── 467a86bf8855de26b2b45b30b7f44e303b557bcc.nq.gz
│   ├── 52baa1532dda8f90a66056da855543c138264d90.nq.gz
│   ├── 5302ba176adde121472212771da19e090c320355.nq.gz
│   ├── 5d08235b60591e9077254cf841f66b85fe19b5e9.nq.gz
│   ├── 5f86332c90df01ce86106d04cacd12282932f555.nq.gz
│   ├── 6069a68501e68e29c39097d6b0754923bdcab1a9.nq.gz
│   ├── 6e45f7cdd3bee10ae6498403a75b2e857845e3d2.nq.gz
│   ├── 70a9f7d9500a200737e43b7abd07eadbf71c7452.nq.gz
│   ├── 71b08d94ec08c1acc1b2dc7b46f228ec6b77df63.nq.gz
│   ├── 7819b66281d95cb09c77d04bba156e1d3705fb51.nq.gz
│   ├── 79859e06010bf4967c5b4b044afea6ef39742938.nq.gz
│   ├── 8983eb919e06d7a80f989fd9e2407ad768c55c0a.nq.gz
│   ├── 8a1cde635fcfe005cc4438d504940505395236a7.nq.gz
│   ├── 8d5e2e08440c7027d0911004405d020e59e159af.nq.gz
│   ├── 98c4624648bfb59b9761e26283c9d954fddd207a.nq.gz
│   ├── 9d66f6a446d5c9b399061bb69665c9673c29b919.nq.gz
│   ├── 9ee58a7a7d37b23ea1d3b25baac006069744cf5c.nq.gz
│   ├── a8b9c1476bc2bca0b2f0a190e637e349feaf7bb6.nq.gz
│   ├── aec6d5be48f1931e566850c002e2aff995a6fe91.nq.gz
│   ├── bf29fe1466009368b20d4e4d1123be2a7cdeebfa.nq.gz
│   ├── c634bd6257977ab9c6d5de4c242f1f303d0ed4e8.nq.gz
│   ├── c9fac653720b27d7fec50cd017f2e5008a9ed9b9.nq.gz
│   ├── ca517f4eb0cec1c691c0c2b54cd5eb85e906f11b.nq.gz
│   ├── cf2d684fbe03e7123f0a3066407390d2ea6bcc3e.nq.gz
│   ├── d007613bc0ee8bddaec0d5f8b07f102631d8dfcd.nq.gz
│   ├── d100980fa853daca17c9d3a738caa8532edf4d74.nq.gz
│   ├── d2d502902f40dcf5281e2fdefbcd2548f95f1c06.nq.gz
│   ├── e1f9ad7b3b48377bfbfaa1b380c384ddea24060f.nq.gz
│   ├── e4b867329e05886a4818f86b117fca2102bc84bf.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e8336cc99cb4f1a1b24a842122b36dc8179e26ee.nq.gz
│   ├── f7f79ec792f5d796ad4d26421022d360701a9a7f.nq.gz
│   ├── f81cabf053fb4487bb3496afbc276556076bc3f2.nq.gz
│   └── fd7e555a2681c941927400cb1b2a85ef532915e7.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 2d08012c56c3ecf9b047402a294c19561a95f93f.nq.gz
├── filetree
│   ├── 2d08012c56c3ecf9b047402a294c19561a95f93f.nq.gz
│   └── 88722ea6df44e57b72d724906d43a11680193637.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

17 directories, 60 files
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

[zopefoundation/zope.event](https://github.com/zopefoundation/zope.event)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
