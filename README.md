# Repolex Knowledge Graph of mkdocstrings/autorefs

RDF knowledge graph data for [mkdocstrings/autorefs](https://github.com/mkdocstrings/autorefs), parsed by [repolex](https://repolex.ai).

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
rlex download mkdocstrings/autorefs
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── fd28aa305e26e6bec58ae1b187c76559105ae7ea
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── fd28aa305e26e6bec58ae1b187c76559105ae7ea
│           └── chunk-001.nq.gz
├── blob
│   ├── 002b2a0406a2be01fdcfcd78c4a90218458ac9cd.nq.gz
│   ├── 0275b7e075a8fe810a46963ded5c519ab2dbf241.nq.gz
│   ├── 0308cf998854b0840da61f2ee10da156dee1051e.nq.gz
│   ├── 0536cbbe261b2d97ed3d94f5b1fd86596a2ae486.nq.gz
│   ├── 06cef79866c5821c0890c79d770cbeaa5958ab03.nq.gz
│   ├── 081b7107d3f6ea73181569191d8b18b91f016c5f.nq.gz
│   ├── 0bf83cdb9ee560cb0fa553728455c959e9937963.nq.gz
│   ├── 0ca7fabfe18b401de8974a8668482dfddfb3b9e3.nq.gz
│   ├── 120b7bc9c7a2e0c2062c359c12d4236726fe2c7c.nq.gz
│   ├── 15b59d08a18df49c533797b8121e683337c8fb67.nq.gz
│   ├── 2660f51b23895c29664a0ffd6822fd62538a3c42.nq.gz
│   ├── 27512e9e9e563d7cbf9473dddaced06fcc1a7467.nq.gz
│   ├── 276c7e5e06bcf6635c7eace9cbc8092145f978db.nq.gz
│   ├── 2d46305a68da4b9569bf6813f4d2fb1131653842.nq.gz
│   ├── 2df98fbcac88d8d93c9d18648ba7d5a800100ce0.nq.gz
│   ├── 304027c8ca1b038bbdc856579cf034cf0f40ab6b.nq.gz
│   ├── 30571233ab2743c8bfa278db17f69b884823c94f.nq.gz
│   ├── 35ec8f1917b21691560159f7e6051600f0674f58.nq.gz
│   ├── 3805aa1eacd4a9dcb3371d325c93e7859c5e5011.nq.gz
│   ├── 461f7e3d73ca89f0dee46d673a8057f563b9873f.nq.gz
│   ├── 4a605cea233197655b1e9ba98af8d6e63e893bd5.nq.gz
│   ├── 4bbae50c9c7119be1186e11f5430a283d3df28d9.nq.gz
│   ├── 4bf53345c9942f765f4e8100a6ab4a9abf36a4e4.nq.gz
│   ├── 4ceef24d6746a8d2a0fd26d26c7787121a61a5d5.nq.gz
│   ├── 5029ee99b7bedc99c3fe523f976b6991f5c9db60.nq.gz
│   ├── 51587578d052005002f5e1f131bfeb180807caed.nq.gz
│   ├── 5b25a00f43bcb9d2a68e49250995865e6608c26c.nq.gz
│   ├── 61935e5d49e2b4f90babe55d6bda7b7401cfc1b9.nq.gz
│   ├── 65beb72ca9fd4c89dbff835b1b2496c8e67052a4.nq.gz
│   ├── 6f0f2faf32486394750d5d5421e2261430b73fef.nq.gz
│   ├── 73145eec7e2a896212b2a9165dcc7449f0abd318.nq.gz
│   ├── 80faec56e2b663d728dae913a47f4305a179fc1d.nq.gz
│   ├── 812789e68bf5688ca56d42a80caecd04c1e0c4b4.nq.gz
│   ├── 820edbb68b9f522797e2f8c0c03ca760631435eb.nq.gz
│   ├── 82377e2175cb6a3e81bcd4650e4c158db89a8004.nq.gz
│   ├── 879ed30f5c694a5b02e85fe3e401965c8e49e8f8.nq.gz
│   ├── 8e84bbffb2b3d6d3d13ae8b8d4d38cd834b2a287.nq.gz
│   ├── 8fa0a330f89e03d5caf0b5868d86b2e88ac0dfdd.nq.gz
│   ├── 92ac8ec5dbe177b6e29da9600c7c3fd18d8069b9.nq.gz
│   ├── 96d1bd542370e81865860f3c84015adbb2513097.nq.gz
│   ├── 97724fa80f2fd81fddb1eb8b00029dc4fee78054.nq.gz
│   ├── 98cbfdd106f6af898b9ceed1ec1f707b532c5173.nq.gz
│   ├── 9ba352d7ddd921cf71f488e3fff5827943ef5d53.nq.gz
│   ├── 9c3bb0deb0a37b99212ded70e3ac4cc40c24d962.nq.gz
│   ├── a09379f1b6893041a9e5249ae2b8e054b532cd23.nq.gz
│   ├── a1ca70c893d8a7db54f7aca28ea018dfc8b05b0d.nq.gz
│   ├── b8353d3b8ce8b24f7ff5a0125795395fb8c96c4c.nq.gz
│   ├── be6475485620a752aa5bd38ac0b58e3ffc84753b.nq.gz
│   ├── c2eda0df52a5c1bd708ad342b50fcc917be81192.nq.gz
│   ├── ccc55e666586eac7f2b87c8c56d66c6f2ec622d9.nq.gz
│   ├── cdc6e59043ec23cca1ca238f1bd20c4bb3f0db3a.nq.gz
│   ├── dc711a48b9bd2f8029f3af22e74526a2cb8661f3.nq.gz
│   ├── dc9a8f17c6e3f0117661042120c4413a21065bce.nq.gz
│   ├── e175fe88da1cb2e8d8190e17504049f75d9df99a.nq.gz
│   ├── e638f9919b38b7b41f9460c8954d542f62563f2c.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6bb5b91b56c550fab69e0f2898006069366f3da.nq.gz
│   ├── f072271cb235e97740a9887ebc76955c62749a18.nq.gz
│   ├── f1909e14b1787b1106a9f6c375cc7714da610f62.nq.gz
│   ├── f26ec1bd1ac699897caee6c72b051538b0758ac0.nq.gz
│   ├── f6ab1aa2cdbbb6aa245be35e5090520815c3f7ef.nq.gz
│   ├── f97321a5d0ecc1a536fc3eeca5a23f446efb07bd.nq.gz
│   └── feef986bff5c126dd89e1ecb754c317c2e010b94.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── fd28aa305e26e6bec58ae1b187c76559105ae7ea.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 71 files
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

[mkdocstrings/autorefs](https://github.com/mkdocstrings/autorefs)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
