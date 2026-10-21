# Repolex Knowledge Graph of glue-viz/glue-statistics

RDF knowledge graph data for [glue-viz/glue-statistics](https://github.com/glue-viz/glue-statistics), parsed by [repolex](https://repolex.ai).

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
rlex download glue-viz/glue-statistics
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f0ab7f5a79038143b7519e5908a03acd61122e28
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f0ab7f5a79038143b7519e5908a03acd61122e28
│           └── chunk-001.nq.gz
├── blob
│   ├── 0ad8e855d137d43c983d618761caa275244903a3.nq.gz
│   ├── 0b2ca68b04b945d4ea5ba3d1f3357f128ec70971.nq.gz
│   ├── 0bcda1b43801970a4e46c33b714b3a7e5b1319e4.nq.gz
│   ├── 0daff1a7a01882c9dd04bc7d01d93aac682db78a.nq.gz
│   ├── 13b443919596e506fee9d3df9fda46774f9b54b4.nq.gz
│   ├── 1ebae5496766059f55ce5d3182892a20ee57f7f8.nq.gz
│   ├── 28cf979932016dc78317214b0ab5942df40ab418.nq.gz
│   ├── 2bb5dca05b9a40e5ce7253eae92e59e21f783fea.nq.gz
│   ├── 32074b40117674568f01e3584600987cee65a424.nq.gz
│   ├── 3ab6f7b8c01a727a31795188ecd0d8c2261a0e95.nq.gz
│   ├── 3bd8fc63d2ef658fb4ca3f8441343c2ec6d1f924.nq.gz
│   ├── 41ea4d6c9639ff51cb312891386624ba4a4967fd.nq.gz
│   ├── 422df341d0a1e7c315881737e58dcb43a8b87b1c.nq.gz
│   ├── 478463e8d9c56ea04bdf3df0ec2d3042c3cb93c6.nq.gz
│   ├── 4f3e4468e11fe13f9067fd6222e9a0629dcfa693.nq.gz
│   ├── 507cf4070b3119185a3515b2e0b98e7632824bc6.nq.gz
│   ├── 5b51f9ed5c0c6ffc38691dbd31fc5d8a815be8e5.nq.gz
│   ├── 5b91db042d44ca620a4484e52cb7534cc31abede.nq.gz
│   ├── 5c50a3e0d9eaf4fbd2cbf83720d417603189ba0d.nq.gz
│   ├── 5cbb85a2a6acbe9bc9ef192f1d58825ba9d68797.nq.gz
│   ├── 5e5dd80b48414815b5752204bf6af86360ac71a5.nq.gz
│   ├── 653c043e5645af24b58235d95e8e4b8eab37c526.nq.gz
│   ├── 65830c9321431c7c2f45dac45ea06a5d43755c4c.nq.gz
│   ├── 660585ecca57b1b20118df9d5bbd26afee2aee1c.nq.gz
│   ├── 6eb81cd58650b48b43a1887c9718c4548c80525b.nq.gz
│   ├── 78abcfade47650e71f58616ef8523a027ba4df9f.nq.gz
│   ├── 7f1099f7790bbd5c9aa1d03d087990cfc732f471.nq.gz
│   ├── 88a2986d9c379853bf612c70bec7b32792b2a5d2.nq.gz
│   ├── 9fee594d6d1d63a8d90df1534eb1f03589436c53.nq.gz
│   ├── b43102d71056b70df8ee06d322faf28baa87976d.nq.gz
│   ├── b7b739fcede79afd3ee89fc89bd35d71b59851fd.nq.gz
│   ├── b9d8bc56804d7e90e0dc1e22b0553183b2f2fc5a.nq.gz
│   ├── bd340754c2e0db2c50c331d7658f13ce1f60a829.nq.gz
│   ├── c013d477e58a8946d802609c7889df4a0dc6d1d0.nq.gz
│   ├── c282c5ead5eea243d54fab5ff0933a2e64c3e00d.nq.gz
│   ├── c342004a607317497cdc941598d2919934a17a29.nq.gz
│   ├── c7a12ae5b3cf1bc620a7a27b40021555b9936c30.nq.gz
│   ├── ce622c45a06e7f4e05b0fcd5fa756c2be2baf2c2.nq.gz
│   ├── d18a4179c669e7eac0ffd8b6ff3be58b992e817f.nq.gz
│   ├── e26a39fdb7958d78e8e22c371a9091b2093c8968.nq.gz
│   ├── f745ec6de422e57dd087c290d210aafa505c72fc.nq.gz
│   ├── f953fda24c3917ac918ad148709bcd5e1f6a72f8.nq.gz
│   ├── fa710b5f7ec2c6ee71554c4de5d7d97f5d56bfc4.nq.gz
│   ├── fb95a6c92ddf0856a2305282a764018b42091300.nq.gz
│   └── fd69f0b5d6a0f64089fdb93636d3d772c6dac5c6.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── f0ab7f5a79038143b7519e5908a03acd61122e28.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 52 files
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

[glue-viz/glue-statistics](https://github.com/glue-viz/glue-statistics)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
