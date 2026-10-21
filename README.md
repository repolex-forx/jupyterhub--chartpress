# Repolex Knowledge Graph of jupyterhub/chartpress

RDF knowledge graph data for [jupyterhub/chartpress](https://github.com/jupyterhub/chartpress), parsed by [repolex](https://repolex.ai).

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
rlex download jupyterhub/chartpress
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f7d727abccb67bbb352f330d92c68e8b995c96cb
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f7d727abccb67bbb352f330d92c68e8b995c96cb
│           └── chunk-001.nq.gz
├── blob
│   ├── 0122430810efa4febb1792af222634ed1984943c.nq.gz
│   ├── 0770e06affb1f102a3b8c57b5fe6101570246c58.nq.gz
│   ├── 0e8a0eb36f4ca2c939201c0d54b5d82a1ea34778.nq.gz
│   ├── 0f17a82d7467d644a80e6267cdc7868c92ce2eae.nq.gz
│   ├── 138960b978142403ea94705c51a983be5476e350.nq.gz
│   ├── 141fd8635b1afe0d6551f19cf0d96865f0bf5f65.nq.gz
│   ├── 14ac9ba46084e33c2d2bd48689275e449c6d14bc.nq.gz
│   ├── 1db01ca74635b8f07e246ae909ff985cae42139d.nq.gz
│   ├── 1df8b2a889d1a46b0130ec06e6b461bbd4c7f225.nq.gz
│   ├── 238818a860a6adecdb4294ec2f5bba39247c6d18.nq.gz
│   ├── 280cb38e416b985ed7c391b97e878c3f998112f5.nq.gz
│   ├── 32e18992cab1c29a8a594511dbaadfe4acf948a1.nq.gz
│   ├── 39e4fbc099ca9847ae3c9f76928ce928796617ae.nq.gz
│   ├── 3c7affbedc8e8f62faa778b52db3bbc916a48251.nq.gz
│   ├── 3f956acf45b575049e1d923967ca3f1e19ba20cd.nq.gz
│   ├── 4270d4cc8b55c1a89fca8a0d64278ec2d6768dad.nq.gz
│   ├── 4392c49f689618395ae267290080139985dcd0f0.nq.gz
│   ├── 4e0b45d2cbd9b8344f46fa4fc61046d3dea97629.nq.gz
│   ├── 50d63339bd9b78f41fef4e88713fefcb646ebfcc.nq.gz
│   ├── 50ec5ef265f96ac5cee31fecfe938146f2be0cc8.nq.gz
│   ├── 557b77de1456dff115f1fdc730d474991c1bb4fe.nq.gz
│   ├── 57407b0c8b6327ccc42c0a6184de4ef8ec9ba40f.nq.gz
│   ├── 6236028729841ce3dbe9816c1726cf2c2a74dffc.nq.gz
│   ├── 660e935b0dd33446c3743f9ba6639a9473b9e5a3.nq.gz
│   ├── 6ad224a51595854c3dfca290c556c8ee37db36fe.nq.gz
│   ├── 6daf425a825ce1750b840b04b4df7301424dd7b9.nq.gz
│   ├── 6f38d212d5701c5e2b87dc5c3a08b298725a1a17.nq.gz
│   ├── 70f49ccd7988251afd88c6d888d73e5dc1fd7021.nq.gz
│   ├── 728abce63912db89f7d7bbc009720de129038c11.nq.gz
│   ├── 747ffb7b3033659bdd2d1e6eae41ecb00358a45e.nq.gz
│   ├── 74f03b6b666320b5c2d3047df00eca2621df4331.nq.gz
│   ├── 77beabdc20b364306fae39e4bdf1adabb005c8f8.nq.gz
│   ├── 7e3d81008ec4d82c860d510f4318cb3b1cd9ac67.nq.gz
│   ├── 8881d8b60bd835ba88de927fe501fe8ccc8dff3b.nq.gz
│   ├── 8aa04d1d044b4797de33e44ef2288849f8ec3787.nq.gz
│   ├── 92c73ecf59ab302cdf3444ee54752f828b0426d0.nq.gz
│   ├── 95fe5368ebc7271f7332d235e11bf24d439922fe.nq.gz
│   ├── 96de9cd72d9784ec1fe9f9129e9c9b03cce0e27a.nq.gz
│   ├── 9bc61be799a4f52f43fc0afcac468c7b76863779.nq.gz
│   ├── a6e34fed9c5a87fcd626e80e6bde0bf0035ed458.nq.gz
│   ├── b0ca6a4d6f3100349a73ec2e89c7b31a8e958f36.nq.gz
│   ├── b66e2a28f868d81fbbaf45cb74b664c93ee135ce.nq.gz
│   ├── beea35181b6fc6b4c5c328098f56329931757eff.nq.gz
│   ├── cce6112b6f3cd67f6b74e1fc8b636905538107a6.nq.gz
│   ├── d0c3cbf1020d5c292abdedf27627c6abe25e2293.nq.gz
│   ├── d30b04049b19d88b01578ccecd1dd3e9bdb10a2d.nq.gz
│   ├── d89dc5905e57b5f6f77a13a0290714c997f3b07b.nq.gz
│   ├── df466b69164bbf29992e288aaa68faea8d255fba.nq.gz
│   ├── e359908bee1cab1e8a09f627a7e85c1bc9aa37b3.nq.gz
│   ├── e3a9723960a3ca9b81198f37c2f968d1059ddec4.nq.gz
│   ├── e54356e4777e233cb6a2ef22c088a6c782d1b6e0.nq.gz
│   ├── e6f085fdaf8dcd9f1288274938a380caa7700810.nq.gz
│   ├── e77e16c44a68408deb8f6053f1ef09fcf3aabad3.nq.gz
│   ├── f4565044256db82333a507460f76f5e74690a826.nq.gz
│   ├── f4a8daec42d3d1da4ec7a2590d682084cc4475c1.nq.gz
│   └── ff26d36d3baae5844580fc9fab556abab56115ba.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── f7d727abccb67bbb352f330d92c68e8b995c96cb.nq.gz
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

[jupyterhub/chartpress](https://github.com/jupyterhub/chartpress)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
