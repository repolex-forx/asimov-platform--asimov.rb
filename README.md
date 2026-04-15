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
├── aggregate
│   ├── ast
│   │   ├── 515e8a456e416892df87a816cf1665c177acd68a.nq.gz
│   │   └── 973897c56692a4be0f664a2606bf1b6e16c8da24
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 515e8a456e416892df87a816cf1665c177acd68a.nq.gz
│   │   └── 973897c56692a4be0f664a2606bf1b6e16c8da24.nq.gz
│   └── repolex
│       ├── 515e8a456e416892df87a816cf1665c177acd68a.nq.gz
│       └── 973897c56692a4be0f664a2606bf1b6e16c8da24
│           └── chunk-001.nq.gz
├── blob
│   ├── 05ab88d5069a5c8779414ce8f2f70b82c87c4d3e.nq.gz
│   ├── 08e982fc64da74c1127b13bd6235ee3abbc59a72.nq.gz
│   ├── 13edb27f8341a15f7ef6805243c5be8572913129.nq.gz
│   ├── 1d1fc9063035c48afe3a01be9a2d3d4bae3d5ea0.nq.gz
│   ├── 1ebe18da0084fdec3ba253965ad40fdd0afdc827.nq.gz
│   ├── 2391f73aa051d3804285ce744f2e9a1c7e08993d.nq.gz
│   ├── 2d1f072e61354130bc567fb3d370a2180779651f.nq.gz
│   ├── 314274c6ef24c6a2f34b2f6151a126b9358474a4.nq.gz
│   ├── 3b1461982c11a189b3af3c7c2f6f2ad57a28d929.nq.gz
│   ├── 3bcbd21a94ff36a79273b2289962e909f4820518.nq.gz
│   ├── 440e49e0fa912c8e8a9817ef9c7db4421ae5953e.nq.gz
│   ├── 4c95385beb111e5e3e03c51ef4177e1e24bd8a45.nq.gz
│   ├── 56c44d4c39184a32401592ce07a824de09cac3ef.nq.gz
│   ├── 57f38eea31088b23cd784bc154a77de22e2fe855.nq.gz
│   ├── 5c44e23136a37aa2f49062b8c215f7853a7949c7.nq.gz
│   ├── 5d1697d37394b1c0242e4727946319b7d3f4db98.nq.gz
│   ├── 60a8bee355e5f0a88ea609aa6dce75ab4f2d89fc.nq.gz
│   ├── 63e72429b90b822a7b17c6cf8b715c26b4f2503d.nq.gz
│   ├── 6c4c39f957be0406731075cc4ae72575adae482b.nq.gz
│   ├── 71a512788f1e41fec7e36550a39ba05e60098a87.nq.gz
│   ├── 7c6c2d2338568681ebf16fb39fdca56fe143b094.nq.gz
│   ├── 81c6dc6b4aede2456d4dc34c369442b065653486.nq.gz
│   ├── 840a8f21581fc99994f5ef2f978dcf2fa2696327.nq.gz
│   ├── 844e01f6e28ccb853504830fb7acca168bb43ae7.nq.gz
│   ├── 8cff681340c4e19be1d8a587442f7a78731cffa0.nq.gz
│   ├── 926c1191945ad1387216d87b7b98a95096672987.nq.gz
│   ├── 940bbfe3a74fdb8c6fa964795def6337201f7c16.nq.gz
│   ├── 945cb1bddb8cdfd5c6f22db993dd368eea6c4c7c.nq.gz
│   ├── 94ef0b98333f0f9d523ebb0f875abe88141099b2.nq.gz
│   ├── 953eefb7dc2a1bb0ed9a08532813d1c68d362f2b.nq.gz
│   ├── 9547533242738f4bf6c8df0887cf890493b74e9e.nq.gz
│   ├── 99cce34b52086a7cd35092c2451db722a1008da8.nq.gz
│   ├── 9d9ce7554783c53cee7bfd6fd8d32ffd42b7c0df.nq.gz
│   ├── 9de1571d1bd59cb3afc7e96b52a2e81d3b865226.nq.gz
│   ├── 9e36714d302e33d25aeaca6c0b53de603f88576a.nq.gz
│   ├── a3c9cdc7bdfa3d851da156bb766bcc4afa20dc60.nq.gz
│   ├── a53ecc787000f9a7fbf1389cb3c607b905c54b1d.nq.gz
│   ├── a62d3898c607bc0937f2b5be75187462f2183dc7.nq.gz
│   ├── a8611627534122887a79f70d19aa13ab696714b1.nq.gz
│   ├── b10a1a5c15eb39033810bcd5a5b58b824859f00f.nq.gz
│   ├── b37c67b65da8dfca16047a8b0257674421f6922e.nq.gz
│   ├── b4e2a20bb6069d33479542fc863e7e36810e0f01.nq.gz
│   ├── bb563233134b02102a0054d6878cacc85e8ce1b7.nq.gz
│   ├── bf1ee8ec18a59bcc8a84a09ee9083f5529f68c7f.nq.gz
│   ├── c34fee89761dad43665f24e95639fb2f3a6fab12.nq.gz
│   ├── c8783b7f754f4fcacc28efc00d23abba7d93a91f.nq.gz
│   ├── cbadbc59bf2079eff0f1d125f6d541caa26e4925.nq.gz
│   ├── cbbffdedc5059539b65051e031acd679786fd51e.nq.gz
│   ├── ce7113ed08f93d0fc78a2b6aa57cc582753c71b3.nq.gz
│   ├── d98f137b528ff5c17d8e20717768841f8feadd34.nq.gz
│   ├── dc778b3842ad6b932aefd6d7006dfec5e45cc400.nq.gz
│   ├── df2b224934dcfaef6cb943dd85625a4b4a0e20a1.nq.gz
│   ├── e004e2c90b402e86ac528c7b3f645b9771e4667f.nq.gz
│   ├── e2022f17c11d4175c6ba749c57ae537bf57aadff.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e84753769db4df01806ac99d6d624c651b64225a.nq.gz
│   ├── ed8416dd125b4df53def62a6f0fc73f4cd0ee639.nq.gz
│   ├── efb98088164f5786b17e83ed384971fc3c74f93c.nq.gz
│   ├── f03dcadab55ab2daa68c6d25f3c75aef88bd17b3.nq.gz
│   ├── f368f2f71ba312b593285d3009e727a7a9e868b5.nq.gz
│   └── f8f2571a8535a18a498207fb01650e0971c3128f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   ├── 515e8a456e416892df87a816cf1665c177acd68a.nq.gz
│   └── 973897c56692a4be0f664a2606bf1b6e16c8da24.nq.gz
├── filetree
│   ├── 515e8a456e416892df87a816cf1665c177acd68a.nq.gz
│   └── 973897c56692a4be0f664a2606bf1b6e16c8da24.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 74 files
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
*Parsed on 2026-04-15 by [repolex](https://repolex.ai)*
