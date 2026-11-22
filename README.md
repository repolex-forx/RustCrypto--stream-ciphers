# Repolex Knowledge Graph of RustCrypto/stream-ciphers

RDF knowledge graph data for [RustCrypto/stream-ciphers](https://github.com/RustCrypto/stream-ciphers), parsed by [repolex](https://repolex.ai).

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
rlex download RustCrypto/stream-ciphers
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b516422ebb49ff0d9140b22ac8c2a627d10a452e
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── b516422ebb49ff0d9140b22ac8c2a627d10a452e.nq.gz
│   └── repolex
│       └── b516422ebb49ff0d9140b22ac8c2a627d10a452e
│           └── chunk-001.nq.gz
├── blob
│   ├── 1035af28b72b0704ebd52dfadb058c31920da61a.nq.gz
│   ├── 1105f1a7d3a420298596ee586769fd91757e1ea9.nq.gz
│   ├── 13ae88391ecb62d8c5de4d30d95d63064147d419.nq.gz
│   ├── 1d3ee20e9ae0a78ba2d65d955cf0ed4ad8fdf46a.nq.gz
│   ├── 1e5006dc141e22213c898c27abaded8d936c32f0.nq.gz
│   ├── 20c4d2de74bd1e943671d11e7702fb89685d75a5.nq.gz
│   ├── 2150aa83071c12d120a9096760e8d0b7e1749192.nq.gz
│   ├── 224354be677d87c004b2e14708882eacf12b941b.nq.gz
│   ├── 26910c8ca8b499bcc32fed078f97fd8a5c629c2f.nq.gz
│   ├── 279e87ad7a492b622dd602c86d0eacdd42b59bf5.nq.gz
│   ├── 283a2c227f8f966704367b0b8905c936c4040dbd.nq.gz
│   ├── 2b63c3a0c89909a2eadc9b400e7c8a951ac66521.nq.gz
│   ├── 2ba566b2950c8406c252702d061976bf92d892ae.nq.gz
│   ├── 2c96d08233511731ba4129c0a6e4650e468dc15d.nq.gz
│   ├── 2d7c3f558b5f58c08fba426d954b19406488d9da.nq.gz
│   ├── 2f33da7521c8fe8dd0c95d9b6d6fb5bd23e373f1.nq.gz
│   ├── 32c5df8a9d9b43d31418fbf57a7ca17f788d8699.nq.gz
│   ├── 343efd8605dadbd3af3cad105e663f2f53c5f4df.nq.gz
│   ├── 3cf09c206f8e04e829be35276d48d9ad41542bf2.nq.gz
│   ├── 3e14c90f2d984f2c6eaf41b6824111789ef67287.nq.gz
│   ├── 3f3e549a6521f51add3c01c3e611245b065d94c0.nq.gz
│   ├── 47e3700c4af5d9c91fc36ba7927b052980eea13d.nq.gz
│   ├── 48c875044afe59739bdcb1db539a316ca22d67cb.nq.gz
│   ├── 49723c9689e31059289ce5e431371434e95cc6a3.nq.gz
│   ├── 4b5947975ae93ce06af4a515ecd55f618ccef05d.nq.gz
│   ├── 524b15777a7c8d6abb8eb4bbc0fce754c575519e.nq.gz
│   ├── 5621690bdaafed201e7037c0d86589ec922794c1.nq.gz
│   ├── 5b37ba5c5e0d974fd58a330848dc1a53ff2d2f9a.nq.gz
│   ├── 60916983c6b5680c8d7a980b8e02a2f3204bab55.nq.gz
│   ├── 645d7f9416e6d8355af78c4417b732e921213173.nq.gz
│   ├── 66386dd704080e3be2a398f944c2485fc9b5409e.nq.gz
│   ├── 66e236bf2dd9b34b7d979328c87c21f73ad353eb.nq.gz
│   ├── 676fc24c8e36be24f2b58799f1847e533636a59f.nq.gz
│   ├── 68367522ada95a09d4a209c81826e6ef243f8114.nq.gz
│   ├── 6ad8e309826d0bac16f82ac29aacd8b190b2b7fa.nq.gz
│   ├── 6fb603a30c3c9917ff6e493304b79c86003ca4b7.nq.gz
│   ├── 702f1053a5d8675adaaf9252a4c91e87372b5bcd.nq.gz
│   ├── 75af424b09a47319630192e20c6e3736f1da11cf.nq.gz
│   ├── 760af926cf9373a6bff2a61bdabe018239d2449e.nq.gz
│   ├── 76a0a7a7af36f2349ab05b7ddd8896903804717b.nq.gz
│   ├── 78173fa2e753d614bb0aa5ad125ddbbe70b282c4.nq.gz
│   ├── 795b2ded3bcf67f8d7314ed746083b80ea6724c3.nq.gz
│   ├── 7a1a5ccff7b7c89e4993977a6631006c00ab3418.nq.gz
│   ├── 7a662a964184d1f77b48ef1a219ef97a69bb5b23.nq.gz
│   ├── 831a08fbb80077a6dcd0a37013400432cb6ef0d8.nq.gz
│   ├── 85c1e09d58d11426d7139ca82d2e03731d87bebe.nq.gz
│   ├── 865c25e28ff7abee107be2dd9ecce1dde280f92a.nq.gz
│   ├── 8e6839fa9f96d251ab21ac548cc8864cc2df819c.nq.gz
│   ├── 9ae90dffd982877f5d5c6844ab0f69df14146e82.nq.gz
│   ├── 9ec0d94aefdbf1a2ea41eeee69689944db4e1f6e.nq.gz
│   ├── 9f84cef522853bd5d4a49716009b9ad0bad4af66.nq.gz
│   ├── a859d3dc6975ee96c3566560fb78b3813aa3a855.nq.gz
│   ├── b1442a414bf0c89559b2035c37a3a3bd6eb06814.nq.gz
│   ├── b1506e6e1150e28abc9a4f3fe5604ffda8b2d6f8.nq.gz
│   ├── b96b32520e828d17a157420e02f2a406d7a5b84e.nq.gz
│   ├── bb867e5f12a1e7fe21833dbc2587a72f017f82a1.nq.gz
│   ├── be5c33bb6917b76ce9399af7ea7b52fd4d578419.nq.gz
│   ├── beec342b0b0b018b5d1891b1a1d65ae9014e5643.nq.gz
│   ├── caf2693f3d1b9a599c9de9876b3f72845699388c.nq.gz
│   ├── cc745fc4d5bb7cb42619f14d080c049b5636867e.nq.gz
│   ├── d8c28240eac8c191147846019b147cb99b1df6a4.nq.gz
│   ├── d8da59c8d06909770b07d73b12db96d35b5fe433.nq.gz
│   ├── dbd693497aeb7ff5e643b0dee8352d5c274b424b.nq.gz
│   ├── e463cdc78ac1bc0dcd3988d87e1d98ab4b32919f.nq.gz
│   ├── e621f157b6fa18d89cfb25a76a0c1ea3cf58484d.nq.gz
│   ├── e794b593672fc4dd903d57c2d5f5c58b34ee72de.nq.gz
│   ├── ea4c39a302e4c91ea6a2b8f252297f7930a6717c.nq.gz
│   ├── ed448d4c3eeb5fd53c6d543ee354f837f6194b2e.nq.gz
│   ├── efc51c61d618719fb05c7a06e24e2a9c54d67c8d.nq.gz
│   ├── f6305b2cf5f2a41131fed45e9ffb74d789da949c.nq.gz
│   ├── f6479a1e84cda42db83811e91c10d50efddd3d93.nq.gz
│   ├── f9309be3e63a978bbea12d1c911f7e8b7d92bf3b.nq.gz
│   ├── f9aa029b41a153ae80fafc42c8bbeafd53ac238f.nq.gz
│   ├── f9d910e2f08624b76f81b98fba092673fb486ebb.nq.gz
│   └── fbc9393c0ce51e0e3fefc4f75a422feff42c2732.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── b516422ebb49ff0d9140b22ac8c2a627d10a452e.nq.gz
├── filetree
│   └── b516422ebb49ff0d9140b22ac8c2a627d10a452e.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 85 files
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

[RustCrypto/stream-ciphers](https://github.com/RustCrypto/stream-ciphers)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
