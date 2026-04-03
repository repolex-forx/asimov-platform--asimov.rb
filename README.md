# Repolex Knowledge Graph of asimov-platform/asimov.rb

RDF knowledge graph data for [asimov-platform/asimov.rb](https://github.com/asimov-platform/asimov.rb), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download asimov-platform/asimov.rb
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── blob
│   ├── 08e982fc64da74c1127b13bd6235ee3abbc59a72.nq.gz
│   ├── 1d1fc9063035c48afe3a01be9a2d3d4bae3d5ea0.nq.gz
│   ├── 1ebe18da0084fdec3ba253965ad40fdd0afdc827.nq.gz
│   ├── 2391f73aa051d3804285ce744f2e9a1c7e08993d.nq.gz
│   ├── 3b1461982c11a189b3af3c7c2f6f2ad57a28d929.nq.gz
│   ├── 3bcbd21a94ff36a79273b2289962e909f4820518.nq.gz
│   ├── 8cff681340c4e19be1d8a587442f7a78731cffa0.nq.gz
│   ├── 9547533242738f4bf6c8df0887cf890493b74e9e.nq.gz
│   ├── 9de1571d1bd59cb3afc7e96b52a2e81d3b865226.nq.gz
│   ├── dc778b3842ad6b932aefd6d7006dfec5e45cc400.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   └── efb98088164f5786b17e83ed384971fc3c74f93c.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 515e8a456e416892df87a816cf1665c177acd68a.nq.gz
└── tag
    └── tag.nq.gz

6 directories, 16 files
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

## Source repository

[asimov-platform/asimov.rb](https://github.com/asimov-platform/asimov.rb)

---
*Parsed on 2026-04-03 by [repolex](https://repolex.ai)*
