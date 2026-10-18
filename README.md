# Repolex Knowledge Graph of sumerc/yappi

RDF knowledge graph data for [sumerc/yappi](https://github.com/sumerc/yappi), parsed by [repolex](https://repolex.ai).

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
rlex download sumerc/yappi
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c2f6d4384e01e3beda62a03dc3c8734aefd6bac0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c2f6d4384e01e3beda62a03dc3c8734aefd6bac0
│           └── chunk-001.nq.gz
├── blob
│   ├── 02b5d417c86be6ec360ab0c4b968373e1854e22a.nq.gz
│   ├── 04446195889cd7e4cce72612146d843ef080c399.nq.gz
│   ├── 0580e3e29e3437ff16cfaec1f1348aef017870d0.nq.gz
│   ├── 123014908bebbfb7ecfa1d15daaceb272fabe05b.nq.gz
│   ├── 130148a1c5a3bb14e5a471e052c0fd9cc729e566.nq.gz
│   ├── 17061ee796e1ab782d4a8555c4515cae9d533f6b.nq.gz
│   ├── 17a7e5d9511b84797b5a7cdbefd0827df26aa420.nq.gz
│   ├── 18bb458a9a60837f96ac321b979203f8e7ef9d6c.nq.gz
│   ├── 1c570f5bd84aea8c5108979b4e7b11c855125c59.nq.gz
│   ├── 1dbb72ee366dcc24d95217465d91d3a21d7e2a9c.nq.gz
│   ├── 297c643b422e7632237827fccf6203b65eb5b045.nq.gz
│   ├── 2ca2930affc6c5ca2153044175173d56076277b5.nq.gz
│   ├── 34a70dc4793994fa862d94fc91b2b8f6b2486ce7.nq.gz
│   ├── 3ccb291ef527c0970202cdd67bfb38ec52d00612.nq.gz
│   ├── 432cd5b57a5315b42503de4fc1b4439861cc8e75.nq.gz
│   ├── 564059b729b3a50a4ff2230686954eeb2f8d827b.nq.gz
│   ├── 5bd750caacbcf0364e8a49ee0dd99bf17507288e.nq.gz
│   ├── 5f420ac0d12225f5a393e0adf0d2b886d9239058.nq.gz
│   ├── 63e83f56e06d5a5db1087dee4f068dda8e26d6d3.nq.gz
│   ├── 64a3323c8d9b9e583da8511c87a96b23b5e3ecd6.nq.gz
│   ├── 69d20a0634fece2462cc2a1af9945093c7a3ad1a.nq.gz
│   ├── 6afdf440e8b8f7fff4a4bc3855069647b64d0fea.nq.gz
│   ├── 6e8a4d0c0cad35d240cb1abe54400135489f58a0.nq.gz
│   ├── 851b509dd9917bd8f3cf7bff6802b6eacb5fde2d.nq.gz
│   ├── 91c74a5898b53d25f9a79a64c32ff8b2ccb9d004.nq.gz
│   ├── 92695a57e0acdc0ef50493969997fce2cbc70212.nq.gz
│   ├── 945397dfb7c182fbb3bf3198202be5506a5c5346.nq.gz
│   ├── 9b7c8b5bee73870c82b5c368df71ef68e320c209.nq.gz
│   ├── 9bb941e86ba75b2dc551ac32e339e0df5d6b1e0d.nq.gz
│   ├── 9e1567c02f51fdf394eabfd16d2c715d3d9a52c9.nq.gz
│   ├── a57c3fe6d2cbd4653b627bb509b961a969f0d294.nq.gz
│   ├── aca95a4b9c014712b6f091caea1cf208e442d710.nq.gz
│   ├── aeaa19f6443a7654a05d6aa662efdc59ec8e268d.nq.gz
│   ├── b0b531d12dec763ded6ca4107b6adaa13413874f.nq.gz
│   ├── b0f9473f10c8d0c029d18fabd7644c5012b40000.nq.gz
│   ├── b351a3ecbff73d4c5c9702e5562cef3ba3bb1775.nq.gz
│   ├── b3e877ee3bb2193cce046320cbe9b80e6941bd8e.nq.gz
│   ├── b5bf083c88800b2daff8aa7cee9963837ae93e56.nq.gz
│   ├── bd5f3d0e28c09056efb0f1ce62ecee6030a521b6.nq.gz
│   ├── c38758e37b5cffb15c4c022718f9813068b5e12b.nq.gz
│   ├── c74430e26cc0eadba501ada1b255815bdc73e5c3.nq.gz
│   ├── d03ed5be811053282c448a2c1bc48611d3347444.nq.gz
│   ├── d29503f2c3e88ae5c2862116d17b774034775dd3.nq.gz
│   ├── dbafb09cdb04d38ae2c4f7e030838b1ad69d9bc9.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ed9e6ae6775fe111272da314eb71b63f58190701.nq.gz
│   ├── efc9d58702d1f7758888a492de773339ea4026ae.nq.gz
│   ├── f0b1063e93c4ebd7f09c53265902dc0a58459652.nq.gz
│   ├── f1738a658c7f0cccea007709015663fe3535043c.nq.gz
│   ├── f2d14f6a91938f087d33ebab76a3e80637ed2817.nq.gz
│   ├── f8d5e49b317cbd22f89be43c189c705fb5d03e7a.nq.gz
│   ├── f9caff5e3c3a925ab54dbf7d2bbdf70db8d38cce.nq.gz
│   ├── fb7293c510ce2e636f9163cf0ec05b639ce09a12.nq.gz
│   └── fd879419c65b046de01f17662e192feea2f4b18c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c2f6d4384e01e3beda62a03dc3c8734aefd6bac0.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 62 files
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

[sumerc/yappi](https://github.com/sumerc/yappi)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
